# ViON - Common

Part of the ViON video surveillance platform ([vionvision.tech](https://vionvision.tech)).

Based on [camera.ui common](https://github.com/cameraui/common) by seydx (MIT), used with the author's permission.
Package names (`@camera.ui/*`, `camera-ui-*`) and Go module paths are kept for compatibility.
To pull upstream changes: `git remote add upstream https://github.com/cameraui/common.git && git fetch upstream && git merge upstream/main`.

[![npm](https://img.shields.io/npm/v/@camera.ui/common?label=npm&logo=npm)](https://www.npmjs.com/package/@camera.ui/common)
[![PyPI](https://img.shields.io/pypi/v/camera-ui-common?label=pypi&logo=pypi&logoColor=white)](https://pypi.org/project/camera-ui-common/)

Shared utilities and helpers powering the ViON ecosystem. Provides common building blocks such as logging, networking and camera helpers used across ViON packages.

Available for two runtimes:

| Runtime | Package                         |
| ------- | ------------------------------- |
| Node    | `@camera.ui/common` (`./node`)  |
| Python  | `camera-ui-common` (`./python`) |

---

_Part of the ViON ecosystem._
