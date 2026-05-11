<!--
SPDX-FileCopyrightText: 2026 Kaito Udagawa <umireon@kaito.tokyo>

SPDX-License-Identifier: Apache-2.0
-->

# vcpkg-registry-kaito-tokyo

A custom [vcpkg](https://vcpkg.io/) registry providing custom ports for Kaito.Tokyo.

## Adding Versions

Update the versions database with the following command:

```bash
vcpkg --x-builtin-ports-root="$(git rev-parse --show-toplevel)/ports" --x-builtin-registry-versions-dir="$(git rev-parse --show-toplevel)/versions" x-add-version --overwrite-version --all
```
