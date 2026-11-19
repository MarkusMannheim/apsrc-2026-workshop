---
order: 3

title: "griphos: A rust and python package for modelling and solving electricity networks"

authors:
  - name: Dan Gordon
    presenter: true
    honorific: Dr
    affiliation: ANU Center for Energy Systems, The Australian National University
    affiliation-short: ACES, ANU

links:
  - label: Repository
    url: https://github.com/bsgip/griphos
  - label: Documentation
    url: https://bsgip.github.io/griphos/griphos/
---

γρῖφος: a riddle, a puzzle, a net.

[griphos](https://github.com/bsgip/griphos) is a new rust/python library for
modelling and solving electricity networks. The bulk of the library is written
in rust, with a convenient python package being provided via python bindings. It
aims to provide a very fast, robust, tightly targeted library that allows
multi-phase modelling of (largely distribution) networks. It leverages the
convenience of rust and python's package management, and is designed to be
suitable for inclusion in a range of software applications aimed both at
industry and academia. A fast power flow solver is included, with OPF to come.

The session will present a brief overview of griphos' features and the modelling
approach taken. The demonstration will feature benchmarking, will allow more
in-depth questions about the features, and will hopefully include a GUI
visualisation.
