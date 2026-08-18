# heroeswearkapes Unraid Community Apps

Unraid Community Applications templates maintained by `heroeswearkapes`.

This repository contains Unraid Docker templates for projects that are developed and maintained in separate source repositories.

## Applications

---

## ComfyUI Intel XPU

Native PyTorch XPU accelerated ComfyUI for Intel Arc GPUs.

Features:

- Intel Arc GPU acceleration
- PyTorch XPU runtime
- ComfyUI Manager support
- Persistent model and workflow storage

Project:

    https://github.com/heroeswearkapes/comfyui-intel-xpu

---

## Schedules Direct XMLTV

Automatically retrieves Schedules Direct guide data, converts it to XMLTV, and serves it over HTTP.

Features:

- Scheduled guide updates
- XMLTV output generation
- HTTP serving for Threadfin, Jellyfin, Plex, Emby, TVHeadend, and other compatible applications
- Supports amd64 and arm64 Docker hosts

Project:

    https://github.com/heroeswearkapes/schedules-direct-xmltv

---

## TTS Workbench

Self-hosted multi-engine AI text-to-speech platform with a unified Gradio interface.

Supported engines:

- Kokoro
  - Fast preset voice synthesis
  - Full voice catalog support

- F5-TTS
  - Reference audio voice cloning
  - Audio normalization
  - Whisper-assisted transcription

- Qwen3-TTS
  - Local AI speech generation
  - CustomVoice support
  - Intel XPU acceleration support

Features:

- Docker-based deployment
- Persistent model and voice storage
- Dynamic engine controls
- Runtime diagnostics
- Intel Arc GPU acceleration support through `/dev/dri`

Project:

    https://github.com/heroeswearkapes/tts-workbench

---

## Repository Structure

    unraid-community-apps/
    ├── ca_profile.xml
    ├── README.md
    ├── icons/
    │   ├── comfyui-intel-xpu.png
    │   ├── schedules-direct-xmltv.png
    │   └── tts_workbench.png
    └── templates/
        ├── comfyui-intel-xpu.xml
        ├── schedules-direct-xmltv.xml
        └── TTS-Workbench.xml

The application source code remains in each project's individual GitHub repository.

This repository contains only:

- Unraid Community Applications templates
- Application metadata
- Icons
- Shared Community Apps assets

## Support

For application-specific issues, use the support link associated with each application's GitHub repository.