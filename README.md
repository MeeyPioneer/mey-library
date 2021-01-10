[![Go Report Card](https://goreportcard.com/badge/github.com/meeypioneer/mey-library)](https://goreportcard.com/report/github.com/meeypioneer/mey-library)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Travis_ci](https://travis-ci.org/meeypioneer/mey-library.svg?branch=master)](https://travis-ci.org/meeypioneer/mey-library)
[![Maintainability](https://api.codeclimate.com/v1/badges/a055db179465dc8176f4/maintainability)](https://codeclimate.com/github/meeypioneer/mey-library/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/a055db179465dc8176f4/test_coverage)](https://codeclimate.com/github/meeypioneer/mey-library/test_coverage)
[![API Reference](https://godoc.org/github.com/meeypioneer/mey-library?status.svg)](https://godoc.org/github.com/meeypioneer/mey-library)

# mey-library

This repository is a collection of common libraries used in the meycoin project.
See [godoc](https://godoc.org/github.com/meeypioneer/mey-library) to get more detail descriptions and usages.

## config

Package config provides an easy way to create and manage configurations for meycoin projects written in go.

## db

Package db is an wrapper of database implementations. Currently, this supports [badgerdb](https://github.com/dgraph-io/badger).
More implementations (e.g. leveldb) will be updated in the future

## log

Package log is a global and configurable logger pkg, based on [zerolog](https://github.com/rs/zerolog)