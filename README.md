flot-pie-3d
===========

Proof of concept for a 3d pie.

My boss really liked the 3d on a pie, so I hack the pie plugin from flot to create the 3d effect.

Right now is made by creating multiple passes of the original pie from bottom to top, so that will create the effect.

Consider this a pre-beta-alpha that don't do a lot of error checking

this are the options:

series: {
  pie: {
   show: true ,
      tilt: 0.9,
      radius: 0.90,
      depth: 20,
      stroke: {
        width: 0
      }
  }
}

will commit an fix as my time permits feel free to fork it, I've release it under the MIT license
