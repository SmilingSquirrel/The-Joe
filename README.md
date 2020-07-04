# The-Joe
The Joe - [BGMC32]
By SmilingSquirrel

Built in UPBGE 0.2.5
Assets made with Blender, Gimp, and Audacity



Goal - Get some coffee!


Controls:
	W,A,S,D - Move
	
	Mouse	- Look Around
	
	Left Mouse	- Interact
	
	Esc	- Go to Main Menu
	
	F12	- Shut down Blender


Credits:
	Models, textures, sounds, animation and logic by SmilingSquirrel.
	Story by SmilingSquirrel and friends.












Bugs:
	I've only identified one bug so far, but it seems it could turn out to be a major problem. While looking around, if the mouse cursor crosses certain areas/objects, the logic spikes. Combine this with the ambients sounds kicking on, and I've dropped to less than 10 FPS a couple times. The area around the mall stairs seems to be the poblem, though there are NO logic bricks used in any objects(excepting the rotating car) in that area. Until I set the car to "No Collision", passing the cursor over it would cause a significant logic spike. I'm afraid I can't figure this one out. (One guess, but it seems like it doesn't fit all situations. Perhaps there are too many "Near" sensors?)
