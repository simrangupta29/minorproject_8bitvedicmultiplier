
# 🔢 8×8 Vedic Multiplier using Verilog (Xilinx Vivado)

## 📌 Project Overview

This project focuses on the **design and implementation of an 8×8 Vedic Multiplier** using the **Urdhva Tiryagbhyam Sutra** from ancient Indian Vedic Mathematics.
The design is coded in **Verilog HDL** and implemented in **Xilinx Vivado** for FPGA-based digital circuit verification.

The Vedic Multiplier is optimized for:

* ✅ Reduced number of computational steps
* ✅ Lower delay & high speed
* ✅ Low power consumption
* ✅ Efficient memory utilization

---

## 🎯 Objectives

* Design and FPGA implementation of **4×4 and 8×8 Vedic Multipliers** using different architectures.
* Explore **Urdhva-Tiryagbhyam Sutra** for efficient multiplication.
* Reduce **delay and resource utilization** compared to conventional multipliers.
* Learn and implement digital design using **Verilog in Vivado**.

---

## 📖 Literature Background

* **Urdhva-Tiryagbhyam Sutra** (Vertically & Crosswise) enables parallel calculation of partial products.
* Reduces delay significantly compared to traditional multipliers.
* Best suited for **high-speed applications** such as DSP, microcomputers, and image processing.

---

## 🏗️ Research Methodology

1. Implement smaller multipliers (2×2, 4×4) using Vedic technique.
2. Build larger multipliers (8×8) by combining smaller blocks.
3. Code written in **Verilog HDL**.
4. Simulation and synthesis performed in **Xilinx Vivado**.

---

## ⚙️ Implementation Details

### 🔹 Verilog Modules

* **HA**: Half Adder
* **Adders**: 4-bit, 6-bit, 8-bit, 12-bit adders
* **Vedic\_2x2**: 2×2 multiplier using half adders
* **Vedic\_4x4**: Built using multiple 2×2 multipliers
* **Vedic\_8x8**: Built using multiple 4×4 multipliers

### 🔹 Testbench

* Testbench (`test_vedic_8`) verifies functionality of the 8×8 multiplier.
* Inputs: two 8-bit numbers (`a` and `b`).
* Output: 16-bit product (`c`).
* `$monitor` used for simulation outputs.

---

## 🧪 Experimental Study

* **Tool Used**: Xilinx Vivado

* **Steps**:

  1. Create a new project
  2. Add Verilog source files
  3. Run RTL Simulation
  4. Analyze schematic & synthesized design

* **Results**:

  * Delay reduced → Higher speed
  * Easy scalability to higher bit-width multipliers
  * Efficient for **DSP and image processing applications**

---

## 📊 Results

* Reduced **delay** and improved **speed** compared to conventional multipliers.
* Ease of implementation for larger arithmetic units.
* Demonstrates real-world application of **Vedic Mathematics** in digital design.

---

## 🚀 Future Work

* FPGA implementation of a fully functional 8×8 Vedic Multiplier.
* Perform **timing and resource utilization analysis**.
* Extend design for higher-bit multipliers (16×16, 32×32).
* Compare performance with traditional multiplier architectures.

## 🛠️ Tools & Technologies

* **Verilog HDL**
* **Xilinx Vivado**
* **FPGA-based implementation**


Would you like me to also include **example Verilog code snippets** (like your `vedic_2x2`, `vedic_4x4`, or `vedic_8x8` modules) inside the README so visitors can quickly see how the design is implemented?
