# VeloxTracer

**VeloxTracer** is a Vulkan-based offline GPU path tracer written in C++ and GLSL.

This project implements physically-based rendering using compute shaders and supports:
- Path tracing with Monte Carlo integration
- GLSL-based BRDF evaluation and sampling
- Vulkan compute pipeline for per-pixel ray processing
- Output to image file (offline rendering, not real-time)

## 🔧 Tech Stack
- **C++** (main application logic)
- **Vulkan** (GPU API)
- **GLSL → SPIR-V** (compute shaders)
- **GLFW** (window/context setup)
- **GLM** (math library)

## 🚧 Status
- Private during development
- Will be made public upon first milestone completion

## 📌 TODO (Reminders)
- [ ] Basic compute shader path tracing
- [ ] Scene description and material input
- [ ] Output rendered image to disk
- [ ] Add optional real-time preview (future)
