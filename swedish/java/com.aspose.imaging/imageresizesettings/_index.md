---
title: "ImageResizeSettings"
second_title: "Aspose.Imaging för Java API-referens"
description: "Klass för bildstorleksändringsinställningar"
type: docs
weight: 63
url: /sv/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Klass för bildstorleksändringsinställningar
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Initierar en ny instans av klassen `ImageResizeSettings` med Resize-typ = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) med Filter-typ = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) med färgkvantiseringsmetod = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med Filter-typ = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) med färgkvantiseringsmetod = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med färgkvantiseringsmetod = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount()) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Hämtar antalet poster |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Ställer in antalet poster |
| [getMode()](#getMode--) | Hämtar interpolationsläget. |
| [setMode(int value)](#setMode-int-) | Ställer in interpolationsläget. |
| [getFilterType()](#getFilterType--) | Hämtar filtertypen. |
| [setFilterType(int value)](#setFilterType-int-) | Ställer in filtertypen. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Hämtar färgkvantiseringsmetoden. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Ställer in färgkvantiseringsmetoden. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Hämtar färgjämförelsemetoden. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Ställer in färgjämförelsemetoden. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Initierar en ny instans av klassen `ImageResizeSettings` med Resize-typ = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) med Filter-typ = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) med färgkvantiseringsmetod = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med Filter-typ = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) med färgkvantiseringsmetod = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeType | int | Resize-typ. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med färgkvantiseringsmetod = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeType | int | Resize-typ. |
| filterType | int | Filter-typ. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med färgjämförelsemetod = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeType | int | Resize-typ. |
| filterType | int | Filter-typ. |
| colorQuantizationMethod | int | Färgkvantiseringsmetod. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Initierar en ny instans av klassen [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) med färgpostantal = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeType | int | Resize-typ. |
| filterType | int | Filter-typ. |
| colorQuantizationMethod | int | Färgkvantiseringsmetod. |
| colorCompareMethod | int | Färgjämförelsemetod. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Hämtar antalet poster

**Returns:**
int - Antalet poster
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Ställer in antalet poster

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Antalet poster |

### getMode() {#getMode--}
```
public int getMode()
```


Hämtar interpolationsläget.

**Returns:**
int - Läge.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Ställer in interpolationsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Läge. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Hämtar filtertypen.

**Returns:**
int - Typen av filtret.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Ställer in filtertypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Typen av filtret. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Hämtar färgkvantiseringsmetoden.

**Returns:**
int - Färgkvantiseringsmetod.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Ställer in färgkvantiseringsmetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Färgkvantiseringsmetod. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Hämtar färgjämförelsemetoden.

**Returns:**
int - Färgjämförelsemetod.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Ställer in färgjämförelsemetoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Färgjämförelsemetod. |

