+++
# Projects widget.
widget = "projects"
active = true
date = 2018-08-15T00:00:00

title = "Projects"
subtitle = ""

# Order that this section will appear in.
weight = 10

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
# [[filter]]
#   name = "All"
#   tag = "*"
#
# [[filter]]
#   name = "Deep Learning"
#   tag = "Deep Learning"
#
# [[filter]]
#   name = "Other"
#   tag = "Demo"

+++

## ORVIS
#### Modern OpenGL 4.6 and C++17 rendering framework

<details>
<p>

This is my most recent framework for personal projects and quick and easy development of OpenGL based applications.
It uses modern C++17, OpenGL 4.6 and a GPU-driven rendering pipeline including [AZDO](https://www.slideshare.net/CassEveritt/approaching-zero-driver-overhead), [DSA](https://www.khronos.org/opengl/wiki/Direct_State_Access), [bindless textures](https://www.khronos.org/opengl/wiki/Bindless_Texture) and [indirect multi-draw](https://www.khronos.org/opengl/wiki/Vertex_Rendering#Indirect_rendering) calls. It also automatically performs GPU-view-frustum-culling and contains a fast model-loader and PBR-shading.

You can take a look at the code here: https://github.com/f-schroeder/orvis

</p>
</details>

___

## Volumetric Lighting
#### Froxel-based real-time volumetric fog

![](img/volumetric.jpg)

<details>
<p>

We implemented the frustum-aligned voxel-grid based volumetric lighting algorithm presented by Bartlomiej Wronski in ["Volumetric Fog and Lighting"](https://books.google.com/books?hl=en&lr=&id=30ZOCgAAQBAJ&oi=fnd&pg=PA217&dq=gpu+pro+6+volumetric+wronski&ots=2ZfubWDDFI&sig=P611iciYxczkBTD5LDngvBYPN10) (GPU Pro 6).
We used OpenGL 4.6 and C++17 and our team consisted of Maximilian Mader ([@maxesstuff](https://twitter.com/maxesstuff)) and Darius Thies.

The code can be found here: https://github.com/Max1412/Graphics2

</p>
</details>

___

## DINO
#### Ray-Tracing framework for distance fields and implicit surfaces

![](img/distancefield.jpg)

<details>
<p>

DINO was developed by me and 12 other students in an internship at the University of Koblenz. 
It renders distance fields and implicit surfaces in real-time and is also able to discretize triangle meshes to SDFs.
Rendering is done using OpenGL and the framework is implemented in C++17.

https://gitlab.uni-koblenz.de/CVFP_DF18/Framework

</p>
</details>

___

## OneHit
#### 3D multiplayer battle arena game (Unreal Engine 4.10)

![](img/onehit.jpg)

<details>
<p>

In this multiplayer game players fight against each other in fast and action-packed battles. 
Each one has to choose one of the four characters and use a variety of attack and defense skills to defeat the opponents. 
The clou: just a single hit kills, so one has to be careful.

This game received the **third price of the CV-Award 2016** at the University of Koblenz.

OneHit was released on [Steam](http://store.steampowered.com/app/697270/OneHit/) on 10/31/2017.

</p>
</details>

___

## CVARK
#### AR-Framework

![](img/cvark.jpg)

<details>
<p>

In this internship I developed the augmented reality framework "CVARK" at the University of Koblenz together with 13 other students.
We used NVIDIA PhysX, OpenCV and OpenGL as well as C++ and GLSL to implement a funny AR-Game.
Take a look at the [demo-video](https://www.facebook.com/followcvark/videos/593819184114932/) to get a better impression.

</p>
</details>
