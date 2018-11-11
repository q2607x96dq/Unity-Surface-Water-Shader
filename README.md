# Unity-Surface-Water-Shader
A water surface shader for Unity

Thank you for downloading Szark's Water Shader!
This is still a WIP Shader and can be improved and added to.
If you have any issues please email jakubshark@gmail.com.

Currently Works:
- Main Texture with Distortion
- Normal Maps with Strength
- Waves with Optional Noise Texture
- Foam Intersection
- Change Color of Anything
- Transparency
- Depth Falloff
- Smoothness
- Flow Maps
- Height Color
- Low Poly Effect
- Underwater Effect

How to Use:
1. Add SzarkWater shader to desired Material
2. Add the Material to any object
3. Play around!

How to Use Under Effect:
1. Add Water Script to your water object
2. Add sphere collider and underwater script to camera
3. Attach a material with the included image effect
3. Make sure collider on water and camera are triggers
4. Disable underwater script on camera

Notes:
- To have reflections use a reflection probe with box projection active
and make the smoothness of the material higher than 0
- You require atleast 2 normal maps for your water for it to look
good.
- Please use the DepthFix script on old versions of Unity below 5.4

Version 1.4-1.5
- Now with Low Poly
- Fixed Normals and Normal Distortion
- Only 1 Normal Map can be used
- Refection is now more correct
- Changes to Example Map
- Now with Underwater Image Effect and
Water Script
- Changes to Names of Example Materials

Version 1.3
- Normals now only appear on the top of 3D objects / non-planar
- Added Optional Water and Underwater Effect Scripts
- Added SzarkUnderWater Image Effect Shader

Version 1.2
- Added Height-Based Color Change
- Fixed Refraction and Normal Distortion

Version 1.1
- Shader should work for older version of Unity
- Example Scene no longer uses pro-builder