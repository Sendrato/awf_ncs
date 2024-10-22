#  AWF NCS

This repository is meant to be used to build the environment based n NCS (nRF Connect SDK), containing the Onomondo
soft SIM library allowing to build the applications available in `awareable-fw/apps_ncs`.

The following repositories will be fetched:
- awareable-fw: awareable stack source code
- nrf: Sendrato's fork of NCS (nRF Connect SDK), used to fetch Zephyr OS and else everything needed by the SDK
- onomondo-softsim: Zephyr module to add softsim feature

Initialize the repository running:

`west init -m git@github.com:Sendrato/awf_ncs.git`

Then pull the other repositories running:

`west update`
