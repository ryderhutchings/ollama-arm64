# Ollama

![License](https://img.shields.io/github/license/ryderhutchings/ollama-arm64)
![GitHub Last Commit](https://img.shields.io/github/last-commit/ryderhutchings/ollama-arm64)
![GitHub Issues](https://img.shields.io/github/issues/ryderhutchings/ollama-arm64)
[![YouTube Subscribers](https://img.shields.io/youtube/channel/subscribers/UCfYoumlckdDcox4TtxZiKtA?label=YouTube&style=flat&color=red&logo=youtube)](https://www.youtube.com/@ryderhutchings)

Install script and setup guide for Ollama on AArch64 Linux devices.

This repo provides an easy install script and setup guide for running models like [deepseek-r1](https://registry.ollama.com/library/deepseek-r1) and [phi3.5](https://registry.ollama.com/library/phi3.5) using Ollama on ARM64 (AArch64) Linux devices, including the Raspberry Pi 5.

## Disclaimer

The official Ollama software is distributed as a binary package, which the script in this install guide downloads and configures automatically.

Ollama is proprietary software owned by its developers and is not included in this repository.
Users must download the Ollama binaries only from the official Ollama website or authorized sources.

This project is not affiliated with or endorsed by Ollama or its parent companies.
Use these scripts at your own risk.

### Getting Started:
> [!NOTE]
> The following install script is provided by the official [Ollama’s website](https://ollama.com/download/linux).

```bash

curl -fsSL https://ollama.com/install.sh | sh

```

### Using the Tool:

Once installed, you can run Ollama commands directly from your terminal:

###### Pull a model from the Ollama registry:
`ollama pull <model-name>`

###### Run a model with a prompt directly:
`ollama run <model-name> "Your prompt here"`

###### Run a model interactively without a prompt directly:
`ollama run <model-name>`

###### List all downloaded models:
`ollama list`

###### Get help and see available commands:
`ollama help`

### Installing DeepSeek-R1
To download and install the [DeepSeek-R1](https://registry.ollama.com/library/deepseek-r1) model:

`ollama pull deepseek-r1`

### Installing Phi-3.5
To download and install the [Phi-3.5](https://registry.ollama.com/library/phi3.5) model:

`ollama pull phi3.5`

