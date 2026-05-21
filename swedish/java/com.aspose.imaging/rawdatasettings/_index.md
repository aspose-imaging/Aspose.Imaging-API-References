---
title: "RawDataSettings"
second_title: "Aspose.Imaging för Java API-referens"
description: "Inställningarna för rådata."
type: docs
weight: 92
url: /sv/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

Inställningarna för rådata.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Initierade en tom instans. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | Initiera en kopia av `origin`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Hämtar pixeldataformatet |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Ställer in pixeldataformatet |
| [getColorPalette()](#getColorPalette--) | Hämtar färgpaletten |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Ställer in färgpaletten |
| [getDitheringMethod()](#getDitheringMethod--) | Hämtar dithermetoden som ska användas för konvertering av rådata |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Ställer in dithermetoden som ska användas för konvertering av rådata |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Hämtar den indexerade färgkonverteraren |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Ställer in den indexerade färgkonverteraren |
| [getCustomColorConverter()](#getCustomColorConverter--) | Hämtar den anpassade färgkonverteraren |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Ställer in den anpassade färgkonverteraren |
| [getFallbackIndex()](#getFallbackIndex--) | Hämtar reservindexet som ska användas när palettindexet är utanför gränserna |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Ställer in reservindexet som ska användas när palettindexet är utanför gränserna |
| [getLineSize()](#getLineSize--) | Hämtar pixelradens storlek i byte för rådatabehandling |
| [setLineSize(int value)](#setLineSize-int-) | Ställer in pixelradens storlek i byte för rådatabehandling |
| [<T>copy()](#-T-copy--) | Skapar en ytlig kopia. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Initierade en tom instans.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


Initierar en kopia av `origin`. Används i [copy()](../../com.aspose.imaging/rawdatasettings\#copy--).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Instansen att göra en kopia av. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Hämtar pixeldataformatet

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Ställer in pixeldataformatet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Pixeldataformatet |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Hämtar färgpaletten

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Ställer in färgpaletten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Hämtar dithermetoden som ska användas för konvertering av rådata

**Returns:**
int - Dithermetoden som ska användas för konvertering av rådata
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Ställer in dithermetoden som ska användas för konvertering av rådata

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Dithermetoden som ska användas för konvertering av rådata |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Hämtar den indexerade färgkonverteraren

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Ställer in den indexerade färgkonverteraren

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Den indexerade färgkonverteraren |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Hämtar den anpassade färgkonverteraren

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Ställer in den anpassade färgkonverteraren

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Den anpassade färgkonverteraren |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Hämtar reservindexet som ska användas när palettindexet är utanför gränserna

**Returns:**
int - Reservindexet som ska användas när palettindexet är utanför gränserna
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Ställer in reservindexet som ska användas när palettindexet är utanför gränserna

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Reservindexet som ska användas när palettindexet är utanför gränserna |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Hämtar pixelradens storlek i byte för rådatabehandling

**Returns:**
int - Pixelradens storlek i byte för rådatabehandling
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Ställer in pixelradens storlek i byte för rådatabehandling

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Pixelradens storlek i byte för rådatabehandling |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Skapar en ytlig kopia.

**Returns:**
T - en ytlig kopia.
