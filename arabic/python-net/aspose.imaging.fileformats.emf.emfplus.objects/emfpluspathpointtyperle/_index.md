---
title: "فئة EmfPlusPathPointTypeRle"
type: docs
weight: 530
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | ينشئ مثالا جديدا من فئة EmfPlusPathPointTypeRle |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bezier | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) بيزيير.<br/>            إذا تم الضبط، تكون نقاط المسار على منحنى بيزيير.<br/>            إذا تم الإلغاء، تكون نقاط المسار على خط رسومي. |
| البيانات | int | r/w | يحصل أو يعيّن البيانات. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | يحصل أو يضبط نوع النقطة.<br/>            PointType (1 بايت): كائن EmfPlusPathPointType<br/>            (القسم 2.2.2.31) الذي يحدد النوع لربطه بنقاط المسار. |
| run_count | System.Byte | r/w | يحصل أو يضبط عدد التشغيل.<br/>            RunCount (6 بت): عدد التشغيل، وهو عدد نقاط المسار <br/>            التي سيتم ربطها بالنوع في حقل PointType. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

ينشئ مثالا جديدا من فئة EmfPlusPathPointTypeRle

