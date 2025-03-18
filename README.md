[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (-------------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (-------------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be useful,)
[comment]: <> (but WITHOUT ANY WARRANTY; without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the)
[comment]: <> (GNU Affero General Public License for more details.)

[comment]: <> (You should have received a copy of the GNU Affero General Public)
[comment]: <> (License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# EVM Chains Info

Returns information about EVM chains.

```bash
  evm-chains-info \
    [options] \
    <target_chain>
```

This program is a dependency for the
[EVM Contracts Tools](
  https://github.com/themartiancompany/evm-contracts-tools)
and it includes a JavaScript library used
by [libEVM](
  https://github.com/themartiancompany/libevm).

It is written and depends on the
[Crash Bash](
  https://github.com/themartiancompany/crash-bash)
library.

## Installation

The program in this source repo
can be installed from source using GNU Make.

```bash
make \
  install
```

It has officially published on the
the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`evm-chains-info`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  evm-chains-info
```

A censorable HTTP Github mirror of the recipe published there
is hosted on
[evm-chains-info-ur](
  https://github.com/themartiancompany/evm-chains-info-ur).
Be aware it could go offline any time.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
