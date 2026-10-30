# VCT Core Libraries ⚙️

[![Language](https://img.shields.io/badge/language-C%2B%2B17-blue.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](#)

A collection of high-performance C++ libraries developed by the **Visual Customization Tools (VCT)** team. 

These libraries power our flagship tool, the **[Valorant Skin Swapper 2026](https://github.com/Visual-Customization-Tools/valorant-skin-swapper-2026)**, and provide developers with the necessary backend to handle real-time asset swapping and memory management safely.

## 📦 Included Modules

*   **`vct-assets`**: A robust file parser for extracting, modifying, and repacking game textures and 3D models on the fly.
*   **`vct-hook`**: A lightweight memory hooking engine designed for minimal performance overhead during active gameplay.
*   **`vct-render`**: DirectX/Vulkan wrappers that allow real-time injection of custom textures into the rendering pipeline.

## 🛠️ Building

Ensure you have **CMake** and a modern C++ compiler (MSVC or Clang) installed.

```bash
git clone https://github.com/Visual-Customization-Tools/vct-core-libs.git
cd vct-core-libs
mkdir build && cd build
cmake ..
cmake --build . --config Release
```
🔗 Related Projects
Valorant Skin Swapper 2026

VCT Documentation

Maintained by the VCT Team.

---
