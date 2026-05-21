---
title: "EmfSmallTextOut"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SMALLTEXTOUT‑Datensatz gibt eine Zeichenkette aus."
type: docs
weight: 147
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSmallTextOut extends EmfDrawingRecordType
```

Der EMR\_SMALLTEXTOUT-Datensatz gibt eine Zeichenkette aus.

Wenn ETO\_SMALL\_CHARS im fuOptions‑Feld gesetzt ist, enthält TextString 8‑Bit‑Codes für Zeichen, abgeleitet von den niederwertigen Bytes der 16‑Bit‑Unicode‑UTF16‑LE‑Zeichencodes, wobei das hochwertige Byte als 0 angenommen wird. Wenn ETO\_NO\_RECT im fuOptions‑Feld gesetzt ist, wird das Bounds‑Feld nicht im Datensatz aufgenommen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSmallTextOut(EmfRecord source)](#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSmallTextOut`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getX()](#getX--) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die x‑Koordinate angibt, an der die Zeichenkette platziert werden soll. |
| [setX(int value)](#setX-int-) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die x‑Koordinate angibt, an der die Zeichenkette platziert werden soll. |
| [getY()](#getY--) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die y‑Koordinate angibt, an der die Zeichenkette platziert werden soll. |
| [setY(int value)](#setY-int-) | Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die y‑Koordinate angibt, an der die Zeichenkette platziert werden soll. |
| [getCChars()](#getCChars--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der 16‑Bit‑Zeichen in der Zeichenkette angibt. |
| [setCChars(int value)](#setCChars-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der 16‑Bit‑Zeichen in der Zeichenkette angibt. |
| [getFuOptions()](#getFuOptions--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die zu verwendenden Textausgabeoptionen angibt. |
| [setFuOptions(int value)](#setFuOptions-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die zu verwendenden Textausgabeoptionen angibt. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt. |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt. |
| [getExScale()](#getExScale--) | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in x‑Richtung skaliert werden soll. |
| [setExScale(float value)](#setExScale-float-) | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in x‑Richtung skaliert werden soll. |
| [getEyScale()](#getEyScale--) | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in y‑Richtung skaliert werden soll. |
| [setEyScale(float value)](#setEyScale-float-) | Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in y‑Richtung skaliert werden soll. |
| [getBounds()](#getBounds--) | Ruft ein optionales, 128‑Bit‑WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ruft ein optionales, 128‑Bit‑WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten angibt. |
| [getTextString()](#getTextString--) | Ruft eine variable‑Längen‑Zeichenkette ab oder legt sie fest, die die zu zeichnende Textzeichenkette enthält, entweder in 8‑Bit‑ oder 16‑Bit‑Zeichencodes, gemäß dem Wert des fuOptions‑Feldes. |
| [setTextString(String value)](#setTextString-java.lang.String-) | Ruft eine variable‑Längen‑Zeichenkette ab oder legt sie fest, die die zu zeichnende Textzeichenkette enthält, entweder in 8‑Bit‑ oder 16‑Bit‑Zeichencodes, gemäß dem Wert des fuOptions‑Feldes. |
### EmfSmallTextOut(EmfRecord source) {#EmfSmallTextOut-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSmallTextOut(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSmallTextOut`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getX() {#getX--}
```
public int getX()
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die x‑Koordinate angibt, an der die Zeichenkette platziert werden soll.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die x‑Koordinate angibt, an der die Zeichenkette platziert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getY() {#getY--}
```
public int getY()
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die y‑Koordinate angibt, an der die Zeichenkette platziert werden soll.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Ruft einen 32‑Bit‑vorzeichenbehafteten Integer ab oder legt ihn fest, der die y‑Koordinate angibt, an der die Zeichenkette platziert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCChars() {#getCChars--}
```
public int getCChars()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der 16‑Bit‑Zeichen in der Zeichenkette angibt. Die Zeichenkette ist NICHT null‑terminiert.

**Returns:**
int
### setCChars(int value) {#setCChars-int-}
```
public void setCChars(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die Anzahl der 16‑Bit‑Zeichen in der Zeichenkette angibt. Die Zeichenkette ist NICHT null‑terminiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFuOptions() {#getFuOptions--}
```
public int getFuOptions()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die zu verwendenden Textausgabeoptionen angibt. Diese Optionen werden durch einen oder eine Kombination von Werten aus der ExtTextOutOptions‑Aufzählung (Abschnitt 2.1.11) festgelegt.

**Returns:**
int
### setFuOptions(int value) {#setFuOptions-int-}
```
public void setFuOptions(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der die zu verwendenden Textausgabeoptionen angibt. Diese Optionen werden durch einen oder eine Kombination von Werten aus der ExtTextOutOptions‑Aufzählung (Abschnitt 2.1.11) festgelegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt.

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in x‑Richtung skaliert werden soll.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in x‑Richtung skaliert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in y‑Richtung skaliert werden soll.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Ruft einen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der angibt, um wie viel der Text in y‑Richtung skaliert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ruft ein optionales, 128‑Bit‑WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ruft ein optionales, 128‑Bit‑WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19) ab oder legt es fest, das das Begrenzungsrechteck in Geräte‑Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getTextString() {#getTextString--}
```
public String getTextString()
```


Ruft eine variable‑Längen‑Zeichenkette ab oder legt sie fest, die die zu zeichnende Textzeichenkette enthält, entweder in 8‑Bit‑ oder 16‑Bit‑Zeichencodes, gemäß dem Wert des fuOptions‑Feldes.

**Returns:**
java.lang.String
### setTextString(String value) {#setTextString-java.lang.String-}
```
public void setTextString(String value)
```


Ruft eine variable‑Längen‑Zeichenkette ab oder legt sie fest, die die zu zeichnende Textzeichenkette enthält, entweder in 8‑Bit‑ oder 16‑Bit‑Zeichencodes, gemäß dem Wert des fuOptions‑Feldes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

