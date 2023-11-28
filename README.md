<br/>
<p align="center">
  <a href="https://github.com/Brian-Hwang/DAQS">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">DAQS</h3>

  <p align="center">
    Dynamic and Accurate QoS for SR-IOV
    <br/>
    Enhancing Quality of Service in Virtual Machine Systems
    <br/>
    <br/>
    <a href="https://daqsdemo.example.com"><strong>View Demo »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/Brian-Hwang/DAQS">Explore the docs</a>
    .
    <a href="https://github.com/Brian-Hwang/DAQS/issues">Report Bug</a>
    .
    <a href="https://github.com/Brian-Hwang/DAQS/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/Brian-Hwang/DAQS/total) ![Contributors](https://img.shields.io/github/contributors/Brian-Hwang/DAQS?color=dark-green) ![Issues](https://img.shields.io/github/issues/Brian-Hwang/DAQS) ![License](https://img.shields.io/github/license/Brian-Hwang/DAQS)

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About The Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

## About The Project

![Screen Shot](images/screenshot.png)

Single Root Input/Output Virtualization(SR-IOV) is a key feature in the PCI Express(PCIe) specifications, which facilitates the shared use of the same device in a virtualized environment by different virtual machines(VMs) and enables network traffic to bypass the usual virtualization stack, reducing interference among Virtual Functions(VFs). However, guaranteeing Quality of Service(QoS) as mandated by Service Level Agreements(SLAs) in these environments is challenging due to the host stack bypassing. This paper discusses these challenges and proposes an approach to ensure accurate QoS in SR-IOV environments by monitoring and regulating traffic from the host side through QEMU Guest Agent. The proposed approach automatically manages active VFs to meet SLA while fully utilizing the host bandwidth.

## Getting Started

### Prerequisites

- List of software and hardware prerequisites.

### Installation

1. Clone the repo

```sh
git clone https://github.com/Brian-Hwang/DAQS.git
```

2. Follow installation instructions

## Usage

Detailed usage instructions will be provided here.
