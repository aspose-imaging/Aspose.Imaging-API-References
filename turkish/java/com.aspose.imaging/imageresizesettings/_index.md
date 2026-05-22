---
title: "ImageResizeSettings"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü yeniden boyutlandırma ayarları sınıfı"
type: docs
weight: 63
url: /tr/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Görüntü yeniden boyutlandırma ayarları sınıfı
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Yeni bir `ImageResizeSettings` sınıfı örneği başlatır; Resize türü = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) ile Filter türü = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) ile Renk kantitatif yöntemi = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) ile Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Filter türü = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) ile Renk kantitatif yöntemi = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) ile Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Renk kantitatif yöntemi = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) ile Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount()) |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Giriş sayısını alır |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Giriş sayısını ayarlar |
| [getMode()](#getMode--) | Ara değerleme modunu alır. |
| [setMode(int value)](#setMode-int-) | Ara değerleme modunu ayarlar. |
| [getFilterType()](#getFilterType--) | Filtre tipini alır. |
| [setFilterType(int value)](#setFilterType-int-) | Filtre tipini ayarlar. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Renk kantitatif yöntemini alır. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Renk kantitatif yöntemini ayarlar. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Renk karşılaştırma yöntemini alır. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Renk karşılaştırma yöntemini ayarlar. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Yeni bir `ImageResizeSettings` sınıfı örneği başlatır; Resize türü = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) ile Filter türü = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) ile Renk kantitatif yöntemi = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) ile Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Filter türü = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) ile Renk kantitatif yöntemi = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) ile Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeType | int | Yeniden boyutlandırma tipi. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Renk kantitatif yöntemi = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) ile Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeType | int | Yeniden boyutlandırma tipi. |
| filterType | int | Filtre tipi. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Renk karşılaştırma yöntemi = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) ile Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeType | int | Yeniden boyutlandırma tipi. |
| filterType | int | Filtre tipi. |
| colorQuantizationMethod | int | Renk kantitatif yöntemi. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Yeni bir [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) sınıfı örneği başlatır; Renk giriş sayısı = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeType | int | Yeniden boyutlandırma tipi. |
| filterType | int | Filtre tipi. |
| colorQuantizationMethod | int | Renk kantitatif yöntemi. |
| colorCompareMethod | int | Renk karşılaştırma yöntemi. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Giriş sayısını alır

**Returns:**
int - Girdi sayısı
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Giriş sayısını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Girdi sayısı |

### getMode() {#getMode--}
```
public int getMode()
```


Ara değerleme modunu alır.

**Returns:**
int - Mod.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Ara değerleme modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Mod. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Filtre tipini alır.

**Returns:**
int - Filtre türü.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Filtre tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Filtre türü. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Renk kantitatif yöntemini alır.

**Returns:**
int - Renk kantitatizasyon yöntemi.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Renk kantitatif yöntemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Renk kantitatizasyon yöntemi. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Renk karşılaştırma yöntemini alır.

**Returns:**
int - Renk karşılaştırma yöntemi.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Renk karşılaştırma yöntemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Renk karşılaştırma yöntemi. |

