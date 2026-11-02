![Embedded vision — Maksim Nuzhdin](assets/embedded-vision.svg)

# Maksim Nuzhdin

**Embedded Engineer · Camera Firmware · FPGA & Embedded Vision**

Based in Haifa, Israel. I develop embedded software and firmware for camera systems, with a focus on device control, image acquisition, hardware interfaces and debugging across firmware, FPGA and host software.


<p>
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&amp;logo=cplusplus&amp;logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" />
  <img alt="AMD Zynq" src="https://img.shields.io/badge/AMD_Zynq-141E30?style=for-the-badge&amp;logo=amd&amp;logoColor=white" />
  <img alt="FPGA ISP" src="https://img.shields.io/badge/FPGA_ISP-087F8C?style=for-the-badge" />
  <img alt="GenICam" src="https://img.shields.io/badge/GenICam-185D62?style=for-the-badge" />
</p>

## Core competencies

- **Embedded C/C++:** camera firmware, device drivers, register maps, peripheral control and hardware bring-up.
- **Camera interfaces and control:** GenICam/GenApi XML, GigE Vision, CoaXPress, MIPI CSI-2 and V4L2 integration.
- **FPGA and SoC development:** AMD/Xilinx Zynq UltraScale+, Vivado, Vitis, RTL/HLS integration and image-processing pipelines.
- **System integration and debugging:** acquisition timing, exposure and trigger control, image transport, firmware updates and customer issue investigation.
- **Engineering tools:** Python utilities, automated checks, Git and technical documentation.

## Featured project — DinxTech MaxCamera

[**MaxCamera**](https://github.com/MaksimNuzhdin/MaxCamera) is my embedded vision portfolio project built around an **ALINX AXU2CGB (Zynq UltraScale+ XCZU2CG)** and an **OV5640 camera module**.


### Through the lens — real MaxCamera captures

<table>
<tr><td align="center"><b>Linear FPGA baseline</b></td><td align="center"><b>Gamma 1.8</b></td><td align="center"><b>AWB + gamma preview</b></td></tr>
<tr><td><img src="https://raw.githubusercontent.com/MaksimNuzhdin/MaxCamera/main/docs/images/02.png" alt="MaxCamera linear FPGA baseline" width="270" /></td><td><img src="https://raw.githubusercontent.com/MaksimNuzhdin/MaxCamera/main/docs/images/03.png" alt="MaxCamera gamma 1.8 processing" width="270" /></td><td><img src="https://raw.githubusercontent.com/MaksimNuzhdin/MaxCamera/main/docs/images/01.png" alt="MaxCamera AWB and gamma preview" width="270" /></td></tr>
</table>

<sub>Saved camera frames · FW 0.3.12 / FPGA v10. The AWB preview uses automatic exposure/gain and is a separate operating mode. [Capture settings and full gallery](https://github.com/MaksimNuzhdin/MaxCamera/tree/main/docs/images).</sub>

The project combines:

- **R5 firmware** for camera control, acquisition and UDP image transport.
- An **FPGA ISP** with defect-pixel correction, black-level correction, gains/AWB, color correction, tone/gamma, denoising, sharpening and bounded scaling.
- **GenApi XML**, local device drivers, host utilities and offline tests.
- Source-based hardware reconstruction, build instructions, architecture documentation and verification reports.

A bounded test in the original development workspace delivered **57 frames at 14.29 FPS**, from a 320 × 240 RGB input scaled to 1280 × 960, with no missing or incomplete frames. A saved output frame exactly matched an independent Q12 reference.

See the repository's [verification scope](https://github.com/MaksimNuzhdin/MaxCamera/blob/main/docs/VERIFICATION.md) for test conditions and qualification limits.

[Explore MaxCamera](https://github.com/MaksimNuzhdin/MaxCamera) · [Documentation](https://github.com/MaksimNuzhdin/MaxCamera/blob/main/docs/INDEX.md)

## Contact

[LinkedIn](https://www.linkedin.com/in/maksim-nuzhdin-07ab96242/) · [Website](https://nuzhdinmaksim.com/)
