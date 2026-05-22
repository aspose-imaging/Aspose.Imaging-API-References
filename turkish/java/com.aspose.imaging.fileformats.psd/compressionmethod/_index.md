---
title: "CompressionMethod"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Raw](#Raw) | Sıkıştırma yok. |
| [RLE](#RLE) | RLE sıkıştırmalı görüntü verisi, tüm tarama satırları (satırlar \* kanallar) için bayt sayılarıyla başlar ve her sayı iki baytlık bir değer olarak saklanır. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | Tahmin olmadan ZIP. |
| [ZipWithPrediction](#ZipWithPrediction) | Tahminli ZIP. |
### Raw {#Raw}
```
public static final short Raw
```


Sıkıştırma yok. Görüntü verisi, RGBA düzlemsel sırada ham baytlar olarak depolanır. Bu, önce tüm R verisinin, ardından tüm G verisinin, sonra tüm B ve son olarak tüm A verisinin yazıldığı anlamına gelir.

### RLE {#RLE}
```
public static final short RLE
```


RLE sıkıştırmalı görüntü verisi, tüm tarama satırları (satırlar \* kanallar) için bayt sayılarıyla başlar ve her sayı iki baytlık bir değer olarak saklanır. Ardından RLE sıkıştırmalı veri gelir ve her tarama satırı ayrı ayrı sıkıştırılır. RLE sıkıştırması, Macintosh ROM alt programı PackBits ve TIFF standardı tarafından kullanılan aynı sıkıştırma algoritmasıdır.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


Tahmin olmadan ZIP.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


Tahminli ZIP.

