---
layout: inner
title: VoxelTerrain
permalink: /voxelterrain/
---

![](/img/posts/voxel_map_image.png)
## Voxel Terrain

<div style="text-align: justify">

<p style="font-size:1.3em">
    This is a project I developed together with a classmate in my last year of ESAT in C, that was tested in a Linux enviroment. It is a program in which we can draw a 3D terrain with voxels from a height map stored in a texture. We then give it colour by reading another texture with the stored colour data. In addition, we also implement a movable camera with parameters to be able to visualise and move around the scene.
</p>

<p style="font-size:1.3em">
    The main objective of the project, apart from programming all of the above, was to optimise this programme as much as possible. To do so, we had to: 
</p>

</div>

- <font size="4"> Focus a lot on removing as many operations as possible from the rendering loops. </font>
- <font size="4"> Use pre-calculations. </font>
- <font size="4"> Reduce the bits needed to store the texture information. </font>
- <font size="4"> Try to replace expensive operations such as multiplication with additions. </font>
