---
title: "EmfGradientRectangle 类"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---

**Summary:** The GradientRectangle object defines a rectangle using TriVertex objects (section 2.2.26) in an <br/>            EMR_GRADIENTFILL record (section 2.3.5.12).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfGradientRectangle()](#EmfGradientRectangle__1) | 初始化 EmfGradientRectangle 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| lower_right | int | r/w | 获取或设置指向 TriVertex 对象数组的索引，该索引指定矩形的右下角顶点。<br/>            该索引必须小于数组的大小，大小由 EMR_GRADIENTFILL 记录的 nVer 字段定义。 |
| upper_left | int | r/w | 获取或设置指向 TriVertex 对象数组的索引，该索引指定矩形的左上角顶点。<br/>            该索引必须小于数组的大小，大小由 EMR_GRADIENTFILL 记录的 nVer 字段定义。 |


### Constructor: EmfGradientRectangle() {#EmfGradientRectangle__1}


```
 EmfGradientRectangle() 
```

初始化 EmfGradientRectangle 类的新实例

