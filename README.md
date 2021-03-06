# mantis-examples

DEPRECATED - moved to https://github.com/netflix/mantis.

[![Build Status](https://img.shields.io/travis/com/Netflix/mantis-examples.svg)](https://travis-ci.com/Netflix/mantis-examples)
[![OSS Lifecycle](https://img.shields.io/osslifecycle/Netflix/mantis-examples.svg)](https://github.com/Netflix/mantis-examples)
[![License](https://img.shields.io/github/license/Netflix/mantis-examples.svg)](https://www.apache.org/licenses/LICENSE-2.0)

A list of simple Mantis jobs demonstrating various capabilities.

## sine-function
A simple single stage job that generates x and y co-ordinates for a sine wave.

## twitter-sample
Processes a twitter stream and performs a word count over a hopping window

## groupby-sample
A multi-stage job that generates synthetic request event data, groups the data
by URI and then calculates counts per URI over a rolling window.

## synthetic-sourcejob
A sample source job that serves a stream of request event data and allows the consumers
to query against it using the MQL language.

## jobconnector-sample
A simple example that demonstrates how to pipe the output of another job
into your job.

## mantis-publish-sample
An example of using the mantis-publish library to send events to Mantis.
