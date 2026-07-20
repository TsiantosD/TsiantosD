<h1 align="center">Hi, I'm Dimitrios Tsiantos</h1>

<p align="center">
  <strong>Computer Architecture · High-Performance Computing · Hardware Security</strong>
</p>

<p align="center">
  My work focuses on RISC-V systems, FPGA design, hardware reliability,
  parallel computing, and hardware/software co-design.
</p>

<p align="center">
  <a href="https://tsiantosd.tech"><strong>Portfolio</strong></a>
  ·
  <a href="https://github.com/TsiantosD"><strong>GitHub</strong></a>
</p>

<!-- <div style="display: flex;">
  <p align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=TsiantosD&theme=github_dark" alt="GitHub statistics for TsiantosD" />
  </p>
  <p align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TsiantosD&theme=github_dark" alt="GitHub contribution summary for TsiantosD" />
  </p>
</div> -->

## Table of Contents

- [About Me](#about-me)
- [Featured Projects](#featured-projects)
- [Project Index](#project-index)
- [Technologies & Tools](#technologies--tools) <!-- - [Current Focus & Interests](#current-focus--interests) -->
- [GitHub Activity](#github-activity)
- [Contact](#contact)

## About Me

I am interested in the intersection of **computer architecture, digital hardware, hardware security, and high-performance computing**. My projects range from RISC-V processor experimentation and FPGA evaluation to fault simulation for VLSI circuits, electromagnetic side-channel research, CUDA optimization, embedded systems, and network protocols.

I enjoy building complete and reproducible engineering workflows that combine low-level implementations with correctness testing, automation, measurements, and clear technical documentation.

## Featured Projects

### [ECE494 — CV32E40P Forwarding Experiments](https://github.com/TsiantosD/ECE494-Microprocessor-Design)

A RISC-V microprocessor design project comparing forwarding variants of the **CV32E40P** core on a ZedBoard-style FPGA platform.

- Evaluates baseline, no-multiplier-forwarding, no-ALU-forwarding, and combined RTL variants.
- Includes assembly-level regression tests and bare-metal RV32IM benchmarks.
- Automates Vivado timing, utilization, power, and critical-path report generation.
- Compares implementation-level results with benchmark cycle measurements.

**Technologies:** RISC-V, SystemVerilog, FPGA, Vivado, Python, Tcl, C, Assembly

---

### [ECE455 — DDR RAM Electromagnetic Air-Gap Exfiltration](https://github.com/TsiantosD/ECE455-Hardware-Security)

An end-to-end hardware-security project that converts controlled DDR memory activity into electromagnetic leakage recoverable with an SDR receiver.

- Implements a user-space C transmitter using controlled RAM activity and non-temporal memory operations.
- Uses an ADALM-PLUTO SDR and GNU Radio for signal reception and OOK demodulation.
- Includes Python tools for framing, alignment, bit recovery, and error analysis.
- Documents experiments across multiple transmission rates and receiver distances.

**Technologies:** C, Python, GNU Radio, SDR, ADALM-PLUTO, Hardware Security

---

### [ECE415 — High-Performance Computing](https://github.com/TsiantosD/ECE415-High-Performance-Computing)

A collection of CPU and GPU optimization projects covering profiling, shared-memory parallelism, CUDA kernels, and multi-GPU execution.

- Optimized Sobel edge detection and K-Means implementations.
- Developed CUDA implementations of 2D convolution and CLAHE.
- Built an N-body simulator with CPU, OpenMP, CUDA, streams, shared-memory tiling, thread coarsening, and multi-GPU variants.
- Uses plots and CSV summaries to compare correctness and throughput across implementations.

**Technologies:** C, C++, CUDA, OpenMP, Python, Linux, Make

---

### [ECE484 — Soft Error Rate Simulator](https://github.com/TsiantosD/ECE484-Radhard-Circuit-Design)

A gate-level netlist parser and simulator for studying fault propagation and **Soft Error Rate (SER)** in digital circuits.

- Parses post-synthesis Verilog netlists into custom C data structures.
- Levelizes circuits and evaluates them across input vectors.
- Injects gate-level bit flips and tracks propagation to sequential elements.
- Validates the custom simulator against Icarus Verilog results.
- Provides a Docker-based workflow for reproducible execution.

**Technologies:** C, Verilog, Python, Docker, Icarus Verilog, Shell

---

### [UPSET](https://github.com/TsiantosD/UPSET)

A collaborative framework for **Single Event Transient analysis** and optimization of VLSI circuits using Static Timing Analysis principles.

- Supports SET generation and propagation across complete circuits.
- Uses timing models and static analysis to provide a faster alternative to exhaustive SPICE-level simulation.
- Includes a Docker Compose workflow, example designs, scripts, reports, and documentation.

**Technologies:** Verilog, Python, Tcl, Docker, VLSI, Static Timing Analysis

[Documentation](https://circuits-and-systems-lab-caslab.github.io/UPSET/)

---

### [Personal Portfolio](https://github.com/TsiantosD/TsiantosD.github.io)

My personal website for presenting engineering projects, coursework, technical reports, and project media.

**Technologies:** TypeScript, JavaScript, HTML, CSS

[Visit tsiantosd.tech](https://tsiantosd.tech)

## Project Index

### Computer Architecture, Digital Design & Reliability

| Project | Description | Main technologies |
| --- | --- | --- |
| [ECE494 — Microprocessor Design](https://github.com/TsiantosD/ECE494-Microprocessor-Design) | CV32E40P forwarding experiments, RTL verification, benchmarks, and FPGA evaluation. | RISC-V, SystemVerilog, Vivado, Python |
| [ECE484 — Rad-Hard Circuit Design](https://github.com/TsiantosD/ECE484-Radhard-Circuit-Design) | Gate-level parser, simulator, fault injection, and SER analysis. | C, Verilog, Python, Docker |
| [UPSET](https://github.com/TsiantosD/UPSET) | Static-timing-based Single Event Transient analysis for VLSI circuits. | Verilog, Python, Tcl, Docker |
<!-- | [CV32E40P Fork](https://github.com/TsiantosD/cv32e40p) | Working fork of the OpenHW Group CV32E40P RISC-V processor core. | SystemVerilog, RISC-V, C, Tcl | -->

### Parallel & High-Performance Computing

| Project | Description | Main technologies |
| --- | --- | --- |
| [ECE415 — High-Performance Computing](https://github.com/TsiantosD/ECE415-High-Performance-Computing) | CPU optimization, OpenMP, CUDA kernels, and multi-GPU experiments. | C, C++, CUDA, OpenMP, Python |
<!-- | [Benchmark Framework](https://github.com/TsiantosD/benchmark-framework) | Supporting framework for collecting and processing benchmark results. | Python, C++, Make | -->

### Hardware Security, Embedded Systems & Communications

| Project | Description | Main technologies |
| --- | --- | --- |
| [ECE455 — Hardware Security](https://github.com/TsiantosD/ECE455-Hardware-Security) | DDR electromagnetic covert channel using SDR reception and signal processing. | C, Python, GNU Radio, SDR |
| [ECE340 — Embedded Systems](https://github.com/TsiantosD/ECE340-Embedded-Systems) | Embedded-systems coursework and hardware/software experiments. | Ada, C, VHDL, Verilog |
| [ECE436 — Wireless Communications](https://github.com/TsiantosD/ECE436-Wireless-Communications) | Wireless-communications coursework and simulation material. | C, Shell, Make |

### Operating Systems, Databases & Networking

| Project | Description | Main technologies |
| --- | --- | --- |
| [ECE318 — Operating Systems](https://github.com/TsiantosD/ECE318-Operating-Systems) | Three operating-systems projects and related systems software. | C, Assembly, Shell |
| [ECE311 — Databases](https://github.com/TsiantosD/ECE311-Databases) | Database coursework and supporting development environment. | Python, Docker, Shell |
| [ECE313 — Networks I](https://github.com/TsiantosD/ECE313-Networks1) | Semester project for computer networking. | Python, Shell |
| [ECE441 — Inter-network Protocol Design](https://github.com/TsiantosD/ECE441-Inter-network-Protocol-Design) | Experiments and implementations related to network protocol design. | Python, Shell |

### Software & Web Development

| Project | Description | Main technologies |
| --- | --- | --- |
| [Personal Portfolio](https://github.com/TsiantosD/TsiantosD.github.io) | Personal engineering portfolio and project showcase. | TypeScript, JavaScript, HTML, CSS |
| [Earth Invaders](https://github.com/TsiantosD/earth-invaders) | Java game project. | Java |
| [Shopranos Theme](https://github.com/TsiantosD/shopranos-theme) | Front-end theme developed for a Shopranos hackathon. | JavaScript, HTML, CSS, SCSS |
| [Blog App](https://github.com/TsiantosD/blog-app) | Demo blog application developed for interviewing purposes. | PHP, Blade, JavaScript, Docker |
| [CodeWeek GitHub Course](https://github.com/TsiantosD/CodeWeekGithubCourse) | Introductory web and GitHub course material. | HTML, CSS |

## Technologies & Tools

### Programming Languages

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,python,java,js,ts,php,bash&perline=10" alt="C, C++, Python, Java, JavaScript, TypeScript, PHP, HTML, CSS, and Bash" />
</p>

<p>
  <!-- <img src="https://img.shields.io/badge/Ada-025E8C?style=for-the-badge&logo=ada&logoColor=white" alt="Ada" /> -->
  <img src="https://img.shields.io/badge/Assembly-6E4C13?style=for-the-badge&logo=assemblyscript&logoColor=white" alt="Assembly" />
  <img src="https://img.shields.io/badge/Tcl-1E5A96?style=for-the-badge&logo=tcl&logoColor=white" alt="Tcl" />
</p>

### Hardware, Architecture & Parallel Computing

<p>
  <img src="https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white" alt="RISC-V" />
  <img src="https://img.shields.io/badge/SystemVerilog-7E4A8C?style=for-the-badge&logoColor=white" alt="SystemVerilog" />
  <img src="https://img.shields.io/badge/Verilog-5C2D91?style=for-the-badge&logoColor=white" alt="Verilog" />
  <img src="https://img.shields.io/badge/VHDL-1565C0?style=for-the-badge&logoColor=white" alt="VHDL" />
  <img src="https://img.shields.io/badge/FPGA-00979D?style=for-the-badge&logoColor=white" alt="FPGA" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/OpenMP-000000?style=for-the-badge&logo=openmp&logoColor=white" alt="OpenMP" />
</p>

### Engineering & Development Tools

<p>
  <img src="https://skillicons.dev/icons?i=git,github,linux,docker,cmake,vscode&perline=6" alt="Git, GitHub, Linux, Docker, CMake, and Visual Studio Code" />
</p>

<p>
  <img src="https://img.shields.io/badge/AMD%20Vivado-F15B2A?style=for-the-badge&logo=amd&logoColor=white" alt="AMD Vivado" />
  <img src="https://img.shields.io/badge/GNU%20Radio-2A2B2E?style=for-the-badge&logo=gnu&logoColor=white" alt="GNU Radio" />
  <img src="https://img.shields.io/badge/Icarus%20Verilog-4B0082?style=for-the-badge&logoColor=white" alt="Icarus Verilog" />
  <img src="https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=gnu&logoColor=white" alt="GNU Make" />
</p>

<!-- ## Current Focus & Interests

- RISC-V processor architecture and RTL verification
- FPGA timing, utilization, and power evaluation
- Hardware reliability, soft errors, and fault-tolerant circuit design
- Electromagnetic side channels and hardware security
- GPU programming and parallel performance optimization
- Reproducible hardware/software experimentation -->

## GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=TsiantosD&theme=github-dark-blue&hide_border=true" alt="TsiantosD GitHub contribution streak" />
</p>

## Contact

I am open to conversations and collaborations related to computer architecture, digital hardware, hardware security, and high-performance computing.

- **Portfolio:** [tsiantosd.tech](https://tsiantosd.tech)
- **GitHub:** [github.com/TsiantosD](https://github.com/TsiantosD)
