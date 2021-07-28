# bitcoind-observer

An experimental Prometheus metric exporter for Bitcoin Core based on _Userspace,
Statically Defined Tracing_ and [eBPF](https://ebpf.io).

This demo is based on **not-yet-released** Bitcoin Core code added in PR
[#22006 tracing: first tracepoints and documentation on User-Space, Statically Defined Tracing (USDT)](https://github.com/bitcoin/bitcoin/pull/22006).

The bitcoind-observer is written in Rust and open source. Code can be found on
[github.com/0xb10c/bitcoind-observer](https://github.com/0xb10c/bitcoind-observer).