(from https://code.google.com/archive/p/daedalus-lib/)

README:

Fully dynamic constrained Delaunay triangulation and pathfinding

Direct download: Sources and demos

Daedalus Lib manages 2D environment modeling and pathfinding.

When I began to code Daedalus, I had many ideas in mind:

    focus on 2D
    fastness and accuracy
    simplicity of use

Why focus only on 2D and not on 3D ? Because constraining to 2D allows to gain simplicity and efficiency. Many great games today are still based on 2D engines involving 2D mechanics, 2D physics and 2D display ; so I hope Daedalus will find his place as a new component for new 2D projects.

Fastness and accuracy are reached by using among the best techniques available in the field of computational geometry : half-edge structure and fully dynamic Delaunay triangulation. Daedalus algorithms are based on many research publications, among them:

    Efficient Triangulation-Based Pathfinding by Douglas Jon Demyen
    Fully Dynamic Constrained Delaunay Triangulations by Kallmann, Bieri and Thalmann
    An improved incremental algorithm for constructing... by Marc Vigo Anglada

For simplicity, I assumed that the library should work without any pre-generated data. Everything should work in real time : constraints insertion/motion/deletion and path generation. Also I assumed that the library should be fault tolerant to designer/developer mistakes : obstacles are clipped, can overlap and can be of any shape : open, convex, concave... At last, the path generation can manage any number of circle-shaped objects in order to avoid any obstacle collision.

Want to learn more ? Read wiki introduction



Fully dynamic constrained Delaunay triangulation and pathfinding

Direct download: Sources and demos

Daedalus Lib manages 2D environment modeling and pathfinding.

When I began to code Daedalus, I had many ideas in mind:

    focus on 2D
    fastness and accuracy
    simplicity of use

Why focus only on 2D and not on 3D ? Because constraining to 2D allows to gain simplicity and efficiency. Many great games today are still based on 2D engines involving 2D mechanics, 2D physics and 2D display ; so I hope Daedalus will find his place as a new component for new 2D projects.

Fastness and accuracy are reached by using among the best techniques available in the field of computational geometry : half-edge structure and fully dynamic Delaunay triangulation. Daedalus algorithms are based on many research publications, among them:

    Efficient Triangulation-Based Pathfinding by Douglas Jon Demyen
    Fully Dynamic Constrained Delaunay Triangulations by Kallmann, Bieri and Thalmann
    An improved incremental algorithm for constructing... by Marc Vigo Anglada

For simplicity, I assumed that the library should work without any pre-generated data. Everything should work in real time : constraints insertion/motion/deletion and path generation. Also I assumed that the library should be fault tolerant to designer/developer mistakes : obstacles are clipped, can overlap and can be of any shape : open, convex, concave... At last, the path generation can manage any number of circle-shaped objects in order to avoid any obstacle collision.

Want to learn more ? Read wiki introduction



 The project was created on Sep 12, 2014.

    License: MIT License
    6 stars
svn-based source control
