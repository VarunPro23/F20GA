**Animations in UnReal Engine**

***Issues Faced and How I Solved Them***

1. The car models, when imported to UnReal did not get imported completely from Blender. Only half the car body was imported. To solve this, I had to change the face orientations of the cars on Blender. Then when I imported the cars into Unreal, the cars were imported completely.

2. The race flag's texture was not imported into Unreal Engine. To solve this, I had to UV map the flag texture on Blender, and then save it as a texture file and then imported it into Unreal engine. The race flag's checker texture was corrected.

3. The traffic signal lights colors were not being applied to the light spheres. Their textures were not imported correctly. To solve this, I created new textures for the lights and then applied it to them.

4. The race flag does not move. I have not been able to solve this issue, but my idea for the flag was to make it flow using a wind force field.

***Animations and Camera***

I used a MasterSequencer to create a fly through camera. There are 5 shots, 7 seconds each, with each shot having different camera positions and rotations. I have added transition effects to make the vidoe look more aesthetic.
