# Draw_diff

It is a kind-of top view (Single Line Diagram) of Road per km-wise. So all the features of road within that particular km like divider width, road width, road-side objects, etc are included in the image. This was created for SLD requirement at our company.

Current Features we have incorporated:
1. Divider position and its width
2. Road position and its width
3. Road-side position and its width
4. Road side objects and relative position
5. Milestone Labels on Road
6. Position of Bridges, Culvert, service road
7. Other fixed indicators
8. Type of soil and chainages

All these things are represented using symbols wherever possible and simple lines.

We have used python library matplotlib to draw everything. There are separte functions which are called when a particular section of road is created. 
