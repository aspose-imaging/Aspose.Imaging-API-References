---
title: "RawDataSettings"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Rohdaten‑Einstellungen"
type: docs
weight: 92
url: /de/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

Die Rohdaten‑Einstellungen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Eine leere Instanz initialisiert. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | Eine Kopie von `origin` initialisieren. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Gibt das Pixel-Datenformat zurück |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Setzt das Pixel-Datenformat |
| [getColorPalette()](#getColorPalette--) | Ermittelt die Farbpalette |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Setzt die Farbpalette |
| [getDitheringMethod()](#getDitheringMethod--) | Ermittelt die Dithering-Methode, die für die Rohdatenkonvertierung verwendet wird |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Setzt die Dithering-Methode, die für die Rohdatenkonvertierung verwendet wird |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Ermittelt den indizierten Farbkonverter |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Setzt den indizierten Farbkonverter |
| [getCustomColorConverter()](#getCustomColorConverter--) | Ermittelt den benutzerdefinierten Farbkonverter |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Setzt den benutzerdefinierten Farbkonverter |
| [getFallbackIndex()](#getFallbackIndex--) | Ermittelt den Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Setzt den Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| [getLineSize()](#getLineSize--) | Ermittelt die Zeilengröße der Pixel in Bytes für die Rohdatenverarbeitung |
| [setLineSize(int value)](#setLineSize-int-) | Setzt die Zeilengröße der Pixel in Bytes für die Rohdatenverarbeitung |
| [<T>copy()](#-T-copy--) | Erstellt eine flache Kopie. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Eine leere Instanz initialisiert.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


Initialisiert eine Kopie von `origin`. Verwendet in [copy()](../../com.aspose.imaging/rawdatasettings\#copy--).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Die Instanz, von der eine Kopie erstellt werden soll. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Gibt das Pixel-Datenformat zurück

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Setzt das Pixel-Datenformat

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Das Pixel-Datenformat |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Ermittelt die Farbpalette

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Setzt die Farbpalette

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Ermittelt die Dithering-Methode, die für die Rohdatenkonvertierung verwendet wird

**Returns:**
int - Die Dithering-Methode, die für die Rohdatenkonvertierung verwendet wird
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Setzt die Dithering-Methode, die für die Rohdatenkonvertierung verwendet wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Dithering-Methode, die für die Rohdatenkonvertierung verwendet wird |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Ermittelt den indizierten Farbkonverter

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Setzt den indizierten Farbkonverter

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Der indizierte Farbkonverter |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Ermittelt den benutzerdefinierten Farbkonverter

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Setzt den benutzerdefinierten Farbkonverter

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Der benutzerdefinierte Farbkonverter |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Ermittelt den Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt

**Returns:**
int - Der Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Setzt den Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Ermittelt die Zeilengröße der Pixel in Bytes für die Rohdatenverarbeitung

**Returns:**
int - Die Zeilengröße der Pixel in Bytes für die Rohdatenverarbeitung
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Setzt die Zeilengröße der Pixel in Bytes für die Rohdatenverarbeitung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Zeilengröße der Pixel in Bytes für die Rohdatenverarbeitung |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Erstellt eine flache Kopie.

**Returns:**
T - Eine flache Kopie.
