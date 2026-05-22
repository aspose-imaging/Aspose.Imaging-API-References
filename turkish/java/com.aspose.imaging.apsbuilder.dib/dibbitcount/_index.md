---
title: "DibBitCount"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BitCount Enumerasyonu, her pikseli tanımlayan bit sayısını ve cihaz bağımsız bitmap DIB'deki maksimum renk sayısını belirtir."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

BitCount enumarasyonu, her pikseli tanımlayan bit sayısını ve cihaz bağımsız bitmap (DIB) içindeki maksimum renk sayısını belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | Piksel başına bit sayısı tanımsızdır. |
| [BIT_COUNT_1](#BIT-COUNT-1) | Görüntü iki renk ile belirtilmiştir. Bitmap'teki her piksel tek bir bit ile temsil edilir. |
| [BIT_COUNT_2](#BIT-COUNT-2) | Görüntü en fazla 16 renk ile belirtilmiştir. |
| [BIT_COUNT_3](#BIT-COUNT-3) | Görüntü en fazla 256 renk ile belirtilmiştir. |
| [BIT_COUNT_4](#BIT-COUNT-4) | Görüntü en fazla 2^16 renk ile belirtilmiştir. |
| [BIT_COUNT_5](#BIT-COUNT-5) | Bitmap en fazla 2^24 renk içerir ve DIB'nin Colors alanı NULL'dur. |
| [BIT_COUNT_6](#BIT-COUNT-6) | Bitmap, en fazla 2^24 renk içerir. |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


Piksel başına bit sayısı tanımsızdır. Görüntünün JPEG veya PNG formatında olması GEREKİR. Bu formatların hiçbiri bir renk tablosu içermez, bu nedenle bu değer renk tablosunun mevcut olmadığını belirtir. JPEG ve PNG sıkıştırma formatlarıyla ilgili daha fazla bilgi için [JFIF] ve [RFC2083] bakınız.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


Görüntü iki renk ile tanımlanmıştır. Bitmap'teki her piksel tek bir bit ile temsil edilir. Bit temizse, piksel renk tablosundaki ilk girişin rengiyle gösterilir; bit ayarlıysa, piksel tablodaki ikinci girişin rengiyle gösterilir.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


Görüntü en fazla 16 renk ile tanımlanmıştır. Bitmap'teki her piksel, renk tablosuna 4-bitlik bir indeksle temsil edilir ve her bayt 2 piksel içerir.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


Görüntü en fazla 256 renk ile tanımlanmıştır. Bitmap'teki her piksel, renk tablosuna 8-bitlik bir indeksle temsil edilir ve her bayt 1 piksel içerir.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


Görüntü en fazla 2^16 renk ile tanımlanmıştır. Bitmap'teki her piksel 16-bitlik bir değerle temsil edilir.

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


Bitmap, en fazla 2^24 renk içerir ve DIB'nin Colors alanı NULL'dır. Bitmap dizisindeki her 3 baytlık üçlü, bir piksel için sırasıyla mavi, yeşil ve kırmızı relatif yoğunlukları temsil eder. Colors renk tablosu, palet tabanlı cihazlarda kullanılan renkleri optimize etmek için kullanılır ve BitmapInfoHeader Nesnesinin ColorUsed alanı tarafından belirtilen giriş sayısını içermelidir.

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


Bitmap, en fazla 2^24 renk içerir.

