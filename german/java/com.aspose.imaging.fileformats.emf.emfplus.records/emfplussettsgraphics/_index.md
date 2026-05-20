---
title: "EmfPlusSetTsGraphics"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetTSGraphics-Datensatz gibt den Zustand eines Grafikgerätekontexts für einen Terminalserver an."
type: docs
weight: 67
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

Der EmfPlusSetTSGraphics-Datensatz gibt den Zustand eines Grafikgerätekontexts für einen Terminalserver an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSetTsGraphics`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | Liest einen Wert, der angibt, ob [basic vga colors]. |
| [getHavePalette()](#getHavePalette--) | Liest einen Wert, der angibt, ob [have palette]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das die Qualität der Liniendarstellung angibt, einschließlich des Typs der Linien‑Anti‑Aliasing. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das die Qualität der Liniendarstellung angibt, einschließlich des Typs der Linien‑Anti‑Aliasing. |
| [getTextRenderHint()](#getTextRenderHint--) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das die Qualität der Textdarstellung angibt, einschließlich des Typs des Text‑Anti‑Aliasing. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das die Qualität der Textdarstellung angibt, einschließlich des Typs des Text‑Anti‑Aliasing. |
| [getCompositingMode()](#getCompositingMode--) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das angibt, wie Quellfarben mit Hintergrundfarben kombiniert werden. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das angibt, wie Quellfarben mit Hintergrundfarben kombiniert werden. |
| [getCompositingQuality()](#getCompositingQuality--) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das den Grad der Glättung angibt, der auf Linien, Kurven und die Kanten gefüllter Flächen angewendet wird, um sie kontinuierlicher oder schärfer definiert erscheinen zu lassen. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das den Grad der Glättung angibt, der auf Linien, Kurven und die Kanten gefüllter Flächen angewendet wird, um sie kontinuierlicher oder schärfer definiert erscheinen zu lassen. |
| [getRenderOriginX()](#getRenderOriginX--) | Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die horizontale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die horizontale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist. |
| [getRenderOriginY()](#getRenderOriginY--) | Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die vertikale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die vertikale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist. |
| [getTextContrast()](#getTextContrast--) | Liest oder setzt ein 16‑Bit‑Unsigned‑Integer, das den Gamma‑Korrekturwert für die Darstellung von anti‑aliased und ClearType‑Text angibt. |
| [setTextContrast(short value)](#setTextContrast-short-) | Liest oder setzt ein 16‑Bit‑Unsigned‑Integer, das den Gamma‑Korrekturwert für die Darstellung von anti‑aliased und ClearType‑Text angibt. |
| [getFilterType()](#getFilterType--) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das angibt, wie Skalierung, einschließlich Dehnung und Schrumpfung, durchgeführt wird. |
| [setFilterType(byte value)](#setFilterType-byte-) | Liest oder setzt ein 8‑Bit‑Unsigned‑Integer, das angibt, wie Skalierung, einschließlich Dehnung und Schrumpfung, durchgeführt wird. |
| [getPixelOffset()](#getPixelOffset--) | Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Gesamtqualität des Bildes und des Text‑Renderings angibt. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Gesamtqualität des Bildes und des Text‑Renderings angibt. |
| [getWorldToDevice()](#getWorldToDevice--) | Liest oder setzt ein 192‑Bit‑EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Transformation vom Weltraum zum Geräteraum festlegt. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Liest oder setzt ein 192‑Bit‑EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Transformation vom Weltraum zum Geräteraum festlegt. |
| [getPalette()](#getPalette--) | Liest oder setzt ein optionales EmfPlusPalette‑Objekt. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Liest oder setzt ein optionales EmfPlusPalette‑Objekt. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSetTsGraphics`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Liest einen Wert, der angibt, ob [basic vga colors]. Ist er gesetzt, enthält die Palette nur die grundlegenden VGA‑Farben.

Wert: `true`, wenn [basic vga colors]; andernfalls `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Liest einen Wert, der angibt, ob [have palette]. Ist er gesetzt, enthält dieser Datensatz ein EmfPlusPalette‑Objekt (Abschnitt 2.2.2.28) im Palette‑Feld nach den Grafik‑Zustandsdaten.

Wert: `true`, wenn [have palette]; andernfalls `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Qualität der Liniendarstellung, einschließlich des Typs der Kantenglättung, festlegt. Er MUSS in der SmoothingMode‑Aufzählung (Abschnitt 2.1.1.28) definiert sein.

Wert: Der Antialias‑Modus.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Qualität der Liniendarstellung, einschließlich des Typs der Kantenglättung, festlegt. Er MUSS in der SmoothingMode‑Aufzählung (Abschnitt 2.1.1.28) definiert sein.

Wert: Der Antialias‑Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Qualität der Textdarstellung, einschließlich des Typs der Text‑Antialias‑Verarbeitung, festlegt. Er MUSS in der TextRenderingHint‑Aufzählung (Abschnitt 2.1.1.32) definiert sein.

Wert: Der Text‑Render‑Hinweis.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Qualität der Textdarstellung, einschließlich des Typs der Text‑Antialias‑Verarbeitung, festlegt. Er MUSS in der TextRenderingHint‑Aufzählung (Abschnitt 2.1.1.32) definiert sein.

Wert: Der Text‑Render‑Hinweis.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der angibt, wie Quellfarben mit Hintergrundfarben kombiniert werden. Er MUSS ein Wert der CompositingMode‑Aufzählung (Abschnitt 2.1.5) sein.

Wert: Der Compositing‑Modus.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der angibt, wie Quellfarben mit Hintergrundfarben kombiniert werden. Er MUSS ein Wert der CompositingMode‑Aufzählung (Abschnitt 2.1.5) sein.

Wert: Der Compositing‑Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der den Glättungsgrad für Linien, Kurven und die Kanten gefüllter Flächen festlegt, um sie kontinuierlicher oder schärfer definiert erscheinen zu lassen. Er MUSS ein Wert der CompositingQuality‑Aufzählung (Abschnitt 2.1.1.6) sein.

Wert: Die Kompositierungsqualität.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der den Glättungsgrad für Linien, Kurven und die Kanten gefüllter Flächen festlegt, um sie kontinuierlicher oder schärfer definiert erscheinen zu lassen. Er MUSS ein Wert der CompositingQuality‑Aufzählung (Abschnitt 2.1.1.6) sein.

Wert: Die Kompositierungsqualität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die horizontale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist.

Wert: Der Render‑Ursprung‑X.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die horizontale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist.

Wert: Der Render‑Ursprung‑X.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die vertikale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist.

Wert: Der Render‑Ursprung‑Y.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Liest oder setzt ein 16‑Bit‑Signed‑Integer, das die vertikale Koordinate des Ursprungs für die Darstellung von Halftoning‑ und Dithering‑Matrizen ist.

Wert: Der Render‑Ursprung‑Y.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der den Gamma‑Korrekturwert für die Darstellung von antialiasiertem und ClearType‑Text festlegt. Dieser Wert MUSS im Bereich von 0 bis 12 liegen, einschließlich.

Wert: Der Textkontrast.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Liest oder setzt einen 16‑Bit‑vorzeichenlosen Integer, der den Gamma‑Korrekturwert für die Darstellung von antialiasiertem und ClearType‑Text festlegt. Dieser Wert MUSS im Bereich von 0 bis 12 liegen, einschließlich.

Wert: Der Textkontrast.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der festlegt, wie Skalierung, einschließlich Dehnung und Schrumpfung, durchgeführt wird. Er MUSS ein Wert der FilterType‑Aufzählung (Abschnitt 2.1.1.11) sein.

Wert: Der Filtertyp.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der festlegt, wie Skalierung, einschließlich Dehnung und Schrumpfung, durchgeführt wird. Er MUSS ein Wert der FilterType‑Aufzählung (Abschnitt 2.1.1.11) sein.

Wert: Der Filtertyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Gesamtqualität des Bildes und des Text‑Renderings angibt. Er MUSS ein Wert der PixelOffsetMode‑Aufzählung (Abschnitt 2.1.1.26) sein.

Wert: Der Pixel‑Versatz.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Liest oder setzt einen 8‑Bit‑vorzeichenlosen Integer, der die Gesamtqualität des Bildes und des Text‑Renderings angibt. Er MUSS ein Wert der PixelOffsetMode‑Aufzählung (Abschnitt 2.1.1.26) sein.

Wert: Der Pixel‑Versatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Liest oder setzt ein 192‑Bit‑EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Transformation vom Weltraum zum Geräteraum festlegt.

Wert: Die Welt‑zu‑Gerät‑Transformation.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Liest oder setzt ein 192‑Bit‑EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Transformation vom Weltraum zum Geräteraum festlegt.

Wert: Die Welt‑zu‑Gerät‑Transformation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


Liest oder setzt ein optionales EmfPlusPalette‑Objekt.

Wert: Die Palette.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


Liest oder setzt ein optionales EmfPlusPalette‑Objekt.

Wert: Die Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

