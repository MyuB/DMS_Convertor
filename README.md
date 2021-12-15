# DMS_Convertor

INHA System Programming worked as Ubuntu

1. gis.h

This header file contains two basic standard libraries used in C.
Two Structs are used to contain the information.
'gisinfo' struct has general information on GIS (degree, minute, seconds, totalSeconds, DMS, direction)
'coordinate' struct is distinguished by latitude and longitude.

1. getGIS.c

This C file contains the codes that read input.txt
This function read input.txt and save those Infos to every two structs.
Finally returns how many lines there are.

1. convert.c

This C file separated DMS to a degree, minute, second each.
Also, this calculates totalSecond of each DMS.

1. printDistance.c

This API prints information as expected into better visualization.
Sorting them into exact scale, it visually looks better.
There is a simple calculation on distanceSecond.
This distanceSecond is calculated in the method of 'Taxi-Cab Geometry' which is just adding the difference between x, y points.

Done.
