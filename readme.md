<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Fedora Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 

<!--[![lint](https://github.com/34N0/awesome-fedora-security/actions/workflows/lint.yaml/badge.svg)](https://github.com/34N0/awesome-fedora-security/actions/workflows/lint.yaml)-->

<!-- subtitle -->

Awesome Fedora Security: A curated collection of projects, featuring hardening scripts, configurations, spins, labs, and environments designed to secure and fortify the Fedora distribution.

<!-- image -->

<a href="https://fedoraproject.org/" target="_blank" rel="noopener noreferrer">
  <img width="150" src="fedora.png" />
</a>

<!-- description -->

[Fedora](https://fedoraproject.org/) is a user-friendly Linux distribution known for its commitment to open-source principles, regular updates, and emphasis on security.

</div>

<!-- TOC -->

## Contents

- [Automation](#automation)
- [Audit](#audit)
- [System Components](#system-components)
- [Images](#images)

<!--- [Follow](#follow)-->

<!-- CONTENT -->

## Automation

- [Fedora Hardened Script](https://github.com/qoijjj/fedora-hardened) - This is a script that hardens the default fedora installation significantly.

- [Ansible Role RHEL9 CIS](https://github.com/ansible-lockdown/RHEL9-CIS) - Automate CIS benchmark compliance with Ansible

- [SolidCore Scripts](https://github.com/solidc0re/solidcore-scripts) - This project aims to protect immutable Fedora variants against a variety of attack vectors with a collection of scripts.

## Audit

- [RHEL9 CIS Audit](https://github.com/ansible-lockdown/RHEL9-CIS-Audit) - Ability to audit a system using a lightweight binary to check the current state.

## System Components

- [Bubblewrap SUID](https://github.com/34N0/bubblewrap-suid-rpm) - This repository contains the .spec file for bundling a setuid variant of Bubblewrap as an RPM. This allows using flatpaks on immutable OSTree distributions with unprivileged_user_namespaces set to 0.

### Hardened Malloc

"Hardened Malloc" is a security-focused general purpose memory allocator providing the malloc API along with various extensions. It provides substantial hardening against heapcorruption vulnerabilities.

- [Fedora Extras](https://github.com/qoijjj/fedora-extras) ([COPR Package](https://copr.fedorainfracloud.org/coprs/qoijjj/hardened_malloc/))

- [RPM Hardened Malloc](https://github.com/solidc0re/rpm-hardened-malloc)

### Kernel Hardened

The hardened Linux kernel; originally from the Arch Linux repository and repackaged for Fedora Linux.

- [Kernel Hardened](https://github.com/d4rklynk/kernel-hardened) ([COPR Package](https://copr.fedorainfracloud.org/coprs/samsepi0l/HardHatOS/)) - This repository tracks the hardened Linux kernel from the Arch Linux repositories and packages ist for Fedora Linux.

## Images

- [Secureblue (Hardened Ublue Images)](https://github.com/secureblue/secureblue) - This repo takes the uBlue starting point and selectively applies minimal hardening so as to provide images that are partially hardened without sacrificing usability for most use cases.

- [Fedora Security Lab](https://github.com/fabaff/security-lab) - The Fedora Security Lab (FSL) provides a safe test environment to work on security auditing, forensics, system rescue and teaching security testing methodologies in universities and other organizations. This repository is a copy of the original development. 

<!-- END CONTENT -->

<!--## Follow-->

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

<!--Who else should we be following!?-->

<!--## Contributing-->

<!--[Contributions of any kind welcome, just follow the guidelines](contributing.md)!--<>

