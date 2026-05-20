---
title: "StringFormat"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Kapselt Textlayout-Informationen wie Ausrichtung, Orientierung und Tabulatoren sowie Anzeige-Manipulationen wie das Einfügen von Auslassungszeichen, die nationale Ziffernersetzung und OpenType-Funktionen."
type: docs
weight: 112
url: /de/java/com.aspose.imaging/stringformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Kapselt Textlayout-Informationen (wie Ausrichtung, Orientierung und Tabulatoren), Anzeige-Manipulationen (wie das Einfügen von Auslassungszeichen und die nationale Ziffernersetzung) und OpenType-Funktionen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StringFormat()](#StringFormat--) | Initialisiert ein neues `com.aspose.imaging.StringFormat`-Objekt. |
| [StringFormat(int options)](#StringFormat-int-) | Initialisiert ein neues `com.aspose.imaging.StringFormat`-Objekt mit der angegebenen Aufzählung `com.aspose.imaging.StringFormatFlags` und Sprache. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.imaging.StringFormat-) | Initialisiert ein neues `com.aspose.imaging.StringFormat`-Objekt aus dem angegebenen vorhandenen `com.aspose.imaging.StringFormat`-Objekt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getGenericDefault()](#getGenericDefault--) | Gibt ein generisches Standard-`com.aspose.imaging.StringFormat`-Objekt zurück. |
| [getGenericTypographic()](#getGenericTypographic--) | Ruft ein generisches typografisches `com.aspose.imaging.StringFormat`-Objekt ab. |
| [getFormatFlags()](#getFormatFlags--) | Ruft eine `com.aspose.imaging.StringFormatFlags`-Aufzählung ab, die Formatierungsinformationen enthält. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Legt eine `com.aspose.imaging.StringFormatFlags`-Aufzählung fest, die Formatierungsinformationen enthält. |
| [getAlignment()](#getAlignment--) | Ruft Textausrichtungsinformationen in der vertikalen Ebene ab. |
| [setAlignment(int value)](#setAlignment-int-) | Legt Textausrichtungsinformationen in der vertikalen Ebene fest. |
| [getLineAlignment()](#getLineAlignment--) | Ruft die Zeilenausrichtung in der horizontalen Ebene ab. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Legt die Zeilenausrichtung in der horizontalen Ebene fest. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Ruft das `com.aspose.imaging.HotkeyPrefix`-Objekt für dieses `com.aspose.imaging.StringFormat`-Objekt ab. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Legt das `com.aspose.imaging.HotkeyPrefix`-Objekt für dieses `com.aspose.imaging.StringFormat`-Objekt fest. |
| [getTrimming()](#getTrimming--) | Ruft die `com.aspose.imaging.StringTrimming`-Aufzählung für dieses `com.aspose.imaging.StringFormat`-Objekt ab. |
| [setTrimming(int value)](#setTrimming-int-) | Legt die `com.aspose.imaging.StringTrimming`-Aufzählung für dieses `com.aspose.imaging.StringFormat`-Objekt fest. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Ruft die Methode ab, die für die Ziffernersetzung verwendet wird. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Legt die Methode fest, die für die Ziffernersetzung verwendet wird. |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Ruft die Sprache ab, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Legt die Sprache fest, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Ruft die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp ab. |
| [getTabStops()](#getTabStops--) | Ruft ein Array von Abständen zwischen Tabstopps in den durch die Eigenschaft `P:Aspose.Imaging.getGraphics().PageUnit` angegebenen Einheiten ab. |
| [getCustomCharIdent()](#getCustomCharIdent--) | Ruft den benutzerdefinierten Zeichenidentifikator ab. |
| [setCustomCharIdent(PointF value)](#setCustomCharIdent-com.aspose.imaging.PointF-) | Legt den benutzerdefinierten Zeichenidentifikator fest. |
| [deepClone()](#deepClone--) | Erstellt einen tiefen Klon dieses `com.aspose.imaging.StringFormat`-Objekts. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Legt Tabstopps für dieses `com.aspose.imaging.StringFormat`-Objekt fest. |
| [toString()](#toString--) | Konvertiert dieses `com.aspose.imaging.StringFormat`-Objekt in eine menschenlesbare Zeichenkette. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Initialisiert ein neues `com.aspose.imaging.StringFormat`-Objekt.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Initialisiert ein neues `com.aspose.imaging.StringFormat`-Objekt mit der angegebenen Aufzählung `com.aspose.imaging.StringFormatFlags` und Sprache.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Optionen | int | Die `com.aspose.imaging.StringFormatFlags`-Aufzählung für das neue `com.aspose.imaging.StringFormat`-Objekt. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.imaging.StringFormat-}
```
public StringFormat(StringFormat format)
```


Initialisiert ein neues `com.aspose.imaging.StringFormat`-Objekt aus dem angegebenen vorhandenen `com.aspose.imaging.StringFormat`-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.imaging/stringformat) | Das `com.aspose.imaging.StringFormat`-Objekt, aus dem das neue `com.aspose.imaging.StringFormat`-Objekt initialisiert wird. |

### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Gibt ein generisches Standard-`com.aspose.imaging.StringFormat`-Objekt zurück.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The generic default `com.aspose.imaging.StringFormat` object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Ruft ein generisches typografisches `com.aspose.imaging.StringFormat`-Objekt ab.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - A generic typographic `com.aspose.imaging.StringFormat` object.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Ruft eine `com.aspose.imaging.StringFormatFlags`-Aufzählung ab, die Formatierungsinformationen enthält.

**Returns:**
int - Eine `com.aspose.imaging.StringFormatFlags` Aufzählung, die Formatierungsinformationen enthält.
### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Legt eine `com.aspose.imaging.StringFormatFlags`-Aufzählung fest, die Formatierungsinformationen enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine `com.aspose.imaging.StringFormatFlags` Aufzählung, die Formatierungsinformationen enthält. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Ruft Textausrichtungsinformationen in der vertikalen Ebene ab.

**Returns:**
int - Eine `com.aspose.imaging.StringAlignment` Aufzählung, die Informationen zur Textausrichtung angibt.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Legt Textausrichtungsinformationen in der vertikalen Ebene fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine `com.aspose.imaging.StringAlignment` Aufzählung, die Informationen zur Textausrichtung angibt. |

### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Ruft die Zeilenausrichtung in der horizontalen Ebene ab.

**Returns:**
int - Eine `com.aspose.imaging.StringAlignment` Aufzählung, die die Zeilenausrichtung darstellt.
### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Legt die Zeilenausrichtung in der horizontalen Ebene fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine `com.aspose.imaging.StringAlignment` Aufzählung, die die Zeilenausrichtung darstellt. |

### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Ruft das `com.aspose.imaging.HotkeyPrefix`-Objekt für dieses `com.aspose.imaging.StringFormat`-Objekt ab.

**Returns:**
int - Das `com.aspose.imaging.HotkeyPrefix` Objekt für dieses `com.aspose.imaging.StringFormat` Objekt, standardmäßig ist `F:Aspose.Imaging.HotkeyPrefix.None`.
### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Legt das `com.aspose.imaging.HotkeyPrefix`-Objekt für dieses `com.aspose.imaging.StringFormat`-Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das `com.aspose.imaging.HotkeyPrefix` Objekt für dieses `com.aspose.imaging.StringFormat` Objekt, standardmäßig ist `F:Aspose.Imaging.HotkeyPrefix.None`. |

### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Ruft die `com.aspose.imaging.StringTrimming`-Aufzählung für dieses `com.aspose.imaging.StringFormat`-Objekt ab.

**Returns:**
int - Eine `com.aspose.imaging.StringTrimming` Aufzählung, die angibt, wie Text, der mit diesem `com.aspose.imaging.StringFormat` Objekt gezeichnet wird, beschnitten wird, wenn er die Ränder des Layoutrechtecks überschreitet.
### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Legt die `com.aspose.imaging.StringTrimming`-Aufzählung für dieses `com.aspose.imaging.StringFormat`-Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Eine `com.aspose.imaging.StringTrimming` Aufzählung, die angibt, wie Text, der mit diesem `com.aspose.imaging.StringFormat` Objekt gezeichnet wird, beschnitten wird, wenn er die Ränder des Layoutrechtecks überschreitet. |

### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Ruft die Methode ab, die für die Ziffernersetzung verwendet wird.

**Returns:**
int - Ein `com.aspose.imaging.StringDigitSubstitute` Aufzählungswert, der festlegt, wie Zeichen in einer Zeichenfolge ersetzt werden, die nicht angezeigt werden können, weil sie von der aktuellen Schriftart nicht unterstützt werden.

Der Setter wurde für die veraltete Methode SetDigitSubstitution eingeführt.
### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Legt die Methode fest, die für die Ziffernersetzung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Ein `com.aspose.imaging.StringDigitSubstitute` Aufzählungswert, der festlegt, wie Zeichen in einer Zeichenfolge ersetzt werden, die nicht angezeigt werden können, weil sie von der aktuellen Schriftart nicht unterstützt werden. |

Der Setter wurde für die veraltete Methode SetDigitSubstitution eingeführt. |

### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Ruft die Sprache ab, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden.

**Returns:**
int - Ein National Language Support (NLS) Sprachbezeichner, der die Sprache identifiziert, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. Sie können die `P:System.Globalization.CultureInfo.LCID` Eigenschaft eines `System.Globalization.CultureInfo` Objekts als NLS-Sprachbezeichner übergeben. Zum Beispiel, nehmen Sie an, Sie erstellen und setzen ein Locale "ar-EG". Wenn Sie `com.aspose.imaging.StringDigitSubstitute.Traditional` an die Methode `com.aspose.imaging.StringFormat.setDigitSubstitution(int)` übergeben, werden arabisch-indische Ziffern zur Anzeigezeit durch westliche Ziffern ersetzt.
### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Legt die Sprache fest, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ein National Language Support (NLS) Sprachbezeichner, der die Sprache identifiziert, die verwendet wird, wenn lokale Ziffern durch westliche Ziffern ersetzt werden. Sie können die `P:System.Globalization.CultureInfo.LCID` Eigenschaft eines `System.Globalization.CultureInfo` Objekts als NLS-Sprachbezeichner übergeben. Zum Beispiel, nehmen Sie an, Sie erstellen und setzen ein Locale "ar-EG". Wenn Sie `com.aspose.imaging.StringDigitSubstitute.Traditional` an die Methode `com.aspose.imaging.StringFormat.setDigitSubstitution(int)` übergeben, werden arabisch-indische Ziffern zur Anzeigezeit durch westliche Ziffern ersetzt. |

### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Ruft die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabstopp ab.

**Returns:**
float - Der erste Tab‑Versatz.

Die Eigenschaft wurde für die entfernte Methode GetTabStops eingeführt.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Ruft ein Array von Abständen zwischen Tabstopps in den durch die Eigenschaft `P:Aspose.Imaging.getGraphics().PageUnit` angegebenen Einheiten ab.

**Returns:**
float[] - Die Tab‑Stopps.

Die Eigenschaft wurde für die entfernte Methode GetTabStops eingeführt.
### getCustomCharIdent() {#getCustomCharIdent--}
```
public PointF getCustomCharIdent()
```


Ruft den benutzerdefinierten Zeichenidentifikator ab.

Wert: Der benutzerdefinierte Zeichen‑Ident.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - the custom character ident.
### setCustomCharIdent(PointF value) {#setCustomCharIdent-com.aspose.imaging.PointF-}
```
public void setCustomCharIdent(PointF value)
```


Legt den benutzerdefinierten Zeichenidentifikator fest.

Wert: Der benutzerdefinierte Zeichen‑Ident.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | der benutzerdefinierte Zeichen‑Ident. |

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Erstellt einen tiefen Klon dieses `com.aspose.imaging.StringFormat`-Objekts.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat) - The deep clone of the current `com.aspose.imaging.StringFormat`.
### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Legt Tabstopps für dieses `com.aspose.imaging.StringFormat`-Objekt fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstTabOffset | float | Die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tab‑Stopp. |
| tabStops | float[] | Ein Array von Abständen zwischen Tab‑Stopps in den durch die Eigenschaft `com.aspose.imaging.Graphics.PageUnit` angegebenen Einheiten. |

### toString() {#toString--}
```
public String toString()
```


Konvertiert dieses `com.aspose.imaging.StringFormat`-Objekt in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Eine Zeichenkettenrepräsentation dieses `com.aspose.imaging.StringFormat`-Objekts.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
