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
- windowed (flat)
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

Design recommendations
- Intentional
	- encourage key moment unique to vision os
	- find how to make new things possible 
	- Models
		- need photorealistic
		- bring them to life with animation
	- do a lot of prototyping
	- build something complementary if too many informations → cross platform
- Immersive exemple
	- transport people somewhere new
	- great environments replicate an accurate sense of depth and scale
	- or consider physical surendings (ex: splats on walls)
	- design meaningfull sound (sound is computed to feel like it belong to your real environment)
- Comfortable
	- require minimal movement
	- keep windows to a minimal and cohesive uis
	- keep related ui elements close to one another (you can put menus outside a window but anchor them to it)
	- keep stuff into a minimal of ui panels to avoid user having to manage all the uis 
	- no light and dark mode, use the real world lighting with glass textures
	- hover 
### Unity
PolySpatial convert scene to RealityKit
- Materials (urp  = lit, simple lit, complex lit. birp = standard)
	- Unity Shader graph supported
	- Unlit supported
	- Occlusion shader supported
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
	- can have multiple group of interactor+  interactable + managers, one per set of interactions (ex: main menu vs individual scenes)
- other options
	- Abstract input system available
	- Map to other interaction systems
	- Access raw hand from the hands package
		- identify gestures
		- apply custom mesh 
## Expérience

### considérations Gameplay


