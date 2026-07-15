<div align="center">
  <img src="Screenshots/Game Logo.png" alt="BadBot Logo" width="400"/>
  
  # BadBot

  **An Action-Packed Unreal Engine 5 Experience**
</div>

---

## 📖 Table of Contents
- [About The Game](#about-the-game)
- [Key Features](#key-features)
- [Screenshots](#screenshots)
- [Technical Details](#technical-details)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation & Launch](#installation--launch)
  - [Packaging the Game](#packaging-the-game)
- [Controls](#controls)
- [Project Structure](#project-structure)
- [License](#license)

---

## 🎮 About The Game

**BadBot** is a dynamic, fast-paced action game developed in Unreal Engine 5. Set against stunning backdrops, including an intricately designed Asian Village environment, the game pushes the boundaries of real-time rendering and fluid gameplay. 

*(Note: Replace this section with a deep dive into the lore, story, and overarching goals of BadBot. What makes your protagonist unique? Who are the enemies?)*

---

## ✨ Key Features

- **Next-Gen Graphics:** Leverages Unreal Engine 5's Lumen and Nanite systems for hyper-realistic lighting and high-fidelity geometry.
- **Dynamic Combat System:** Fluid movement paired with responsive and engaging combat mechanics.
- **Rich Environments:** Explore diverse levels, starting with a beautifully crafted Asian Village map (`BadBotLevel.umap`).
- **Enhanced Input System:** Fully utilizes UE5's Enhanced Input for seamless control mapping across multiple input devices (Keyboard/Mouse, Gamepad, and VR setups).
- **Blueprint-Driven Logic:** Highly modular and customizable game logic powered by Unreal's visual scripting.

---

## 📸 Screenshots

Here is a look at BadBot in action!

### Splash Screen
![Splash Screen](Screenshots/Splash%20Screen.png)

### Gameplay & Environments
*Click to enlarge.*

<div align="center">
  <img src="Screenshots/1.png" alt="Screenshot 1" width="800" />
  <br/><br/>
  <img src="Screenshots/3.png" alt="Screenshot 2" width="800" />
  <br/><br/>
  <img src="Screenshots/4.png" alt="Screenshot 3" width="800" />
</div>

---

## 🛠 Technical Details

- **Engine Version:** Unreal Engine 5.6
- **Target Platforms:** Windows PC (Scalable to Consoles & VR)
- **Input Handling:** Enhanced Input Subsystem
- **Rendering:** Lumen Global Illumination & Reflections, Virtual Shadow Maps
- **Core Architecture:** Blueprint Only (Extensible to C++)

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

- **Epic Games Launcher:** Required to install the engine.
- **Unreal Engine 5.6:** Make sure this specific version (or newer) is installed.
- **Hardware:** A dedicated GPU capable of running DirectX 12 (NVIDIA RTX series or AMD equivalent) is highly recommended for Lumen.

### Installation & Launch

1. **Clone or Extract:** Clone the repository or extract the project folder to your desired location.
2. **Open the Engine:** Launch Unreal Engine 5.6 from the Epic Games Launcher.
3. **Browse to Project:** In the Unreal Project Browser, click on **Browse** and navigate to your extracted folder.
4. **Select UProject:** Open the `BadBot.uproject` file.
5. **Play In Editor (PIE):** Once all shaders have compiled and the project is fully loaded, hit the **Play** button on the top toolbar (Shortcut: `Alt + P`) to start the game.

### Packaging the Game

To build a standalone executable that you can share:
1. Open the project in the Unreal Editor.
2. Navigate to **Platforms** in the top menu bar.
3. Select **Windows** > **Package Project**.
4. Choose an output directory and wait for the engine to cook the assets and build the `.exe`.
5. Run the resulting executable in your output folder.

---

## 🕹 Controls

BadBot supports both Keyboard & Mouse and Gamepad inputs seamlessly. *(Edit these if custom keybinds are assigned in the Input Mapping Context)*

### Keyboard & Mouse
| Action | Key Binding |
| :--- | :--- |
| **Move** | `W`, `A`, `S`, `D` |
| **Look / Aim** | `Mouse Movement` |
| **Primary Attack** | `Left Mouse Button` |
| **Secondary / ADS** | `Right Mouse Button` |
| **Jump** | `Spacebar` |
| **Sprint** | `Left Shift` |
| **Interact** | `E` |
| **Pause Menu** | `Esc` |

### Gamepad (Xbox / PlayStation)
| Action | Key Binding |
| :--- | :--- |
| **Move** | `Left Stick` |
| **Look / Aim** | `Right Stick` |
| **Primary Attack** | `Right Trigger (RT / R2)` |
| **Secondary / ADS** | `Left Trigger (LT / L2)` |
| **Jump** | `Face Button Bottom (A / Cross)` |
| **Interact** | `Face Button Left (X / Square)` |
| **Pause Menu** | `Start / Options` |

---

## 📂 Project Structure

An overview of the main directories you'll interact with:

- `Config/`: Contains `.ini` configuration files (e.g., DefaultInput.ini).
- `Content/`: The main hub for all game assets.
  - `Asian_Village/`: Assets specific to the village environment.
  - `Blueprints/`: Core game logic, character controllers, and managers.
  - `Input/`: Input Actions (IA) and Input Mapping Contexts (IMC).
  - `Maps/`: Level files (e.g., `BadBotLevel.umap`).
  - `UI/`: Widgets, HUDs, and menus.
- `Screenshots/`: Promotional and gameplay images for documentation.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details. *(Update this if you are using a different license or if it's closed source).*
