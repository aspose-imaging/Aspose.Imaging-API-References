---
title: "EmfPlusPath Sınıfı"
type: docs
weight: 490
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | EmfPlusPath sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | Yol noktası sayısını alır veya ayarlar <br/>
            Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini nasıl yorumlayacağını belirten 32-bit işaretsiz tam sayı |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | Yol noktalarının PathPoints alanında yol çizmek için nasıl kullanılacağını belirten bir dizi alır veya ayarlar. <br/>            Bu dizideki nesnelerin türü, PathPointFlags alanındaki R bayrağıyla belirtilir. |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Yol noktaları dizisini alır veya ayarlar<br/>            Yolu belirten PathPointCount noktasından oluşan bir dizi. Bu dizideki nesnelerin türü, PathPointFlags alanı tarafından aşağıdaki gibi belirtilir:<br/>            P bayrağı ayarlıysa, noktalar EmfPlusPointR nesneleri (bölüm 2.2.2.37) tarafından belirtilen göreli konumlardır.<br/>            P bayrağı temiz ve C bayrağı ayarlıysa, noktalar EmfPlusPoint nesneleri (bölüm 2.2.2.35) tarafından belirtilen mutlak konumlardır.<br/>            P bayrağı temiz ve C bayrağı da temizse, noktalar EmfPlusPointF nesneleri (bölüm 2.2.2.36) tarafından belirtilen mutlak konumlardır. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Sürümü alır veya ayarlar. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

EmfPlusPath sınıfının yeni bir örneğini başlatır

