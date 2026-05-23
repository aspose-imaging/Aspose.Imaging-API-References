---
title: "EmfPlusPenOptionalData Sınıfı"
type: docs
weight: 560
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | EmfPlusPenOptionalData sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | İsteğe bağlı EmfPlusCompoundLineData nesnesini alır veya ayarlar (bölüm 2.2.2.9) <br/>            kalemin bileşik çizgisini tanımlayan, paralel çizgiler ve boşluklardan oluşan bir dizi kayan nokta değerini belirten. Bu alan, <br/>            PenDataCompoundLine bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır. |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | İsteğe bağlı EmfPlusCustomEndCapData nesnesini alır veya ayarlar (bölüm 2.2.2.11) <br/>            bu kalemle çizilen bir çizginin sonunda kullanılacak özel uç şekli tanımlar, <br/>            kare, daire veya elmas gibi çeşitli şekillerden biri olabilir. Bu <br/>            alan, PenDataCustomEndCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır. |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | İsteğe bağlı EmfPlusCustomStartCapData nesnesini alır veya ayarlar (bölüm 2.2.2.15) <br/>            bu kalemle çizilen bir çizginin başlangıcında kullanılacak özel başlangıç uç şekli tanımlar, <br/>            kare, daire veya elmas gibi çeşitli şekillerden biri olabilir. <br/>            Bu alan, PenDataCustomStartCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır. |
| dash_offset | float | r/w | İsteğe bağlı 32 bit kayan nokta değerini alır veya ayarlar, bu değer <br/>            kesikli bir çizgi deseninde bir çizginin başlangıcından ilk boşluğun başlangıcına olan mesafeyi belirler. Bu alan, <br/>            PenDataDashedLineOffset bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | İsteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar, bu sayı kesikli bir çizgideki her bir tire'nin her iki ucunun şeklini belirler. Bu alan, <br/>            PenDataDashedLineCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır ve değer DashedLineCapType enumarasyonunda (bölüm 2.1.1.10) tanımlanmalıdır. |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | İsteğe bağlı EmfPlusDashedLineData nesnesini alır veya ayarlar (bölüm 2.2.2.16) <br/>            özel bir kesikli çizgideki tire ve boşluk uzunluklarını belirten. Bu alan, PenDataDashedLine bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır. |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | İsteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar, bu sayı CustomEndCapData alanındaki bir çizginin ucunun şeklini belirler. Bu alan, PenDataEndCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır ve değer LineCapType enumarasyonunda tanımlanmalıdır. |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | İsteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar, bu sayı aynı kalemle çizilen ve uçları birleşen iki çizginin nasıl birleştirileceğini belirler. Bu alan, PenDataJoin bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır ve değer LineJoinType enumarasyonunda (bölüm 2.1.1.19) tanımlanmalıdır. |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | İsteğe bağlı 32 bit işaretli tam sayıyı alır veya ayarlar, bu sayı bu kalem nesnesiyle çizilen çizgilerin stilini belirler. Bu alan, PenDataLineStyle bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlıysa <br/>            bulunmalıdır ve değer LineStyle enumarasyonunda (bölüm 2.1.1.20) tanımlanmalıdır. |
| miter_limit | float | r/w | İsteğe bağlı 32-bit kayan nokta değerini alır veya ayarlar, bu değer miter <br/>            limitini belirtir, bu da miter uzunluğunun çizgi genişliğine olan maksimum izin verilen oranıdır. Miter uzunluğu, <br/>            birleşimin iç tarafındaki çizgi duvarlarının kesişiminden <br/>            birleşimin dış tarafındaki çizgi duvarlarının kesişimine olan mesafedir. <br/>            İki çizgi arasındaki açı küçük olduğunda miter uzunluğu büyük olabilir. Bu alan, <br/>            PenDataMiterLimit bayrağı PenDataFlags alanında <br/>            EmfPlusPenData nesnesinde ayarlanmışsa VAR OLMALIDIR. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | İsteğe bağlı 32-bit işaretli tam sayı alır veya ayarlar, bu sayı <br/>            kalem genişliğinin çizilen çizginin koordinatlarına göre dağılımını belirtir. Bu alan <br/>            VAR OLMALIDIR eğer PenDataNonCenter bayrağı PenDataFlags alanında <br/>            EmfPlusPenData nesnesinde ayarlanmışsa, ve <br/>            değer PenAlignment <br/>            enumarasyonunda (bölüm 2.1.1.24) tanımlanmış olmalıdır. |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | İsteğe bağlı 32-bit işaretli tam sayı alır veya ayarlar, şekli belirler<br/>             bir çizginin başlangıcını CustomStartCapData alanında. <br/>            Bu alan VAR OLMALIDIR eğer PenDataStartCap bayrağı PenDataFlags alanında <br/>            EmfPlusPenData nesnesinde ayarlanmışsa, ve değer <br/>            LineCapType enumarasyonunda (bölüm 2.1.1.18) tanımlanmış olmalıdır. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | İsteğe bağlı bir EmfPlusTransformMatrix nesnesi alır veya ayarlar (bölüm 2.2.2.47) <br/>            dünya uzayından aygıt uzayına dönüşümü belirler <br/>            kalem için. Bu alan VAR OLMALIDIR eğer PenDataTransform <br/>            bayrağı PenDataFlags alanında EmfPlusPenData <br/>            nesnesinde ayarlanmışsa. |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

EmfPlusPenOptionalData sınıfının yeni bir örneğini başlatır

