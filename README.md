# Awesome WireGuard [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of WireGuard tools, projects, and resources.

WireGuard® - fast, modern, secure VPN tunnel.

## Contents

<details>

<summary><b>Expand Table of Contents</b></summary>

- [What is WireGuard](#what-is-wireguard)
- [Official Resources](#official-resources)
- [Where to Start](#where-to-start)
- [Projects](#projects)
  - [Tools](#tools)
  - [Mesh Network](#mesh-network)
  - Deployment
  - Monitoring
  - Security
    - Protocol
    - Encryption
  - Runtime
  - [User Interface](#user-interface)
    - [Terminal / CLI](terminal--cli)
    - [Web](#web)
    - Desktop
    - Dashboards
  - Development
    - Development Environment
    - Testing
    - Boilerplate
  - Homeserver
  - [Services based on WireGuard](#services-based-on-wireguard)
    - Cloud Service
    - [VPN](#vpn)
  - [Extensions / Plugins](#extensions--plugins)
  - Optimization
  - Language Bindings
  - [Alternative Implementations](#alternative-implementations)
- [Useful Resources](#useful-resources)
  - [Blog Posts](#blog-posts)
  - [Articles](#articles)
  - [Demos and Examples](#demos-and-examples)
  - [Good Tips](#good-tips)
  - [Tutorials](#tutorials)
  - [Videos](#videos)
  - [Books](#books)
  - [Podcasts and Interviews](#podcasts-and-interviews)
  - [Presentations](#presentations)
  - [Newsletters](#newsletters)
- Uncategorized
- Communities and Meetups
  - English
  - Chinese

</details>

---

## What is WireGuard

> WireGuard® is an extremely simple yet fast and modern VPN that utilizes 
> state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more 
> useful than IPsec, while avoiding the massive headache. It intends to be 
> considerably more performant than OpenVPN. WireGuard is designed as a general 
> purpose VPN for running on embedded interfaces and super computers alike, 
> fit for many different circumstances. Initially released for the Linux kernel, 
> it is now cross-platform (Windows, macOS, BSD, iOS, Android) and widely 
> deployable. It is currently under heavy development, but already it might 
> be regarded as the most secure, easiest to use, and simplest VPN solution 
> in the industry.

_Source: [Official WireGuard project website](https://www.wireguard.com/)_

## Official Resources
  
- [Next Generation Kernel Network Tunnel](https://www.wireguard.com/papers/wireguard.pdf) [PDF] - Whitepaper.
- [WireGuard Docs](https://github.com/pirate/wireguard-docs) - Unofficial WireGuard documentation.

## Where to Start

- [Quick Start](https://www.wireguard.com/quickstart/) - Official quick start.

---

## Projects

### Tools

- [wg-quick](https://git.zx2c4.com/wireguard-tools/about/src/man/wg-quick.8) - Official cross-platform tool to set up a WireGuard interface simply.
- [easy-wg-quick](https://github.com/burghardt/easy-wg-quick) - Creates Wireguard configuration for hub and peers with ease.
- [dsnet](https://github.com/naggie/dsnet/) - Simple command to manage a centralised wireguard VPN. Think wg-quick but quicker: key generation + address allocation.
- [wgctrl](https://github.com/WireGuard/wgctrl-go) - Package wgctrl enables control of WireGuard interfaces on multiple platforms.
- [Zero overhead wireguard setup](https://github.com/finzzz/wgzero)
- [wg-make](https://github.com/tevino/wg-make) - A tool to help set up WireGuard based networks. Currently, it generates configurations for peers according to a single configuration file.

### Mesh Network

- [Tailscale](https://tailscale.com/) - Tailscale is a WireGuard-based app that makes secure, private networks easy for teams of any scale.
- [Headscale](https://github.com/juanfont/headscale) - An open source implementation of the Tailscale control server.
- [innernet](https://github.com/tonarino/innernet) - A private network system that uses WireGuard under the hood. It is similar in its goals to Slack's nebula or Tailscale.
- [Kilo](https://github.com/squat/kilo) - Kilo is a multi-cloud network overlay built on WireGuard and designed for Kubernetes (k8s + wg = kg).
- [Wiretrustee](https://github.com/wiretrustee/wiretrustee) - Connect your devices into a single secure private WireGuard-based mesh network.
- [wesher](https://github.com/costela/wesher) - wesher creates and manages an encrypted mesh overlay network across a group of nodes.
- Not Wireguard-based
  - [Tinc](https://www.tinc-vpn.org/) - tinc is a VPN daemon that uses tunnelling and encryption to create a secure private network between hosts on the Internet.
  - [Nebula](https://github.com/slackhq/nebula) - Slack's Nebula is a scalable overlay networking tool.
  - [Zerotier](https://zerotier.com) - Directly Connecting the World's Devices with Universal Software Defined Networking.

### Deployment

### Monitoring

### Security

####  Protocol

#### Encryption

### Runtime

### User Interface

#### Terminal / CLI

- [WireGuard in NetworkManager](https://blogs.gnome.org/thaller/2019/03/15/wireguard-in-networkmanager/) - Linux NetworkManager has WireGuard support.
- [WireGuard installer](https://github.com/angristan/wireguard-install) - WireGuard VPN installer for Linux servers.
- [PiVPN](https://github.com/pivpn/pivpn) - The Simplest VPN installer (scripts), designed for Raspberry Pi.
- [wireguard-install](https://github.com/Nyr/wireguard-install) - WireGuard road warrior installer for Ubuntu, Debian, CentOS and Fedora.
- [WireGuard-Manager](https://github.com/complexorganizations/wireguard-manager) - enables you to build your own vpn under a minute.
- Desktop
  - [Network-Manager VPN Plugin for WireGuard](https://github.com/max-moser/network-manager-wireguard)

#### Web

- [vx3r/wg-gen-web](https://github.com/vx3r/wg-gen-web) - Simple Web based configuration generator for WireGuard.
- [Subspace](https://github.com/subspacecloud/subspace) - A simple WireGuard VPN server GUI.
- [WireGuard UI](https://github.com/EmbarkStudios/wg-ui) - WireGuard Web UI for self-serve client configurations, with optional auth.

#### Desktop

#### Dashboards

### Development

#### Development Environment

#### Testing

#### Boilerplate

### Homeserver

### Services based on WireGuard

#### Cloud Service

#### VPN

- [Mullvad](https://github.com/mullvad/mullvadvpn-app)

### Extensions / Plugins

- [wgsd](https://github.com/jwhited/wgsd) - A CoreDNS plugin that serves WireGuard peer information via DNS-SD (RFC6763) semantics. This enables use cases such as mesh networking, NAT-to-NAT connectivity, and dynamic discovery of WireGuard endpoint.

### Optimization

### Language Bindings

### Alternative Implementations

- [boringtun](https://github.com/cloudflare/boringtun) - Userspace WireGuard implementation in Rust by Cloudflare.

## Useful Resources

### Blog Posts

- [WireGuard: great protocol, but skip the Mac app](https://rachelbythebay.com/w/2020/12/24/wg/)
- [WireGuard on Kubernetes with Adblocking](https://codingcoffee.dev/blog/wireguard_on_kubernetes_with_adblocking/)
- [SSH and User-mode IP WireGuard](https://fly.io/blog/ssh-and-user-mode-ip-wireguard/)
- [Setup and Adblocking VPN Using WireGuard and NextDNS](https://blog.paramdeo.com/2019/07/03/setup-an-adblocking-vpn-using-wireguard-and-nextdns.html)
- [WireGuard Endpoint Discovery and NAT Traversal using DNS-SD](https://www.jordanwhited.com/posts/wireguard-endpoint-discovery-nat-traversal/)

### Articles

- [In-kernel WireGuard is on its way to FreeBSD and the pfSense router](https://arstechnica.com/gadgets/2021/03/in-kernel-wireguard-is-on-its-way-to-freebsd-and-the-pfsense-router/)
- [It's Looking Like Android Could Be Embracing WireGuard - "A Sane VPN"](https://www.phoronix.com/scan.php?page=news_item&px=WireGuard-Android-GKI-Enabled)

### Demos and Examples

### Good Tips

### Tutorials

- [How to easily configure WireGuard](https://www.stavros.io/posts/how-to-configure-wireguard/)
- [Getting Started with WireGuard](https://miguelmota.com/blog/getting-started-with-wireguard/)
- [What They Don’t Tell You About Setting Up A WireGuard VPN](https://dev.to/tangramvision/what-they-don-t-tell-you-about-setting-up-a-wireguard-vpn-1h2g)
- [Building a simple VPN with WireGuard with a Raspberry Pi as Server](https://snikt.net/blog/2020/01/29/building-a-simple-vpn-with-wireguard-with-a-raspberry-pi-as-server/)
- [Setting up a home VPN server with Wireguard (macOS)](https://mikkel.hoegh.org/2019/11/01/home-vpn-server-wireguard/)

### Videos

### Books

### Podcasts and Interviews

### Presentations

- [Presentations by Jason A. Donenfeld](https://www.wireguard.com/presentations/) - A list of all Jason's presentations.

### Newsletters

## Uncategorized

## Communities and Meetups

- English
- Chinese

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## Copyright

"WireGuard" and the "WireGuard" logo are registered trademarks of Jason A. Donenfeld.

## License

<details>

<summary><b>Expand License</b></summary>

This repository contains a variety of content; some developed by Cedric Chee, 
and some from third-parties. The third-party content is distributed under the 
license provided by those parties.

*I am providing code and resources in this repository to you under an open 
source license. Because this is my personal repository, the license you receive 
to my code and resources is from me and not my employer.*

The content developed by Cedric Chee is distributed under the following license:

### Text

The text content is released under the CC-BY-NC-ND license.
Read more at [Creative Commons](https://creativecommons.org/licenses/by-nc-nd/3.0/us/legalcode).

### Code

The code in this repository is released under the [MIT license](LICENSE).
</details>
