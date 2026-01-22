..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025, 2026  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


================
evm-chains-info
================

----------------------------------------------------------------
Ethereum Virtual Machine Blockchains Information Retrieval Tool
----------------------------------------------------------------
:Version: evm-chains-info |version|
:Manual section: 1


Synopsis
========

evm-chains-info *[options]* (*target-chain*)


Description
===========

Returns info about EVM blockchains retrieving
the information from local databases in
JSON format in the format provided by
*evm-chains*.


Options
=======

-C target-command       Target command. It can be
                        - 'get' or
                        - 'set'.

-i input-type           Input type. It can be 'id' or 'name',
                        'amount'.

-o output-type          Output type. It can be 'id', 'name',
                        'rpc', 'explorers'.

-m retrieval-mode       It can be 'offline'.

-u <y/n>                Whether to look for the database in
                        he user level configuration directory.

-d db-path              Path of the chains' info json file
                        to be used for 'offline' retrieval
                        mode. Can be input more than once.

-s selection-method     When output type is 'rpc',
                        selection criterion to use when
                        more than one is available.
                        It can be 'kirsh', 'random' or
                        'all'.

-k                      Whether to include, when output type
                        is 'rpc', the ones requiring an api key.

-a                      Retrieve results for all networks.

-h                      Displays help message.

-c                      Enable color output

-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/evm-chains-info/-/issues


Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.


See also
========

* evm-chains

.. include:: variables.rst
