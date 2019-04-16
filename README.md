# makedl

Fetch `Makefile` files from Github.

**Table of Contents**

<!-- toc -->

- [Installation](#installation)
    + [Via Go](#via-go)
- [Usage](#usage)

<!-- tocstop -->

## Installation

#### Via Go

```console
$ go get -u -v github.com/evalexpr/makedl
```

## Usage

```console
$ makedl [language]
```

This will download `[language].Makefile` from https://github.com/evalexpr/makefiles
to the current working directory.

