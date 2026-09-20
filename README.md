# SillyTavern API Connection Workspace

This repository documents my workspace configuration for running advanced open-weight LLMs on lightweight local hardware via cloud API endpoints.

## Hardware & Environment Setup
- **Client 1:** Android Environment via Termux (Mobile portability)
- **Client 2:** Local Laptop Node (NVIDIA RTX 3050 Laptop GPU)
- **Frontend:** SillyTavern

## Project Goal
Because local hardware limits execution to tiny 3B/8B quantized models, this setup leverages high-throughput cloud providers (like Fireworks AI) to proxy completions from larger models (like Llama-3-70B) directly into the SillyTavern API interface.
