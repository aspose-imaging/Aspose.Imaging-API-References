---
title: EmfPlusRecordType
second_title: Aspose.Imaging for .NET API Referansı
description: RecordType numaralandırması EMF meta dosyalarında kullanılan kayıt türlerini tanımlar.
type: docs
weight: 5030
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

RecordType numaralandırması, EMF+ meta dosyalarında kullanılan kayıt türlerini tanımlar.

```csharp
public enum EmfPlusRecordType : short
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| EmfPlusHeader | `16385` | Bu kayıt, meta dosyasındaki EMF+ verilerinin başlangıcını belirtir. EMF kaydından sonraki ilk EMF kaydına YERLEŞTİRİLMELİDİR.[`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) kayıt ([MS-EMF] bölüm 2.3.4.2 kaydı). |
| EmfPlusEndOfFile | `16386` | Bu kayıt, meta dosyasındaki EMF+ verilerinin sonunu belirtir. |
| EmfPlusComment | `16387` | Bu kayıt, isteğe bağlı özel verileri belirtir. |
| EmfPlusGetDC | `16388` | Bu kayıt, meta dosyasında karşılaşılan sonraki EMF kayıtlarının İŞLENMESİ GEREKTİĞİNİ belirtir. Bir sonraki EMF+ kaydıyla karşılaşıldığında EMF kayıtları işlenmeyi durdurur. |
| EmfPlusMultiFormatStart | `16389` | Bu kayıt saklıdır ve KULLANILMAMALIDIR. |
| EmfPlusMultiFormatSection | `16390` | Bu kayıt saklıdır ve KULLANILMAMALIDIR. |
| EmfPlusMultiFormatEnd | `16391` | Bu kayıt saklıdır ve KULLANILMAMALIDIR. |
| EmfPlusObject | `16392` | Bu kayıt, grafik işlemlerinde kullanılacak bir nesneyi belirtir. |
| EmfPlusClear | `16393` | Bu kayıt çıktıyı temizler`koordinat uzayı` ve belirli bir arka plan rengi ve şeffaflıkla başlatır. |
| EmfPlusFillRects | `16394` | Bu kayıt, belirtilen bir fırça kullanılarak bir dizi dikdörtgenin içinin nasıl doldurulacağını tanımlar. |
| EmfPlusDrawRects | `16395` | Bu kayıt, bir dizi dikdörtgen çizmek için kalem vuruşlarını tanımlar. |
| EmfPlusFillPolygon | `16396` | Bu kayıt, belirtilen bir fırça kullanarak bir çokgenin içini dolduracak verileri tanımlar. |
| EmfPlusDrawLines | `16397` | Bu kayıt, bir dizi bağlantılı çizgi çizmek için kalem vuruşlarını tanımlar. |
| EmfPlusFillEllipse | `16398` | Bu kayıt, belirtilen bir fırça kullanılarak bir elipsin içinin nasıl doldurulacağını tanımlar. |
| EmfPlusDrawEllipse | `16399` | Bu kayıt, bir elips çizmek için kalem vuruşlarını tanımlar. |
| EmfPlusFillPie | `16400` | Bu kayıt, belirli bir fırça kullanılarak bir elipsin iç bölümünün bir bölümünün nasıl doldurulacağını tanımlar. |
| EmfPlusDrawPie | `16401` | Bu kayıt, bir elipsin bir bölümünü çizmek için kalem vuruşlarını tanımlar. |
| EmfPlusDrawArc | `16402` | Kayıt, bir elips yayı çizmek için kalem vuruşlarını tanımlar. |
| EmfPlusFillRegion | `16403` | Bu kayıt, belirli bir fırça kullanılarak bir bölgenin içinin nasıl doldurulacağını tanımlar. |
| EmfPlusFillPath | `16404` | Kayıt, bir grafik yolunda tanımlanan şekillerin iç kısımlarının belirtilen bir fırça ile nasıl doldurulacağını tanımlar. Yol, rastgele bir çizgi, eğri ve şekil dizisini tanımlayan bir nesnedir. |
| EmfPlusDrawPath | `16405` | Kayıt, şekilleri bir grafik yolunda çizmek için kalem vuruşlarını tanımlar. Yol, rastgele bir çizgi, eğri ve şekil dizisini tanımlayan bir nesnedir. |
| EmfPlusFillClosedCurve | `16406` | Bu kayıt, belirtilen bir fırça kullanılarak kapalı bir kardinal spline'ın içinin nasıl doldurulacağını tanımlar. |
| EmfPlusDrawClosedCurve | `16407` | Bu kayıt, kapalı bir ana eğri çizgisi çizmek için kalemi ve vuruşları tanımlar. |
| EmfPlusDrawCurve | `16408` | Bu kayıt, bir ana eğri çizmek için kalem vuruşlarını tanımlar. |
| EmfPlusDrawBeziers | `16409` | Bu kayıt, bir Bezier spline çizmek için kalem vuruşlarını tanımlar. |
| EmfPlusDrawImage | `16410` | Bu kayıt, ölçeklenmiş bir[`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)nesne (bölüm 2.2.1.4). Bir görüntü, bit eşlem veya meta dosya verilerinden oluşabilir. |
| EmfPlusDrawImagePoints | `16411` | Bu kayıt, bir paralelkenar içinde ölçeklenmiş bir EmfPlusImage nesnesini tanımlar. Bir görüntü, bit eşlem veya meta dosya verilerinden oluşabilir. |
| EmfPlusDrawString | `16412` | Bu kayıt, bir yazı tipine, bir yerleşim dikdörtgenine ve bir biçime dayalı bir metin dizesi tanımlar. |
| EmfPlusSetRenderingOrigin | `16413` | Bu kayıt, belirtilen yatay ve dikey koordinatlarda işlemenin kökenini tanımlar. Bu, tarama fırçaları ve piksel taklidi desenleri başına 8 ve 16 bit için geçerlidir. |
| EmfPlusSetAntiAliasMode | `16414` | Bu kayıt, metin kenar yumuşatmanın etkinleştirilip etkinleştirilmeyeceğini tanımlar. Metin kenar yumuşatma, çıktı yüzeyine çizildiğinde karakter gliflerinin çizgilerinin ve kenarlarının daha düzgün görünmesini sağlayan bir yöntemdir. |
| EmfPlusSetTextRenderingHint | `16415` | Bu kayıt, metin oluşturmak için kullanılan süreci tanımlar. |
| EmfPlusSetTextContrast | `16416` | Bu kayıt, belirtilen metin gama değerine göre metin kontrastını ayarlar. |
| EmfPlusSetInterpolationMode | `16417` | Bu kayıt, belirtilen görüntü filtreleme türüne göre bir nesnenin enterpolasyon modunu tanımlar. Enterpolasyon modu, ölçeklemenin (uzatma ve küçültme) nasıl gerçekleştirildiğini etkiler. |
| EmfPlusSetPixelOffsetMode | `16418` | Bu kayıt, belirtilen piksel merkezleme değerine göre piksel ofset modunu tanımlar. |
| EmfPlusSetCompositingMode | `16419` | Bu kayıt, birleştirme modunu, kaynak renklerin arka plan renkleriyle nasıl birleştirildiğini belirten alfa karıştırma durumuna göre tanımlar. |
| EmfPlusSetCompositingQuality | `16420` | Bu kayıt, birden çok nesneden bileşik görüntüler oluşturmak için istenen kalite düzeyini tanımlayan birleştirme kalitesini tanımlar. |
| EmfPlusSave | `16421` | Bu kayıt, belirtilen bir dizin tarafından tanımlanan grafik durumunu, kaydedilmiş grafik durumları yığınına kaydeder. Her yığın dizini, belirli bir kaydedilmiş durumla ilişkilendirilir ve dizin, bir[`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) durumu geri yüklemek için kaydedin (bölüm 2.3.7.4). |
| EmfPlusRestore | `16422` | Bu kayıt, kaydedilmiş grafik durumları yığınından belirtilen bir dizin tarafından tanımlanan grafik durumunu geri yükler. Her yığın dizini, belirli bir kaydedilmiş durumla ilişkilendirilir ve dizin, bir[`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave) durumu kaydetmek için kaydedin (bölüm 2.3.7.5). |
| EmfPlusBeginContainer | `16423` | Bu kayıt, yeni bir grafik durum kapsayıcısını açar ve bunun için bir dönüşüm belirtir. Grafik kapsayıcıları, grafik durumunun öğelerini korumak için kullanılır. |
| EmfPlusBeginContainerNoParams | `16424` | Bu kayıt, yeni bir grafik durumu kapsayıcısını açar. |
| EmfPlusEndContainer | `16425` | Bu kayıt, daha önce bir kapsayıcı işlemi başlatma tarafından açılmış bir grafik durumu kapsayıcısını kapatır. |
| EmfPlusSetWorldTransform | `16426` | Bu kayıt, oynatma cihazı_bağlamındaki geçerli dünya uzay dönüşümünü, belirtilen bir dönüşüm matrisine göre tanımlar. |
| EmfPlusResetWorldTransform | `16427` | Bu kayıt, mevcut dünya uzay dönüşümünü tanımlama matrisine sıfırlar. |
| EmfPlusMultiplyWorldTransform | `16428` | Bu kayıt, geçerli dünya alanını belirtilen bir dönüştürme matrisi ile çarpar. |
| EmfPlusTranslateWorldTransform | `16429` | Bu kayıt, belirtilen yatay ve dikey mesafelerle geçerli dünya alanına bir çeviri dönüşümü uygular. |
| EmfPlusScaleWorldTransform | `16430` | Bu kayıt, belirtilen yatay ve dikey ölçek faktörleriyle geçerli dünya alanına bir ölçeklendirme dönüşümü uygular. |
| EmfPlusRotateWorldTransform | `16431` | Bu kayıt, geçerli dünya alanını belirli bir açıyla döndürür. |
| EmfPlusSetPageTransform | `16432` | Bu kayıt, mevcut dünya uzay dönüşümü için ekstra ölçeklendirme faktörlerini belirtir. |
| EmfPlusResetClip | `16433` | Bu kayıt, dünya alanı için geçerli kırpma bölgesini sonsuza sıfırlar. |
| EmfPlusSetClipRect | `16434` | Bu kayıt, geçerli kırpma bölgesini bir dikdörtgenle birleştirir. |
| EmfPlusSetClipPath | `16435` | Bu kayıt, geçerli kırpma bölgesini bir grafik yolu ile birleştirir. |
| EmfPlusSetClipRegion | `16436` | Bu kayıt, geçerli kırpma bölgesini başka bir grafik bölgesiyle birleştirir. |
| EmfPlusOffsetClip | `16437` | Bu kayıt, dünya uzayının geçerli kırpma bölgesinde bir çeviri dönüşümü uygular. |
| EmfPlusDrawDriverString | `16438` | Bu kayıt, karakter konumlarıyla metin çıktısını belirtir. |
| EmfPlusStrokeFillPath | `16439` | Bu kayıt, yoldaki tüm açık şekilleri kapatır, geçerli kalemi kullanarak yolun ana hatlarını çizer ve geçerli fırçayı kullanarak içini doldurur. |
| EmfPlusSerializableObject | `16440` | Bu kayıt, bir veri arabelleğine serileştirilmiş bir görüntü efektleri parametre bloğunu tanımlar. |
| EmfPlusSetTSGraphics | `16441` | Bu kayıt, bir terminal sunucusu için bir grafik aygıtı bağlamının durumunu belirtir. |
| EmfPlusSetTSClip | `16442` | Bu kayıt, bir terminal sunucusu için grafik aygıtı bağlamındaki kırpma alanlarını belirtir. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
