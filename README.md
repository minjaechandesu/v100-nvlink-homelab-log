# V100 NVLink Homelab Log

## Overview
This repository documents a personal homelab project using NVIDIA Tesla V100 SXM2 GPUs with NVLink.

The project started from pure curiosity after discovering OEM NVLink boards circulating in China.
It is not a commercial or ROI-driven setup, but a hands-on engineering log focused on learning
datacenter GPU hardware and scientific computing workflows.

## Hardware Specification

### System Overview
- Form factor: Open-frame home lab
- Usage: Non-datacenter personal engineering / scientific computing environment

### CPU
- AMD EPYC 7543

### Memory
- SK Hynix DDR4 ECC RDIMM 2933Y
- 64 GB × 4 (Total 256 GB)

### Motherboard
- Gigabyte MZ32-AR0

### GPU
- NVIDIA GeForce RTX 3090
- NVIDIA Tesla V100-SXM2-32GB ×2
- NVLink: OEM NVLink bridge board (China OEM)

### Power Delivery
- Main system (motherboard / CPU): Corsair RM850x
- GPU / NVLink subsystem: Seasonic Focus 1000W

### Cooling
- Air cooling
- All fans and heatsinks configured using Noctua components

![IMG_0104](https://github.com/user-attachments/assets/71b72ef4-cff0-4d1a-a411-4848f04449cd)

![IMG_0103](https://github.com/user-attachments/assets/c70a7a56-e0ca-428f-b9a1-7c05fd8d4b83)

![IMG_0102](https://github.com/user-attachments/assets/fb55964e-7789-41ac-a7f3-1f3d502ee2d3)


https://github.com/user-attachments/assets/475a06e2-d779-444d-b27a-58a5267b7d70

![IMG_0126](https://github.com/user-attachments/assets/136844ef-ea66-4b28-b987-ea4f8037db2e)




## Goals
- Practical experience with datacenter-grade GPUs
- Understanding NVLink topology and behavior
- Learning multi-GPU scientific computing workflows

## Notes
This repository is intended as an engineering log and reproducibility reference,
not as a performance benchmark or production guide.
