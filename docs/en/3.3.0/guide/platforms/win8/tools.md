---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
---

# Windows 8 Command-line Tools

The `cordova` command-line utility is a high-level tool that allows
you to build applications across several platforms at once. An older
version of the Cordova framework provides sets of command-line tools
specific to each platform. To use them as an alternative to the CLI,
you need to download this version of Cordova from
[cordova.apache.org](http://cordova.apache.org). The download contains
separate archives for each platform. Expand the platform you wish to
target. The tools described here are typically available in the
top-level `bin` directory, otherwise consult the __README__ file for
more detailed directions.

For information on the low-level command-line interface that enables
plugins, see Using Plugman to Manage Plugins. See Application Plugins
for an overview.

## Windows 8

The Windows 8 command-line tools only support creating new projects.
Commands must be run from a cmd or powershell prompt.

## Create a Project

Run the `create` command with the following parameters:

* Path to your new Cordova Windows 8 project

* Package Name, following reverse-domain style convention. This becomes the default Namespace.

* Project name
