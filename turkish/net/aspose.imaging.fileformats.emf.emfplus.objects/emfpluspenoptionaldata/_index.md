---
title: EmfPlusPenOptionalData
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusPenOptionalData nesnesi bir grafik için isteğe bağlı verileri belirtir pen
type: docs
weight: 5680
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

EmfPlusPenOptionalData nesnesi, bir grafik için isteğe bağlı verileri belirtir pen

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | İsteğe bağlı EmfPlusCompoundLineData nesnesini (bölüm 2.2.2.9) alır veya ayarlar , paralel çizgiler ve boşluklardan oluşan bir kalemin bileşik çizgisini tanımlayan kayan nokta değerleri dizisini belirtir. Bu alan, PenDataCompoundLine bayrağı, EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa MUTLAKA VARDIR |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | İsteğe bağlı EmfPlusCustomEndCapData nesnesini alır veya ayarlar (bölüm 2.2.2.11) bu, bu kalemle çizilen bir çizginin sonunda kullanılacak şekil olan özel uç başlığı şeklini tanımlar. Kare, daire veya elmas gibi çeşitli şekillerden herhangi biri olabilir. PenDataCustomEndCap bayrağı, EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa, bu alanı MUTLAKA OLMALIDIR |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | Bu kalemle çizilen bir çizginin başlangıcında kullanılacak şekil olan özel başlangıç başlığı şeklini tanımlayan isteğe bağlı EmfPlusCustomStartCapData nesnesini (bölüm 2.2.2.15) alır veya ayarlar. Kare, daire veya elmas gibi çeşitli şekillerde herhangi bir olabilir. PenDataCustomStartCap bayrağı , EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa, bu alan MUTLAKA mevcut olmalıdır. |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | Kesikli bir çizgide her çizginin her iki ucunun şeklini belirten isteğe bağlı 32 bitlik işaretli tamsayıyı alır veya ayarlar. PenDataDashedLineCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan OLMALIDIR ve değeri DashedLineCapType numaralandırma (bölüm 2.1.1.10) içinde tanımlanmalıdır ZORUNLU. |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | Özel bir kesikli çizgide tire ve boşluk uzunluklarını belirten isteğe bağlı EmfPlusDashedLineData nesnesi (bölüm 2.2.2.16) alır veya ayarlar. EmfPlusPenData nesnesinin PenDataFlags alanında PenDataDashedLine bayrağı ayarlanmışsa bu alan MUTLAKA VARDIR. |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | Bir çizginin başlangıcından ilk boşluğunun başlangıcına kadar olan mesafesini kesikli çizgi deseninde belirten isteğe bağlı 32 bit kayan nokta değerini alır veya ayarlar. PenDataDashedLineOffset bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa, bu alan OLMALIDIR. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | CustomEndCapData alanında bir satırın sonu için shape belirten isteğe bağlı 32 bit işaretli tamsayıyı alır veya ayarlar. PenDataEndCap bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alanı MUTLU OLMALIDIR ve değeri LineCapType numaralandırmasında tanımlanmalıdır ZORUNLU. |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | Aynı kalem tarafından çizilen ve uçları buluşan iki çizginin nasıl birleştirileceğini belirten isteğe bağlı bir 32 bit işaretli tamsayı alır veya ayarlar. PenDataJoin bayrağı, EmfPlusPenData nesnesinin PenDataFlags alanında içinde ayarlanmışsa ve değeri LineJoinType numaralandırmasında (bölüm 2.1.1.19) tanımlıysa ZORUNLUDUR. |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | Bu kalem nesnesiyle çizilen çizgiler için kullanılan stilini belirten isteğe bağlı 32 bit işaretli tamsayıyı alır veya ayarlar. PenDataLineStyle bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan OLMALIDIR ve değeri LineStyle numaralandırmasında tanımlanmalıdır (bölüm 2.1.1.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | Gönye uzunluğunun çizgi genişliğine izin verilen maksimum oranı olan gönye sınırını belirten isteğe bağlı 32 bit kayan nokta değerini alır veya ayarlar. Gönye uzunluğu, birleştirmenin içindeki çizgi duvarlarının kesişiminden, birleştirmenin dışındaki çizgi duvarlarının kesişme noktasına olan mesafedir. İki çizgisi arasındaki açı küçük olduğunda gönye uzunluğu büyük olabilir. EmfPlusPenData nesnesinin PenDataFlags alanında PenDataMiterLimit bayrağı ayarlanmışsa bu alan MUTLAKA VARDIR. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | Kalem genişliğinin çizilen çizginin koordinatlarına göre dağılımını belirten isteğe bağlı 32 bit işaretli tamsayıyı alır veya ayarlar. PenDataNonCenter bayrağı EmfPlusPenData nesnesinin PenDataFlags alanında ayarlanmışsa bu alan OLMALIDIR ve değer PenAlignment numaralandırmasında tanımlanmalıdır (bölüm 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | CustomStartCapData alanında bir satırın başlangıcı için şeklini belirten isteğe bağlı bir 32 bit işaretli tamsayı alır veya ayarlar. PenDataStartCap bayrağı, EmfPlusPenData nesnesinin PenDataFlags alanında olarak ayarlanmışsa ve değeri LineCapType numaralandırması 'de (bölüm 2.1.1.18) tanımlıysa bu alan MUTLAKA VAR OLMALIDIR. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | Kalem için bir dünya alanından aygıt alanına dönüşüm belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar. EmfPlusPenData nesnesinin PenDataFlags alanında PenDataTransform bayrağı ayarlanmışsa bu alan MUTLAKA VARDIR. |

### Ayrıca bakınız

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
