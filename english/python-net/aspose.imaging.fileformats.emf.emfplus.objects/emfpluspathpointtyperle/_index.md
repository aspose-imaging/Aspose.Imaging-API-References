---
title: EmfPlusPathPointTypeRle Class
type: docs
weight: 530
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusPathPointTypeRle type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusPathPointTypeRle()|Initializes a new instance of the EmfPlusPathPointTypeRle class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|data|Gets or sets the data.|
|bezier|Gets or sets a value indicating whether this [EmfPlusPathPointTypeRle](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) is bezier.<br/>            If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.|
|run_count|Gets or sets the run count.<br/>            RunCount (6 bits): The run count, which is the number of path <br/>            points to be associated with the type in the PointType field|
|point_type|Gets or sets the type of the point.<br/>            PointType (1 byte): An EmfPlusPathPointType object<br/>            (section 2.2.2.31) that specifies the type to associate with the path points.|
