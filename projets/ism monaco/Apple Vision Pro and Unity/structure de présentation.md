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


### Unity



## Expérience

### considérations Gameplay
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
	- hover effects for interactive elements
	- use at least 60 points of space for tap targets 
- Delightfull
	- honor spacial awareness 
		- arm reach = interactive, keep items close if they are interactive
		- use cues to help understand what to do
	- Create real-world parity
		- mimic real world interactions
		- do user testing
	- Abstract away complexities
		- automate some features that used to need to be done manually in the real world