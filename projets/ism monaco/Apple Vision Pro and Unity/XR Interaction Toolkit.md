- high level
- abstract hands and controllers
- support 3D interaction
- locomotion
- visual feedback
# Modules
## Interactables 
objects that can be interacted with (define how to react on interaction)
	- Simple : subscribe to events
	- grab : follow hand position on grab and inherit velocity on release
	- teleport : area or location a user can teleport to
	- Custom
## Interactors
objects that can interact with interactables (specify how that interaction happen)
	- Direct : select on touch
	- Ray : far away and easily customizable
	- Socket : make an area accept an object
	- Poke : Direct + direction filtering for a button to work
	- Gaze : Ray + fancies for easier use for eye tracking
## interaction manager
tie those together
	- can have multiple group of interactor+  interactable + managers, one per set of interactions (ex: main menu vs individual scenes)
## Other options
- Abstract input system available
- Map to other interaction systems
- Access raw hand from the hands package
	- identify gestures
	- apply custom mesh 