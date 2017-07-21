# How to create a simple character from scratch

This is a short guide on creating a character in blender for myself.

## Steps

1. Get a picture of the character, either draw it or find a character reference on the internet. This should be front and side view of the desired character.
2. Set the reference picture as the background image in blender: Press "N" -> Add image*2 -> Set to front and side and move the background/object as desired
3. Enter edit mode on a cube and view in wireframe. Now use "B" to box select vertecies and "A" to select all, aswell as "C" to select some
4. Do a loop cut in the middle of the box with "Ctrl+R" and select all vertecies on one side of the box. Delete them with "X" or "Delete"
5. Add the mirror modifier to the object, Clip should be enabled
6. Now start modeling the torso (for example) by selecting and running the vertecies to the shoulder, neck and chest
7. Select vertecies which make up faces and extrude them to create the character

Things Ive learned:
- Its smart to create the body and legs first in front view -> switch to side and adjust the model -> back to front to create the arms and legs -> At this point we start smoothing out the model by whatever looks good. This last step may take a while

8. Finally we may add a subdivision modifier to smooth out the model. Now we may move onto mapping the model, creating materials, rigging, animating and so on.
