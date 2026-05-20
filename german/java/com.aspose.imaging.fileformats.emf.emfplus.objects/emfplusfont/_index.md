---
title: "EmfPlusFont"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusFont‑Objekt gibt Eigenschaften an, die das Erscheinungsbild von Text bestimmen, einschließlich Schriftgröße und -stil."
type: docs
weight: 42
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

Das EmfPlusFont-Objekt gibt Eigenschaften an, die das Aussehen von Text bestimmen, einschließlich Schriftart, Größe und Stil.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Liest oder setzt eine Zeichenkette mit Length Unicode‑Zeichen, die den Namen der Schriftfamilie enthält. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Liest oder setzt eine Zeichenkette mit Length Unicode‑Zeichen, die den Namen der Schriftfamilie enthält. |
| [getFontStyleFlags()](#getFontStyleFlags--) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der Attribute der Zeichen‑glyphen angibt, die das Aussehen der Schrift beeinflussen, wie fett und kursiv. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der Attribute der Zeichen‑glyphen angibt, die das Aussehen der Schrift beeinflussen, wie fett und kursiv. |
| [getSizeUnit()](#getSizeUnit--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die für das EmSize‑Feld verwendeten Einheiten angibt. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die für das EmSize‑Feld verwendeten Einheiten angibt. |
| [getEmSize()](#getEmSize--) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Em‑Größe der Schrift in den durch das SizeUnit‑Feld angegebenen Einheiten festlegt. |
| [setEmSize(float value)](#setEmSize-float-) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Em‑Größe der Schrift in den durch das SizeUnit‑Feld angegebenen Einheiten festlegt. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Liest oder setzt eine Zeichenkette mit Length Unicode‑Zeichen, die den Namen der Schriftfamilie enthält.

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Liest oder setzt eine Zeichenkette mit Length Unicode‑Zeichen, die den Namen der Schriftfamilie enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der Attribute der Zeichen‑glyphen angibt, die das Aussehen der Schrift beeinflussen, wie fett und kursiv. Dieser Wert MUSS aus FontStyle‑Flags (Abschnitt 2.1.2.4) bestehen.

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der Attribute der Zeichen‑glyphen angibt, die das Aussehen der Schrift beeinflussen, wie fett und kursiv. Dieser Wert MUSS aus FontStyle‑Flags (Abschnitt 2.1.2.4) bestehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die für das Feld EmSize verwendeten Einheiten angibt. Dies sind typischerweise die Einheiten, die beim Entwerfen der Schriftart verwendet wurden. Der Wert MUSS in der UnitType‑Aufzählung (Abschnitt 2.1.1.33) liegen.

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die für das Feld EmSize verwendeten Einheiten angibt. Dies sind typischerweise die Einheiten, die beim Entwerfen der Schriftart verwendet wurden. Der Wert MUSS in der UnitType‑Aufzählung (Abschnitt 2.1.1.33) liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Em‑Größe der Schrift in den durch das SizeUnit‑Feld angegebenen Einheiten festlegt.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Em‑Größe der Schrift in den durch das SizeUnit‑Feld angegebenen Einheiten festlegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

