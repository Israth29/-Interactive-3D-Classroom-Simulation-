# -Interactive-3D-Classroom-Simulation-
3D Computer Graphics project simulating a classroom environment. Implements geometrical transformations, shading models, and user interaction using OpenGL/GLUT.

![Main Screenshot](screenshots/main_view.png)
*(Note: Upload your "Figure 5" or "Figure 6" image to a folder named 'screenshots' in your repo and rename it to main_view.png, or update this link)*

##  Project Overview
This project demonstrates the fundamental concepts of Computer Graphics, including **hierarchical 3D modeling**, **texture mapping**, **Phong lighting**, and **interactive animation**. The simulation creates a realistic academic environment where users can navigate freely, control electrical appliances (fans/lights), and interact with architectural elements.

##  Key Features
*   **Realistic Modeling:** Procedural generation of chairs, tables, whiteboard, and ceiling fans using hierarchical transformations.
*   **Dynamic Lighting:** Implementation of Ambient, Diffuse, and Specular lighting with toggles for multiple light sources (Tube lights, Spotlights).
*   **Texture Mapping:** Realistic bitmap textures applied to walls, floors, and windows (including an outdoor view).
*   **Interactive Animation:**
    *   Rotating ceiling fans with start/stop control.
    *   Smooth opening/closing animations for doors and windows.
*   **Camera Navigation:** Full control to walk through the room, pan the camera, and zoom in/out.

##  Built With
*   **Language:** C++
*   **Library:** OpenGL / GLUT (OpenGL Utility Toolkit)
*   **IDE:** Code::Blocks (MinGW)

##  Controls
The simulation features a comprehensive control system for navigation and interaction.

| Key | Action |
| :--- | :--- |
| **Navigation** | |
| `w` / `e` | Move Camera Up / Down |
| `a` / `s` | Move Camera Left / Right |
| `o` / `p` | Rotate Camera Left / Right |
| `+` / `-` | Zoom In / Out |
| **Interaction** | |
| `d` | Open / Close Window & Door |
| `;` | Start Fans |
| `*` | Stop Fans |
| **Lighting Controls** | |
| `t` | Toggle Light 1 (Main Light) |
| `y` | Toggle Light 2 (Secondary Light) |
| `u` | Toggle Light 3 (Spot/CSE Light) |
| `b`, `n`, `m` | Enter Edit Mode for Light 1, 2, or 3 |
| `1` - `6` | Adjust intensity (Ambient/Diffuse/Specular) in Edit Mode |

## How to Run
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YourUsername/Your-Repo-Name.git
    ```
2.  **Open the Project:**
    *   Open `Group A-Final Project.cbp` in **Code::Blocks**.
3.  **Texture Setup (Important):**
    *   Ensure the `.bmp` image files (`wall1.bmp`, `top.bmp`, etc.) are located in the **same directory** as the executable file (usually `bin/Debug/`).
4.  **Build and Run:**
    *   Press `F9` or click **Build & Run**.

## 👥 Contributors
*   **Akhi** (ID:C223202)
*   **Fayeza** (ID:C223206)
*   **Israth** (ID:C223229)

 
