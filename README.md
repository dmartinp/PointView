The PointView Quark
===================
_An interactive view displaying a collection of points in 3D space._

Points are `Cartesian` points (optionally specified as directional pairs of
`[azimuth, elevation]`) rendered through a 3-D or orthogonal projection. The
model of points can be rotated or animated and the perspective can also be
manipulated. Points can be displayed with colors, individually or in groups, and
connecting lines can illustrate relationships between them.

The view and rotation controls are most conveniently changed through the UI
built into the view, though these methods and more are available for more
elaborate display of the points.

![PointView Interface](HelpSource/img/PointView_interface.png)

Installing
==========

Install via SuperCollider's command line:

>`Quarks.install("https://github.com/ambisonictoolkit/PointView")`

It's recommended but not required that you also install the
[SphericalDesign]("https://github.com/ambisonictoolkit/SphericalDesign")
Quark for the ability to form a triangular mesh across convex sets of points:

>`Quarks.install("https://github.com/ambisonictoolkit/SphericalDesign")`


Feedback and Bug Reports
========================

Known issues are logged at
[GitHub](https://github.com/ambisonictoolkit/PointView/issues).


Change log
==========

0.3.0
- add export view to an image, optionally with or without controls shown.

0.2.0
- add ability to specify stroke width and color for each connection.
- depth-first drawing of connections and axes to enchance 3D effect.
- add axis stroke width setter method.
- scale orthographic projection view down slightly to allow room for index text on outermost points.

0.1.0
- initial release.

Credits
=======

The development of the PointView Quark for SuperCollider3 is supported
by
[The University of Washington's Center for Digital Arts and Experimental Media (DXARTS)](https://dxarts.washington.edu/).
&nbsp;

Copyright the ATK Community, Joseph Anderson, and Michael McCrea, 2018.

* J Anderson : [[e-mail]](mailto:joanders[at]uw.edu)
* M McCrea : [[e-mail]](mailto:mtm5[at]uw.edu)


Contributors
------------

*  Michael McCrea (@mtmccrea)
