---
order: 5

title: "BMOPF tools: reproducible optimisation of unbalanced distribution networks"

authors:
  - name: Sleiman Mhanna
    honorific: Dr
    affiliation: The University of Melbourne
    affiliation-short: UniMelb


links:
  - label: VVWO
    url: https://arxiv.org/abs/2609.15370
  - label: Tellegen
    url: https://tellegen.dev/
  - label: Tellegen repository
    url: https://github.com/eigenergy/tellegen
  - label: BMOPFTools
    url: https://github.com/frederikgeth/BMOPFTools.jl
  - label: IEEE taskforce community
    url: https://github.com/distribution-system-opt/math-and-data-model-specifications
---

This talk introduces the open-source modelling resources and tools of the IEEE PES Task Force on Benchmarking Multiconductor OPF for Distribution Systems ([BMOPF](https://github.com/distribution-system-opt)). The task force is developing shared mathematical and data specifications to enable meaningful benchmarking and reproducible research on unbalanced distribution networks. The presentation will introduce [BMOPFTools.jl](https://github.com/frederikgeth/BMOPFTools.jl) and its capabilities for inspecting and preparing network models, performing multiconductor power flow and optimal power flow, and checking results.

A live demonstration in [Tellegen](https://tellegen.dev/) will showcase interactive exploration of distribution network models and results, including optimal power flows across medium- and low-voltage (MV-LV) networks and Volt-VAr-Watt optimisation (VVWO) in unbalanced four-wire networks. The VVWO example will highlight agreement with OpenDSS when it converges and improved convergence reliability for the proposed VVWO formulations in the tested cases with high PV uptake. The demonstration will illustrate how open tools can make power flow and optimisation studies more accessible. The talk will also highlight opportunities to use and contribute to these shared modelling resources.
