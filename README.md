# litex-uv-template

Template repository for astral's uv packet manager for Enjoy-Digital's LiteX hardware framework

## Installation

```bash
sudo apt update
sudo apt install libevent-dev libjson-c-dev verilator
sudo apt install gcc-riscv64-unknown-elf
uv sync
```

> Note:
> Optionally, you can delete the `uv.lock` file to force `uv` to redownload and rebuild dependencies for your system.

## Quick test

```bash
uv run litex_sim --cpu-type=vexriscv
```
