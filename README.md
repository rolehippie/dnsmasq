# dnsmasq

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/dnsmasq) [![Testing Build](https://github.com/rolehippie/dnsmasq/workflows/testing/badge.svg)](https://github.com/rolehippie/dnsmasq/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/dnsmasq/workflows/readme/badge.svg)](https://github.com/rolehippie/dnsmasq/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/dnsmasq/workflows/galaxy/badge.svg)](https://github.com/rolehippie/dnsmasq/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/dnsmasq)](https://github.com/rolehippie/dnsmasq/blob/master/LICENSE)

Ansible role to install and configure dnsmasq DNS caching server.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

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

- [rolehippie.docker](https://github.com/rolehippie/docker)

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
