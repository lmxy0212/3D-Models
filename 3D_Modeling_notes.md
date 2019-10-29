## 3D Modeling

[TOC]

### Sep17

-----

- Multi-cut tool

- Edit mesh -> merge
- 3 -> see irregularity
- Bridge tool: edit mesh -> bridge
- circularize
- mesh -> combine
- eye ->select 4 polygons -> delete ->add sphere -> make edges follow the eyeball
  - same # edges from upper and bottom eyelid
- hw: by Thur
  - 3 animal w/only 4 sided polygon(submission)
  - what interior of a room to model (idea)
- five side and triangle -> connecting conner -> collapse
- finding triangles: mesh ->optimize/cleanup->selecting matching polygon
- scale tool-> flate surface for the center=> modify-> freez transformation -> merge
- add edge loop:
  - select a surface(hold shift and select multi faces)
  - hold shift -> select center blue point
  - drag and adjust the loop

## Sep 19

- D -> pivot point
- mesh display -> reverse
- pivot point at conner
- create -> camera
  - panel -> look through selected 
- view camera setting -> resolution 
- time frame -> m (mark)
- select surface(extract) -> plus sign on the left of the object in Outliner -> Arnold -> light -> mesh light -> attribute -> turn light visiable on
- Arnold render?



- wp rename:
  - on the lower left conner -> MEL 
  - run rehash
  - run wp_rename
- F => center
- snaping
  - x:grid snaping
  - v:point sniping
- component: edge face vertex
- extrude: command e/ shit and move
- double click: select edge loop// hit a triangle, stop
- command right click -> edge loop utility
- Multicut tool
  - ctrl 
- channel editor: positioning
- view:
  - 4 : see the reference
  - 5 : see the form
  - 3: see smoothed shape
- display -> add selected object // for image plane
- leg and limbs -> 4 polygon to extrude from
- shift select/ ctrl deleting select
- mirroring:
  - no faces inside -> select -> delete faces in the center
  - double click the entire boarder -> scale to the same surface -> x snap to grid
  - cmd d -> scale x -1
- area light: make the object to be the light // use extract for the object
- display -> polygon -> show face normal 
  - usually dont render things twice

## Sep 26

- surportive edges -> sharp edge when smoth
- curtain -> supporting edge at top bottom and sides -> 1d -> more folds



## Oct 1

### modeling a Sci fi grenade

- edit -> duplicate special -> option box
- symetrical by 16
- 64
- quad draw tool
  - tab -> create surface
  - shift -> smooth brush
- modify central pivot
- edge -> control  -> right click -> edge ring
- side -> enviroment -> image plane
- Display layer -> add selected -> R
- ctrl B -> chamfer-> fraction
- 200 = 5 * 5 * 4 * 2*
- duplicate transform:
  - 20 segments -> dup -> instance
- 



## oct 2

- deformer

  - bend
    - envelope:1
    - 1 unit wide:
  - lattice

- wire + face -> extrude follow the wire

- average vertex -> cmd G

- G: last cmd used




## OCT 29

Cmd + right click -> To faces

Model checker Jakob JK

python-> cmd return(run)
Lamina: 2 faces on top of each other







