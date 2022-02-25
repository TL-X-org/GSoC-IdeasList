# TL-X.org Google Summer of Code 2022 Project Ideas and Application Process

## Introduction

[TL-X.org](https://tl-x.org) is applying as an organization in [Google Summer of Code (GSoC) 2022](https://summerofcode.withgoogle.com/). We invite applicants who are relatively new to the world of open source to get involved in our mission. This would be our first year in GSoC, though TL-X projects have been a growing part of GSoC for several years under the umbrella of the [Free and Open Source Silicon Foundation (FOSSi)](https://www.fossi-foundation.org/). As you can see below, our projects tend to be small-scale, but large impact, and GSoC participants play leading roles in the projects.

## Past Projects

Under [FOSSi](https://www.fossi-foundation.org/), we've been involved in the following projects, resulting in blog posts, papers, presentations, tutorials, and awards, in addition to ground-breaking capabilities and demonstrations.

### 2021

**Bala Dhinesh**: Created a [Virtual FPGA lab](https://github.com/os-fpga/Virtual-FPGA-Lab) to augment physical FPGA lab classes. Bala subsequently conducted a tutorial session at VSDOpen 2021 using his work, and it has been adopted by the [Open Source FPGA Foundation](https://osfpga.org). Bala's work was awarded honorable mention in [UBooth@DAC](https://www.sigda.org/sigda-events/ubooth/).

**Ninad Jangle**: Explored [block-based circuit](https://github.com/ninja3011/Block_Based_Circuit_Design) design, using [Blockly](https://developers.google.com/blockly) to create point-and-click TL-Verilog modeling. With this proof-of-concept environment, Ninad was able to create a RISC-V CPU core without a text editor! Ninad's work was awarded honorable mention in [UBooth@DAC](https://www.sigda.org/sigda-events/ubooth/).

**Nitin Mishra**: Develop TL-Verilog logic for a [tensor core extension to RISC-V](https://github.com/natu4u/GSOC_TensorCore), described in this [blog](https://medium.com/@nmishra9/tensorcore-extension-for-deep-learning-41728fc22495).

**Vineet Jain**: Worked on a many-core [WARP-V](https://warp-v.org) (TL-Verilog RISC-V) implementation for cloud FPGAs, demonstrating visualization of packet flow and execution of a simple many-core test program.

2021 projects are summarized in this [blog](https://www.linkedin.com/pulse/what-students-up-tl-verilog-gsoc-2021-steve-hoover/), showing how well we all executed to the [plan](https://www.linkedin.com/pulse/another-exciting-summer-tl-verilog-google-code-steve-hoover/).

### 2020

**Shivam Potdar**: Added M-type extensions and long-latency instruction support to [WARP-V](https://warp-v.org), complete with formal verification, and prepared it for Linux boot and many-core integration with [OpenPiton](https://parallel.princeton.edu/openpiton/).

**Vineet Jain**: Added F-type and B-type extensions to [WARP-V](https://warp-v.org), and contributed to network-on-chip development.

### 2019

**Akos Hadnagy**: Extended the [1st CLaaS](https://github.com/os-fpga/1st-CLaaS) framework for hardware acceleration using cloud FPGAs with automated deployment and support for local development with ~100x faster simulation than using Xilinx's tools! His work was featured on the [Google open-source blog](https://opensource.googleblog.com/2019/09/unleashing-open-source-silicon.html).

**Alaa Salman**: Characterized the [WARP-V](https://warp-v.org) core on Xilinx FPGAs; completed a study of synthesis retiming capabilities; and demonstrated the integration of WARP-V (in TL-Verilog) with Rocket (in Chisel).

### 2018

**Akos Hadnagy**: Formally verified [WARP-V](https://warp-v.org), resulting in a [paper](https://arxiv.org/pdf/1811.12474.pdf), a [blog post](https://www.semiwiki.com/forum/content/7850-verifying-risc-v-1-page-code-e.html) on SemiWiki, and presentations at [ORConf](https://youtu.be/fqr4Z9wLNvQ) and VSDOpen highlighting the benefits of TL-Verilog for verification.

**Ahmed Salman**: Extended a library of generic TL-Verilog "flow" components and co-authored a [paper](https://arxiv.org/pdf/1811.01780.pdf) illustrating the long-sought-after feasibility of top-down hardware modeling.


## Application Guidelines

In your project proposal (application) please follow the general [guidance from GSoC](https://google.github.io/gsocguides/student/writing-a-proposal).

### Before Applying

While we aim to invite new contributors to our community, GSoC tends to be very competitive, and TL-Verilog projects draw very strong interest from the community. While TL-X.org is not a household name, folks who know about us are very excited to be a part of the movement. Some even contribute after being rejected for GSoC. And most former GSoC participants, continue their involvement. It's not often you get an opportunity to disrupt an industry the size of the silicon industry.

The point is, while you are expected to be fairly new to open source, your application must stand out. Demonstrate your passion. Many successful applications have been from applicants we knew about before picking up their applications. They have done their homework. They have ramped up on the technology. They have demonstrated their abilities by completing course assignments or individual projects. They have shared with the community. At the same time, please do not ask uninformed questions just to make yourself known. This will ensure we don't bother reading your application. In addition, we look for bright minds, so if you are a student, you should be doing well in related coursework.

### Application Format

Please submit using `.pdf` format, and include the following information in your application (as suggested by GSoC, with additional information). Format your application to be well organized and easy to read.

#### Name and Contact Information

Putting your full name on the proposal is not enough. Provide full contact information, including email addresses, websites, social links, and telephone number.

#### Title

Your title should be short, clear and interesting. The job of the title is to convince the reviewer to read your synopsis.

#### Synopsis

Start your proposal with a short summary, designed to convince the reviewer to read the rest of the proposal.

#### Benefits to Community

Don’t forget to make your case for a benefit to the organization, not just to yourself. Why would Google and your organization be proud to sponsor this work? How would open source or society as a whole benefit? What cool things would be demonstrated?

#### Deliverables

Include a brief, clear work breakdown structure with milestones and deadlines. Make sure to label deliverables as optional or required. You may want your plan to start by producing some kind of white paper, or planning the project in traditional Software Engineering style. It’s OK to include thinking time (“investigation”) in your work schedule. Deliverables should include investigation, coding and documentation.

#### Related Work

You should understand and communicate other people’s work that may be related to your own. Do your research, and make sure you understand how the project you are proposing fits into the target organization. Be sure to explain how the proposed work is different from similar related work.

#### Biographical Information

Keep your personal info brief. Be sure to communicate personal experiences and skills that might be relevant to the project. Summarize your education, work, and open source experience. List your skills and give evidence of your qualifications. Convince your organization that you can do the work. Any published work, successful open source projects and the like should definitely be mentioned. This section is like a resume, but targeted to your proposal.

### What We Look For

As we review your application we want to see that your application, especially your deliverables and timeline, demonstrate to us that you understand the work involved and its role in the community. We want to see realistic milestones and goals. And you must convince us, in your biography, that you can deliver.


## Google Summer of Code TL-X.org Ideas List 2022

Below are some project ideas for contributing in Google Summer of Code to the TL-X initiative to reinvigorate the silicon industry through open source.

You are encouraged to pursue ideas of your own, however, projects below have interested mentors. Before submitting a proposal outside of those listed below, it would be wise to first reach out to a potential mentor.
 
### TL-VHDL/TL-C/TL-Clash/etc.

TL-Verilog is a Verilog implementation of TL-X, and currently, Verilog is the only target language for TL-X. This project would see through the vision of layering transaction-level support in other languages. TL-VHDL would help to broaden the reach of the technology. TL-C would connect transaction-level design with System-C and therefore high-level synthesis. And, TL-Clash would explore the integration of transaction-level modeling with a stronger type system among other language benefits.

_Required skills_:

  - Hardware modeling in TL-Verilog, VHDL, System-C, and/or [Clash](https://qbaylogic.com/).
  - Java

_Experience_: intermediate/advanced

_Difficulty_: medium

_Duration_: ~350 hrs.

_Mentors_: Tuyen Truong, [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))


### TL-UVM

In theory, TL-X should be applicable to UVM as well as Verilog. Since UVM does not have open-source support, no one has yet tried. But it would be great to uncover issues and put together examples. It looks like Modelsim supports UVM and is freely available for Intel FPGAs. There might be other options.

_Required skills_:

  - UVM
  - TL-Verilog

_Experience_: intermediate/advanced

_Difficulty_: medium

_Duration_: ~175 or ~350 hrs.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))

### Visualization of SweRV

The SweRV core is an open-source SystemVerilog RISC-V CPU core developed by Western Digital. It is an interesting core for college course and is being highlighted in the [RVfpga course](https://www.imgtec.com/news/press-release/imagination-announces-the-first-risc-v-computer-architecture-course/) for one. Visualizing the operation of the core can greatly enhance the learning experience. This project aims to do so. SweRV is be built and simulated within Makerchip in [this repo](https://www.imgtec.com/news/press-release/imagination-announces-the-first-risc-v-computer-architecture-course/).

_Required skills_:

  - JavaScript and VIZ
  - CPU microarchitecture
  - SystemVerilog

_Experience_: intermediate

_Difficulty_: beginner/medium

_Duration_: ~350 hrs

_Discussion_: [TL-Verilog User's Slack workspace](https://join.slack.com/t/tl-verilog-users/shared_invite/zt-4fatipnr-dmDgkbzrCe0ZRLOOVm89gA) `#swerv-viz` channel.

_Mentors_: TBD from Western Digital/RVFPGA, [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))


### TL-Verilog Editor Modes

This general category of smaller projects improves the ecosystem for TL-Veriog development by creating editor support for various text editors and IDEs. Many editor modes already exist. A few possibilities include:

  - Tree-sitter support. This seems to currently have the strongest momentum across editors. It is used by Atom. There is a conversion flow for CodeMirror 6. VSCode does not currently support it, but this is likely coming soon.
  - Adding JavaScript editing support within the TL-Verilog mode for Code Mirror (used by Makerchip) for \viz blocks
  - Improved support for M4 editing in TL-Verilog mode for Code Mirror.
  - GitHub support for TL-Verilog (DONE, but awaiting acceptance)

_Experience_: intermediate

_Difficulty_: medium

_Duration_: ~175 or ~350 hrs.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))

### TL-Verilog Timing Reports

This project will help designers to relate timing information from synthesis tools back to TL-Verilog's higher-level context (hierarchy, pipelines, and transactions). Scripts are needed to map RTL signal names to their original TL-Verilog names. This will be applied to timing reports from open source synthesis tools so timing information can be reported with respect to TL-Verilog source code.

_Experience_: intermediate

_Duration_: ~175 or ~350 hrs.

_Duration_: ~175 or ~350 hrs.

_Mentors_: [Steve Hoover](https://www.linkedin.com/in/steve-hoover-a44b607/) ([email](mailto:steve.hoover@redwoodeda.com))
