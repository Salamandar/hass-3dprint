[![hacs][hacs-badge]](https://hacs.xyz)
[![License][license-shield]](LICENSE.md)
![Project Maintenance][maintenance-shield]

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
<!-- [![Build Status][build-shield]][build]
[![Test Coverage][coverage-shield]][coverage] -->


[hacs-badge]: https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/salamandar/hass-3dprint.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Salamandar-blue.svg?style=for-the-badge

[releases]: https://github.com/salamandar/hass-3dprint/releases
[releases-shield]: https://img.shields.io/github/release/salamandar/hass-3dprint.svg?style=for-the-badge

[commits]: https://github.com/salamandar/hass-3dprint/commits/master
[commits-shield]: https://img.shields.io/github/commit-activity/y/salamandar/hass-3dprint.svg?style=for-the-badge

[forum]: https://community.home-assistant.io/
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge

[build]: https://github.com/salamandar/hass-3dprint/actions/workflows/build.yaml
[build-shield]: https://img.shields.io/github/workflow/status/salamandar/hass-3dprint/Build?style=for-the-badge

[coverage]: https://app.codecov.io/gh/salamandar/hass-3dprint/
[coverage-shield]: https://img.shields.io/codecov/c/gh/salamandar/hass-3dprint?style=for-the-badge



# Hass-3dprint

_Component to integrate with 3D Printers._

**This component will set up the following platforms.**

Platform | Description
-- | --
`binary_sensor` | Show something `True` or `False`.
`sensor` | Show info from API.
`switch` | Switch something `True` or `False`.

![example][exampleimg]

{% if not installed %}
## Installation

1. Click install.
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Blueprint".

{% endif %}

## Installation

Easiest install is via [HACS](https://hacs.xyz/):

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=salamandar&repository=https%3A%2F%2Fgithub.com%2Fsalamandar%2Fhass-3dprint)

`HACS -> Explore & Add Repositories -> hass-3dprint`

Notes:

- HACS does not "configure" the integration for you. You must go to `Configuration > Integrations` and add your 3d printer after installing via HACS.

Please visit the [main documentation](https://github.com/salamandar/hass-3dprint)
for full installation instructions of this integration.
