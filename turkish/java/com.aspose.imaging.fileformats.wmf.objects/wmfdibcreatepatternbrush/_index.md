---
title: "WmfDibCreatePatternBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_DIBCREATEPATTERNBRUSH kaydı, 2.2.1.1 bölümünde bir Brush Object bölümü oluşturur ve desen, 2.2.2.9 bölümündeki DeviceIndependentBitmap DIB nesnesi tarafından belirtilir."
type: docs
weight: 29
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

META\_DIBCREATEPATTERNBRUSH kaydı, bir DeviceIndependentBitmap (DIB) Nesnesi (bölüm 2.2.2.9) tarafından belirtilen bir desenle bir Brush Nesnesi (bölüm 2.2.1.1) oluşturur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStyle()](#getStyle--) | Alır veya ayarlar stili. |
| [setStyle(int value)](#setStyle-int-) | Alır veya ayarlar stili. |
| [getColorUsage()](#getColorUsage--) | Renk kullanımını alır veya ayarlar. |
| [setColorUsage(int value)](#setColorUsage-int-) | Renk kullanımını alır veya ayarlar. |
| [getSourceBitmap()](#getSourceBitmap--) | Kaynak bitmap'i alır veya ayarlar. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Kaynak bitmap'i alır veya ayarlar. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Alır veya ayarlar stili.

Değer: Bu alan için geçerli değerler aşağıdaki gibi tanımlanır: değer BS\\_PATTERN değilse, BS\\_DIBPATTERNPT varsayılmalıdır. Bu değerler BrushStyle Sıralaması'nda (bölüm 2.1.1.4) belirtilir.

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Alır veya ayarlar stili.

Değer: Bu alan için geçerli değerler aşağıdaki gibi tanımlanır: değer BS\\_PATTERN değilse, BS\\_DIBPATTERNPT varsayılmalıdır. Bu değerler BrushStyle Sıralaması'nda (bölüm 2.1.1.4) belirtilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Renk kullanımını alır veya ayarlar.

Değer: Bir DIB Nesnesinin Colors alanı açık RGB değerleri veya bir palet içindeki indeksler içerir.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Renk kullanımını alır veya ayarlar.

Değer: Bir DIB Nesnesinin Colors alanı açık RGB değerleri veya bir palet içindeki indeksler içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Kaynak bitmap'i alır veya ayarlar.

Değer: Fırçada kullanılacak deseni tanımlayan değişken-bit DIB Nesne verisi.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Kaynak bitmap'i alır veya ayarlar.

Değer: Fırçada kullanılacak deseni tanımlayan değişken-bit DIB Nesne verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

