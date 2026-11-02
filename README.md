# Maksim Nuzhdin

**Embedded Engineer · Camera Firmware · FPGA & Embedded Vision**

Based in Haifa, Israel. I develop embedded software and firmware for camera systems, with a focus on device control, image acquisition, hardware interfaces and debugging across firmware, FPGA and host software.

## Core competencies

- **Embedded C/C++:** camera firmware, device drivers, register maps, peripheral control and hardware bring-up.
- **Camera interfaces and control:** GenICam/GenApi XML, GigE Vision, CoaXPress, MIPI CSI-2 and V4L2 integration.
- **FPGA and SoC development:** AMD/Xilinx Zynq UltraScale+, Vivado, Vitis, RTL/HLS integration and image-processing pipelines.
- **System integration and debugging:** acquisition timing, exposure and trigger control, image transport, firmware updates and customer issue investigation.
- **Engineering tools:** Python utilities, automated checks, Git and technical documentation.

## Featured project — DinxTech MaxCamera

[**MaxCamera**](https://github.com/MaksimNuzhdin/MaxCamera) is my embedded vision portfolio project built around an **ALINX AXU2CGB (Zynq UltraScale+ XCZU2CG)** and an **OV5640 camera module**.

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
