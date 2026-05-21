---
title: "EmfRop4"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir bitmap'in ön plan ve arka plan renkleri için üçlü raster işlemlerini belirten dörtlü raster işlemi."
type: docs
weight: 110
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

Bir bitmap'in ön plan ve arka plan renkleri için üçlü raster işlemlerini belirten dörtlü raster işlemi. Bu değerler, kaynak dikdörtgenin renk verisinin hedef dikdörtgenin renk verisiyle nasıl birleştirileceğini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | `EmfRop4` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Arka plan ROP3'ünü alır. |
| [getForegroundRop3()](#getForegroundRop3--) | Ön plan ROP3'ünü alır. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


`EmfRop4` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dwordData | int | dword verisi. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Arka plan ROP3'ü alır. WMF Ternary Raster Operation sayımı ([MS-WMF] bölüm 2.1.1.31) içindeki 24 bitlik üçlü raster işlem değerinin işaretsiz, en yüksek anlamlı 8 bitidir. Bu kod, kaynak ve hedef bitmap'lerin ve fırça deseninin arka plan renk verilerini nasıl birleştirileceğini tanımlar.

Değer: Arka plan ROP3.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Ön plan ROP3'ü alır. WMF Ternary Raster Operation sayımı içindeki 24 bitlik üçlü raster işlem değerinin işaretsiz, en yüksek anlamlı 8 bitidir. Bu kod, kaynak ve hedef bitmap'lerin ve fırça deseninin ön plan renk verilerini nasıl birleştirileceğini tanımlar.

Değer: Ön plan ROP3.

**Returns:**
byte
