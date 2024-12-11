# thèmes
## capacités techniques

### ShariiingXR

SDK pour interaction avec AVP :
- Partage de perspective
- notes et notifications transposées dans le casque
![](Pasted%20image%2020241211103951.png)

### AVP
Full hand tracking 
- Pas de bataille en temps réel
- Manipulation organique

Eye Tracking
- interaction par sélection

Types of apps
- Immersives AR bounded to a small area (shared space)
- Fully immersive VR 

types of volume camera
- bounded - shared space (unity dimension and transform, real world size, movable by user)
- unbounded (full space, only one at a time)

input type
- Look and tap (most common: distant, direct touch, multiple taps)
- hands (exact position, hand package: unbounded only, with permission)
- head pose (exact position, input system: unbounded only)
- AR (arkit: unbounded only, with permission)
- bluetooth devices (keyboards, controllers, other system supported devices)
### Unity
PolySpatial convert scene to RealityKit
- Materials (urp  = lit, simple lit, complex lit. birp = standard)
	- Unity Shader graph supported
	- Unlit supported
	- Occlusion shader supported
	- 
Unity allow play to device with simulator

UI
- UGUI
- UI Toolkit

Input options
- XR Interaction Toolkit (abstract inputs)
	- high level
	- abstract hands and controllers
	- support 3D interaction
	- locomotion
	- visual feedback
- unity input system (Unity Input System)
- raw hand data (unity hands package)


Recommended config 
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

XR Interaction Toolkit
- Interactables : objects that can be interacted with (define how to react on interaction)
	- Simple : subscribe to events
	- grab : follow hand position on grab and herit velocity on release
	- teleport : area or location a user can teleport to
	- Custom
- Interactors : objects that can interact with interactables (specify how that interaction happen)
	- Direct : select on touch
	- Ray : far away and easely customizable
	- Socket : make an area accept an object
	- Poke : Direct + direction filtering for a button to work
	- Gaze : Ray + fancies for easier use for eye tracking
- interaction manager : tie those together
## Expérience

### considérations Gameplay


