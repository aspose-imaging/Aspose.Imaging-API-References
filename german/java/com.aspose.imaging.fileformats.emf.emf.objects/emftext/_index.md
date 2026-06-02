---
title: "EmfText"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmrText-Objekt enthält Werte für die Textausgabe."
type: docs
weight: 35
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

Das EmrText-Objekt enthält Werte für die Textausgabe.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getReference()](#getReference--) | Ruft ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) ab oder legt es fest, das die Koordinaten des Referenzpunkts angibt, der zur Positionierung der Zeichenkette verwendet wird. |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | Ruft ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) ab oder legt es fest, das die Koordinaten des Referenzpunkts angibt, der zur Positionierung der Zeichenkette verwendet wird. |
| [getChars()](#getChars--) | Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die die Anzahl der Zeichen in der Zeichenkette angibt. |
| [setChars(int value)](#setChars-int-) | Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die die Anzahl der Zeichen in der Zeichenkette angibt. |
| [getOptions()](#getOptions--) | Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die angibt, wie das im Feld Rectangle angegebene Rechteck verwendet wird. |
| [setOptions(int value)](#setOptions-int-) | Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die angibt, wie das im Feld Rectangle angegebene Rechteck verwendet wird. |
| [getRectangle()](#getRectangle--) | Ruft ein optionales WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Beschneidungs‑ und/oder Undurchsichtigkeitsrechteck in logischen Einheiten definiert. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Ruft ein optionales WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Beschneidungs‑ und/oder Undurchsichtigkeitsrechteck in logischen Einheiten definiert. |
| [getStringBuffer()](#getStringBuffer--) | Ruft den Zeichenketten‑Puffer UndefinedSpace1 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | Ruft den Zeichenketten‑Puffer UndefinedSpace1 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | Ruft den optionalen Glyphen‑Index‑Puffer ab. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | Legt den optionalen Glyphen‑Index‑Puffer fest. |
| [getDxBuffer()](#getDxBuffer--) | Ruft den optionalen Zeichenabstands‑Puffer UndefinedSpace2 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | Ruft den optionalen Zeichenabstands‑Puffer UndefinedSpace2 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


Ruft ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) ab oder legt es fest, das die Koordinaten des Referenzpunkts angibt, der zur Positionierung der Zeichenkette verwendet wird. Der Referenzpunkt wird durch den letzten EMR\\_SETTEXTALIGN‑Datensatz (Abschnitt 2.3.11.25) definiert. Wenn ein solcher Datensatz nicht gesetzt wurde, ist die Standardausrichtung TA\\_LEFT,TA\\_TOP.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


Ruft ein WMF‑PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15) ab oder legt es fest, das die Koordinaten des Referenzpunkts angibt, der zur Positionierung der Zeichenkette verwendet wird. Der Referenzpunkt wird durch den letzten EMR\\_SETTEXTALIGN‑Datensatz (Abschnitt 2.3.11.25) definiert. Wenn ein solcher Datensatz nicht gesetzt wurde, ist die Standardausrichtung TA\\_LEFT,TA\\_TOP.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die die Anzahl der Zeichen in der Zeichenkette angibt.

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die die Anzahl der Zeichen in der Zeichenkette angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die angibt, wie das im Feld Rectangle angegebene Rechteck verwendet wird. Dieses Feld kann eine Kombination aus mehreren ExtTextOutOptions‑Aufzählungswerten (Abschnitt 2.1.11) sein.

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Ruft eine 32‑Bit‑vorzeichenlose Ganzzahl ab oder legt sie fest, die angibt, wie das im Feld Rectangle angegebene Rechteck verwendet wird. Dieses Feld kann eine Kombination aus mehreren ExtTextOutOptions‑Aufzählungswerten (Abschnitt 2.1.11) sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Ruft ein optionales WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Beschneidungs‑ und/oder Undurchsichtigkeitsrechteck in logischen Einheiten definiert. Dieses Rechteck wird auf die Textausgabe angewendet, die vom enthaltenden Datensatz durchgeführt wird.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Ruft ein optionales WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das ein Beschneidungs‑ und/oder Undurchsichtigkeitsrechteck in logischen Einheiten definiert. Dieses Rechteck wird auf die Textausgabe angewendet, die vom enthaltenden Datensatz durchgeführt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


Ruft den Zeichenketten‑Puffer UndefinedSpace1 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. Das Feld OutputString muss nicht unmittelbar auf den vorhergehenden Teil dieser Struktur folgen. OutputString (variabel): Ein Array von Zeichen, das die auszugebende Zeichenkette angibt. Der Ort dieses Feldes wird durch den Wert von offString in Bytes vom Beginn dieses Datensatzes aus bestimmt. Die Anzahl der Zeichen wird durch den Wert von Chars angegeben.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


Ruft den Zeichenketten‑Puffer UndefinedSpace1 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. Das Feld OutputString muss nicht unmittelbar auf den vorhergehenden Teil dieser Struktur folgen. OutputString (variabel): Ein Array von Zeichen, das die auszugebende Zeichenkette angibt. Der Ort dieses Feldes wird durch den Wert von offString in Bytes vom Beginn dieses Datensatzes aus bestimmt. Die Anzahl der Zeichen wird durch den Wert von Chars angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


Ruft den optionalen Glyphen‑Index‑Puffer ab. Wenn die Optionen das Flag ETO\\_GLYPH\\_INDEX besitzen, dann sind die Codes für Zeichen in einer auszugebenden Textzeichenkette tatsächlich Indizes der Zeichen‑Glyphen in einer TrueType‑Schrift (2.1.11 ExtTextOutOptions‑Aufzählung). Glyphen‑Indizes sind schriftspezifisch, daher muss die verwendete Schrift IDENTISCH mit der Schrift sein, die zur Erzeugung der Indizes verwendet wurde, um die korrekten Zeichen bei der Wiedergabe anzuzeigen.

**Returns:**
int[] – der optionale Glyphen‑Index‑Puffer.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


Legt den optionalen Glyphen‑Index‑Puffer fest. Wenn die Optionen das Flag ETO\\_GLYPH\\_INDEX besitzen, dann sind die Codes für Zeichen in einer auszugebenden Textzeichenkette tatsächlich Indizes der Zeichen‑Glyphen in einer TrueType‑Schrift (2.1.11 ExtTextOutOptions‑Aufzählung). Glyphen‑Indizes sind schriftspezifisch, daher muss die verwendete Schrift IDENTISCH mit der Schrift sein, die zur Erzeugung der Indizes verwendet wurde, um die korrekten Zeichen bei der Wiedergabe anzuzeigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] | der optionale Glyphen‑Index‑Puffer. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


Ruft den optionalen Zeichenabstands‑Puffer UndefinedSpace2 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. Das Feld OutputDx muss nicht unmittelbar auf den vorhergehenden Teil dieser Struktur folgen. OutputDx (variabel): Ein Array von 32‑Bit‑vorzeichenlosen Ganzzahlen, das den Ausgabespacing zwischen den Ursprüngen benachbarter Zeichenzellen in logischen Einheiten angibt. Der Ort dieses Feldes wird durch den Wert von offDx in Bytes vom Beginn dieses Datensatzes aus bestimmt. Wenn ein Spacing definiert ist, enthält dieses Feld die gleiche Anzahl Werte wie Zeichen in der Ausgabekette. Wenn das Options‑Feld des EmrText‑Objekts das Flag ETO\\_PDY enthält, dann enthält dieser Puffer doppelt so viele Werte wie Zeichen in der Ausgabekette, jeweils einen horizontalen und einen vertikalen Versatz, in dieser Reihenfolge. Wenn ETO\\_RTLREADING angegeben ist, werden Zeichen von rechts nach links statt von links nach rechts angeordnet. Keine anderen Optionen beeinflussen die Interpretation dieses Feldes.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


Ruft den optionalen Zeichenabstands‑Puffer UndefinedSpace2 (variabel) ab oder legt ihn fest: Eine optionale Anzahl ungenutzter Bytes. Das Feld OutputDx muss nicht unmittelbar auf den vorhergehenden Teil dieser Struktur folgen. OutputDx (variabel): Ein Array von 32‑Bit‑vorzeichenlosen Ganzzahlen, das den Ausgabespacing zwischen den Ursprüngen benachbarter Zeichenzellen in logischen Einheiten angibt. Der Ort dieses Feldes wird durch den Wert von offDx in Bytes vom Beginn dieses Datensatzes aus bestimmt. Wenn ein Spacing definiert ist, enthält dieses Feld die gleiche Anzahl Werte wie Zeichen in der Ausgabekette. Wenn das Options‑Feld des EmrText‑Objekts das Flag ETO\\_PDY enthält, dann enthält dieser Puffer doppelt so viele Werte wie Zeichen in der Ausgabekette, jeweils einen horizontalen und einen vertikalen Versatz, in dieser Reihenfolge. Wenn ETO\\_RTLREADING angegeben ist, werden Zeichen von rechts nach links statt von links nach rechts angeordnet. Keine anderen Optionen beeinflussen die Interpretation dieses Feldes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

