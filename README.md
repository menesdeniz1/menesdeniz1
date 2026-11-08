# Mücahid Enes Deniz

**Software Engineer · Industrial Computer Vision · C++ & Python**

I build industrial machine-vision software end to end — from Basler cameras, motorized lenses and PLCs to model inference, data storage and operator UIs — and I build LLM-agent and full-stack side projects.

**At Kastamonu Entegre (Hayat Holding)** — code is private (employer):

- **Patented fiber analysis system** — C++/Python machine vision for MDF fibers, running at three plants; migrated from C++17/Qt 6 to a Dockerized Python stack (ONNX Runtime YOLO segmentation, OpenCV, PostgreSQL, Redis) with PLC-driven lens automation and autofocus.
- **Parquet defect inspection** — a C++17/Qt 6 five-stage pipeline (line-scan acquisition, stitching, YOLO inference with ONNX Runtime/OpenVINO, finalization, disk I/O) with bounded queues and OPC UA reject signals, running on a live production line.
- **Panel geometry and truck-load measurement** — production hardening of an MDF squareness system (team of three) and fusion of four SICK LiDAR streams for cargo volume.

## Selected projects

| Project | What you can explore |
| --- | --- |
| [resumefill](https://github.com/menesdeniz1/resumefill) | LLM browser agent (Gemini, browser-use, Playwright, Streamlit) that pre-fills job-application forms from a CV and never submits them; 190 tests and CI. |
| [KeepMoney](https://github.com/menesdeniz1/keepmoney) | Full-stack price and stock tracker with a web dashboard and Telegram bot: FastAPI, PostgreSQL, React/TypeScript, Docker Compose, 1,100+ automated tests and a 7-job CI. |
| [KeepAwake](https://github.com/menesdeniz1/keepawake) | Cross-platform tray utility (PySide6/Qt) for idle scheduling and power management on Windows, macOS and Linux/X11, with a SHA-256-verified auto-updater and release pipeline. |
| [Tracker](https://github.com/menesdeniz1/tracker) | Telegram price bot run as a 24/7 service; self-updates on push, smoke-tests and rolls back to the last known-good version. |
| [Computer Vision Capstone](https://github.com/menesdeniz1/capstone-project) | Team capstone: YOLOv8 colour detection with camera input and a Bluetooth-controlled servo sorter. |
| [Face-Mask Detection](https://github.com/menesdeniz1/face-mask-detection) | Team coursework comparing YOLOv8 and SSD; YOLOv8 reached 0.806 mAP@0.5. |

## More engineering work

- [SetPrice](https://github.com/menesdeniz1/setprice): the earlier price-tracking prototype that became KeepMoney.
- [Rating Prediction](https://github.com/menesdeniz1/rating-prediction): collaborative filtering in C++17 with tests.
- [Graph Partitioning](https://github.com/menesdeniz1/graph-partitioning-problem): spectral clustering and a genetic algorithm.
- [P2P File Sharing](https://github.com/menesdeniz1/p2p-file-sharing): peer discovery and chunk-based transfers.
- [Reader–Writer Synchronization](https://github.com/menesdeniz1/reader-writer-problem): Java concurrency with semaphores.
- [Godot Game Prototype](https://github.com/menesdeniz1/godot_egitim): grid movement, hazards, shields and power-ups.
- [Temperature Sensor](https://github.com/menesdeniz1/temperature-sensor): Arduino PWM fan control.

I am especially interested in turning computer-vision and machine-learning ideas into reliable production systems. I develop with Claude Code, and I also enjoy systems programming, automation and game development.
