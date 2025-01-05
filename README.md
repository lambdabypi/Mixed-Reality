# Mixed-Reality
This repository includes all the MR games I've developed

## [MR Application 1: 3D Design Prototype in VR](https://drive.google.com/drive/folders/1D4Ru9sWPzxNoFze7tQyVP97eHJJs9WBZ?usp=drive_link)

This VR application serves as an early prototype for a potential 3D design app. It focuses on implementing basic XR interactions and key functionalities.

### Environment
- Custom skybox and floor
- Platform/table and shelf included
- At least four interactable objects from VR Interactable Objects package placed on the shelf

### Navigation and Controllers
- Right controller: Direct interaction only
- Left controller: Teleportation with reticle for destination visualization

### Feedback
- Hover and Select feedback with sound clips and vibrations
- Interactable objects play sound on collision and have bouncy material

### Interactions

**Highlight Object**
- Selected objects change to custom highlight color (modifiable in Inspector)
- Color reverts when deselected

**Clone Object**
- Press A button (primary) on right controller to clone selected object
- Clones current version, not prefab

**Destroy Object**
- Press B button (secondary) on right controller to destroy grabbed object
- Visual effect and sound clip played on destruction

**Color Wand**
- Placed on platform at game start
- Pickable by either controller
- Change tip color with trigger button (random color each press)
- Touch interactable objects with tip to change their color

## [MR Application 2: Enhanced 3D Design App](https://drive.google.com/drive/folders/1wtBRERsUyAXOc7pYJAxRrhQW5TQyHjW6?usp=sharing)

This application builds upon the first, adding various UIs and novel interactions.

### Environment
- Custom skybox and floor
- Platform included
- At least six shapes from XR Interaction Objects folder on wrist menu

### Controllers
- Left controller: Wrist menu control (3D rotatable object)
- Right controller: Direct interaction only, with pointer for interactions

### Wrist Menu

**Shapes Panel**
- Default panel
- Six different addable shapes
- Shapes highlight white when hovered
- Selected shapes added to scene with effects

**Colors Panel**
- At least four selectable colors
- Colors applied to right controller pointer on hover
- Visual feedback on hover

**Menu Panel**
- Reset button to reload current level

### Interactions

**Highlight Object**
- Hovered objects match pointer color
- Reverts to original color when not hovered

**Color Object**
- Press trigger to apply pointer color to hovered object

**Clone Object**
- Press A button to clone selected object
- Cloned objects respond to physics and self-destruct at distance

**Destroy Object**
- Press B button to destroy grabbed object with effects

**Resize Object**
- Use right joystick to scale objects (up to 4x larger, down to 0.5x smaller)

## [MR Application 3: VR Beat-Driven Exercise Game](https://drive.google.com/drive/folders/1Igqp2nR8dTN9q5NnTgaij6RjqFosabfu?usp=drive_link)

This application is a VR game inspired by BeatSaber and HitStream, focusing on destroying diamonds to the beat of music.

### Scenes
1. **Lobby**: Main menu with three level selection buttons
2. **Levels**: Three game levels with similar design but different songs

### Gameplay Mechanics

**Shapes (Diamonds)**
- Spawn at distance, move forward
- Players punch with correct controller (color-coded)
- Break into pieces when correctly punched (based on punch strength)
- Score increments on successful punch

**Blocks**
- Obstacles to avoid
- Random spawning and sizing
- Players lose points on collision

### Scorekeeping
- Start at 0 points
- Gain points by punching diamonds correctly
- Lose points for incorrect punches or block collisions
- Game over if score drops below 0
- Win by surviving until end of song

### Level Manager
- Monitors game state (Win/Lose)
- Manages UI updates and game-over conditions

### Feedback
- Haptic feedback for all collisions
- Controller vibrations for punches and collisions

## [MR Application 4: AR Darts Game](https://drive.google.com/drive/folders/1B307jAyu7O6ybj23X5barGDR7bR4lzfa?usp=drive_link)

This AR game utilizes spatial awareness for an immersive darts experience.

### Dart Board
- Traditional design with scoring slices
- Initially placed at default position
- Plays impact sound when hit

### Spatial Anchor
- Players anchor board to real-world surface
- Anchor persists across game sessions
- Repositionable by grabbing and moving

### Scoring
- Displays best score, current score, and time
- 1-minute gameplay
- Points awarded based on board sections hit

### Dart Behavior
- Three darts in holder on left controller
- Grabbable by right controller only
- Physics-based throwing with realistic force
- Points scored only when dart tip hits board

### Dart Spawner
- Maintains up to three available darts

### Helper UI
- START GAME button to begin
- RESTART button to reload scene
- RESET button to clear game data and anchors

This AR Darts game combines spatial awareness, physics-based interactions, and persistent data to create an engaging and realistic darts experience in augmented reality.

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/32279430/eb9e56bf-3b30-4da9-b8e9-31b1b78ae67e/paste.txt
