# UV mapping and texturing

Just a short tut for myself on how to give my character life after modelling with

## Steps

1. First we must have a model to map
2. To UV unwrap we can use smart UV project, but that might not work or give the best result, so we will do this manually.
We do this by first selecting the model and going into edit mode.
3. Now we mark specifically what needs to be unwrapped by selecting faces, hitting "Ctrl+E" and selecting mark seam.

Things Ive learned:
- Seams are about telling the unwrapper where to cut the mesh and unwrap it. An example would be a sphere with a seam around equator. This would tell the unwrapper to unwrap two half spheres which would make it easy for us to apply an image as the texture of the object:

![Unwrapping a sphere](/notes/assets/Unwrap_spheres.png)

4. After doing this we select all with "A", hit "U" and unwrap the model.
5. Now the model is unwrapped and we may start applying out textures
