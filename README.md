Parametric Brushless RC Fan Generator
=====================================

Introduction
------------

This is a fork of hyperair's parametric fan blade generator. This program generates
cooling fans appropriate for mounting onto the back of a brushless rc motors.
A high hub to diameter ratio is neccesary in order to generate enough
pressure to draw air through the motor windings. Additionally, a course pitch is
recommended to generate airflow at low rpms. Fan's have been tested at 15k rpm.

Set propeller\_d to the diameter of the motor (eg 63mm). Set hub\_recess to the
diameter of the extruded part of the motor, which contains the scew holes.
Finally, set screwhole\_r to the distance between the screw hole and the center
of the stator shaft.

Attach cooling fan with M3 machine screws.


Required libraries
-------------------

You need to install the following into one of
[OpenSCAD's library locations](http://en.wikibooks.org/wiki/OpenSCAD_User_Manual/Libraries#Library_Locations)

 * [MCAD (dev branch)](https://github.com/openscad/MCAD/tree/dev)
 * [scad-utils](https://github.com/openscad/scad-utils)
