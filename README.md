# Quarry

Install Python package as a standalone application.

## Background

<!-- TODO: Write background -->

## Requirements

Requires Bash (Currently, do not support other shell. We need your help!).

- `git`
- Tools to build Python interpreters (such as `gcc`, `make`, `autoconf`)
- Libraries linked to Python interpreters (such as `readline`, `zlib`, `libssl`)

<!-- TODO: Add examples to install requirements-->

## Install

```
$ git clone https://github.com/doloopwhile/quarry ~/.quarry
$ ~/.quarry/bin/quarry update
$ echo 'eval "$(~/.quarry/bin/quarry init -)"' >> ~/.bashrc
```

## Basic Usage

```
$ quarry install hoge
```

```
$ quarry exec hoge
```

```
$ quarry list
```

```
$ quarry info hoge
```

```
$ quarry update
```

# Q&A

## Should I set up Jupyter with Quarry?
