# Metrics Reporter, SLF4J as JSON

The built-in `SLF4JReporter` that ships with the `dropwizard/metrics` library writes its output in a plain-text format.

This library is a fork of that single class to support logging in a JSON format.

## Versioning

The version of this library is intended to match the version of the `io.dropwizard.metrics/metrics-core` dependency the `clubhouse/backend` code base depends on.

## Building

To start, the JAR will be built locally using `mvn package` and will then be committed to the `maven_repository` folder within the `clubhouse/backend` repository.

## License

Copyright © 2020 Clubhouse Software, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

### Original License

The code in this library was adapted from
[dropwizard/metrics][dropwizard-metrics], the copyright and license for which
are given below:

> Copyright (c) 2010-2013 Coda Hale, Yammer.com, 2014-2018 Dropwizard Team

> Published under Apache Software License 2.0, see LICENSE


<!-- Link URLS -->
[dropwizard-metrics]: https://github.com/dropwizard/metrics
