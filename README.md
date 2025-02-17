# 🎮 **Nightmare Interactive Experience**  
*A Unity-based immersive horror exhibit for the Creative Tech module (CW2) in my 3rd year of University.*  

---

## 🌐 **Project Overview**  
The **Nightmare Interactive Experience** is a **first-person horror exhibit** designed in **Unity**. Players explore a dark, foggy forest, collecting **five gargoyle artefacts** while being pursued by a **relentless enemy**. As the artefacts are gathered, the environment dynamically shifts from **a terrifying nightmare to a serene daytime scene**, symbolising the player's escape.  

Inspired by **Slender: The Eight Pages** and **Phasmophobia**, the exhibit creates a **tense and atmospheric experience** using **dynamic lighting, environmental storytelling, and audio-driven suspense mechanics**.  

---

## ✨ **Features**  
✅ **First-Person Exploration** – Navigate using **WASD & mouse controls**.  
✅ **Artefact Collection System** – Collect **five gargoyle artefacts** to progress.  
✅ **Dynamic Environment Transitions** – Changes from **nightmare to peaceful daytime** after completing objectives.  
✅ **AI-Powered Enemy** – A stalking figure that reacts dynamically to the player’s movements.  
✅ **Ambient Sound Design** – Proximity-based audio cues create suspense.  
✅ **Lighting & Fog Effects** – Real-time atmospheric shifts enhance immersion.  

---

## 🛠 **Technologies Used**  
- 🎮 **Unity** – Game engine used for development.  
- 🖥️ **C#** – Scripting for movement, interactions, and AI behaviour.  
- 🔊 **FMOD/Unity Audio Engine** – Created dynamic sound transitions.  
- 🌫️ **Unity Terrain & Particle Systems** – Used for **fog effects and environmental design**.  
- 🔦 **Post-Processing Effects** – Adjusted lighting, shadows, and bloom to create tension.  

---

## 🔄 **Key Features & Implementation**  
### 🔹 **First-Person Movement**  
- Utilised **Unity’s CharacterController** to ensure smooth player navigation.  
- Restricted **camera rotation** to maintain a natural field of view.  

### 🔹 **Enemy AI Behaviour**  
- The enemy **randomly patrols and chases the player** using a **NavMesh Agent**.  
- Proximity-based **audio and visual distortions** warn players of nearby danger.  

### 🔹 **Artefact Interaction & Collection System**  
- **Raycasting** detects when the player is near an artefact.  
- The **crosshair changes colour** to indicate an interactable object.  
- **Collecting all artefacts triggers an environment shift** (night → day).  

### 🔹 **Dynamic Environment & Sound Design**  
- **Eerie, tension-filled soundscape** changes based on player location.  
- **Lighting & fog density dynamically decrease** after collecting artefacts.  
- Entering the **church** triggers an **ambient nursery rhyme** sound effect.  

---

## ❌ **Challenges & Modifications**  
### **Removed Features Due to Time Constraints**  
🚫 **Puzzle Mechanics** – Originally planned but deprioritised to focus on core gameplay.  
🚫 **Advanced Enemy Animations** – Used **basic animations** instead of motion-captured sequences.  

### **Overcoming Development Challenges**  
- **Balancing the enemy AI** took multiple iterations to ensure fair difficulty.  
- **Debugging movement & interaction systems** required refining raycasting logic.  
- **Project file corruption** forced a **partial rebuild**, improving overall code efficiency.  

---

## 🔮 **Future Improvements**  
🔹 **Refine enemy animations** for more lifelike movement.  
🔹 **Expand AI behaviour** for more unpredictable enemy actions.  
🔹 **Introduce puzzle-solving mechanics** to deepen gameplay.  
🔹 **Optimise performance** for smoother frame rates in larger environments.  

---

## 📚 **Resources & References**  
📌 **[Game Studies – Horror Game Atmosphere](https://gamestudies.org/2102/articles/dudek)**  
📌 **[PC Gamer – Phasmophobia Sound Design](https://www.pcgamer.com/phasmophobia-is-the-best-ghost-game-ever-made/)**  
📌 **[Unity AI & NavMesh Documentation](https://docs.unity3d.com/Manual/NavMesh.html)**  
📌 **[Stack Overflow – Raycasting for Object Interaction](https://stackoverflow.com/questions/7426056/unity-raycast-not-hitting-object)**  

---

### **Final Thoughts**  
This project successfully combines **horror atmosphere, interactive mechanics, and dynamic storytelling** into a **memorable first-person experience**. Through **environmental changes, audio cues, and AI-driven suspense**, players feel **immersed in the nightmare until they escape**.  

Despite **development setbacks**, I’m **proud** of the final product and excited to explore **more advanced Unity development** in future projects! 🚀  

---

