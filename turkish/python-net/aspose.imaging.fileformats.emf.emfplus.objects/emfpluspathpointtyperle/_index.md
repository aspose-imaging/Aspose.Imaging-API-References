---
title: "EmfPlusPathPointTypeRle Sınıfı"
type: docs
weight: 530
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---

**Summary:** The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression.<br/>             0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>             B|1|RunCount   | PointType       |<br/>            B (1 bit): If set, the path points are on a Bezier curve.<br/>            If clear, the path points are on a graphics line.<br/>            RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field.<br/>            PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointTypeRle

**Inheritance:** EmfPlusBasePointType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle__1) | EmfPlusPathPointTypeRle sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bezier | bool | r/w | Bu [EmfPlusPathPointTypeRle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/) nesnesinin bezier olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanırsa, yol noktaları bir Bezier eğrisindedir.<br/>            Temizlenirse, yol noktaları bir grafik çizgisindedir. |
| veri | int | r/w | Veriyi alır veya ayarlar. |
| point_type | [EmfPlusPathPointType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/) | r/w | Noktanın tipini alır veya ayarlar.<br/>            PointType (1 byte): Bir EmfPlusPathPointType nesnesi<br/>            (section 2.2.2.31) yol noktalarıyla ilişkilendirilecek tipi belirten. |
| run_count | System.Byte | r/w | Run sayısını alır veya ayarlar.<br/>            RunCount (6 bit): Run sayısı, PointType alanındaki tip ile ilişkilendirilecek yol <br/>            noktalarının sayısıdır. |


### Constructor: EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle__1}


```
 EmfPlusPathPointTypeRle() 
```

EmfPlusPathPointTypeRle sınıfının yeni bir örneğini başlatır.

