# dnsmasq

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/dnsmasq) [![Testing Build](https://github.com/rolehippie/dnsmasq/workflows/testing/badge.svg)](https://github.com/rolehippie/dnsmasq/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/dnsmasq/workflows/readme/badge.svg)](https://github.com/rolehippie/dnsmasq/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/dnsmasq/workflows/galaxy/badge.svg)](https://github.com/rolehippie/dnsmasq/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/dnsmasq)](https://github.com/rolehippie/dnsmasq/blob/master/LICENSE) 

Ansible role to install and configure dnsmasq DNS caching server. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [dnsmasq_interfaces](#dnsmasq_interfaces)
  * [dnsmasq_listen_address](#dnsmasq_listen_address)
  * [dnsmasq_nameservers](#dnsmasq_nameservers)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

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

## Dependencies

* [rolehippie.docker](https://github.com/rolehippie/docker)

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
