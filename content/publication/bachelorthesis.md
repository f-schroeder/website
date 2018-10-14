+++
title = "Global Illumination using GPU Path Tracing and the Line Space datastructure"

# Date first published.
date = "2017-03-24"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Felix Schröder"]

image_preview = "ba_thesis.jpg"
image = "ba_thesis.jpg"

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = "Bachelor Thesis"
publication_short = "Bachelor Thesis"

# Abstract and optional shortened version.
abstract = "This thesis presents a novel technique in computer graphics to simulate realtime global illumination using path tracing. Path tracing is done with compute shaders on the graphics card (GPU) to perform rendering in a highly parallelized manner. To improve the overall performance of tracing rays, the Line Space is used as an acceleration data structure in different variations, resulting in better empty space skipping. The Line Space saves scene information based on a previous voxelization in direction-dependent shafts and is generated and traversed on the GPU. With this procedure, indirect lighting and soft shadows can be computed in a physically correct way. Furthermore, using the Line Space, path tracing can be performed mostly independent of the complexity of the scene geometry with over 100 frames per second, which is truly real-time and much faster than using a comparable voxel grid. The image quality is not affected negatively by this technique and the shadow quality is in most cases much better compared to shadow-mapping."

abstract_short = "This thesis presents a novel technique in computer graphics to simulate realtime global illumination using path tracing. Path tracing is done with compute shaders on the graphics card (GPU) to perform rendering in a highly parallelized manner. To improve the overall performance of tracing rays, the Line Space is used as an acceleration data structure in different variations, resulting in better empty space skipping. <br> This work received the *first price of the CV-Award 2017* at the University of Koblenz."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["linespace"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Full PDF", url = "https://kola.opus.hbz-nrw.de/frontdoor/index/index/docId/1438"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true
+++

This work received the **first price of the CV-Award 2017** at the University of Koblenz.
