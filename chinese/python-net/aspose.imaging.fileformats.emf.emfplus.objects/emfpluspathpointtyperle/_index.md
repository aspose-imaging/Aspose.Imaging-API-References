---
title: "EmfPlusPathPointTypeRle 类"
type: docs
weight: 530
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | 初始化 EmfPlusPathPointTypeRle 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bezier | bool | r/w | 获取或设置一个值，指示此 [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) 是否为贝塞尔。<br/>            如果设置，则路径点位于贝塞尔曲线上。<br/>            如果清除，则路径点位于图形直线上。 |
| 数据 | int | r/w | 获取或设置数据。 |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | 获取或设置点的类型。<br/>            PointType（1 字节）：一个 EmfPlusPathPointType 对象<br/>            （章节 2.2.2.31）指定与路径点关联的类型。 |
| run_count | System.Byte | r/w | 获取或设置运行计数。<br/>            RunCount（6 位）：运行计数，即路径点的数量，<br/>            这些点与 PointType 字段中的类型关联。 |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

初始化 EmfPlusPathPointTypeRle 类的新实例

