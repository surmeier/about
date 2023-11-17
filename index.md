---
layout: null
---

<link rel="stylesheet" type="text/css" href="styles.css">

Hi, my name is Carson. I'm currently majoring in math and computer science at 
Northwestern University. I work in the 
[Prescience Lab](http://presciencelab.org/), led by Professor Peter Dinda. 

My main research interests are operating system microkernels, hardware/software 
formal verification, cryptography, and homotopy type theory. 

The following projects are my current focus:

- [Village](https://github.com/vlang-project): compiler for NESL/VCODE to 
LLVM-IR. My current work is adding exception support to RISC-V Vector 
Extensions in the 
[BOOM/Ocelot](https://github.com/tenstorrent/riscv-ocelot) core.

  Significant portions of BOOM written in Verilog are being converted to 
  verified Chisel through 
  [ChiselVerify](https://www.sciencedirect.com/science/article/pii/S0141933122002666). 
  A portion of this work is done at 
  [Sandia National Lab](https://www.sandia.gov/).

- `Beet Takeshi` (Creator): a provably perfect decompilation of the `NES` game 
[Takeshi no Chōsenjō](https://en.wikipedia.org/wiki/Takeshi_no_Ch%C5%8Dsenj%C5%8D).

I'm also actively working on the following projects:

- [Constellation](https://constellation-project.net/): NU and CMU project
group aimed at developing full software and hardware stack for frictionless 
heterogeneous parallelism.

- [Privacy Backplane](https://privacy-backplane.org/): NU, UMich, and Pitt 
project group focused on enabling individualized privacy policies in TEE-enabled
IoT environments, such as cashierless stores. 

- [WASMwand](https://github.com/wasmwand) (Creator, Senior Thesis): 
a topological [MLIR](https://mlir.llvm.org/) dialect and 
[unikernel](http://unikernel.org/) WASM runtime for distributed networks. 
A whitepaper, literature review, and MVP will be released August 1st, 2024; 
little to no project details will be shared until then.

- `Tortoise` (Creator): a distributed model of differential privacy, and a
[libp2p](https://libp2p.io/) implementation of said model. Builds upon ideas 
from `Privacy Backplane`. I'm currently integrating Kademlia DHT and Gossip-Sub 
based clock sync into the `libp2p` work.

- `BEANDIP`: using dispersed interrupt polling to replace hardware interrupts. 
I'm working on using BEANDIP in conjunction with the
[Green-Tao theorem](https://en.wikipedia.org/wiki/Green%E2%80%93Tao_theorem) 
and a FPGA prime sequence generator to mitigate timing-related side-channel attacks.

Notable previous work:

- `CARAT KOP`: memory guards for Linux kernel modules. A paper on this topic 
was accepted to [ROSS 2023](https://events.cels.anl.gov/ross/2023/) as of 
September 8th, 2023. 

- [Nautilus Microkernel](https://github.com/PeterDinda/nautilus), core member 
of the team responsible for the `RISC-V` and `ARMv8-A` port.

- `TrackFM`: a transparent, and user level, far memory management system, 
developed at Hexsa Lab in [IIT](https://www.iit.edu/). Work was focused on 
`LLVM` integration.

- Linux kernel projects:
[Mesa VirGL](https://docs.mesa3d.org/drivers/virgl.html),
[KVM](https://www.linux-kvm.org/page/Main_Page)

Language knowledge:

- I'm highly proficient in `Rust`, `C`, `C++`, `Lean 4`, `Scala/Chisel HDL`, 
`RISC-V Assembly`, `WASM`, `R/ggplot2`, and `Python`.

- I have high familiarity with and am actively learning `TLA+`, `Sail DSL`, 
`Haskell`, `Coq`, `Cubical Agda`, and `Nix`.

I also work on open-source maintenance on a variety of small projects.
In my free time I like playing online Go, marathon running, and 
retrofitting the fans in my server rack so I can sleep.
If you're interested in working on something together, contact me at 
`first_name@surmeier.us`
