# PolySpatial
PolySpatial convert scene to RealityKit
- Materials (urp  = lit, simple lit, complex lit. birp = standard)
	- Unity Shader graph supported
	- Unlit supported
	- Occlusion shader supported
Unity allow play to device with simulator
# UI
- UGUI
- UI Toolkit
# Input options
- [[XR Interaction Toolkit]]
  - high level
  - abstract hands and controllers
  - support 3D interaction
  - locomotion
  - visual feedback
- unity input system (Unity Input System)
- raw hand data (unity hands package)
# Recommended config 
- unity 2022
- urp ⇒ static foveated rendering
- input system package
- static foveated rendering
- single pass instanced rendering (one draw call per eye)
- depth compositing (ensure proper depth buffer writing)

Building workflow
- Select build target
- enable XR plugin
- recompile natives if needed
- building in unity generate an Xcode project
- Then test on Xcode Simulator