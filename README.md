<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="3D WebXR Furniture" />

&#xa0;

<a href="https://padmavatisb.github.io/AR_RoomDecor/">Demo</a>

</div>

<h1 align="center">3D WebXR Furniture</h1>

<p align="center">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/padmavatisb/AR_RoomDecor?color=56BEB8" /> -->
  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/padmavatisb/AR_RoomDecor?color=56BEB8" /> -->
  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/padmavatisb/AR_RoomDecor?color=56BEB8" /> -->

</p>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/padmavatisb" target="_blank">Author</a>
</p>

<br>

## :dart: About

Use augmented reality (AR) to pick and place a selection of furniture models into your surroundings in real-time using your mobile's camera.  
This project leverages ThreeJS to render the scene and furniture models, WebXR to enable AR mode with real-time environment lighting, hit testing for placing furniture on the floor, and dom-overlay for UI.

View the **live demo on your mobile** at:  
➡️ [https://padmavatisb.github.io/AR_RoomDecor/](https://padmavatisb.github.io/AR_RoomDecor/)

## :checkered_flag: Starting (using demo)

1. Using your phone, open: [https://padmavatisb.github.io/AR_RoomDecor/](https://padmavatisb.github.io/AR_RoomDecor/)
2. Click the `Enter AR` button at the bottom of the screen.
3. Allow camera permissions.
4. Scroll through the row of furniture selections at the bottom. Click a thumbnail to select (you’ll see a white border).
5. Move your phone around — a white ring (reticle) will appear showing where you can place furniture.
6. While the reticle is visible, tap the screen to place the selected furniture model.
7. Continue walking around and panning to view the furniture in real 3D space.
8. Switch furniture selections anytime to place different items.
9. Click `Stop AR` to exit.

## :sparkles: Features

:heavy_check_mark: Hit Testing  
:heavy_check_mark: Real-Time Environment Light Estimation  
:heavy_check_mark: Augmented Reality with WebXR  
:heavy_check_mark: Realistic 3D Models with Textures  
:heavy_check_mark: Horizontally Scrollable Furniture Selection  
:heavy_check_mark: DOM Overlay UI

## :rocket: Technologies

This project uses:

- [ThreeJS](https://threejs.org/)
- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://immersiveweb.dev/)

## :white_check_mark: Requirements

Before running locally, make sure you have:

- [Git](https://git-scm.com)
- [Node](https://nodejs.org/en/)

## :checkered_flag: Starting locally

```bash
# Clone this project
git clone https://github.com/padmavatisb/AR_RoomDecor.git

# Go into the project directory
cd AR_RoomDecor

# Install dependencies
npm install

# Start the development server
npm run start
