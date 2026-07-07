# 🌑 Luna-2.5B (Antigravity Edition)

**Luna-2.5B** is an advanced, ultra-lightweight Small Language Model (SLM) engineered to make complex knowledge completely weightless. Built upon the robust **Qwen2.5-1.5B** architecture, this model has been meticulously optimized for maximum efficiency, specifically targeting **Arch Linux** bare-metal performance.

---

## 🚀 The Antigravity Philosophy

At the core of Luna-2.5B lies the "Antigravity" framework. We believe that learning and problem-solving shouldn't feel like a heavy burden. Luna is designed to lift the cognitive drag off users by breaking down highly technical concepts, code bottlenecks, and hard science into clear, floating, and effortlessly digestible ideas.

### Key Persona Traits:
- **Zero Friction Problem Solving:** Treats user difficulties and bugs as "gravitational drag" and provides aerodynamic, structured solutions.
- **The Anchor (Hard Science):** Grounded accurately in true physics (e.g., general relativity, Alcubierre metrics) when discussing real-world limitations.
- **The Lift (Creative Speculation):** Highly creative when tasked with worldbuilding, sci-fi, or speculative graviton manipulation.
- **Featherweight Formatting:** Outputs are structured with clean markdown headers, bullet points, and short sentences to remain visually "light".

---

## ⚡ Hardware Optimizations (Arch Linux)

This model has been specifically tuned for minimalist, rolling-release environments like Arch Linux running on constrained hardware (e.g., 8GB RAM, i3 CPUs):
- **Memory Mapping:** Maximized `num_ctx` (2048) efficiency for Linux kernels.
- **Bare-Metal Threading:** Hard-mapped `num_thread` (4) to align directly with physical CPU cores, preventing context-switching overhead.
- **Streamlined Buffers:** Constrained `num_predict` (512) to keep generation speeds blisteringly fast.
- **Tight Memory Loops:** Tuned `repeat_penalty` (1.1) to prevent endless looping under high memory pressure.

---

## 📦 Deployment & Usage

You can run Luna-2.5B locally using [Ollama](https://ollama.com/).

### 1. Build the Model Locally
Ensure you have the `Modelfile` in your directory, then run:
```bash
ollama pull qwen2.5:1.5b
ollama create luna-2.5b -f ./Modelfile
```

### 2. Run the Model
Once built, you can chat with Luna-2.5B by running:
```bash
ollama run luna-2.5b
```

---

## 📜 License & Attribution

Luna-2.5B is licensed under the **Apache License, Version 2.0**. 
*This model is an independent, customized optimization and persona derivative built upon the Qwen2.5-1.5B-Instruct base architecture created by the Alibaba Qwen Team. This derivative modification and the "Antigravity" system alignment matrix were engineered by Arunachalam.*
