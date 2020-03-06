# Metrics Reporter, SLF4J as JSON

The built-in `SLF4JReporter` that ships with the `dropwizard/metrics` library writes its output in a plain-text format.

This library is a fork of that single class to support logging in a JSON format.

## Versioning

The version of this library is intended to match the version of the `io.dropwizard.metrics/metrics-core` dependency the `clubhouse/backend` code base depends on.

## Building

To start, the JAR will be built locally using `mvn package` and will then be committed to the `maven_repository` folder within the `clubhouse/backend` repository.
