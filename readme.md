# Le Ngoc Uy Phong

**Digital Design Verification (DV)**  
Senior Computer Engineering Student, Ho Chi Minh City University of Technology (HCMUT)  
Open to **Design Verification Internship** opportunities (ASIC / IP / Subsystem Verification)

[Email](mailto:lengocuyphong@gmail.com) · [LinkedIn](https://www.linkedin.com/in/phong-le-ngoc-b196a53a8/)

---

## Focus

Dedicated exclusively to **Digital Design Verification** for ASIC and SoC designs. My core technical focus is **SystemVerilog for Verification**, complemented by **UVM 1.2 fundamentals**, solid RTL microarchitecture comprehension, and dual-vendor simulation and debug experience across **Synopsys** and **Cadence** Linux flows.

---

## Verification Skills & EDA Toolchain

| Area | Tools & Technologies |
| :--- | :--- |
| **Primary Language** | **SystemVerilog for Verification** (OOP, interfaces, clocking blocks, constrained-random stimulus, functional coverage, basic SVA, self-checking testbenches) |
| **Methodology & HDL** | **UVM 1.2** *(Fundamentals: agent, driver, monitor, sequencer, scoreboard, env, sequences)*, **Verilog HDL** (RTL analysis & testbenches), **Cocotb** (Python) |
| **Synopsys Toolchain** | **VCS** (simulation), **Verdi** (FSDB waveform & nTrace debug), **URG** (code & functional coverage), **SpyGlass** (RTL lint & static checks) |
| **Cadence Toolchain** | **Xcelium** (`xrun` simulation), **SimVision** / **Verisium Debug** (waveform & debug), **HAL** (RTL lint) |
| **Protocols & Workflow** | **AMBA APB**, **UART**, **RV32IM** microarchitecture · **Linux**, **Makefile**, **Bash**, **Tcl**, **Python**, **Git** |

---

## Selected Public Repositories

### [Register-based Timer with APB Interface](https://github.com/phonglengoc/Register-based-Timer-with-APB-interface)
`Verilog` · `AMBA APB`
- Configurable register-based timer RTL with an AMBA APB slave FSM supporting wait states (`apb_slave_fsm.v`, `timer_core.v`, `timer_top.v`).
- Verified register read/write transactions, wait-state handshaking, and timer configurations using a Verilog testbench (`tb/test_bench.v`).

### [5-Stage Pipelined RISC-V Processor (RV32IM)](https://github.com/phonglengoc/RISCV-Pipelined-Processor)
`Verilog` · `Cocotb` · `pytest` · `RV32IM`
- 5-stage pipelined RV32IM processor with forwarding bypasses (MX/WX/WD), load-use stall logic, branch flush, Carry-Lookahead Adder, and an 8-stage pipelined unsigned divider.
- Verified instruction execution and pipeline hazard behavior using a **Cocotb + pytest** architectural test suite (`testcase_python/testbench.py`) alongside directed Verilog testbenches (`tb_processor.v`).

### [SHA3-256 Hardware Core with UART Interface](https://github.com/phonglengoc/sha3-256)
`Verilog` · `UART` · `Keccak-f[1600]`
- Modular SHA3-256 (`Keccak-f[1600]`) RTL core integrated with UART RX/TX and a synchronization bridge (`top_system.v`).
- Validated module-level and system-level functionality through pattern-driven Verilog testbenches (`tb_top_system*.v`, `tb_uart.v`, `PATTERN_wrapper_v4.v`).
