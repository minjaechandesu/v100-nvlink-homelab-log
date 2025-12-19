# System Summary

This document summarizes the actual hardware and software environment
used in this V100 SXM2 NVLink homelab project.

---

## Operating System
- OS: Ubuntu 24.04.3 LTS
- Kernel: 6.8.0-90-generic

---

## CPU
- AMD EPYC 7543

---

## Memory
- SK Hynix DDR4 ECC RDIMM 2933Y
- 64 GB × 4 (Total 256 GB)

---

## Motherboard
- Gigabyte MZ32-AR0

---

## GPU Configuration
- NVIDIA GeForce RTX 3090
- NVIDIA Tesla V100-SXM2-32GB ×2
- NVLink: OEM NVLink bridge board (China OEM)

---

## Driver & CUDA
- NVIDIA Driver: 580.95.05
- CUDA Version: 13.0

---

## Power Delivery
- Motherboard / CPU power: Corsair RM850x
- GPU / NVLink power: Seasonic Focus 1000W

---

## Cooling
- Air cooling
- All cooling components and fans are Noctua-based

---

## Notes
- V100 SXM2 GPUs detected correctly
- NVLink topology verified via `nvidia-smi topo -m`
- Operated in a non-datacenter home lab environment
