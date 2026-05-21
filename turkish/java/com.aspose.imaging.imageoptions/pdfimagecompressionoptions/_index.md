---
title: "PdfImageCompressionOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Pdf görüntü sıkıştırma seçenekleri"
type: docs
weight: 35
url: /tr/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Pdf görüntü sıkıştırma seçenekleri
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Auto](#Auto) | Her görüntü için en uygun sıkıştırmayı otomatik olarak seçer. |
| [None](#None) | Ham görüntü baytlarını kaydeder ve bu da daha büyük pdf dosya boyutlarına yol açar. |
| [Rle](#Rle) | Run Length sıkıştırması. |
| [Flate](#Flate) | Flate sıkıştırması. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | Tahminci seçimi, süreci hızlandırmak için PNG Paeth tahmincisi ile sınırlıdır. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | Tahminci seçimi daha karmaşıktır ve daha küçük görüntü boyutları sağlamalıdır, ancak daha fazla zaman alır. |
| [Jpeg](#Jpeg) | Jpeg sıkıştırması. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Şeffaflığı desteklemez. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Şeffaflığı desteklemez. |
### Auto {#Auto}
```
public static final int Auto
```


Her görüntü için en uygun sıkıştırmayı otomatik olarak seçer.

### None {#None}
```
public static final int None
```


Ham görüntü baytlarını kaydeder ve bu da daha büyük pdf dosya boyutlarına yol açar.

### Rle {#Rle}
```
public static final int Rle
```


Run Length sıkıştırması.

### Flate {#Flate}
```
public static final int Flate
```


Flate sıkıştırması.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


Tahminci seçimi, süreci hızlandırmak için PNG Paeth tahmincisi ile sınırlıdır. Pratikte şaşırtıcı derecede iyi performans gösterir. [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor) öğesinden daha iyidir.

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


Tahminci seçimi daha karmaşıktır ve daha küçük görüntü boyutları sağlamalıdır, ancak daha fazla zaman alır. RFC 2083 bunun en iyi yol olduğunu söylüyor. Ancak test verilerinde temel tahminci [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) çok iyi performans göstererek, optimize edilmiş tahmincinin %25-40 daha düşük sıkıştırma oranı kazanmasına neden olur.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Jpeg sıkıştırması. Şeffaflığı desteklemez.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 Şeffaflığı desteklemez.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 Şeffaflığı desteklemez.

