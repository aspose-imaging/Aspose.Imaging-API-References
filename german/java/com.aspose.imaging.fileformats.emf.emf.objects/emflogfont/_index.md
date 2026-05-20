---
title: "EmfLogFont"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das LogFont‑Objekt gibt die grundlegenden Attribute einer logischen Schrift an."
type: docs
weight: 22
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

Das LogFont‑Objekt gibt die grundlegenden Attribute einer logischen Schrift an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeight()](#getHeight--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe, in logischen Einheiten, der Zeichenzelle oder des Zeichens der Schrift angibt. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe, in logischen Einheiten, der Zeichenzelle oder des Zeichens der Schrift angibt. |
| [getWidth()](#getWidth--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die durchschnittliche Breite, in logischen Einheiten, der Zeichen in der Schrift angibt. |
| [setWidth(int value)](#setWidth-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die durchschnittliche Breite, in logischen Einheiten, der Zeichen in der Schrift angibt. |
| [getEscapement()](#getEscapement--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die den Winkel, in Zehntelgrad, zwischen dem Escapement‑Vektor und der X‑Achse des Geräts angibt. |
| [setEscapement(int value)](#setEscapement-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die den Winkel, in Zehntelgrad, zwischen dem Escapement‑Vektor und der X‑Achse des Geräts angibt. |
| [getOrientation()](#getOrientation--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die den Winkel, in Zehntelgrad, zwischen der Grundlinie jedes Zeichens und der X‑Achse des Geräts angibt. |
| [setOrientation(int value)](#setOrientation-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die den Winkel, in Zehntelgrad, zwischen der Grundlinie jedes Zeichens und der X‑Achse des Geräts angibt. |
| [getWeight()](#getWeight--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die das Gewicht der Schrift im Bereich von 0 bis 1000 angibt. |
| [setWeight(int value)](#setWeight-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die das Gewicht der Schrift im Bereich von 0 bis 1000 angibt. |
| [getItalic()](#getItalic--) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine kursive Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden. |
| [setItalic(byte value)](#setItalic-byte-) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine kursive Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden. |
| [getUnderline()](#getUnderline--) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine unterstrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden. |
| [setUnderline(byte value)](#setUnderline-byte-) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine unterstrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden. |
| [getStrikeout()](#getStrikeout--) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine durchgestrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine durchgestrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden. |
| [getCharSet()](#getCharSet--) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die den Satz von Zeichen‑glyphen angibt. |
| [setCharSet(byte value)](#setCharSet-byte-) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die den Satz von Zeichen‑glyphen angibt. |
| [getOutPrecision()](#getOutPrecision--) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Ausgabegenauigkeit angibt. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Ausgabegenauigkeit angibt. |
| [getClipPrecision()](#getClipPrecision--) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Abschneidegenauigkeit angibt. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Abschneidegenauigkeit angibt. |
| [getQuality()](#getQuality--) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Ausgabequalität angibt. |
| [setQuality(byte value)](#setQuality-byte-) | Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die die Ausgabequalität angibt. |
| [getPitchAndFamily()](#getPitchAndFamily--) | Liest oder setzt ein WMF‑PitchAndFamily‑Objekt ([MS‑WMF] Abschnitt 2.2.2.14), das die Schriftbreite und -familie der Schrift angibt. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | Liest oder setzt ein WMF‑PitchAndFamily‑Objekt ([MS‑WMF] Abschnitt 2.2.2.14), das die Schriftbreite und -familie der Schrift angibt. |
| [getFacename()](#getFacename--) | Liest oder setzt einen Facename (64 Bytes): Eine Zeichenkette von höchstens 32 Unicode‑Zeichen, die den Schriftartnamen der Schrift angibt. |
| [setFacename(String value)](#setFacename-java.lang.String-) | Liest oder setzt einen Facename (64 Bytes): Eine Zeichenkette von höchstens 32 Unicode‑Zeichen, die den Schriftartnamen der Schrift angibt. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe, in logischen Einheiten, der Zeichenzelle oder des Zeichens der Schrift angibt. Der Zeichenhöhenwert, auch als Em‑Größe bekannt, ist der Wert der Zeichenzellenhöhe minus dem internen Zeilenabstand. Der Schriftzuordner SOLLTE den im Feld Height angegebenen Wert wie folgt interpretieren.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Höhe, in logischen Einheiten, der Zeichenzelle oder des Zeichens der Schrift angibt. Der Zeichenhöhenwert, auch als Em‑Größe bekannt, ist der Wert der Zeichenzellenhöhe minus dem internen Zeilenabstand. Der Schriftzuordner SOLLTE den im Feld Height angegebenen Wert wie folgt interpretieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die durchschnittliche Breite, in logischen Einheiten, der Zeichen in der Schrift angibt. Wenn der Wert des Feldes Width null ist, SOLLTE ein geeigneter Wert aus anderen LogFont‑Werten berechnet werden, um eine Schrift mit dem vom Typografen beabsichtigten Seitenverhältnis zu finden.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die durchschnittliche Breite, in logischen Einheiten, der Zeichen in der Schrift angibt. Wenn der Wert des Feldes Width null ist, SOLLTE ein geeigneter Wert aus anderen LogFont‑Werten berechnet werden, um eine Schrift mit dem vom Typografen beabsichtigten Seitenverhältnis zu finden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Winkel in Zehntelgrad zwischen dem Escapement‑Vektor und der X‑Achse des Geräts angibt. Der Escapement‑Vektor ist parallel zur Grundlinie einer Textzeile.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der den Winkel in Zehntelgrad zwischen dem Escapement‑Vektor und der X‑Achse des Geräts angibt. Der Escapement‑Vektor ist parallel zur Grundlinie einer Textzeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die den Winkel, in Zehntelgrad, zwischen der Grundlinie jedes Zeichens und der X‑Achse des Geräts angibt.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die den Winkel, in Zehntelgrad, zwischen der Grundlinie jedes Zeichens und der X‑Achse des Geräts angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der das Gewicht der Schriftart im Bereich von null bis 1000 angibt. Zum Beispiel ist 400 normal und 700 fett. Wenn dieser Wert null ist, kann ein Standardgewicht verwendet werden.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der das Gewicht der Schriftart im Bereich von null bis 1000 angibt. Zum Beispiel ist 400 normal und 700 fett. Wenn dieser Wert null ist, kann ein Standardgewicht verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine kursive Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine kursive Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine unterstrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine unterstrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine durchgestrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


Liest oder setzt eine 8‑Bit‑vorzeichenlose Ganzzahl, die eine durchgestrichene Schrift angibt, wenn sie auf 0x01 gesetzt ist; andernfalls MUSS sie auf 0x00 gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der den Zeichensatz der Glyphen angibt. Er MUSS ein Wert aus der WMF‑CharacterSet‑Aufzählung ([MS‑WMF] Abschnitt 2.1.1.5) sein. Wenn der Zeichensatz unbekannt ist, SOLLTE die Metadateiverarbeitung nicht versuchen, Zeichenketten, die mit dieser Schriftart gerendert werden, zu übersetzen oder zu interpretieren.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der den Zeichensatz der Glyphen angibt. Er MUSS ein Wert aus der WMF‑CharacterSet‑Aufzählung ([MS‑WMF] Abschnitt 2.1.1.5) sein. Wenn der Zeichensatz unbekannt ist, SOLLTE die Metadateiverarbeitung nicht versuchen, Zeichenketten, die mit dieser Schriftart gerendert werden, zu übersetzen oder zu interpretieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der die Ausgabegenauigkeit angibt. Die Ausgabegenauigkeit definiert, wie genau die Schriftart an die angeforderte Höhe, Breite, Zeichenorientierung, Escapement, Pitch und Schriftarttyp angepasst werden muss. Er MUSS ein Wert aus der WMF‑OutPrecision‑Aufzählung sein.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der die Ausgabegenauigkeit angibt. Die Ausgabegenauigkeit definiert, wie genau die Schriftart an die angeforderte Höhe, Breite, Zeichenorientierung, Escapement, Pitch und Schriftarttyp angepasst werden muss. Er MUSS ein Wert aus der WMF‑OutPrecision‑Aufzählung sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der die Abschneidegenauigkeit angibt. Die Abschneidegenauigkeit definiert, wie Zeichen, die teilweise außerhalb des Abschneidebereichs liegen, abgeschnitten werden. Es kann einer oder mehrere der WMF‑ClipPrecision‑Flags sein.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der die Abschneidegenauigkeit angibt. Die Abschneidegenauigkeit definiert, wie Zeichen, die teilweise außerhalb des Abschneidebereichs liegen, abgeschnitten werden. Es kann einer oder mehrere der WMF‑ClipPrecision‑Flags sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der die Ausgabequalität angibt. Die Ausgabequalität definiert, wie genau versucht wird, die logischen Schriftartattribute an die einer tatsächlichen physischen Schriftart anzupassen. Er MUSS einer der Werte in der WMF‑FontQuality‑Aufzählung ([MS‑WMF] Abschnitt 2.1.1.10) sein.

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


Liest oder setzt einen 8‑Bit vorzeichenlosen Integer, der die Ausgabequalität angibt. Die Ausgabequalität definiert, wie genau versucht wird, die logischen Schriftartattribute an die einer tatsächlichen physischen Schriftart anzupassen. Er MUSS einer der Werte in der WMF‑FontQuality‑Aufzählung ([MS‑WMF] Abschnitt 2.1.1.10) sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


Liest oder setzt ein WMF‑PitchAndFamily‑Objekt ([MS‑WMF] Abschnitt 2.2.2.14), das Pitch und Familie der Schriftart angibt. Schriftfamilien beschreiben das Aussehen einer Schriftart allgemein. Sie dienen dazu, eine Schriftart anzugeben, wenn die angegebene Schriftart nicht verfügbar ist.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


Liest oder setzt ein WMF‑PitchAndFamily‑Objekt ([MS‑WMF] Abschnitt 2.2.2.14), das Pitch und Familie der Schriftart angibt. Schriftfamilien beschreiben das Aussehen einer Schriftart allgemein. Sie dienen dazu, eine Schriftart anzugeben, wenn die angegebene Schriftart nicht verfügbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


Liest oder setzt einen Facename (64 Bytes): Eine Zeichenkette von höchstens 32 Unicode‑Zeichen, die den Namen der Schriftart angibt. Wenn die Länge dieser Zeichenkette weniger als 32 Zeichen beträgt, MUSS ein abschließendes NULL‑Byte vorhanden sein, nach dem der Rest dieses Feldes IGNORIERT werden MUSS.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


Liest oder setzt einen Facename (64 Bytes): Eine Zeichenkette von höchstens 32 Unicode‑Zeichen, die den Namen der Schriftart angibt. Wenn die Länge dieser Zeichenkette weniger als 32 Zeichen beträgt, MUSS ein abschließendes NULL‑Byte vorhanden sein, nach dem der Rest dieses Feldes IGNORIERT werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

