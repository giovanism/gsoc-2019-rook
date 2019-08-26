# GSoC Meta Tracker: Enable multiple network interfaces for Rook storage providers

This repository contains [@giovanism][giovanism] progress and report during GSoC
programs.

## Project Abstract

> This project aims to create new API to enable multiple network interface for
> Rook storage providers. Currently, Rook providers only choice is to use
> hostNetwork or not. The new API will be used to define networks resource for
> Rook clusters. Rook operators will be able to consume those definitions and
> manage them. Therefore, it enables more fine-grained control over storage
> providers network access.

# Links

- [GSoc proposal][gsoc-proposal]
- [Project on GSoC website][gsoc-project]
- [Design: Multi-homed Cluster Network Spec][design-doc]

# Pull Requests

## Rook

- [rook/rook#3338][rook-3338] - Design: Multi-homed Cluster Network Spec
- [rook/rook#3576][rook-3576] - Multi-homing networking
- [rook/rook#3598][rook-3598] - docs: Update kubespray development-environment instructions

## Multus CNI

- [intel/multus-cni#351][multus-351] - Support pre v3.2 "interfaceRequest"

[giovanism]: https://github.com/giovanism
[gsoc-proposal]: https://github.com/giovanism/gsoc-2019-rook/blob/master/archive/Enable%20multiple%20network%20interfaces%20for%20Rook%20storage%20providers.pdf
[gsoc-project]: https://summerofcode.withgoogle.com/projects/#4703411130335232
[design-doc]: https://github.com/rook/rook/blob/master/design/multi-homed-cluster.md
[rook-3338]: https://github.com/rook/rook/pull/3338
[rook-3576]: https://github.com/rook/rook/pull/3576
[rook-3598]: https://github.com/rook/rook/pull/3598
[multus-351]: https://github.com/intel/multus-cni/pull/351
