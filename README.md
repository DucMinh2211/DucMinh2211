<div align="center">

# Hi, I'm Duc Minh 👋

**CS Student @ HCMUT · Ho Chi Minh City, Vietnam**

*Building fast things — engines, systems, and everything in between.*

[![GitHub followers](https://img.shields.io/github/followers/DucMinh2211?style=flat-square&color=6e40c9)](https://github.com/DucMinh2211?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=DucMinh2211&style=flat-square&color=6e40c9)](https://github.com/DucMinh2211)

</div>

---

## 🧑‍💻 About Me

- 🎓 **Computer Science student** at Ho Chi Minh City University of Technology (HCMUT / Bach Khoa)
- 🔭 Focused on **Systems Programming**, **Game Engine Development**, and **High-Performance Computing**
- ⚡ I love writing low-level code that squeezes every bit of performance out of hardware
- 🛠️ My go-to languages are **C++**, **C**, **Rust**, and **Python**
- 🎮 Passionate about **game engine architecture**, **ECS/DOTS**, and real-time simulation
- 🤖 Interested in **AI algorithms** (Alpha-Beta pruning, MCTS) and **embedded systems** (ESP32, FreeRTOS)

---

## 🛠️ Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=flat-square&logo=godotengine&logoColor=white)

**Game Dev & Engines**

![SDL2](https://img.shields.io/badge/SDL2-1C4395?style=flat-square)
![SDL3](https://img.shields.io/badge/SDL3-1C4395?style=flat-square)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)
![ImGui](https://img.shields.io/badge/Dear%20ImGui-gray?style=flat-square)
![Flecs](https://img.shields.io/badge/Flecs%20ECS-orange?style=flat-square)

**Systems & Embedded**

![FreeRTOS](https://img.shields.io/badge/FreeRTOS-green?style=flat-square)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![WinAPI](https://img.shields.io/badge/Win32%20API-0078D6?style=flat-square&logo=windows&logoColor=white)

**Build & Tools**

![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Cargo](https://img.shields.io/badge/Cargo-000000?style=flat-square&logo=rust&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### 🎮 Game Engines & Simulations

#### [Levi-ECS Engine](https://github.com/DucMinh2211/levi-ecs) · `C++20` `SDL3` `Flecs` `Lua` `ImGui`
> A high-performance 2D game engine built from scratch with a full studio editor.

- **ECS architecture** powered by [Flecs v4](https://github.com/SanderMertens/flecs) for data-oriented, cache-friendly entity management
- **Lua hot-reloading** via sol2 — change game logic at runtime with zero restarts
- **Integrated Studio Editor** using Dear ImGui with Scene Hierarchy and Inspector panels
- **Cross-platform** (Windows, Linux, macOS) via CMake; hardware-accelerated 2D rendering with SDL3

---

#### [ECS Unity Combat Simulation](https://github.com/DucMinh2211/ecs-unity-test) · `Unity DOTS` `C# Jobs` `Burst Compiler`
> 50,000-warrior real-time battle simulation benchmarking ECS/DOTS vs traditional OOP.

| Metric | ECS / DOTS | Traditional OOP |
|:---|:---:|:---:|
| FPS @ 50,000 units | **60–80 FPS** | ~10 FPS |
| Max playable scale | **100,000+ units** | ~20,000 units |
| Threading | 100% CPU (Job System) | Single-threaded |
| Memory access | Linear (cache-friendly) | Random (cache-misses) |

- Custom **spatial hashing grid** with spiral search + reservoir sampling for O(1)-space random targeting
- Fully benchmarked on Dell G15 5530 (i7-13650HX, RTX 4060)

---

#### [GP2-Shooter](https://github.com/DucMinh2211/GP2-shooter) · `C` `SDL2`
> A 2D shooter game built directly on SDL2 with custom physics and collision detection.

- Custom `Vector2` math library, OBB and circle collision detection
- Modular component architecture: `AnimatedSprite`, `BasicAI`, `BuffItem`, `HitBox`, `InputHandler`
- Cross-platform (Linux, macOS, Windows) via Makefile

---

#### [Game Programming #5](https://github.com/DucMinh2211/gp_5) · `GDScript` `Godot`
> A game programming course assignment built in the Godot Engine.

---

### 🤖 AI & Algorithms

#### [Chess AI](https://github.com/DucMinh2211/chess_ai_intro-252) · `Python` `Alpha-Beta` `MCTS`
> Full chess engine with multiple AI opponents and a web-based GUI via Eel.

- **Alpha-Beta Pruning** with Negamax + Quiescence Search (mitigates the horizon effect)
- **Transposition Table** caching for repeated position lookup
- **MCTS** (Monte Carlo Tree Search) with UCT selection
- **Hybrid Engine**: MCTS candidate generation fed into Alpha-Beta evaluation
- Piece-Square Tables (PST) for positional heuristics
- Benchmarked against Chess.com bots from 250 to 1800 Elo — D3/Q4 defeated Komodo (1600 Elo)

---

#### [OPLang Compiler](https://github.com/DucMinh2211/oplang-compiler) · `Python`
> A compiler implementation for the OPLang language — HCMUT HK251 Principles of Programming Languages assignment.

- Lexer, parser, type checker, and code generation pipeline
- Built as part of the formal PPL course at Bach Khoa University

---

### 🔌 Embedded & IoT

#### [Smart-Lab Sentinel](https://github.com/DucMinh2211/smart-lab) · `C++17` `ESP-IDF` `FreeRTOS`
> Professional-grade IoT security & environmental monitoring system for a laboratory.

- **Sub-1ms intrusion detection** via hardware ISR + FreeRTOS binary semaphore
- **Hardware Abstraction Layer (HAL)** — business logic fully decoupled from ESP-IDF drivers; unit-testable on PC
- **Dual-mode operation**: Guest-taking Mode (comfort automation) vs. Sentinel Mode (security)
- **NVS persistence**: modes, alarm volume, and timers survive reboots
- Supports both Wokwi simulation and real ESP32-S3 hardware
- Built with a hybrid 3-phase workflow: Termux Logic Mocking → Wokwi Simulation → ESP32-S3 Hardware

---

#### [TCS3200 Color Detection](https://github.com/DucMinh2211/tcs3200-color_detech-arduino) · `C++` `Arduino`
> Color Recognition System using Arduino, TCS3200 sensor, and I2C LCD display.

---

### 🛠️ System Utilities

#### [Taskbar Number Overlay](https://github.com/DucMinh2211/taskbar-number) · `Rust` `Win32 API`
> Lightweight Windows utility displaying index numbers over taskbar icons for fast `Win + [Number]` switching.

- Transparent, topmost overlay window that doesn't interfere with mouse/keyboard input
- **UI Automation API** for robust taskbar icon detection across Windows versions
- System tray integration with Pause/Resume toggle
- Dynamic refresh every 500 ms; pre-built binaries available for x64 and x86

---

#### [DADN-252](https://github.com/DucMinh2211/dadn-252) · `TypeScript`
> IoT device management and data platform project.

---

#### [Exam Helper](https://github.com/DucMinh2211/exam-helper) · `TypeScript`
> A TypeScript utility tool for exam preparation assistance.

---

## 📊 GitHub Stats

<div align="center">

![Duc Minh's GitHub stats](https://github-readme-stats.vercel.app/api?username=DucMinh2211&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=DucMinh2211&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

<div align="center">

*"The best performance optimization is the one you never have to undo."*

</div>
