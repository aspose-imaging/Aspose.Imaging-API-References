---
title: "SampleRoundingMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "n-bit değerinin 8-bit değere dönüştürülme yolunu tanımlar."
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

n-bit değerinin 8-bit değere dönüştürülme yolunu tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Extrapolate](#Extrapolate) | 8 bitlik bir değeri n bite sığdırmak için dışarıdan genişletir, burada 1 < n < 8. |
| [Truncate](#Truncate) | 8 bitlik bir değeri n bite sığdırmak için kırpar, burada 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


8 bitlik bir değeri n bite sığdırmak için dışarıdan genişletir, burada 1 < n < 8. Tüm olası 8 bitlik değerlerin sayısı 1 << 8 = 256'dır, 0'dan 255'e kadar. Tüm olası n bitlik değerlerin sayısı 1 << n'dir, 0'dan (1 << n) - 1'e kadar. Bazı 8 bitlik değer V8'e karşılık gelen en mantıklı n bitlik değer Vn, Vn = V8 >> (8 - n) şeklindedir.

### Truncate {#Truncate}
```
public static final int Truncate
```


8 bitlik bir değeri n bite sığdırmak için kırpar, burada 1 < n < 8. Tüm olası n bitlik değerlerin sayısı 1 << n'dir, 0'dan (1 << n) - 1'e kadar. Bazı 8 bitlik değer V8'e karşılık gelen en mantıklı n bitlik değer Vn, Vn = V8 & ((1 << n) - 1) şeklindedir.

