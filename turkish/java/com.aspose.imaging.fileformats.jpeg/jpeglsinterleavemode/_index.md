---
title: "JpegLsInterleaveMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Çok bileşenli renk piksel verisi için interleave modunu tanımlar."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Çok bileşenli (renk) piksel verileri için ara birleştirme modunu tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [None](#None) | Veri, bileşen bazında şu şekilde kodlanıp saklanır: RRRGGGBBB. |
| [Line](#Line) | Interleave modu satır bazlıdır. |
| [Sample](#Sample) | Veri örnek bazında kodlanıp saklanır. |
### None {#None}
```
public static final int None
```


Veri, bileşen bazında şu şekilde kodlanıp saklanır: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


Interleave modu satır bazlıdır. Bir sonraki satıra geçmeden önce her bileşenin tam bir satırı kodlanır.

### Sample {#Sample}
```
public static final int Sample
```


Veri örnek bazında kodlanıp saklanır. Renkli görüntüler için bu, RGBRGBRGB gibi bir formattır.

