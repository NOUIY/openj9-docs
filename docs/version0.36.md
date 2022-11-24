<!--
* Copyright (c) 2017, 2022 IBM Corp. and others
*
* This program and the accompanying materials are made
* available under the terms of the Eclipse Public License 2.0
* which accompanies this distribution and is available at
* https://www.eclipse.org/legal/epl-2.0/ or the Apache
* License, Version 2.0 which accompanies this distribution and
* is available at https://www.apache.org/licenses/LICENSE-2.0.
*
* This Source Code may also be made available under the
* following Secondary Licenses when the conditions for such
* availability set forth in the Eclipse Public License, v. 2.0
* are satisfied: GNU General Public License, version 2 with
* the GNU Classpath Exception [1] and GNU General Public
* License, version 2 with the OpenJDK Assembly Exception [2].
*
* [1] https://www.gnu.org/software/classpath/license.html
* [2] http://openjdk.java.net/legal/assembly-exception.html
*
* SPDX-License-Identifier: EPL-2.0 OR Apache-2.0 OR GPL-2.0 WITH
* Classpath-exception-2.0 OR LicenseRef-GPL-2.0 WITH Assembly-exception
-->

# What's new in version 0.36.0

The following new features and notable changes since version 0.35.0 are included in this release:

- [New binaries and changes to supported environments](#binaries-and-supported-environments)
- [New `-XX:JITServerAOTmx` option added](#new-xxjitserveraotmx-option-added)

## Features and changes

### Binaries and supported environments

Eclipse OpenJ9&trade; release 0.36.0 supports OpenJDK 8, 11, and 17.

To learn more about support for OpenJ9 releases, including OpenJDK levels and platform support, see [Supported environments](openj9_support.md).

### New `-XX:JITServerAOTmx` option added

This option specifies the maximum amount of memory that can be used by the JITServer AOT cache. Instead of unlimited memory consumption, the maximum amount of memory that all AOT cache instances combined can use at the server is now limited to 300 MB, by default.

For more information, see [`-XX:JITServerAOTmx`](xxjitserveraotmx.md).

## Known problems and full release information

To see known problems and a complete list of changes between Eclipse OpenJ9 v0.33.1 and v0.35.0 releases, see the [Release notes](https://github.com/eclipse-openj9/openj9/blob/master/doc/release-notes/0.35/0.35.md).

<!-- ==== END OF TOPIC ==== version0.35.md ==== -->
