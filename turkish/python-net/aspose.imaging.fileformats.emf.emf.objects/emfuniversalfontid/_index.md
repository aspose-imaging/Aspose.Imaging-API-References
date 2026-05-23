---
title: "EmfUniversalFontId Sınıfı"
type: docs
weight: 280
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | EmfUniversalFontId sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| checksum | int | r/w | Yazı tipinin sağlama toplamı olan 32 bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Sağlama toplamı değeri aşağıdaki anlamlara sahiptir.<br/>            0x00000000  Nesne bir cihaz yazı tipidir. <br/>            0x00000001  Nesne, istemci makinesine kurulmuş bir Type 1 yazı tipidir ve <br/>            PostScript yazıcı sürücüsü tarafından cihaz yazı tipi olarak numaralandırılır. <br/>            0x00000002  Nesne bir yazı tipi değildir, ancak bir Type 1 rasterleştiricisidir. <br/>            3 ≤ değer   Nesne bir bitmap, vektör veya TrueType yazı tipidir, ya da bir Type 1 rasterleştirici tarafından oluşturulmuş bir Type 1 rasterleştirilmiş yazı tipidir. |
| index | int | r/w | Yazı tipi nesnesiyle ilişkili bir dizin olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. <br/>            Bu alanın anlamı yazı tipi türüne göre belirlenir. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

EmfUniversalFontId sınıfının yeni bir örneğini başlatır

