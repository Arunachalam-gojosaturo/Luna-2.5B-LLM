# 🌙 Luna-2.5B

<p align="center">
  <em>Arunachalam's Luna-2.5B: A specialized tool for the Arch Linux community. Developed by a 7-year veteran builder based in (Tamil Nadu), India.</em>
</p>

---

## ⚡ Installation & Download Options

### 1. Arch Linux (AUR) - *Recommended for Arch Users*
You can easily install Luna-2.5B natively on Arch Linux using your favorite AUR helper (like `yay`). This automatically installs `ollama` and configures the `luna-llm` command:
```bash
yay -S luna-llm
```
Once installed, simply run:
```bash
luna-llm
```

### 2. Direct Ollama Pull
If you already have [Ollama](https://ollama.com) installed on any OS, you can pull and run the model directly from the Ollama registry:
```bash
ollama run Arunachalam-arch/luna-2.5b
```

### 3. Hugging Face (Raw Weights)
If you prefer to use the model with standard Hugging Face tools, Transformers, or vLLM, you can download the raw weights directly from our Hugging Face repository:
👉 **[Download from Hugging Face](https://huggingface.co/Arunachallam/Luna-2.5B-LLM)**

### 4. Manual Local Build
You can clone this repository and build the model locally using the provided `Modelfile`:
```bash
git clone https://github.com/Arunachalam-gojosaturo/Luna-2.5B-LLM.git
cd Luna-2.5B-LLM
ollama create luna-2.5b -f Modelfile
ollama run luna-2.5b
```

---

## ✨ Features

- **⚡ Lightweight & Fast:** Optimized parameters tailored for minimal hardware overhead without sacrificing intelligence.
- **🐧 Arch Linux Native:** Expert knowledge of pacman, AUR, Hyprland workflows, Bash, Zsh, and Kitty out of the box.
- **💻 Developer-Focused:** Built-in proficiency for Python, FastAPI, Docker, Git, Node.js, and general terminal mastery.
- **📦 Seamless Ollama Integration:** Pre-configured parameters (like hardware threading and context sizing) for instant deployment and efficiency.

---

## 💡 Example Prompts

Here are a few things you can ask Luna-2.5B:

- *"How do I write a minimal FastAPI server using Docker?"*
- *"What's the best way to optimize my Hyprland config for an Intel i3?"*
- *"Write a Bash script to automate backing up my dotfiles using git."*
- *"Explain the difference between pacman and yay in Arch Linux."*

---

## ⚙️ Technical Details & Requirements

| Property | Details |
|----------|---------|
| **Base Architecture** | Qwen2.5-1.5B-Instruct |
| **Model Size** | ~1.5 Billion Parameters |
| **Context Window** | 2048 (Optimized for rolling release & memory efficiency) |
| **Customization** | Arunachalam |
| **License** | Apache 2.0 |

### 🖥️ Recommended Environment

- **OS:** Arch Linux (or any lightweight Linux distro)
- **Hardware:** Intel Core i3 (or equivalent) + 8GB RAM minimum
- **Terminal Setup:** Zsh, Kitty, Hyprland

---

## ❤️ Credits & Ecosystem

- **Original Qwen Architecture:** [Qwen Team](https://huggingface.co/Qwen)
- **Customization & Tuning:** Arunachalam, a 7-year veteran builder based in Tamil Nadu, India.
- **Hosting:** Available on [Ollama](https://ollama.com/Arunachalam-arch/luna-2.5b) & [Hugging Face](https://huggingface.co/Arunachallam/Luna-2.5B-LLM)
