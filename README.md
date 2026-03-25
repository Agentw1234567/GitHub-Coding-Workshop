# 🦖 Yoshi's JavaScript Adventure: WIECS Workshop Edition

Welcome to the **Women in Engineering and Computer Science (WIECS)** GitHub/Coding Workshop! 



---

## 🛠 Setting Up Your Environment
To begin your development journey, follow these steps:

1. **Fork this Repository:** Click the 'Fork' button at the top right of this page to create your own copy.
2. **Clone to Your Machine:** Use `git clone [YOUR_REPO_URL]` or open it directly in your preferred web IDE (like GitHub Codespaces or VS Code).
3. **Open the Game:** Launch `index.html` in your browser to see the current state of the engine.

---

## 👩‍💻 The Development Sprints
This workshop is divided into **6 Sprints**. After you complete the code for each challenge, you must **Commit** and **Push** your changes to GitHub to "save" your progress in the cloud.

### Sprint 1: The Architect
**Goal:** Data Structures & World Building.
- Locate the `levels` array in `script.js`.
- **Task:** Design Level 3, 4, and 5 using the grid system (0=Sky, 1=Brick, 2=[?], 3=Goomba, 4=Goal).
- *Git Check:* `git commit -m "feat: design all 5 levels"`

### Sprint 2: UI Synchronization
**Goal:** DOM Manipulation.
- Find the `loadLevel` function. 
- **Task:** Write the code to update the HTML `innerText` for the Level Number and the Player's Score.
- *Git Check:* `git commit -m "feat: connect game data to HUD"`

### Sprint 3: World Boundaries
**Goal:** Conditional Logic (The "Pit" Check).
- Find the `update` function.
- **Task:** Program a check to see if Yoshi's `y` position is greater than the `canvas.height`. If so, trigger the Game Over state.
- *Git Check:* `git commit -m "fix: implement pit death logic"`

### Sprint 4: The Head-Butt
**Goal:** Collision Direction.
- **Task:** Inside the platform loop, detect if Yoshi is moving **up** (`vY < 0`) and hitting a block. If the block is an "item" type, make it disappear!
- *Git Check:* `git commit -m "feat: add head-butt block destruction"`

### Sprint 5: Stomp or Die
**Goal:** Complex Physics Logic.
- **Task:** Program the enemy collision. If Yoshi lands on a Goomba's head, he should bounce and get points. If he hits them from the side, he loses.
- *Git Check:* `git commit -m "feat: implement enemy stomp system"`

### Sprint 6: Progression System
**Goal:** Level State Management.
- **Task:** Detect when Yoshi touches the Goal (Flagpole). Increment the `currentLevel` and reload the world.
- *Git Check:* `git commit -m "feat: complete level progression system"`

---

## 🎨 Asset Credits
- **Yoshi Sprite:** [PNGAll - Yoshi](https://www.pngall.com/wp-content/uploads/11/Yoshi-PNG-Images.png)
- **Enemy Sprite:** [PNGMart - Goomba](https://www.pngmart.com/files/23/Goomba-PNG-Photo.png)
- **Question Sprite** [melonDS Community - BlockBoy](https://melonds.kuribo64.net/board/userpic/397_1573947385.png)
- **Brick:** [FreePNGImg - Mario Tiles](https://freepngimg.com/thumb/brick/90535-mario-square-super-bros-brown-free-photo-png.png)

---
**Happy Coding, Engineers!** 🚀
