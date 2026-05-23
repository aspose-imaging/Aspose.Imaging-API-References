---
title: "EmfFormat Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | EmfFormat sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| off_data | int | r/w | Verinin, EMR_COMMENT_PUBLIC kaydındaki tanımlayıcı alanının <br/>            başlangıcından ofsetini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar (bölüm 2.3.3.4). <br/>            Ofset 32-bit hizalı OLMAK ZORUNDADIR. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Görüntü verisinin biçimini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. <br/>            Bu değer FormatSignature numaralandırmasında OLMAK ZORUNDADIR (bölüm 2.1.14). |
| size_data | int | r/w | Verinin bayt cinsinden boyutunu belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar |
| version | int | r/w | Biçim sürüm numarasını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. <br/>            İmza alanı kapsüllenmiş PostScript (EPS) belirtirse, <br/>            bu değer 0x00000001 OLMAK ZORUNDIR; aksi takdirde bu değer yoksayılmalıdır. |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

EmfFormat sınıfının yeni bir örneğini başlatır

