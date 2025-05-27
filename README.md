# BlockfyML CCMF - Restaurant Monitoring AI

![banner_blockfyml](https://github.com/user-attachments/assets/41306d33-e648-47dc-9b92-3fab9af03e77)

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python 3.8+">
  <img src="https://img.shields.io/badge/License-Proprietary-red" alt="Proprietary License">
  <img src="https://img.shields.io/badge/Release-v2.1.0-green" alt="Version 2.1.0">
</div>

## 🚀 No-Code Drag & Drop AI Builder

BlockfyML allows you to create AI workflows with a conversational builder and a vast library of tools and pre-trained foundational deep learning models.

```diff
+ New in v2.1: Session persistence & multi-image batch processing
! Now supports real-time video streams via RTSP
```
```mermaid
graph LR
    A[User Image] --> B(MagicWand AI)
    B --> C{DETR-ResNet50}
    B --> D{Faster R-CNN}
    C --> E[Object Tags]
    D --> F[People Count]
    E & F --> G[Annotated Output]
    G --> H((Cloud Storage))
```
