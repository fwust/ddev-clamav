# ddev-clamav <!-- omit in toc -->

[![tests](https://github.com/fwust/ddev-clamav/actions/workflows/tests.yml/badge.svg)](https://github.com/fwust/ddev-clamav/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

- [Introduction](#introduction)
- [Getting Started](#getting-started)

## Introduction

[ClamAV®](https://www.clamav.net/) is an open-source antivirus engine for detecting trojans, viruses, malware & other malicious threats.

This add-on allows you to run [ClamAV](https://www.clamav.net/) through the DDEV web service.
The docker image used : [tiredofit/clamav](https://github.com/tiredofit/docker-clamav).

## Getting Started

Install the DDEV ClamAV:

For DDEV v1.23.5 or above run

```shell
ddev add-on get fwust/ddev-clamav
```

For earlier versions of DDEV run

```shell
ddev get fwust/ddev-clamav
```

Then restart your project.

```shell
ddev restart
```
