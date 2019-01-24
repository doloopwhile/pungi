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
$ git clone https://github.com/doloopwhile/pungi ~/.pungi
$ ~/.pungi/bin/pungi update
$ echo 'eval "$(~/.pungi/bin/pungi init -)"' >> ~/.bashrc
```

## Basic Usage

```
$ pungi install hoge
```

```
$ pungi exec hoge
```

```
$ pungi list
```

```
$ pungi info hoge
```

```
$ pungi update
```

# Q&A

## Should I set up Jupyter with Quarry?
