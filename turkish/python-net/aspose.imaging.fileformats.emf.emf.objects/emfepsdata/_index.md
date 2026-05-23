---
title: "EmfEpsData Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | EmfEpsData sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Alır veya ayarlar üç Point28_4 nesnesinden oluşan bir dizi (bölüm 2.2.23) <br/>            28.4 bit FIX gösterimi kullanarak çıktı paralelogramının koordinatlarını tanımlayan. |
| post_script_data | System.Byte | r/w | PostScript verisinin bayt dizisini alır veya ayarlar. Bu dizinin uzunluğu <br/>            SizeData alanından hesaplanabilir. Bu veri GÖRÜNTÜ oluşturmak için kullanılabilir. |
| size_data | int | r/w | Bu nesnenin toplam boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar |
| version | int | r/w | PostScript dil seviyesini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu <br/>            değer 0x00000001 OLMALIDIR |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

EmfEpsData sınıfının yeni bir örneğini başlatır

