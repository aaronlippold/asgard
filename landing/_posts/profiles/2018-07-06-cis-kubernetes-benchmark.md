---
layout: post
date: 2018-07-06
github: https://gitlab.mitre.org/inspec/cis-kubernetes-benchmark.git
category: profile


# inspec.yml
name: cis-kubernetes-benchmark
title: CIS Kubernetes Benchmark Profile
maintainer: Kristian Vlaardingerbroek
copyright: Schuberg Philis B.V.
copyright_email: kvlaardingerbroek@schubergphilis.com
license: Apache-2.0
summary: An InSpec Compliance profile for the CIS Kubernetes Benchmark
version: 0.2.0
---

# CIS Kubernetes Benchmark - InSpec Profile

## Description
This profile implements the [CIS Kubernetes 1.1.0 Benchmark](https://www.cisecurity.org/benchmark/kubernetes/).

## Attributes

To switch between the CIS profile levels the following attribute can be used:

  * `cis_level: 2`
    define which profile level to use, accepted values are `1` and `2`.

## License and Author

* Author:: Kristian Vlaardingerbroek <kvlaardingerbroek@schubergphilis.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
