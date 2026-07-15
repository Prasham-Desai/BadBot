![BadBot Logo](<./Screenshots/Game Logo.png>)

# BadBot

**An Action-Packed Unreal Engine 5 Experience**

---

## 🎮 About The Game

**BadBot** is a dynamic, fast-paced action game developed in Unreal Engine 5. 

**Story:** Futuristic bots have taken up an ancient village, and a bad bot gone rogue is defending the village against them!

The game features multi-level progression culminating in an epic boss fight at the end. Built with a floating pawn movement system, you have complete 3D mobility to navigate the beautifully crafted Asian Village and engage in intense combat.

---

## ✨ Key Features

- **Multi-Level Progression:** Fight through multiple levels leading up to a final boss fight.
- **Next-Gen Graphics:** Leverages Unreal Engine 5's Lumen and Nanite systems for hyper-realistic lighting and high-fidelity geometry.
- **Unique Movement:** Full 3D mobility utilizing a floating pawn movement system.
- **Rich Environments:** Explore diverse levels, starting with a beautifully crafted ancient Asian Village map.
- **Blueprint-Driven Logic:** Highly modular and customizable game logic powered by Unreal's visual scripting.

---

## 📸 Screenshots

Here is a look at BadBot in action!

### Splash Screen
![Splash Screen](<./Screenshots/Splash Screen.png>)

### Gameplay & Environments
![Screenshot 1](./Screenshots/1.png)

![Screenshot 2](./Screenshots/3.png)

![Screenshot 3](./Screenshots/4.png)

---

## 🛠 Technical Details

- **Engine Version:** Unreal Engine 5.6
- **Target Platforms:** Windows PC
- **Input Handling:** Enhanced Input Subsystem
- **Rendering:** Lumen Global Illumination & Reflections, Virtual Shadow Maps
- **Core Architecture:** Blueprint Only

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

BadBot uses a floating pawn movement system allowing for omnidirectional movement. 

### Keyboard & Mouse
| Action | Key Binding |
| :--- | :--- |
| **Move (Forward/Left/Back/Right)** | `W`, `A`, `S`, `D` |
| **Move Up** | `Spacebar` |
| **Move Down** | `Shift` |
| **Look / Aim** | `Mouse Movement` |
| **Fire (Hold for constant)** | `Left Mouse Button` |
| **Pause Menu** | `Esc` |

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

This is an unlicensed personal project created for the purpose of learning and experimenting with Unreal Engine 5.
