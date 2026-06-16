<h1 align="center">Lucid Explorer</h1>

<p align="center">
  A modern Windows file explorer powered by local AI.
</p>

<p align="center">
  Finder-inspired Design • Local LLMs • Vision AI • Image Generation • Privacy First
</p>

<p align="center">
  Developed by <b>JodStudiOS</b>
</p>


---

## Overview

Lucid Explorer is a next-generation Windows file manager designed by JodStudiOS.

Inspired by macOS Finder and modern desktop environments, Lucid Explorer combines fluid file navigation with powerful on-device artificial intelligence. Users can browse files, analyze documents, chat with local AI models, generate images, and interact with their workspace without relying on cloud services.

The goal is simple:

**Create the most beautiful and intelligent file explorer available for Windows.**

---

## Why Lucid Explorer?

Most file managers focus solely on browsing files.

Lucid Explorer extends the desktop experience by combining:

* Modern Finder-inspired interface
* Powerful local AI assistant
* Privacy-first architecture
* GPU-accelerated AI inference
* Intelligent document understanding
* Image generation capabilities
* Workspace-aware conversations

Everything is designed to feel fast, fluid, and intuitive.

---

## Features

### File Explorer

* Grid, Tile, and Details views
* Smooth animations and transitions
* Smart sidebar with:

  * Folder tree
  * Favorites
  * Recent locations
  * Color tags
  * Drive list
* Full file operations:

  * Create
  * Rename
  * Delete
  * Copy
  * Cut
  * Paste
* Finder-style file naming
* Properties dialog
* "This PC" overview
* Drive usage indicators
* Custom frameless window
* Rounded corners
* Gradient title bar

### Keyboard Shortcuts

| Shortcut         | Action      |
| ---------------- | ----------- |
| Backspace        | Navigate Up |
| F5               | Refresh     |
| F2               | Rename      |
| Delete           | Delete      |
| Ctrl + A         | Select All  |
| Ctrl + C         | Copy        |
| Ctrl + X         | Cut         |
| Ctrl + V         | Paste       |
| Ctrl + Shift + N | New Folder  |
| Alt + Enter      | Properties  |

---

## AI Assistant

Lucid AI is built directly into the explorer.

### Chat Mode

* Local LLM conversations
* Streaming responses
* Markdown rendering
* Workspace-aware context

Supported models:

* Qwen2.5 1.5B
* Qwen2.5 3B
* Qwen2.5 7B

### Vision Mode

Analyze:

* Images
* PDFs
* Documents
* Screenshots

Supported models:

* Qwen2.5-VL
* MiniCPM-V

### Image Generation(Unstable)

Generate images directly inside the application using:

* FLUX.1 Dev models
* Local Stable Diffusion runtime

### Code Mode(Coming Soon)

* Programming assistance
* Code explanation
* Debugging help
* Code generation

---

## File Ingestion Pipeline

Lucid Explorer includes an advanced document processing system.

### Supported Formats

* PDF
* DOCX
* XLSX
* PPTX
* TXT
* Markdown
* Images

### Processing Features

* PDF text extraction
* OCR fallback for scanned documents
* Structure-aware chunking
* Image understanding
* Context preparation for AI models

---

## GPU Support

Automatic hardware detection for:

### NVIDIA

* CUDA acceleration
* Dynamic layer offloading

### AMD

* Vulkan acceleration

### Intel

* Integrated GPU support

### CPU Fallback

* Multi-threaded inference
* Automatic optimization

---
## ScreenShots
<img width="1283" height="809" alt="Lucid2" src="https://github.com/user-attachments/assets/7f3a9788-8bb3-4b26-bd94-ec54722b65c0" />
<img width="1283" height="805" alt="Lucid1" src="https://github.com/user-attachments/assets/4f0b6aa0-80e9-45c4-8966-8a8914a35009" />
<img width="1284" height="813" alt="Lucid3" src="https://github.com/user-attachments/assets/690315d9-b7bf-40dc-bec3-f45a24a3e374" />
<img width="1600" height="900" alt="Lucid4" src="https://github.com/user-attachments/assets/afe33fe4-66d8-44dd-94cb-3884a6341da1" />

---

## System Requirements

### Minimum

| Component | Requirement          |
| --------- | -------------------- |
| OS        | Windows 10/11 64-bit |
| RAM       | 4 GB                 |
| VRAM      | 2 GB                 |
| Storage   | 2 GB                 |

### Recommended

| Component | Requirement |
| --------- | ----------- |
| RAM       | 8 GB+       |
| VRAM      | 4 GB+       |
| SSD       | Recommended |

---

## Installation

### Download

Download the latest release from the Releases page.

### Build From Source

Clone the repository:

```bash
git clone https://github.com/SayantanJ/LucidExplorer.git
cd LucidExplorer
```

Install dependencies:

```bash
flutter pub get
```

Build:

```bash
flutter build windows --release
```

Copy required runtime files:

```text
ai.png
llama.cpp/
stable-diffusion.cpp/
```

into:

```text
build/windows/x64/runner/Release/
```

---

## Project Structure

```text
LucidExplorer/
│
├── lib/
│   ├── main.dart
│   │
│   ├── core/
│   │
│   ├── features/
│   │   ├── ai/
│   │   └── explorer/
│   │
│   ├── models/
│   ├── services/
│   ├── shared/
│   └── theme/
│
├── windows/
├── llama.cpp/
├── stable-diffusion.cpp/
└── assets/
```

---

## Technology Stack

| Category          | Technology             |
| ----------------- | ---------------------- |
| Framework         | Flutter 3.9+           |
| Language          | Dart                   |
| State Management  | Riverpod               |
| Routing           | go_router              |
| Window Management | window_manager         |
| AI Runtime        | llama.cpp              |
| Image Generation  | stable-diffusion.cpp   |
| Native APIs       | Win32 FFI              |
| PDF Processing    | syncfusion_flutter_pdf |
| UI Framework      | Material 3             |
| Typography        | Google Fonts (Poppins) |

---

## Privacy

Lucid Explorer is designed with privacy in mind.

* Local AI execution
* No mandatory cloud services
* User-controlled models
* User-controlled data
* Offline-capable workflows

Your files remain on your machine.

---

## License

Licensed under a custom license created and validated by SayantanTheCmd

See the LICENSE file for details.

---
##Developed By 

**Sayantan Jana**


---

<p align="center">
  Built with Flutter ❤️ by JOD Studios
</p>
