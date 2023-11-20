---
layout: inner
title: RollEngine
permalink: /rollengine/
---

![](/img/posts/rollengine_capture.png)
## RollEngine

<div style="text-align: justify">

<p style="font-size:1.3em">
    This project consists of a graphics engine that I made with a classmate in my last year of ESAT. For this, we use libraries like GLFW, glm, or imgui to be able to perform rendering tasks, as well as to create an interface to be able to use all the functionalities of the engine. This engine was made mostly in C++ and with OpenGL, and also supports:
</p>

</div>

- <font size="4"> Geometries </font>
- <font size="4"> Materials </font>
- <font size="4"> Lights </font>
- <font size="4"> Shadows </font>
- <font size="4"> Deferred rendering </font>
- <font size="4"> Post processes </font> 
- <font size="4"> Lua scripting </font>

Some of the rendering techniques we implemented in this project are the following:

<div style="text-align: justify">

<ul style="font-size:1.3em">
    <li>Render to texture: To do this, we use the framebuffers provided by OpenGl, so that we can store textures with the colour values of our scene in them.</li>
    <li>Shadow mapping: The idea with this technique is to render the scene from the point of view of the light that produces shadow, and whatever you can see from your point of view will be lit, and whatever you can't see will be shadow.</li>
    <li>HDR & Bloom: In our engine, we can implement several post-processes. Among them, we chose to implement bloom, which works best using HDR, which basically consists in allowing it to exceed the clamped limit of the light colour values, and return them to their original range at the end without losing detail.</li>
    <li>Deferred Shading: We try to render the scene in a normal way by binding our geometry framebuffer to store position, normal and diffuse & specular values in their corresponding textures, and laterm at a final stage we render a quad by binding the three previous textures and calculating the lighting in the shaders using these textures.</li>
</ul>

</div>