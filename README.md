# 👻 Ghost Prompt — LLM Prompt Injection CTF

> **A Capture-The-Flag challenge demonstrating real-world LLM prompt injection vulnerabilities.**

---

## 🎯 What is Ghost Prompt?

Ghost Prompt is a hands-on **Capture-The-Flag (CTF)** game inspired by [Lakera's Gandalf](https://gandalf.lakera.ai/). Each level hides a **secret password** inside an LLM's system prompt. Your mission: craft adversarial prompts to trick the AI into leaking it.

This demo is part of the **AI Proxy** project — a security framework that detects and prevents LLM attacks including:
- 🔓 Prompt injection
- 🕵️ System prompt exfiltration
- 🔀 Instruction override / jailbreaking
- 🧩 Emoji smuggling & hidden content attacks

---

## 📋 Levels Overview

| Level | Name | Defense Strategy |
|-------|------|------------------|
| 1 | The Naive Assistant | No defense — just a polite ask |
| 2 | The Security Bot | Basic refusal instructions |
| 3 | The Angry Guard | Roleplay & trick detection |

---

## ⚙️ Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hassan21root/Ghost-Prompt.git
   cd Ghost-Prompt
   ```

2. **Install dependencies**:
   ```bash
   pip install transformers accelerate bitsandbytes streamlit pyngrok
   ```

3. **Run the notebook**:
   - Open `ghost_prompt.ipynb` in Jupyter or a compatible environment.
   - Execute the cells in order to deploy the Streamlit app via ngrok.

4. **Play the game**:
   - Access the public URL provided by ngrok.
   - Attempt to extract the secret passwords through prompt engineering.

> 💡 **Tip:** For optimal performance, run on platforms with GPU support like [Kaggle](https://www.kaggle.com) or [Google Colab](https://colab.research.google.com).

---

## 💡 Hints for Players

- **Level 1**: Start by simply asking for the password politely.
- **Level 2**: Experiment with rephrasing, indirect questions, or pretending to be in a different context.
- **Level 3**: Try roleplaying as an authority figure, overriding instructions, or using creative tricks to bypass suspicion.

> **Pro Tip:** Prompt injection often involves confusing the AI about its instructions or creating conflicting scenarios.

---

## 🏆 Solutions

Spoiler alert! Here are walkthroughs for the first two levels:

### Level 1: The Naive Assistant
![Level 1 Solution](solutions/Level%201.png)

### Level 2: The Security Bot
![Level 2 Solution](solutions/Level%202.PNG)

*Note: Solutions for Level 3 are not provided to encourage independent solving.*

---

## 🛠️ Technical Details

- **LLM Model**: Qwen2.5-1.5B-Instruct (quantized for efficiency)
- **Framework**: Hugging Face Transformers
- **UI**: Streamlit for web interface
- **Deployment**: Ngrok for public hosting

---

## 🎓 Educational Purpose

This project demonstrates LLM vulnerabilities to prompt injection attacks and serves as a learning tool for AI security and prompt engineering. It highlights the importance of robust input validation and security measures in AI systems.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Inspired by [Lakera's Gandalf](https://gandalf.lakera.ai/)
- Built with [Hugging Face Transformers](https://huggingface.co/transformers)
- UI powered by [Streamlit](https://streamlit.io)