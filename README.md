# RTR_DXScene_SnowyCastleScene
Project I worked on as a part of my University Degree (Computer Games Development). 

I was required to implement a 3D "Castle" scene showing at minimum certain aspects of a castle such as towers, and that uses rendering techniques that were discussed in lectures such as; Texture Mapping and Water Effects at minimum. With one of; Foliage Effects, Particle Systems, and/or Lighting + Glow effects.

For this coursework I chose a castle on an island surrounded by a moat. The castle was accessed from Turbosquid as a single model (including the "hill"). However I used Blender3D to split the object and export each section as .obj (grouping them based on similar textures and shapes such as the castle was stone and square, the towers were stone and cylindrical etc) I also customised the materials to neaten them up a bit for import into DX11.  I used textures I found on the internet (google images) and modified them also. I also removed a good number of objects from the original also (as there were FAR too many polys/vertices), many of which were not visible, and I didn't want them.

The rendering techniques implemented in this scene are;
1. Texture Mapping (Anisotropic filtering, Normal + Environment mapping)
2. Water Effects (The moat)
3. Foliage Effects (the 4 Trees + the grass at the "bottom" of the hill)
4. Particle Systems (Fire, Smoke, as well as the snow) -- Compute shaders were also attempted (and I have left the compute shader I attemped in this repo - however it does not work at all. I left it in incase anyone else wants to give it a go)

The project started from one of the Tutorials as a starting point, and was expanded by myself from there.

Controls are;

Hold left mouse button, and move the mouse around to move the camera. Scroll wheel controls zoom. You cannot pan the camera.
