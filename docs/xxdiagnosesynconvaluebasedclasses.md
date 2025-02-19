<!--
* Copyright (c) 2017, 2025 IBM Corp. and others
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
* [2] https://openjdk.org/legal/assembly-exception.html
*
* SPDX-License-Identifier: EPL-2.0 OR Apache-2.0 OR GPL-2.0-only WITH Classpath-exception-2.0 OR GPL-2.0-only WITH OpenJDK-assembly-exception-1.0
-->

# -XX:DiagnoseSyncOnValueBasedClasses

![Start of content that applies only to Java 16 and later](cr/java16plus.png) This HotSpot option provides warnings about improper attempts to synchronize on instances of a value-based class. The option is recognized by Eclipse OpenJ9&trade; for compatibility.


## Syntax

        -XX:DiagnoseSyncOnValueBasedClasses=<number>


| `<number>` value  | Effect                                       |
|-------------------|----------------------------------------------|
| 1                 | Generate `VirtualMachineError` error         |
| 2                 | Print a warning message                      |

## See also

- [What's new in version 0.25.0](version0.25.md#new-jdk-16-features)

<!-- ==== END OF TOPIC ==== xxdiagnosesynconvaluebasedclasses.md ==== -->
