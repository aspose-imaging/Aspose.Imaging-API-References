---
title: "EmfPlusPath 类"
type: docs
weight: 490
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | 初始化 EmfPlusPath 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | 获取或设置路径点计数 <br/>            一个 32 位无符号整数，指定如何解释此对象定义的点及其关联的点类型。 |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | 获取或设置一个数组，用于指定 PathPoints 字段中的点如何用于绘制路径。 <br/>            该数组中对象的类型由 PathPointFlags 字段中的 R 标志指定 |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置路径点数组<br/>            一个由 PathPointCount 个点组成的数组，用于指定路径。该数组中对象的类型由 PathPointFlags 字段指定，如下：<br/>            如果设置了 P 标志，则这些点是由 EmfPlusPointR 对象（第 2.2.2.37 节）指定的相对位置。<br/>            如果未设置 P 标志且设置了 C 标志，则这些点是由 EmfPlusPoint 对象（第 2.2.2.35 节）指定的绝对位置。<br/>            如果 P 标志和 C 标志均未设置，则这些点是由 EmfPlusPointF 对象（第 2.2.2.36 节）指定的绝对位置。 |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | 获取或设置版本。 |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

初始化 EmfPlusPath 类的新实例

