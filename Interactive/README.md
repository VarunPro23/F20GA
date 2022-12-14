**Interactive output of scene**

***Loading Models***

The models were first placed in a new blender file. Any modifiers used were applied to the objects. After applying all modifiers, all objects were joined into one object using *Ctrl+J*. Then, the singular object is selected and light mapped, to ensure the textures of all objects are present. 

After light mapping the objects, we add a new image texture to each material node. Then, we bake the object. The combined texture after baking is stored in the light map, and is mapped to the new image texture that we created. All materials except for one material is deleted, and the shader node is deleted, while the new image texture is used to give the object a texture. We then export the blender file as a gltf file, along with the texture. 

Once exported, we open VSCode and change the file name to the gltf file we exported and run the code. The models load onto the OpenGL window.

***Scene structure***

The scene has a signal, a race flag, a mustang and an aston martin. The cars are placed in front of the signal, and the flag is placed behind the signal.  

***Lighting***

There is a light included in the scene. I have written code to move the position of the light along the x and y axes, to show the different lighting on the models.

***Interaction within scene***

There are three types of interactions in the scene. The camera can rotate left and right, move front,back, up and down, while the lights move. 

*Key W* and *Key S* are used to zoom in and out of the scene. *Key A* and *Key D* are used to move the camera left and right. *Key Z* and *Key X* are used to move the camera up and down. 

The *up*,*down*,*left* and *right* arrow keys are used to rotate the camera around the object. The number keys *0*,*1*,*2* and *3* are used to move the lights in the scene. 
