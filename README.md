[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Android WiFi Utils (`android-wifi-utils`)

A collection of utilities to easily manage various Android
WiFi settings.

Most of the utilities require administrative
permissions (root) on most Android devices.

Includes:

 - `android-bssid-scan`,
 - `wifi-tethering-status`: Returns tethering status.

It uses the
[Crash Bash](
  https://github.com/themartiancompany/crash-bash)
library.

## Installation

The program in this source repository
can be installed from source using GNU Make.

```bash
make \
  install
```

The utilities has been officially published
on the the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
