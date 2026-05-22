---
title: "RawDataSettings"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Ham veri ayarları"
type: docs
weight: 92
url: /tr/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

Ham veri ayarları
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Boş bir örnek başlatıldı. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | `origin`'in bir kopyasını başlat. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Piksel veri biçimini alır |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Piksel veri formatını ayarlar |
| [getColorPalette()](#getColorPalette--) | Renk paletini alır |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Renk paletini ayarlar |
| [getDitheringMethod()](#getDitheringMethod--) | Ham veri dönüşümü için kullanılacak tarama yöntemini alır |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Ham veri dönüşümü için kullanılacak tarama yöntemini ayarlar |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Indeksli renk dönüştürücüyü alır |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Indeksli renk dönüştürücüyü ayarlar |
| [getCustomColorConverter()](#getCustomColorConverter--) | Özel renk dönüştürücüyü alır |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Özel renk dönüştürücüyü ayarlar |
| [getFallbackIndex()](#getFallbackIndex--) | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi ayarlar |
| [getLineSize()](#getLineSize--) | Ham veri işleme için piksel satır boyutunu bayt olarak alır |
| [setLineSize(int value)](#setLineSize-int-) | Ham veri işleme için piksel satır boyutunu bayt olarak ayarlar |
| [<T>copy()](#-T-copy--) | Yüzeysel bir kopya oluşturur. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Boş bir örnek başlatıldı.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


`origin` öğesinin bir kopyasını başlatır. [copy()](../../com.aspose.imaging/rawdatasettings\#copy--) içinde kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Kopyası yapılacak örnek. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Piksel veri biçimini alır

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Piksel veri formatını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Piksel veri formatı |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Renk paletini alır

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Renk paletini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Ham veri dönüşümü için kullanılacak tarama yöntemini alır

**Returns:**
int - Ham veri dönüşümü için kullanılacak tarama yöntemi
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Ham veri dönüşümü için kullanılacak tarama yöntemini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Ham veri dönüşümü için kullanılacak tarama yöntemi |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Indeksli renk dönüştürücüyü alır

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Indeksli renk dönüştürücüyü ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | İndeksli renk dönüştürücü |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Özel renk dönüştürücüyü alır

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Özel renk dönüştürücüyü ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Özel renk dönüştürücü |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır

**Returns:**
int - Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeks
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeks |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Ham veri işleme için piksel satır boyutunu bayt olarak alır

**Returns:**
int - Ham veri işleme için piksel satır boyutu (bayt cinsinden)
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Ham veri işleme için piksel satır boyutunu bayt olarak ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Ham veri işleme için bayt cinsinden piksel satır boyutu |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Yüzeysel bir kopya oluşturur.

**Returns:**
T - Yüzeysel bir kopya.
