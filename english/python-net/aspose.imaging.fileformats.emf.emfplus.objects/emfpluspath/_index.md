---
title: EmfPlusPath Class
type: docs
weight: 490
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | Initializes a new instance of the EmfPlusPath class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Gets or sets Path points count <br/>            A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Gets or sets an array that specifies how the points in the PathPoints field are used to draw the path. <br/>            The type of objects in this array is specified by the R flag in the PathPointFlags field |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets array of path points<br/>            An array of PathPointCount points that specify the path. The type of objects in this array are specified by the PathPointFlags field, as follows:<br/>            If the P flag is set, the points are relative locations that are specified by EmfPlusPointR objects (section 2.2.2.37).<br/>            If the P flag is clear and the C flag is set, the points are absolute locations that are specified by EmfPlusPoint objects (section 2.2.2.35).<br/>            If the P flag is clear and the C flag is clear, the points are absolute locations that are specified by EmfPlusPointF objects (section 2.2.2.36). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Gets or sets the version. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

Initializes a new instance of the EmfPlusPath class

