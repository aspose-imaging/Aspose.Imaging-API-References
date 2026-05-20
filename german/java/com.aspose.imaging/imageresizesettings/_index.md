---
title: "ImageResizeSettings"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Klasse für Bildgrößenänderungs‑Einstellungen"
type: docs
weight: 63
url: /de/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Klasse für Bildgrößenänderungs‑Einstellungen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Initialisiert eine neue Instanz der `ImageResizeSettings`‑Klasse mit Resize‑Typ = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) mit Filter‑Typ = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) mit Farbkodierungs‑Methode = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Filter‑Typ = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) mit Farbkodierungs‑Methode = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Farbkodierungs‑Methode = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount()) |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Liest die Eintragsanzahl |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Setzt die Eintragsanzahl |
| [getMode()](#getMode--) | Liest den Interpolationsmodus. |
| [setMode(int value)](#setMode-int-) | Setzt den Interpolationsmodus. |
| [getFilterType()](#getFilterType--) | Liest den Typ des Filters. |
| [setFilterType(int value)](#setFilterType-int-) | Setzt den Typ des Filters. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Liest die Farbkodierungs‑Methode. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Setzt die Farbkodierungs‑Methode. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Liest die Farbvergleichs‑Methode. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Setzt die Farbvergleichs‑Methode. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Initialisiert eine neue Instanz der `ImageResizeSettings`‑Klasse mit Resize‑Typ = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) mit Filter‑Typ = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) mit Farbkodierungs‑Methode = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Filter‑Typ = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) mit Farbkodierungs‑Methode = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeType | int | Resize‑Typ. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Farbkodierungs‑Methode = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeType | int | Resize‑Typ. |
| filterType | int | Filter‑Typ. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Farbvergleichs‑Methode = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeType | int | Resize‑Typ. |
| filterType | int | Filter‑Typ. |
| colorQuantizationMethod | int | Farbkodierungs‑Methode. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Initialisiert eine neue Instanz der [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings)‑Klasse mit Farb‑Eintragsanzahl = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeType | int | Resize‑Typ. |
| filterType | int | Filter‑Typ. |
| colorQuantizationMethod | int | Farbkodierungs‑Methode. |
| colorCompareMethod | int | Farbvergleichsmethode. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Liest die Eintragsanzahl

**Returns:**
int - Die Eintragsanzahl
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Setzt die Eintragsanzahl

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Eintragsanzahl |

### getMode() {#getMode--}
```
public int getMode()
```


Liest den Interpolationsmodus.

**Returns:**
int - Der Modus.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Setzt den Interpolationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Modus. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Liest den Typ des Filters.

**Returns:**
int - Der Typ des Filters.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Setzt den Typ des Filters.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Typ des Filters. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Liest die Farbkodierungs‑Methode.

**Returns:**
int - Die Farbquantisierungsmethode.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Setzt die Farbkodierungs‑Methode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Farbquantisierungsmethode. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Liest die Farbvergleichs‑Methode.

**Returns:**
int - Die Farbvergleichsmethode.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Setzt die Farbvergleichs‑Methode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Farbvergleichsmethode. |

