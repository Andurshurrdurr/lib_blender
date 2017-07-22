# UV mapping and materials

Just a short tut for myself on how to give my character life after modelling with materials.

## High level overview

- Materials define all the properties regarding how a model will display itself in color, diffuseness, glossyness, transparency, translucency and so on. There is very little limit to what can be done with materials.
- Texturing is about giving our material specific values at specific coordinates on our mesh. Texturing cannot occur before we add materials to our models.
- UV mapping is the process of unwrapping our 3D model from the 3D space to a 2D space. Using the UV map we can do more advanced stuff with our models, such as applying an image on our model.

**Basically:**
*Create model/mesh -> UV map (Optional) -> Apply materials + Texturing*

## Steps

1. First we must have a model to map
2. To UV unwrap we can use smart UV project, but that might not work or give the best result, so we will do this manually.
We do this by first selecting the model and going into edit mode.
3. Now we mark specifically what needs to be unwrapped by selecting faces, hitting "Ctrl+E" and selecting mark seam.

Things Ive learned:
- Seams marks where the unwrapper can not join our model in the UV map.
- Using seams, we can mark and unwrap the model into multiple 2D pieces.
- An example may be to mark a seam accross the equator of a sphere. This will unwrap the sphere into two 2D domes. See below

![Unwrapping a sphere](/notes/assets/Unwrap_spheres.png)

4. After doing this we select all with "A", hit "U" and unwrap the model.
5. Now the model is unwrapped and we may start applying our material using the UV wrap

## Hotkeys


After unwrapping in UV Editor
- CTRL-A : Avg size
- CTRL-P : Pack
