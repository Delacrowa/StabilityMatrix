# Stability Matrix

[![Build](https://github.com/LykosAI/StabilityMatrix/actions/workflows/build.yml/badge.svg)](https://github.com/LykosAI/StabilityMatrix/actions/workflows/build.yml)
[![Discord Server](https://img.shields.io/discord/1115555685476868168?logo=discord&logoColor=white&label=Discord%20Server)](https://discord.com/invite/TUrgfECxHz)
[![Release](https://img.shields.io/github/v/release/LykosAI/StabilityMatrix?label=Latest%20Release&link=https%3A%2F%2Fgithub.com%2FLykosAI%2FStabilityMatrix%2Freleases%2Flatest)][release]

[release]: https://github.com/LykosAI/StabilityMatrix/releases/latest
[download-win-x64]: https://github.com/LykosAI/StabilityMatrix/releases/latest/download/StabilityMatrix-win-x64.zip
[download-linux-x64]: https://github.com/LykosAI/StabilityMatrix/releases/latest/download/StabilityMatrix-linux-x64.zip
[download-macos-arm64]: https://github.com/LykosAI/StabilityMatrix/releases/latest/download/StabilityMatrix-macos-arm64.dmg

[auto1111]: https://github.com/AUTOMATIC1111/stable-diffusion-webui
[sdwebui-directml]: https://github.com/lshqqytiger/stable-diffusion-webui-directml
[webui-ux]: https://github.com/anapnoe/stable-diffusion-webui-ux
[comfy]: https://github.com/comfyanonymous/ComfyUI
[sdnext]: https://github.com/vladmandic/automatic
[voltaml]: https://github.com/VoltaML/voltaML-fast-stable-diffusion
[invokeai]: https://github.com/invoke-ai/InvokeAI
[fooocus]: https://github.com/lllyasviel/Fooocus
[fooocus-mre]: https://github.com/MoonRide303/Fooocus-MRE
[ruined-fooocus]: https://github.com/runew0lf/RuinedFooocus
[fooocus-controlnet]: https://github.com/fenneishi/Fooocus-ControlNet-SDXL
[kohya-ss]: https://github.com/bmaltais/kohya_ss
[onetrainer]: https://github.com/Nerogar/OneTrainer

[civitai]: https://civitai.com/
[huggingface]: https://huggingface.co/

![Header image for Stability Matrix, Multi-Platform Package Manager and Inference UI for Stable Diffusion](https://cdn.lykos.ai/static/sm-banner-rounded.webp)

[![Windows](https://img.shields.io/badge/Windows%2010,%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)][download-win-x64]
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)][download-linux-x64]
[![macOS](https://img.shields.io/badge/mac%20os%20%28apple%20silicon%29-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)][download-macos-arm64]

Multi-Platform Package Manager and Inference UI for Stable Diffusion

### 🖱️ One click install and update for Stable Diffusion Web UI Packages
- Supports:
  - [Automatic1111][auto1111], [Stable Diffusion WebUI DirectML][sdwebui-directml], [SD Web UI-UX][webui-ux], [SD.Next][sdnext]
  - [Fooocus][fooocus], [Fooocus ControlNet SDXL][fooocus-controlnet], [Ruined Fooocus][ruined-fooocus]
  - [ComfyUI][comfy]
  - [VoltaML][voltaml]
  - [InvokeAI][invokeai]
  - [Kohya's GUI][kohya-ss]
  - [OneTrainer][onetrainer]
- Manage plugins / extensions for supported packages ([Automatic1111][auto1111], [Comfy UI][comfy], [SD Web UI-UX][webui-ux], and [SD.Next][sdnext])
- Easily install or update Python dependencies for each package
- Embedded Git and Python dependencies, with no need for either to be globally installed
- Fully portable - move Stability Matrix's Data Directory to a new drive or computer at any time

### ✨ Inference - A Reimagined Interface for Stable Diffusion, Built-In to Stability Matrix
- Powerful auto-completion and syntax highlighting using a formal language grammar
- Workspaces open in tabs that save and load from `.smproj` project files

![](https://cdn.lykos.ai/static/sm-banner-inference-rounded.webp)

- Customizable dockable and float panels
- Generated images contain Inference Project, ComfyUI Nodes, and A1111-compatible metadata
- Drag and drop gallery images or files to load states

<p align="center">
  <img style="width: 80%; height: 80%" src="https://github.com/LykosAI/StabilityMatrix/assets/13956642/4341cc34-a584-4e9c-bb3b-276009bdae80" alt=""/>
</p>

### 🚀 Launcher with syntax highlighted terminal emulator, routed GUI input prompts
- Launch arguments editor with predefined or custom options for each Package install
- Configurable Environment Variables

<p align="center">
  <img style="width: 80%; height: 80%" src="https://github.com/LykosAI/StabilityMatrix/assets/13956642/75456866-9d95-47c6-8c0a-fdc19443ee02" alt=""/>
</p>

### 🗃️ Checkpoint Manager, configured to be shared by all Package installs
- Option to find CivitAI metadata and preview thumbnails for new local imports

### ☁️ Model Browser to import from [CivitAI][civitai] and [HuggingFace][huggingface]
- Automatically imports to the associated model folder depending on the model type
- Downloads relevant metadata files and preview image
- Pause and resume downloads, even after closing the app

<p align="center">
  <img style="width: 80%; height: 80%" src="https://github.com/LykosAI/StabilityMatrix/assets/13956642/30b9f610-6033-4307-8d92-7d72b93cd73e" alt=""/>
</p>

### Shared model directory for all your packages
- Import local models by simple drag and drop
- Option to automatically find CivitAI metadata and preview thumbnails for new local imports

<p align="center">
  <img style="width: 80%; height: 80%" src="https://github.com/LykosAI/StabilityMatrix/assets/13956642/d42d1c53-67a4-45a0-b009-21400d44e17e" alt=""/>
</p>

- Find connected metadata for existing models
<p align="center">
  <img style="width: 80%; height: 80%" src="https://cdn.lykos.ai/static/sc-checkpoints-find-connected.gif" alt=""/>
</p>

## Localization
Stability Matrix is now available in the following languages, thanks to our community contributors:
- 🇺🇸 English
- 🇯🇵 日本語 
  - kgmkm_mkgm
- 🇨🇳 中文（简体，繁体）
  - jimlovewine
- 🇮🇹 Italiano
  - Marco Capelli
- 🇫🇷 Français
  - eephyne
- 🇪🇸 Español
  - Carlos Baena 
  - Lautaroturina
- 🇷🇺 Русский
  - aolko
- 🇹🇷 Türkçe
  - Progesor
- 🇩🇪 Deutsch
  - Mario da Graca
- 🇵🇹 Português
  - nextosai

If you would like to contribute a translation, please create an issue or contact us on Discord. Include an email where we'll send an invite to our [POEditor](https://poeditor.com/) project.

## Disclaimers
All trademarks, logos, and brand names are the property of their respective owners. All company, product and service names used in this document and licensed applications are for identification purposes only. Use of these names, trademarks, and brands does not imply endorsement.

## License

This repository maintains the latest source code release for Stability Matrix, and is licensed under the [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.en.html). Binaries and executable releases are licensed under the [End User License Agreement](https://lykos.ai/license).
