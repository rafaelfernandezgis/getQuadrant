# getQuadrant

Geometrically, this straightforward function tells us what quadrant the vector is found.
- The function is written in JavaScript.
- It works fine using cartesian coordinates. I tried it in EPSG: 3857 too. It works fine in local distances . For any other projected systems it worked fine as well.

All what you need is to pass these arguments: xEnd, yEnd, xOri, yOri
- xEnd: _second point which defines the line. Coordinate X_
- yEnd: _second point which defines the line. Coordinate Y_
- xOri: _first point which defines the line. Coordinate X_
- yOri: _first point which defines the line. Coordinate Y_

you'll get an **number** for the quadrant.

- 1 for the first quadrant
- 2 second quadrant
- 3 third quadrant
- 4 fourth quadrant
- 5 Over the positive axis abscissa
- 6 Over the negative axis abscissa
- 7 Over the positive axis ordinate
- 8 Over the negative axis ordinate
- 9 on the origin

![Alt text](https://cloud.githubusercontent.com/assets/6051197/11338711/46075884-91d0-11e5-9987-dba25d8ce504.PNG)

See an example in [fiddle](http://jsfiddle.net/rafaelfernandezgis/d81cccde/)
