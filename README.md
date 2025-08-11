# workspace

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/dnsmasq)
[![General Workflow](https://github.com/rolehippie/dnsmasq/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/dnsmasq/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/dnsmasq/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/dnsmasq/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/dnsmasq/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/dnsmasq/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/dnsmasq)](https://github.com/rolehippie/dnsmasq/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.dnsmasq-blue)](https://galaxy.ansible.com/rolehippie/dnsmasq)

Ansible role to install and configure dnsmasq DNS caching server.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [dnsmasq_addresses](#dnsmasq_addresses)
  - [dnsmasq_interfaces](#dnsmasq_interfaces)
  - [dnsmasq_listen_address](#dnsmasq_listen_address)
  - [dnsmasq_nameservers](#dnsmasq_nameservers)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### dnsmasq_addresses

List of addresses to map dns for

#### Default value

```YAML
dnsmasq_addresses: []
```

### dnsmasq_interfaces

List of interfaces to bind to

#### Default value

```YAML
dnsmasq_interfaces: []
```

### dnsmasq_listen_address

List of addresses to bind to

#### Default value

```YAML
dnsmasq_listen_address: []
```

### dnsmasq_nameservers

List of upstream name servers

#### Default value

```YAML
dnsmasq_nameservers:
  - 8.8.8.8
  - 1.1.1.1
```

## Discovered Tags

**_dnsmasq_**

## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
