# InnoEngine

**A simple 3D game engine:
using:

- Vulkan 1.4

- SDL3

- BulletPhysics

- C++20 (Rust planned for 2027)

- ECS (Entity Component System)

 **
target: Windows 10-11, Ubuntu, Arch
(macOS, IOS, Android - later) 

Games(in dev):
- Toxicity (Toxic City) - (Co-op FPS/TPS + Racing) 2026

## Features


- [ ] -  textures render (indev)

- [ ] - player actor (indev)
- [ ] - .cae animations (indev)

- [ ] - car (indev)
- [X] - connect SDL3
- [X] - SDL3 music ( mixer later with stable v3)
- [ ] - SDL3 net 
- [X] - vma - allocation 
- [X] - build for arch


      not soon:
- [X] - invert y, to usual style (later for camera movement?)
- [ ]  - ragdoll (later)
- [ ] - RTX
- [ ] - game separated
- [ ] - SDL3 ttf (later)
- [ ] - engine UI (imgui like), but with editor
- [ ] - [ ] - terrain LODs
- [ ] - terrain edit tool     
- [ ] - (how connect lua in ubuntu? (not important)
- [ ] - shadows

from other (maybe here, but not sure:
- [x] PBR materials
- [x] HDR lighting
- [x] GLTF mesh importer
- [x] Skinned meshes and animations
- [x] Fonts and text
- [x] Dynamic rendering (Vulkan)
- [x] In-game UI
- [x] Dear ImGui
- [x] AABB collisions
- [x] Shadow mapping
- [x] Audio

## Requirements

### Runtime

  - Windows 10
  - Linux: X, Wayland (untested)
  - Mac OSX: untested, will require MoltenVk
- GPU supporting Vulkan 1.3+, its driver, and loader

### Development

- CMake 3.23+


## Usage
