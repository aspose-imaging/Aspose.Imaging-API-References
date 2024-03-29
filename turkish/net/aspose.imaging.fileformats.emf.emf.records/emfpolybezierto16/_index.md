---
title: EmfPolyBezierTo16
second_title: Aspose.Imaging for .NET API Referansı
description: EMR_POLYBEZIERTO16 kaydı geçerli konuma dayalı olarak bir veya daha fazla Bezier eğrisi belirtir.
type: docs
weight: 3990
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
## EmfPolyBezierTo16 class

EMR_POLYBEZIERTO16 kaydı, geçerli konuma dayalı olarak bir veya daha fazla Bezier eğrisi belirtir.

```csharp
public sealed class EmfPolyBezierTo16 : EmfRecord
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPolyBezierTo16](emfpolybezierto16#constructor)() | Yeni bir örneğini başlatır[`EmfPolyBezierTo16`](../emfpolybezierto16) sınıf. |
| [EmfPolyBezierTo16](emfpolybezierto16#constructor_1)(EmfRecord) | Yeni bir örneğini başlatır[`EmfPolyBezierTo16`](../emfpolybezierto16) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/apoints) { get; set; } | Points dizisini belirten [MS-WMF] bölüm 2.2.2.16'da belirtilen WMF PointS nesnelerinin Count uzunluk dizisini alır veya ayarlar |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/bounds) { get; set; } | Aygıt birimlerinde sınırlayıcı dikdörtgeni belirten [MS-WMF] bölüm 2.2.2.19, 'de belirtilen 128 bit WMF RectL nesnesini alır veya ayarlar. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Rekorun boyutunu alır veya ayarlar |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Türü alır veya ayarlar. |

### Notlar

Kübik Bezier eğrileri, aPoints alanı tarafından belirtilen uç noktalar ve kontrol noktaları kullanılarak tanımlanır. Birinci eğri, ikinci ve üçüncü noktaları kontrol noktaları olarak kullanılarak birinci noktadan dördüncü noktaya çizilir. Sıradaki her bir sonraki eğri tam olarak üç noktaya daha ihtiyaç duyar: önceki eğrinin bitiş noktası başlangıç noktası olarak kullanılır, dizisindeki sonraki iki nokta kontrol noktalarıdır ve üçüncüsü bitiş noktasıdır. Kübik Bezier eğrileri, mevcut pen kullanılarak çizilmelidir.

### Ayrıca bakınız

* class [EmfRecord](../emfrecord)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
