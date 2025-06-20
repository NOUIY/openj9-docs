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

# -Djdk.nativePBKDF2

This option enables or disables OpenSSL native cryptographic support for the PBKDF2 (Password based key derivation) algorithm.

## Syntax

        -Djdk.nativePBKDF2=[true|false]


| Setting           | value    | Default                                                                        |
|-------------------|----------|:------------------------------------------------------------------------------:|
| `-Djdk.nativePBKDF2` | true     | :fontawesome-solid-check:{: .yes aria-hidden="true"}<span class="sr-only">yes</span> |
| `-Djdk.nativePBKDF2` | false    |                                                                                |

## Explanation

OpenSSL support is enabled by default for the PBKDF2 algorithm. If you want to turn off support for this algorithm only, set this option to `false`. To turn off support for this and other algorithms, see the [`-Djdk.nativeCrypto`](djdknativecrypto.md) system property command line option.

## See also

- [What's new in version 0.53.0](version0.53.md#openssl-support-added-for-pbkdf2-algorithm)

<!-- ==== END OF TOPIC ==== djdknativepbkdf2.md ==== -->
