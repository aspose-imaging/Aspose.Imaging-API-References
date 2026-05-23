---
title: "EmfVertexData Sınıfı"
type: docs
weight: 1460
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | EmfVertexData sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | ulMode alanının değerine bağlı olarak nTri GradientRectangle nesneleri (bölüm 2.2.7) veya <br/>            GradientTriangle nesneleri (bölüm 2.2.8) içeren bir dizi alır veya ayarlar. <br/>            Her nesne, VertexObjects alanındaki TriVertex nesneleri dizisine indeksleri belirtir. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | nVer TriVertex nesneleri (bölüm 2.2.26) içeren bir dizi alır veya ayarlar. Her <br/>            nesne, ulMode alanının değerine bağlı olarak bir dikdörtgen ya da üçgenin bir köşesinin konumunu ve rengini belirtir. |
| vertex_padding | System.Byte | r/w | ulMode alanının değeri GradientRectangle <br/>            nesnelerini (bölüm 2.2.7) gösteriyorsa, nTri kez dört bayt uzunluğunda isteğe bağlı değişken uzunlukta bir dizi alır veya ayarlar. ulMode alanının değeri GradientTriangle <br/>            nesnelerini (bölüm 2.2.8) gösteriyorsa, VertexPadding bulunmaz. Bu alan YOK SAYILMALIDIR. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

EmfVertexData sınıfının yeni bir örneğini başlatır

