# QUBE - A Connect4 in 3D Game
QUBE is a modern, browser-based reimagining of the classic connect-four game, set in a zero-gravity 3D environment. Challenge a sophisticated AI opponent and be the first to align four pieces in a row in any dimension. With its sleek, neon-cyberpunk aesthetic and intuitive 3D controls, QUBE offers a unique strategic challenge.

<div align="center">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/tin2tin/QUBE_Connect4_in_3D/master/index.html">PLAY</a><br><br>
</div>

https://github.com/user-attachments/assets/77b0f991-8285-4523-8683-bd9b86a430fa

## Features

*   **True 3D Gameplay**: Play on a 4x4x4 cube where winning lines can be formed horizontally, vertically, and diagonally across any axis.
*   **Advanced AI Opponent**: Face an AI with multiple difficulty levels:
    *   **Easy**: A great starting point for new players.
    *   **Medium**: A balanced opponent that will block obvious wins.
    *   **Hard**: An aggressive AI that actively seeks to create threats.
    *   **Very Hard**: A formidable opponent that can plan ahead, creating and defending against complex "fork" attacks (two winning lines at once).
*   **Stunning Visuals**: Rendered with Three.js, the game features a dark, futuristic theme with glowing neon pieces, reflective surfaces, and an immersive environment map.
*   **Intuitive Controls**: An innovative control scheme allows you to select a row for piece placement simply by clicking on a face of the cube, making 3D placement feel natural.
*   **Interactive UI**: Clean, modern interface for setting up games, tracking scores, and controlling game settings like music.
*   **Atmospheric Music**: Includes looping background music to enhance the sci-fi atmosphere, with an easy-to-use toggle button.

## How to Play

### The Objective

Be the first player to place four of your pieces in a continuous straight line. Lines can be formed:
*   Horizontally on any layer.
*   Vertically through any column.
*   Diagonally across any single plane.
*   Diagonally through the entire cube from one corner to another.

### Controls

1.  **Camera**: Click and drag with the **left mouse button** to rotate the cube. Use the **mouse wheel** to zoom in and out.
2.  **Select a Row**: **Hover** over the cube to see potential rows highlight in real-time. **Left-click** on any cell face to select that row for your turn.
3.  **Choose a Position**: Once a row is selected:
    *   **Left-click** on any empty, highlighted cell within that row to move your temporary preview piece there.
    *   Press the **Spacebar** to automatically cycle to the next available position in the selected row.
4.  **Confirm or Cancel**:
    *   Click the **"Confirm"** button or press **Enter** to finalize your move and place your piece.
    *   Click the **"Cancel"** button, press **Escape**, or **right-click** anywhere to deselect the current row and choose a different one.

## Technical Details

*   **Rendering Engine**: [Three.js](https://threejs.org/) (r128)
*   **Languages**: HTML, CSS, JavaScript (ES6 Modules)
*   **Key Three.js Features**:
    *   `OrbitControls` for camera manipulation.
    *   `RGBELoader` for High Dynamic Range (HDR) environment maps.
    *   `MeshStandardMaterial` for realistic, reflective playing pieces.
    *   Dynamic cube mapping for real-time reflections on a central sphere.
