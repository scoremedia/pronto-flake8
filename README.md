# [Pre-Alpha] Pronto runner for flake8 (using flake8 from npm)

[![Gem Version](https://badge.fury.io/rb/pronto-flake8.svg)](http://badge.fury.io/rb/pronto-flake8)
[![Build Status](https://travis-ci.org/scoremedia/pronto-flake8.svg?branch=master)](https://travis-ci.org/scoremedia/pronto-flake8)
[![Code Climate](https://codeclimate.com/github/scoremedia/pronto-flake8/badges/gpa.svg)](https://codeclimate.com/github/scoremedia/pronto-flake8)
[![Test Coverage](https://codeclimate.com/github/scoremedia/pronto-flake8/badges/coverage.svg)](https://codeclimate.com/github/scoremedia/pronto-flake8/coverage)
[![Dependency Status](https://gemnasium.com/badges/github.com/scoremedia/pronto-flake8.svg)](https://gemnasium.com/github.com/scoremedia/pronto-flake8)

Pronto runner for [flake8](http://flake8.pycqa.org/en/latest/), a Python Style Guide Enforcer. [What is Pronto?](https://github.com/mmozuras/pronto)


## Configuration of pronto-flake8

pronto-flake8 can be configured by placing a `.pronto_flake8.yml` inside the directory where pronto is run.

Following options are available:

| Option               | Meaning                                | Default                                   |
| -------------------- | -------------------------------------- | ----------------------------------------- |
| flake8_executable      | flake8 executable to call.               | `flake8` (calls `flake8` in `PATH`)           |


Example configuration to call custom flake8 executable:

```yaml
# .pronto_flake8.yml
flake8_executable: '/my/custom/path/flake8'
```
