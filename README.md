# DMS_Convertor
INHA System Programming worked as Ubuntu

1. gis.h

This header file contains two basic standard libraries using in C.
Two Structs are used for contain the information.
'gisinfo' struct has general information on GIS (degree, minute, seconds, totalSeconds, dms, direction)
'coordinate' struct is distinguised by latitude and longitude.

2. getGIS.c

This C file contains the codes that read input.txt
This function basically read input.txt and save those info to each two struct.
Finally returns how many lines there are.

3. convert.c

This C file basically separated dms to degree, minute, second each.
Also, this calcuates totalSecond of each dms.

4. printDistance.c

This API basically prints information as expected into better visualization.
Sorting them into exact scale, it visually looks better.
There is simple calculation on distanceSecond.
This distanceSecond is calculated in method of 'Taxi-Cab Geometry' which is just adding difference between x, y points.

Done.
