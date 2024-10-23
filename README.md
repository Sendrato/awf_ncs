#  AWF NCS

Repository to setup NCS / nRF Connect SDK (sendrato-fork) to build `awareable-fw/apps`.

The following repositories will be fetched:
- `nrf`: Sendrato's fork of NCS, used to fetch Zephyr OS and everything else needed by the SDK.
- `awareable-fw`: Awareable-stack.
- `onomondo-softsim`: Zephyr module to add Onomondo-softsim feature.

To setup repository:

```
mkdir <SOME-PATH>/awf-zephyr-env
cd <SOME-PATH>/awf-zephyr-env
west init -m git@github.com:Sendrato/awf_ncs.git --mr main
west update
```

> NOTE: For full setup of CLion and Zephyr SDK, see `awareable-fw` repository and wiki.
