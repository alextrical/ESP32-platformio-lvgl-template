# ESP32 + LVGL + PlatformIO Template

A minimal, reusable template for ESP32‑based projects using [LVGL](https://github.com/lvgl/lvgl) and [PlatformIO](https://platformio.org) with the Arduino framework.  
This repo is designed to be used as a GitHub template so new projects start with LVGL already wired up and a basic UI loop.

---

## 🎯 What this template includes

- ESP32 target (customizable via `platformio.ini`)  
- Arduino framework (`framework = arduino`)  
- LVGL as a dependency (latest stable via `lib_deps`)  
- Basic LVGL initialization loop (`lv_init()`, display driver, input driver)  
- Ready‑to‑modify `main.cpp` with a simple UI example  
- `.gitignore` tailored for PlatformIO projects  

---

## 🚀 Getting started

1. **Use this as a template**  
   On GitHub, click the big green **“Use this template”** button and create a new repository.

2. **Clone your new repo**  
   ```bash
   git clone https://github.com/your-username/your-new-repo-name.git
   cd your-new-repo-name
