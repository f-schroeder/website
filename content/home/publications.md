+++
# Recent Publications widget.
# This widget displays recent publications from `content/publication/`.
widget = "publications"
active = true
date = 2018-08-15T00:00:00

title = "Publications"
subtitle = ""

# Order that this section will appear in.
weight = 20

# Number of publications to list.
count = 10

# List format.
#   0 = Simple
#   1 = Detailed
#   2 = APA
#   3 = MLA
list_format = 3

# Filter by publication type.
# -1: Any
#  0: Uncategorized
#  1: Conference proceedings
#  2: Journal
#  3: Work in progress
#  4: Technical report
#  5: Book
#  6: Book chapter
publication_type = "-1"

# Exclude publications that are shown in the Selected Publications widget?
exclude_selected = false
+++

## Global Illumination using GPU Path Tracing and the Line Space datastructure</h2>
#### Bachelor Thesis

![](img/ba_thesis.jpg)

<details>
<p>

This thesis presents a novel technique in computer graphics to simulate realtime global illumination using path tracing. Path tracing is done with compute shaders on the graphics card (GPU) to perform rendering in a highly parallelized manner. To improve the overall performance of tracing rays, the Line Space is used as an acceleration data structure in different variations, resulting in better empty space skipping. The Line Space saves scene information based on a previous voxelization in direction-dependent shafts and is generated and traversed on the GPU. With this procedure, indirect lighting and soft shadows can be computed in a physically correct way. Furthermore, using the Line Space, path tracing can be performed mostly independent of the complexity of the scene geometry with over 100 frames per second, which is truly real-time and much faster than using a comparable voxel grid. The image quality is not affected negatively by this technique and the shadow quality is in most cases much better compared to shadow-mapping.

Click the following link to download the full document (in german language): https://kola.opus.hbz-nrw.de/frontdoor/index/index/docId/1438

This work received the **first price of the CV-Award 2017** at the University of Koblenz.

</p>
</details>

___

## Comparison of Rendering Pipelines
#### Seminar Work

![](img/pipelines.png)

<details>
<p>

This seminar work presents a brief comparison of the rendering pipelines in the Unity Engine 5, the Unreal Engine 4 and a basic OpenGL renderer. The pipelines are compared with the example of deferred shading and also other concepts like ray tracing are briefly addressed.

The full PDF document can be found [here](https://wp.uni-koblenz.de/fschroeder/wp-content/uploads/sites/29/2017/07/SW_Pipelines.pdf) (in german language).

</p>
</details>
