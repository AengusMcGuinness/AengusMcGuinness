# Aengus McGuinness

Harvard CS '27. I build C++ systems where latency matters.

**Now:** Senior at Harvard — Advanced Computer Networks, Advanced Topics in Computer Architecture, Systems Security. Writing lock-free queues on the side.

**Ironsite** (SF), May–August 2026 — Member of Technical Staff, Infrastructure. Autoscaled vLLM inference over GPU spot fleets, cross-cloud capacity and data residency, exactly-once processing under preemption.

### Selected work

- **[RCache](https://github.com/AengusMcGuinness/CS2640-Final-Project)** — one-sided RDMA distributed cache in C++/`libibverbs`. Three transports (TCP/RPC, two-sided RDMA, one-sided reads over a registered hash table); 974k ops/s at a flat 12 µs p99, 13× the throughput and 13× lower tail latency than TCP. → [report](https://aengusmcguinness.com/2640-report.pdf)
- **[Stream buffer prefetcher](https://github.com/AengusMcGuinness/1411-Project)** — Pin-based memory-hierarchy simulator over SPEC CPU2006. Jouppi fixed-depth streams collapse `libquantum`'s effective L1D misses 43×, while irregular workloads pay up to 9× the L2 traffic for ~2%. Team project; I built the fixed-depth simulator and the Pin sweep harness. → [report](https://aengusmcguinness.com/1411-report.pdf)

Most interested in problems where p99 is the constraint — low-latency networking, inference serving, and the layers below.

[aengusmcguinness.com](https://aengusmcguinness.com) · [LinkedIn](https://www.linkedin.com/in/aengus-mcguinness) · [Email](mailto:amcguinness@college.harvard.edu)
