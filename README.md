
# MBTI Simulator Lab

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)

**Advanced Social Dynamics & Personality Simulation**

[Download Latest Release](https://github.com/MbtiDev/mbtiSimulation/releases) • [Report Bug](https://github.com/MbtiDev/mbtiSimulation/issues) • [View Changelog](#changelog)

</div>

---

## 🧠 About

**MBTI Simulator Lab** is a desktop application designed to model social interactions. By simulating agents based on the Myers-Briggs Type Indicator (MBTI), users can visualize how different personality types influence group dynamics, emotional contagion, and overall group stability.

Built with a passion for psychology and data science, this tool bridges the gap between theoretical personality frameworks and observable behavioral patterns.

## ✨ Key Features

### 🔬 Real-Time Simulation Engine
*   **Dynamic Agents:** Create agents based on all 16 MBTI types.
*   **Cognitive Interaction:** Agents interact based on compatibility, stress levels, and mood.
*   **Scenarios:** Load preset environments (e.g., "Political Debate", "Crisis Team") to see how specific group compositions behave.
*   **Live Metrics:** Monitor Group Stability, Emotional Contagion, and Network Density in real-time.

### 📊 Professional Data Visualization
*   **Network Graph:** Visualize social connections. Supports custom avatars and interactive node inspection.
*   **Adaptive Heatmap:** A professional, monochromatic heat map that visualizes compatibility matrices. Features adaptive color scaling and smart hover interactions to read specific values instantly.
*   **Trend Analysis:** Track group stability over time to identify patterns of harmony or conflict.

### 🛠️ Research & Analysis Tools
*   **Mode System:**
    *   **Simulation:** Live view of the evolving network.
    *   **Research:** Deep dive into compatibility metrics and relationship insights.
    *   **Data & History:** Comprehensive tabular data views alongside historical trend graphs.
*   **Agent Inspector:** Click any node to view detailed stats (Mood, Stress, Leadership, Trust Scores) and relationship history.

### 💾 Smart State Management
*   **Custom .mbti Format:** Save and load your simulations using the proprietary `.mbti` file extension.
*   **Seamless Integration:** Double-click any `.mbti` file on your desktop to launch the simulator and load that state instantly (Beta).

### 🚀 Live Updates & Connectivity
* The software will be updated casually, adding new features.
---

## 📸 Screenshots

> *The Simulation Mode featuring the Network Graph and Event Log.*

<img width="1360" height="768" alt="Screenshot (206)" src="https://github.com/user-attachments/assets/7daa39d9-d204-48ee-b7da-4d72674b932e" />

> *The Research Mode displaying the Adaptive Compatibility Heatmap.*

<img width="1360" height="768" alt="Screenshot (207)" src="https://github.com/user-attachments/assets/70c8ee4a-a330-41da-9839-5f743061fc39" />

> *The Data histpry Featuring The Group stability History With a Table.*

<img width="1360" height="768" alt="Screenshot (208)" src="https://github.com/user-attachments/assets/845dcee8-3a49-47d3-bb68-a4490a098964" />

---

## 🚀 Installation

### Via Installer (Recommended)
1. Download the latest `MBTI_Simulator_Lab_Setup.exe` from the [Releases](https://github.com/MbtiDev/mbtiSimulation/releases) page.
2. Run the installer.
3. Launch the application from the Start Menu or Desktop.

### System Requirements
*   **OS:** Windows 10 or Windows 11 (x64).
*   **Disk Space:** ~200 MB.
*   **Internet:** Required for update checks and dynamic link fetching (Offline mode available).

---

## 📖 Usage Guide

### 1. Start a Scenario / Start from scratch
Add agents into the simulation, or simply use the **Scenario** dropdown at the bottom to load a preset. This instantly populates the environment with agents and sets global parameters.

### 2. Control the Simulation
*   **Play/Pause:** Start or freeze the simulation.
*   **Speed:** Adjust simulation speed (1x, 2x, 5x).
*   **Aggression:** Modify the global aggression parameter to see how conflict affects group stability.

### 3. Inspect Agents
Click on any node (circle) in the **Simulation** tab to open the **Agent Inspector**. Here you can view detailed stats and their top 10 strongest connections.

### 4. Analyze Data
Switch to the **Research** tab to view the Heatmap. Hover over cells to see specific compatibility scores between agents.

### 5. Save Your Work
Click **Save** to export the current state as a `.mbti` file. You can load this later, or simply double-click the file icon in Windows File Explorer to resume.

---

## 🛠️ Technology Stack

This project is built using Python, leveraging powerful libraries for computation and visualization:

*   **GUI:** `PySide6` (Qt for Python)
*   **Computation:** `NumPy`, `Pandas`
*   **Visualization:** `Matplotlib` (Backend_qtagg)
*   **Packaging:** `PyInstaller`, `Inno Setup`

---

## 👨‍💻 Developer

Built by an INTJ developer who is passionate about psychology.

*   **Website:** [MBTI Simulator Lab](https://mbtisimulatorlab.rf.gd)


---

<div align="center">

**If you find this tool useful, consider giving it a ⭐ Star on GitHub!**
