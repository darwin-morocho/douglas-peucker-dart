Polyline simplification library for dart projects like flutter.

Extracted from PHP: [AKeN / simplify-php](https://github.com/AKeN/simplify-php) (by Rotari Gheorghe)



 ## **HOW TO USE**

 ```dart
 import 'package:douglas_peucker/douglas_peucker.dart';

.
.
.


List<Point> points = List<Point>();

points.add(Point(0,-1));
points.add(Point(0,0));
points.add(Point(1,3));
points.add(Point(4,6));
points.add(Point(10,9));



 List <Point> newPolyline = DouglasPeucker.simplify(points,tolerance: 0.0004,highestQuality:false);


 ```
