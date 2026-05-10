# Inside Blackwell — Dual-Die, MX-FP4 / NVFP4, NVLink 5

A low-level deep dive into NVIDIA's 2024 Blackwell architecture: the dual-die B100/B200 packaging with the 10 TB/s NV-HBI link on CoWoS-L, 5th-generation tensor cores accelerating both MX-FP4 (open OCP, 32-element E8M0 blocks) and NVFP4 (NVIDIA, 16-element E4M3 blocks + per-tensor FP32) microscaling formats at ~9 PFLOPS dense FP4 per package, the 2nd-gen Transformer Engine, RAS and decompression engines, TEE-IO confidential computing, 192 GB HBM3e at 8 TB/s, NVLink 5 at 1.8 TB/s, NVSwitch 4 with NVLink-Sharp in NVL72, the GB200 Grace-Blackwell superchip, and the consumer RTX 50 series with GDDR7. Includes an interactive Blackwell SKU picker.

**Live site:** https://brendanjameslynskey.github.io/NVIDIA_GPU_32_Blackwell_Low_Level/

Part of the [NVIDIA GPU Architectures series](https://github.com/BrendanJamesLynskey/LLMs#nvidia-gpu-architectures).
