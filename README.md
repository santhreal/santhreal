<div align="center">

# santh

**Open source Rust security and infrastructure tooling.**

Every tool is a crate. Every crate composes. Install any piece alone.

**[santh.dev](https://santh.dev)** · **[blog](https://santh.dev/blog/)** · **[crates.io](https://crates.io/users/santhreal)** · **[@SanthProject](https://x.com/SanthProject)**

</div>

```
santh
├─ tools       keyhog · gossan · wafrift · truestack · envseal
├─ libraries   codewalk · attackstr · secfinding · openpack · procjail
├─ engines     simdsieve · dfajit · flashsieve · ziftsieve · ebpfkit
└─ substrate   vyre · matchkit          # gpu - cpu - jit, one matching trait
```

## Flagship

| | |
|---|---|
| **[keyhog](https://github.com/santhreal/keyhog)** | Open-source secret scanner. 923 detectors, GPU + SIMD scan paths, SARIF output. `cargo install keyhog` |
| **[vyre](https://github.com/santhreal/vyre)** | Compiler-grade sequential GPU compute: workgroup-local stacks, queues, hashmaps, dominator trees, fixed-point dataflow. |
| **[gossan](https://github.com/santhreal/gossan)** | Attack surface management and recon: subdomains, ports, tech fingerprinting, hidden endpoints. |
| **[wafrift](https://github.com/santhreal/wafrift)** | WAF evasion testing toolkit: grammar + encoding mutation, dialect-specific bypasses, evolutionary search. |
| **[truestack](https://github.com/santhreal/truestack)** | Security-aware technology fingerprinting: what is actually running, not what headers claim. |

## Libraries and engines

| | |
|---|---|
| **[codewalk](https://github.com/santhreal/codewalk)** | Security-aware file tree walker: gitignore, binary detection, mmap, parallel. |
| **[simdsieve](https://github.com/santhreal/simdsieve)** | SIMD byte-pattern pre-filtering. AVX2, AVX-512, NEON behind one trait. |
| **[openpack](https://github.com/santhreal/openpack)** | Safe archive reader for ZIP-derived formats (ZIP, CRX, JAR, APK, IPA). |
| **[procjail](https://github.com/santhreal/procjail)** | Process sandbox for untrusted code: namespaces, firejail, bubblewrap. |
| **[attackstr](https://github.com/santhreal/attackstr)** | Grammar-based security payload generation, TOML-driven, mutation engine. |
| **[secfinding](https://github.com/santhreal/secfinding)** | Universal security finding types: Severity, Evidence, Finding, Reportable. |
| **[dfajit](https://github.com/santhreal/dfajit)** | JIT compilation of DFA transition tables to native x86-64 jump tables. |
| **[matchkit](https://github.com/santhreal/matchkit)** | Vocabulary types for multi-pattern matching, CPU or GPU. |
| **[flashsieve](https://github.com/santhreal/flashsieve)** | Storage-level pre-filtering for pattern matching. |
| **[ziftsieve](https://github.com/santhreal/ziftsieve)** | Search compressed data without full decompression. |
| **[ebpfkit](https://github.com/santhreal/ebpfkit)** | Kernel-space eBPF JIT pipeline filter compiler. |

## Penetration testing

Human-led engagements run by the people who build these tools. Every engagement is scoped and priced over email: **contact@santh.dev** · [how engagements work](https://santh.dev/pentest/)

---

<sub>MIT or Apache-2.0 licensed. No JavaScript on [santh.dev](https://santh.dev). No trackers anywhere.</sub>
