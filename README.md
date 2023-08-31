# clickup

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/clickup)
[![General Workflow](https://github.com/rolehippie/clickup/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/clickup/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/clickup/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/clickup/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/clickup/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/clickup/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/clickup)](https://github.com/rolehippie/clickup/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.clickup-blue)](https://galaxy.ansible.com/rolehippie/clickup)

Ansible role to install clickup task management.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [clickup_appimage](#clickup_appimage)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### clickup_appimage

Download URL for the appimage to install

#### Default value

```YAML
clickup_appimage: https://desktop.clickup.com/linux
```

## Discovered Tags

**_clickup_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
