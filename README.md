_TL-X.org will be applying as an organization in Google Summer of Code 2022. These are some project ideas for contributing in Google Summer of Code to the TL-X initiative to reinvigorate the silicon industry through open source._

# Google Summer of Code TL-X.org Ideas List 2022

## TL-VHDL/TL-C/TL-Clash/etc.

TL-Verilog is a Verilog implementation of TL-X, and currently, Verilog is the only target language for TL-X. This project would see through the vision of layering transaction-level support in other languages. TL-VHDL would help to broaden the reach of the technology. TL-C would connect transaction-level design with System-C and therefore high-level synthesis. And, TL-Clash would explore the integration of transaction-level modeling with a stronger type system among other language benefits.

_Required skills_:

  - Hardware modeling in TL-Verilog, VHDL, System-C, and/or [Clash](https://qbaylogic.com/).
  - Java

_Experience_: intermediate/advanced

_Difficulty_: medium

_Duration_: ~350 hrs.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))


## TL-UVM

In theory, TL-X should be applicable to UVM as well as Verilog. Since UVM does not have open-source support, no one has yet tried. But it would be great to uncover issues and put together examples. It looks like Modelsim supports UVM and is freely available for Intel FPGAs. There might be other options.

_Required skills_:

  - UVM
  - TL-Verilog

_Experience_: intermediate/advanced

_Difficulty_: medium

_Duration_: ~175 or ~350 hrs.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))

## Visualization of SweRV

The SweRV core is an open-source SystemVerilog RISC-V CPU core developed by Western Digital. It is an interesting core for college course and is being highlighted in the [RVfpga course](https://www.imgtec.com/news/press-release/imagination-announces-the-first-risc-v-computer-architecture-course/) for one. Visualizing the operation of the core can greatly enhance the learning experience. This project aims to do so. SweRV is be built and simulated within Makerchip in [this repo](https://www.imgtec.com/news/press-release/imagination-announces-the-first-risc-v-computer-architecture-course/).

_Required skills_:

  - JavaScript and VIZ
  - CPU microarchitecture
  - SystemVerilog

_Experience_: intermediate

_Difficulty_: beginner/medium

_Duration_: ~350 hrs

_Discussion_: [TL-Verilog User's Slack workspace](https://join.slack.com/t/tl-verilog-users/shared_invite/zt-4fatipnr-dmDgkbzrCe0ZRLOOVm89gA) `#swerv-viz` channel.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))


## TL-Verilog Editor Modes

This general category of smaller projects improves the ecosystem for TL-Veriog development by creating editor support for various text editors and IDEs. Many editor modes already exist. A few possibilities include:

  - Tree-sitter support. This seems to currently have the strongest momentum across editors. It is used by Atom. There is a conversion flow for CodeMirror 6. VSCode does not currently support it, but this is likely coming soon.
  - Adding JavaScript editing support within the TL-Verilog mode for Code Mirror (used by Makerchip) for \viz blocks
  - Improved support for M4 editing in TL-Verilog mode for Code Mirror.
  - GitHub support for TL-Verilog (DONE, but awaiting acceptance)

_Experience_: intermediate

_Difficulty_: medium

_Duration_: ~175 or ~350 hrs.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))

## TL-Verilog Timing Reports

This project will help designers to relate timing information from synthesis tools back to TL-Verilog's higher-level context (hierarchy, pipelines, and transactions). Scripts are needed to map RTL signal names to their original TL-Verilog names. This will be applied to timing reports from open source synthesis tools so timing information can be reported with respect to TL-Verilog source code.

_Experience_: intermediate

_Duration_: ~175 or ~350 hrs.

_Duration_: ~175 or ~350 hrs.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))
