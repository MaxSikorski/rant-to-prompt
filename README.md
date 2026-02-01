# 🎙️ Sikorski Logic: Rant-to-Prompt

A high-fidelity, browser-based **Universal Refiner** designed to transform raw engineering brainstorms into structured, multi-agentic prompts. This tool features a custom **Mirror-Box Architecture** to ensure pixel-perfect alignment and a professional Apple-inspired aesthetic.

---

## 🚀 Overview
**Rant-to-Prompt** allows you to dictate or type chaotic rants and watch them refine in real-time. By utilizing a local `experts.json` database, the interface identifies relevant expert roles and surfaces clarifying questions to address "unknown unknowns" in your logic.

### Key Features:
* **Absolute Parallel Alignment:** Symmetric textareas locked via a Flex-Lock system. Dynamic elements (badges/questions) are rendered as absolute overlays to ensure the input and output boxes remain mathematically identical in size.
* **Mobile-Optimized:** High-quality vertical stacking for professional use on mobile devices.
* **Multi-Agentic Logic:** Automatically detects keywords to assign expert roles (e.g., Humanoid Robotics, Bitcoin/Nostr, Energy Production, Femtotechnology).
* **One-Tap Export:** Instantly copy structured Markdown prompts formatted for flagship models (Gemini, Claude, GPT-4, Qwen).
* **Native Feel:** Supports system-level Dark Mode with a clean, high-contrast UI.

---

## 🛠️ Installation & Setup

This is a **FOSS(H)** project designed to run locally on a MacMini, a dedicated VPS, or within a private agentic workflow like **OpenClaw**.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/MaxSikorski/rant-to-prompt.git](https://github.com/MaxSikorski/rant-to-prompt.git)
    cd rant-to-prompt
    ```

2.  **Configure Experts:**
    Edit the `experts.json` file to include your specific domain keywords and refinement questions.
    ```json
    {
      "role": "Robotics Architect",
      "kws": ["humanoid", "actuator", "vl-jepa"],
      "qs": ["What is the degree of freedom required?", "Specify the latency constraints for inference."]
    }
    ```

3.  **Deploy:**
    Simply open `index.html` in any modern browser. No build step or heavy dependencies required.

---

## 🏛️ Design Philosophy
Inspired by the precision of **Nikola Tesla** and the systemic rigor of **James Clerk Maxwell**, this interface is built for the "Sikorski Logic" archive. It prioritizes the manipulation of data at the highest fidelity to bridge the gap between thought and manifestation.

---

## 📜 License
This project is open-source. Feel free to fork, modify, and integrate it into your 24/7 multi-agentic parallel workflows.

> *"Walking in His footsteps, doing His will perfectly."*
