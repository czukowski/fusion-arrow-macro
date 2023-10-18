![Arrows.png](https://repository-images.githubusercontent.com/704959692/8836442d-c041-4561-a305-0e452bd39ddd)

Fusion Arrow Macro
==================

A set of macro tools for DaVinci Resolve Fusion to create parametric arrows based on an arc.

Currently, arrow head and width, as well as input image size are not configurable. Feel free to use this as a template
and modify to suit your needs.

Arrow tool
----------

Just a plain arrow, connect its output to Backgroud node, etc. Its only parameter is a Curvature.

ArrowColorTransform tool
------------------------
 
Arrow tool connected to a Backgroud node and a Transform node, combined into a single tool. The following addition
controls are exposed:

 - Color, in the same way as with a usual Background node (plain, gradients, etc)
 - Offset from center
 - Scale
 - Rotation angle
 - Flip (horizontal and vertical)

ArrowColorTransformShadow tool
------------------------------

ArrowColorTransform tool with additional nodes in order to simulate a Drop shadow effect, it has some additional controls:

 - Blend
 - Blur strength (combined or separately horizontal and vertical)
 - Shadow distance
 - Shadow angle (using some crude math)
 - Shadow scale
 - Shadow color (plain)
