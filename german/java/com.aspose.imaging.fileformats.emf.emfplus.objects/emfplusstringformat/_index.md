---
title: "EmfPlusStringFormat"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusStringFormat‑Objekt gibt Textlayout‑Anzeige­manipulationen und Sprachidentifikation an."
type: docs
weight: 74
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusStringFormat extends EmfPlusGraphicsObjectType
```

Das EmfPlusStringFormat-Objekt gibt Textlayout, Anzeige-Manipulationen und Spracherkennung an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDigitLanguage()](#getDigitLanguage--) | Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt, das die für numerische Ziffern im String zu verwendende Sprache angibt. |
| [setDigitLanguage(short value)](#setDigitLanguage-short-) | Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt, das die für numerische Ziffern im String zu verwendende Sprache angibt. |
| [getDigitSubstitution()](#getDigitSubstitution--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie numerische Ziffern im String gemäß einer Gebietsschema‑ oder Sprachdefinition ersetzt werden. |
| [setDigitSubstitution(int value)](#setDigitSubstitution-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie numerische Ziffern im String gemäß einer Gebietsschema‑ oder Sprachdefinition ersetzt werden. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabulatorstopp angibt. |
| [setFirstTabOffset(float value)](#setFirstTabOffset-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabulatorstopp angibt. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den Verarbeitungstyp angibt, der bei einem Tastenkombinationspräfix (d. h. einem Und‑Zeichen) für einen String durchgeführt wird. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den Verarbeitungstyp angibt, der bei einem Tastenkombinationspräfix (d. h. einem Und‑Zeichen) für einen String durchgeführt wird. |
| [getLanguage()](#getLanguage--) | Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt (Abschnitt 2.2.2.23), das die für den String zu verwendende Sprache angibt. |
| [setLanguage(short value)](#setLanguage-short-) | Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt (Abschnitt 2.2.2.23), das die für den String zu verwendende Sprache angibt. |
| [getLeadingMargin()](#getLeadingMargin--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Länge des Abstandes angibt, der zur Ausgangsposition eines Strings hinzugefügt wird. |
| [setLeadingMargin(float value)](#setLeadingMargin-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Länge des Abstandes angibt, der zur Ausgangsposition eines Strings hinzugefügt wird. |
| [getLineAlign()](#getLineAlign--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie der String vertikal im Layout‑Rechteck ausgerichtet wird. |
| [setLineAlign(int value)](#setLineAlign-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie der String vertikal im Layout‑Rechteck ausgerichtet wird. |
| [getRangeCount()](#getRangeCount--) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten EmfPlusCharacterRange‑Objekte (Abschnitt 2.2.2.8) angibt. |
| [setRangeCount(int value)](#setRangeCount-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten EmfPlusCharacterRange‑Objekte (Abschnitt 2.2.2.8) angibt. |
| [getStringAlignment()](#getStringAlignment--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie der String horizontal im Layout‑Rechteck ausgerichtet wird. |
| [setStringAlignment(int value)](#setStringAlignment-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie der String horizontal im Layout‑Rechteck ausgerichtet wird. |
| [getStringFormatData()](#getStringFormatData--) | Liest oder setzt ein EmfPlusStringFormatData‑Objekt (Abschnitt 2.2.2.44), das optionale Textlayout‑Daten angibt. |
| [setStringFormatData(EmfPlusStringFormatData value)](#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-) | Liest oder setzt ein EmfPlusStringFormatData‑Objekt (Abschnitt 2.2.2.44), das optionale Textlayout‑Daten angibt. |
| [getStringFormatFlags()](#getStringFormatFlags--) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die Textlayout‑Optionen für Formatierung, Beschneidung und Schriftartenverwaltung angibt. |
| [setStringFormatFlags(long value)](#setStringFormatFlags-long-) | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die Textlayout‑Optionen für Formatierung, Beschneidung und Schriftartenverwaltung angibt. |
| [getTabstopCount()](#getTabstopCount--) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten Tabulatorstopps angibt. |
| [setTabstopCount(int value)](#setTabstopCount-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten Tabulatorstopps angibt. |
| [getTracking()](#getTracking--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der das Verhältnis des horizontal zugewiesenen Raums für jedes Zeichen in einem angegebenen String zur schriftspezifischen Zeichenbreite angibt. |
| [setTracking(float value)](#setTracking-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der das Verhältnis des horizontal zugewiesenen Raums für jedes Zeichen in einem angegebenen String zur schriftspezifischen Zeichenbreite angibt. |
| [getTrailingMargin()](#getTrailingMargin--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Länge des Abstandes angibt, der nach einem String freigelassen wird. |
| [setTrailingMargin(float value)](#setTrailingMargin-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Länge des Abstandes angibt, der nach einem String freigelassen wird. |
| [getTrimming()](#getTrimming--) | Liest oder setzt, gibt an, wie Zeichen von einem String, der zu groß ist, um in ein Layout‑Rechteck zu passen, abgeschnitten werden. |
| [setTrimming(int value)](#setTrimming-int-) | Liest oder setzt, gibt an, wie Zeichen von einem String, der zu groß ist, um in ein Layout‑Rechteck zu passen, abgeschnitten werden. |
### EmfPlusStringFormat() {#EmfPlusStringFormat--}
```
public EmfPlusStringFormat()
```


### getDigitLanguage() {#getDigitLanguage--}
```
public short getDigitLanguage()
```


Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt, das die für numerische Ziffern im String zu verwendende Sprache angibt. Beispielsweise muss dieses Feld, wenn der String arabische Ziffern enthält, einen Sprachidentifikator enthalten, der eine arabische Sprache spezifiziert.

**Returns:**
short
### setDigitLanguage(short value) {#setDigitLanguage-short-}
```
public void setDigitLanguage(short value)
```


Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt, das die für numerische Ziffern im String zu verwendende Sprache angibt. Beispielsweise muss dieses Feld, wenn der String arabische Ziffern enthält, einen Sprachidentifikator enthalten, der eine arabische Sprache spezifiziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getDigitSubstitution() {#getDigitSubstitution--}
```
public int getDigitSubstitution()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie numerische Ziffern im String gemäß einer Gebietsschema‑ oder Sprachdefinition ersetzt werden. Dieser Wert MUSS in der StringDigitSubstitution‑Aufzählung (Abschnitt 2.1.1.30) definiert sein.

**Returns:**
int
### setDigitSubstitution(int value) {#setDigitSubstitution-int-}
```
public void setDigitSubstitution(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie numerische Ziffern im String gemäß einer Gebietsschema‑ oder Sprachdefinition ersetzt werden. Dieser Wert MUSS in der StringDigitSubstitution‑Aufzählung (Abschnitt 2.1.1.30) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabulatorstopp angibt.

**Returns:**
float
### setFirstTabOffset(float value) {#setFirstTabOffset-float-}
```
public void setFirstTabOffset(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabulatorstopp angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den Verarbeitungstyp angibt, der bei einem Tastenkombinationspräfix (d. h. einem Und‑Zeichen) für einen String durchgeführt wird. Im Wesentlichen gibt dieses Feld an, ob Tastenkombinationspräfixe, die sich auf Text beziehen, angezeigt werden sollen. Der Wert MUSS in der HotkeyPrefix‑Aufzählung (Abschnitt 2.1.1.14) definiert sein.

**Returns:**
int
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den Verarbeitungstyp angibt, der bei einem Tastenkombinationspräfix (d. h. einem Und‑Zeichen) für einen String durchgeführt wird. Im Wesentlichen gibt dieses Feld an, ob Tastenkombinationspräfixe, die sich auf Text beziehen, angezeigt werden sollen. Der Wert MUSS in der HotkeyPrefix‑Aufzählung (Abschnitt 2.1.1.14) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLanguage() {#getLanguage--}
```
public short getLanguage()
```


Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt (Abschnitt 2.2.2.23), das die für den String zu verwendende Sprache angibt.

**Returns:**
short
### setLanguage(short value) {#setLanguage-short-}
```
public void setLanguage(short value)
```


Liest oder setzt ein EmfPlusLanguageIdentifier‑Objekt (Abschnitt 2.2.2.23), das die für den String zu verwendende Sprache angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getLeadingMargin() {#getLeadingMargin--}
```
public float getLeadingMargin()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Länge des Abstandes angibt, der zur Ausgangsposition eines Strings hinzugefügt wird. Der Standardwert ist 1/6 Zoll; für typografische Schriften beträgt der Standardwert 0.

**Returns:**
float
### setLeadingMargin(float value) {#setLeadingMargin-float-}
```
public void setLeadingMargin(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Länge des Abstandes angibt, der zur Ausgangsposition eines Strings hinzugefügt wird. Der Standardwert ist 1/6 Zoll; für typografische Schriften beträgt der Standardwert 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getLineAlign() {#getLineAlign--}
```
public int getLineAlign()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie der String vertikal im Layout‑Rechteck ausgerichtet wird. Dieser Wert MUSS in der StringAlignment‑Aufzählung definiert sein.

**Returns:**
int
### setLineAlign(int value) {#setLineAlign-int-}
```
public void setLineAlign(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, wie der String vertikal im Layout‑Rechteck ausgerichtet wird. Dieser Wert MUSS in der StringAlignment‑Aufzählung definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRangeCount() {#getRangeCount--}
```
public int getRangeCount()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten EmfPlusCharacterRange‑Objekte (Abschnitt 2.2.2.8) angibt.

**Returns:**
int
### setRangeCount(int value) {#setRangeCount-int-}
```
public void setRangeCount(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten EmfPlusCharacterRange‑Objekte (Abschnitt 2.2.2.8) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStringAlignment() {#getStringAlignment--}
```
public int getStringAlignment()
```


Liest oder legt fest ein 32‑Bit‑vorzeichenloses Integer, das angibt, wie die Zeichenkette horizontal im Layout‑Rechteck ausgerichtet wird. Dieser Wert MUSS in der StringAlignment‑Aufzählung (Abschnitt 2.1.1.29) definiert sein.

**Returns:**
int
### setStringAlignment(int value) {#setStringAlignment-int-}
```
public void setStringAlignment(int value)
```


Liest oder legt fest ein 32‑Bit‑vorzeichenloses Integer, das angibt, wie die Zeichenkette horizontal im Layout‑Rechteck ausgerichtet wird. Dieser Wert MUSS in der StringAlignment‑Aufzählung (Abschnitt 2.1.1.29) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStringFormatData() {#getStringFormatData--}
```
public EmfPlusStringFormatData getStringFormatData()
```


Liest oder setzt ein EmfPlusStringFormatData‑Objekt (Abschnitt 2.2.2.44), das optionale Textlayout‑Daten angibt.

**Returns:**
[EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata)
### setStringFormatData(EmfPlusStringFormatData value) {#setStringFormatData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData-}
```
public void setStringFormatData(EmfPlusStringFormatData value)
```


Liest oder setzt ein EmfPlusStringFormatData‑Objekt (Abschnitt 2.2.2.44), das optionale Textlayout‑Daten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusStringFormatData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata) |  |

### getStringFormatFlags() {#getStringFormatFlags--}
```
public long getStringFormatFlags()
```


Liest oder legt fest ein 32‑Bit‑vorzeichenloses Integer, das Textlayout‑Optionen für Formatierung, Beschneidung und Schriftartenverwaltung angibt. Dieser Wert MUSS aus StringFormat‑Flags (Abschnitt 2.1.2.8) zusammengesetzt sein.

**Returns:**
long
### setStringFormatFlags(long value) {#setStringFormatFlags-long-}
```
public void setStringFormatFlags(long value)
```


Liest oder legt fest ein 32‑Bit‑vorzeichenloses Integer, das Textlayout‑Optionen für Formatierung, Beschneidung und Schriftartenverwaltung angibt. Dieser Wert MUSS aus StringFormat‑Flags (Abschnitt 2.1.2.8) zusammengesetzt sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### getTabstopCount() {#getTabstopCount--}
```
public int getTabstopCount()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten Tabulatorstopps angibt.

**Returns:**
int
### setTabstopCount(int value) {#setTabstopCount-int-}
```
public void setTabstopCount(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die die Anzahl der im Feld StringFormatData definierten Tabulatorstopps angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTracking() {#getTracking--}
```
public float getTracking()
```


Liest oder legt fest einen 32‑Bit‑Gleitkommawert, der das Verhältnis des horizontalen Raums, der jedem Zeichen in einer angegebenen Zeichenkette zugewiesen wird, zur schriftspezifischen Breite des Zeichens angibt. Große Werte für diese Eigenschaft bedeuten viel Abstand zwischen den Zeichen; Werte kleiner als 1 können zu Zeichenüberlappungen führen. Der Standardwert ist 1,03; für typografische Schriften beträgt der Standardwert 1,00.

**Returns:**
float
### setTracking(float value) {#setTracking-float-}
```
public void setTracking(float value)
```


Liest oder legt fest einen 32‑Bit‑Gleitkommawert, der das Verhältnis des horizontalen Raums, der jedem Zeichen in einer angegebenen Zeichenkette zugewiesen wird, zur schriftspezifischen Breite des Zeichens angibt. Große Werte für diese Eigenschaft bedeuten viel Abstand zwischen den Zeichen; Werte kleiner als 1 können zu Zeichenüberlappungen führen. Der Standardwert ist 1,03; für typografische Schriften beträgt der Standardwert 1,00.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getTrailingMargin() {#getTrailingMargin--}
```
public float getTrailingMargin()
```


Liest oder legt fest einen 32‑Bit‑Gleitkommawert, der die Länge des nach einer Zeichenkette zu hinterlassenden Abstandes angibt. Der Standardwert ist 1/6 Zoll; für typografische Schriften beträgt der Standardwert 0.

**Returns:**
float
### setTrailingMargin(float value) {#setTrailingMargin-float-}
```
public void setTrailingMargin(float value)
```


Liest oder legt fest einen 32‑Bit‑Gleitkommawert, der die Länge des nach einer Zeichenkette zu hinterlassenden Abstandes angibt. Der Standardwert ist 1/6 Zoll; für typografische Schriften beträgt der Standardwert 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Liest oder legt fest, wie Zeichen aus einer zu groß für ein Layout‑Rechteck passenden Zeichenkette abgeschnitten werden. Dieser Wert MUSS in der StringTrimming‑Aufzählung (Abschnitt 2.1.1.31) definiert sein.

**Returns:**
int
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Liest oder legt fest, wie Zeichen aus einer zu groß für ein Layout‑Rechteck passenden Zeichenkette abgeschnitten werden. Dieser Wert MUSS in der StringTrimming‑Aufzählung (Abschnitt 2.1.1.31) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

