---
title: "EmfRegionDataHeader Sınıfı"
type: docs
weight: 250
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | EmfRegionDataHeader sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 128-bit WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19), bu nesne bölgenin sınırlarını belirtir <br/>             |
| count_rects | int | r/w | Bu bölgede bulunan dikdörtgen sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| rgn_size | int | r/w | Dikdörtgen tamponunun bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. |
| size | int | r/w | Bu nesnenin bayt cinsinden boyutunu belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu MUTLAKA 0x00000020 olmalıdır. |
| tür | int | r/w | Bölge tipini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar. Bu <br/>            RDH_RECTANGLES (0x00000001) OLMALI. |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

EmfRegionDataHeader sınıfının yeni bir örneğini başlatır

