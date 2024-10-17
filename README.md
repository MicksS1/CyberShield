# CyberShield

![CyberSheild_Gameplay](https://github.com/user-attachments/assets/11d0776f-900e-4ef7-9bc2-0186eead96e4)

## 🔴 About This Project
<p align="justify">CyberShield was originally developed as a submission for the Indie Game Ignite (IGI) Showcase and the GameToday Indie Game Competition, but we decided to expand the game even after the competition to further explore its potential. </p>

<br>

## 📋 Project Info

| **Role** | **Development Time** | **Engine** |
|:-|:-|:-|
| Game Programmer | 2 months | Unity 2022|

<br>

## 👤 Meet the Team
- Michael Ardisa (Programmer)
- Allan Alexander Matthew (Designer)
- Nicholas Diporedjo (3D Artist)

<br>

## ♦️About Game
<p align="justify">CyberShield is an isometric top-down action RPG where players can battle a variety of cyber threats like malware, trojans, and other digital dangers in the computer world. The game introduces a unique gameplay experience by fusing cybersecurity concepts with fast-paced action mechanics.</p>

<br>

## 🎮 Gameplay
<p align="justify">Players engage in intense combat, dodging and countering threats using weapons like machete, katana, and hammer. As they progress, they will face tougher enemies and adapt to new challenges. The game currently features 2 levels, and we plan to add more in future updates.</p>

<br>

## ⚙️ Game Mechanics I Created
### Dash Mechanic

![dashMechanic (1)](https://github.com/user-attachments/assets/13778158-761b-4779-a85f-76f97022ce22)

- Logic is located within the `PMove.cs` script
- The dash works by increasing player velocity and allows direction change mid-dash.
- Trail Renderer component is used for visual impact.
- Trail time is gradually reduced via coroutine at the end of the dash.
- Retracting effect is applied to the trail for a smoother dash experience.

### Scriptable Objects Utilization for Weapon Data

![image](https://github.com/user-attachments/assets/bfc19472-e461-4053-bf48-082c41f49d29)
![image](https://github.com/user-attachments/assets/645bd655-bc99-433d-ad02-e5bec9d51125)

- Located within the `Weapon.cs` script
- Scriptable objects are used to store key weapon data in the 'Resources' folder.
- Flexible method for managing and modifying weapon attributes.
- Adding new weapons is efficient: create a new weapon asset file and adjust it's data.

<br>

## 📜 Scripts

|  Script       | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| `Weapon.cs` | Scriptable object class used to determine which data needs to be stored. |
| `EBehaviour.cs`  | Responsible for how the enemies behave around the player. |
| `PMove.cs`  | Manages all isometric (skewed) player movements. |
| `ECombat.cs`  | Manages the logic behind the enemies' combat. |
| `PCombat.cs`  | Manages the logic behind the player's combat. |
| `etc`  |

<br>

## 🕹️ Controls

| **Key Binding** | **Function** |
|:-|:-|
| W, A, S, D | Basic movement |
| Left-Click | Attack |
| L-Shift | Dash |

<br>

## 💻 Setup

This game is still in beta, a playable version will be available soon!
