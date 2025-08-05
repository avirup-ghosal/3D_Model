# 🥿 Three.js Shoe Viewer

A 3D shoe model viewer built with **Three.js** and hosted on **GitHub Pages**.  
Features realistic lighting, orbit controls, and smooth model rendering with GLTFLoader.

## 🚀 Live Demo
[**View on GitHub Pages**](https://avirup-ghosal.github.io/3D_Model/)
## Approach
This 3D shoe viewer is built using **Three.js** with the **GLTFLoader** to import a .glb model. The scene includes multiple light sources (spotlight, point lights, ambient light) to ensure good visibility from all angles, including the underside of the shoe.
Camera control is handled using **OrbitControls** with restricted zoom limits to maintain focus on the model.
The model is placed above a transparent plane to give a floating effect without a visible floor.
The project is hosted on GitHub Pages and the 3D model is stored inside the public/model_data/ folder.
