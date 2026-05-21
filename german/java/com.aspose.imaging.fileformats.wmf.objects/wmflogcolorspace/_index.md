---
title: "WmfLogColorSpace"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das LogColorSpace‑Objekt gibt einen logischen Farbraum für den Wiedergabe‑Geräte‑Context an, der der Name eines Farbprofils in ASCII‑Zeichen sein kann."
type: docs
weight: 44
url: /de/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpace extends MetaObject
```

Das LogColorSpace-Objekt gibt einen logischen Farbraum für den Wiedergabegeräte-Kontext an, der der Name eines Farbprofils in ASCII-Zeichen sein kann.

Die Felder Endpoints, GammaRed, GammaGreen und GammaBlue werden verwendet, um einen logischen Farbraum anzugeben. Das Feld Endpoints ist ein CIEXYZTriple‑Objekt, das die x‑, y‑ und z‑Werte des RGB‑Endpunkts des Farbraums enthält. Die Beziehung zwischen den Tristimulus‑Werten X,Y,Z und den Chromatizitätswerten x,y,z wird wie folgt ausgedrückt: x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z). Die Felder GammaRed, GammaGreen und GammaBlue enthalten Werte im "8.8 fixed point"‑Format, einer Technik zur Darstellung von Nicht‑Ganzzahlen. Jeder Wert besteht aus einer nullerweiterten 8‑Bit‑Magnitude gefolgt von einem 8‑Bit‑Bruchteil, wobei die kombinierten 16 Bits um 8 Bits nach links verschoben werden. Somit ist in 32 Bits der reale Wert N.F = 00000000nnnnnnnnffffffff00000000, wobei "nnnnnnnn" und "ffffffff" die binären Darstellungen von N bzw. F sind. Zum Beispiel wäre für die reale Zahl 10,5 nnnnnnnn = 00001010 (binär 10) und ffffffff = 00000101 (binär 5), und der vollständige 32‑Bit‑Binärwert wäre 00000000000010100000010100000000, was dem hexadezimalen Wert 0x0A50 entspricht.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfLogColorSpace()](#WmfLogColorSpace--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSignature()](#getSignature--) | Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `signature` von Farbraumobjekten angibt; er MUSS auf den Wert 0x50534F43 gesetzt werden, der die ASCII‑Kodierung der Zeichenkette "PSOC" ist. |
| [setSignature(int value)](#setSignature-int-) | Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `signature` von Farbraumobjekten angibt; er MUSS auf den Wert 0x50534F43 gesetzt werden, der die ASCII‑Kodierung der Zeichenkette "PSOC" ist. |
| [getVersion()](#getVersion--) | Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der eine `version`‑Nummer definiert; er MUSS 0x00000400 sein. |
| [setVersion(int value)](#setVersion-int-) | Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der eine `version`‑Nummer definiert; er MUSS 0x00000400 sein. |
| [getSize()](#getSize--) | Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `size` dieses Objekts in Bytes definiert. |
| [setSize(int value)](#setSize-int-) | Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `size` dieses Objekts in Bytes definiert. |
| [getColorSpaceType()](#getColorSpaceType--) | Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der den Farbraumtyp angibt. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der den Farbraumtyp angibt. |
| [getIntent()](#getIntent--) | Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der die Zielsetzung der Gamut‑Abbildung definiert. |
| [setIntent(int value)](#setIntent-int-) | Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der die Zielsetzung der Gamut‑Abbildung definiert. |
| [getEndpoints()](#getEndpoints--) | Liest oder schreibt ein CIEXYZTriple‑Objekt (Abschnitt 2.2.2.7), das die CIE‑Chromatizitäts‑Koordinaten x, y und z der drei Farben definiert, die den RGB-`endpoints` des logischen Farbraums des zugehörigen Bitmaps entsprechen. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Liest oder schreibt ein CIEXYZTriple‑Objekt (Abschnitt 2.2.2.7), das die CIE‑Chromatizitäts‑Koordinaten x, y und z der drei Farben definiert, die den RGB-`endpoints` des logischen Farbraums des zugehörigen Bitmaps entsprechen. |
| [getGammaRed()](#getGammaRed--) | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Rot definiert. |
| [setGammaRed(int value)](#setGammaRed-int-) | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Rot definiert. |
| [getGammaGreen()](#getGammaGreen--) | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Grün definiert. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Grün definiert. |
| [getGammaBlue()](#getGammaBlue--) | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Blau definiert. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Blau definiert. |
| [getFilename()](#getFilename--) | Liest oder schreibt eine optionale ASCII‑Zeichenkette, die den Namen einer Datei angibt, die ein Farbprofil enthält. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Liest oder schreibt eine optionale ASCII‑Zeichenkette, die den Namen einer Datei angibt, die ein Farbprofil enthält. |
### WmfLogColorSpace() {#WmfLogColorSpace--}
```
public WmfLogColorSpace()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `signature` von Farbraumobjekten angibt; er MUSS auf den Wert 0x50534F43 gesetzt werden, der die ASCII‑Kodierung der Zeichenkette "PSOC" ist.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `signature` von Farbraumobjekten angibt; er MUSS auf den Wert 0x50534F43 gesetzt werden, der die ASCII‑Kodierung der Zeichenkette "PSOC" ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der eine `version`‑Nummer definiert; er MUSS 0x00000400 sein.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der eine `version`‑Nummer definiert; er MUSS 0x00000400 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `size` dieses Objekts in Bytes definiert.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Liest oder schreibt einen 32‑Bit‑vorzeichenlosen Integer, der die `size` dieses Objekts in Bytes definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der den Farbraumtyp angibt. Er MUSS in der Aufzählung LogicalColorSpace definiert sein (Abschnitt 2.1.1.14). Wenn dieser Wert LCS\_sRGB oder LCS\_WINDOWS\_COLOR\_SPACE ist, MUSS der sRGB‑Farbraum verwendet werden.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der den Farbraumtyp angibt. Er MUSS in der Aufzählung LogicalColorSpace definiert sein (Abschnitt 2.1.1.14). Wenn dieser Wert LCS\_sRGB oder LCS\_WINDOWS\_COLOR\_SPACE ist, MUSS der sRGB‑Farbraum verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der die Zielsetzung der Gamut‑Abbildung definiert. Er MUSS in der Aufzählung GamutMappingIntent definiert sein (Abschnitt 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Liest oder schreibt einen 32‑Bit‑vorzeichenbehafteten Integer, der die Zielsetzung der Gamut‑Abbildung definiert. Er MUSS in der Aufzählung GamutMappingIntent definiert sein (Abschnitt 2.1.1.11).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Liest oder schreibt ein CIEXYZTriple‑Objekt (Abschnitt 2.2.2.7), das die CIE‑Chromatizitäts‑Koordinaten x, y und z der drei Farben definiert, die den RGB-`endpoints` des logischen Farbraums des zugehörigen Bitmaps entsprechen. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Liest oder schreibt ein CIEXYZTriple‑Objekt (Abschnitt 2.2.2.7), das die CIE‑Chromatizitäts‑Koordinaten x, y und z der drei Farben definiert, die den RGB-`endpoints` des logischen Farbraums des zugehörigen Bitmaps entsprechen. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Rot definiert. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Rot definiert. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Grün definiert. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Grün definiert. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Blau definiert. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Liest oder schreibt einen 32‑Bit‑Festkommawert, der die abgestimmte Antwortkurve für Blau definiert. Wenn das Feld `ColorSpaceType` nicht LCS\_CALIBRATED\_RGB angibt, MUSS dieses Feld ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Liest oder schreibt eine optionale ASCII‑Zeichenkette, die den Namen einer Datei angibt, die ein Farbprofil enthält. Wenn ein Dateiname angegeben ist und das Feld `ColorSpaceType` auf LCS\_CALIBRATED\_RGB gesetzt ist, SOLLTEN die anderen Felder dieser Struktur ignoriert werden.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Liest oder schreibt eine optionale ASCII‑Zeichenkette, die den Namen einer Datei angibt, die ein Farbprofil enthält. Wenn ein Dateiname angegeben ist und das Feld `ColorSpaceType` auf LCS\_CALIBRATED\_RGB gesetzt ist, SOLLTEN die anderen Felder dieser Struktur ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

