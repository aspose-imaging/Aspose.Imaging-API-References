---
title: "EmfPlusPenData Sınıfı"
type: docs
weight: 550
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | EmfPlusPenData sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | İsteğe bağlı EmfPlusPenOptionalData nesnesini alır veya ayarlar (bölüm 2.2.2.34) <br/>
            bu nesne kalem nesnesi için ek verileri belirtir. Bu alanın belirli <br/>
            içeriği PenDataFlags alanının değerine göre belirlenir. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | OptionalData alanındaki veriyi belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar <br/>
            Bu değer MUTLAKA PenData bayraklarından (bölüm 2.1.2.7) oluşmalıdır. |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Kalem için ölçüm birimlerini belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar <br/>
            Değer MUTLAKA UnitType enumarasyonundan (bölüm 2.1.1.33) gelmelidir. |
| pen_width | float | r/w | Kalem birimi (PenUnit alanı) tarafından belirtilen birimlerde kalemin çizdiği çizginin genişliğini belirten 32-bit kayan nokta değerini alır veya ayarlar <br/>
            Sıfır genişlik belirtilirse, birimlere göre belirlenen minimum bir değer kullanılır. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

EmfPlusPenData sınıfının yeni bir örneğini başlatır

