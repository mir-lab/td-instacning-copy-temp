---
layout: default
title: Variation 3 | UV Offset
nav_order: 1
parent: Puzzle Pieces
---

## Puzzle Pieces
# Variation 3 | UV Offset

*****

[Load Example](?remoteTox=){: .btn .btn-load-example .mr-2}
[Open Network](?openNetwork=True){: .btn .btn-td-network .mr-2}
[Web](?openInBrowser=True){: .btn .btn-load-web .mr-2}

Our final example of this puzzle piece challenge looks at how to use the UV offset parameters for instancing. Here rather than actually slicing up our image, we instead provide a set of offset coordinates for where to sample our texture from. This kind of slicing is highly efficient, but difficult to "read" visually when looking at TouchDesigner. In order to understand what's really happing in this example it's important to have a handle on the relationship between texture coordinates and geometry.

---

#### Tested in TouchDesigner099 2020.23680 
>*Updated 06.03.20*  
Matthew Ragan  
Zoe Sandoval  