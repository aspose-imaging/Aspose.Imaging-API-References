---
title: "EmfLogFontPanose"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das LogFontPanose‑Objekt gibt die PANOSE‑Merkmale einer logischen Schrift an."
type: docs
weight: 25
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

Das LogFontPanose‑Objekt gibt die PANOSE‑Merkmale einer logischen Schrift an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Initialisiert eine neue Instanz der `EmfLogFontPanose`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFullName()](#getFullName--) | Liest oder setzt eine Zeichenkette aus 64 Unicode‑Zeichen, die den vollständigen Namen der Schrift definiert. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Liest oder setzt eine Zeichenkette aus 64 Unicode‑Zeichen, die den vollständigen Namen der Schrift definiert. |
| [getStyle()](#getStyle--) | Liest oder setzt eine Zeichenkette von 32 Unicode‑Zeichen, die den Stil der Schriftart definiert. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Liest oder setzt eine Zeichenkette von 32 Unicode‑Zeichen, die den Stil der Schriftart definiert. |
| [getVersion()](#getVersion--) | Liest oder setzt Dieses Feld MUSS ignoriert werden. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt Dieses Feld MUSS ignoriert werden. |
| [getStyleSize()](#getStyleSize--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Punktgröße angibt, bei der Font‑Hinting durchgeführt wird. |
| [setStyleSize(int value)](#setStyleSize-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Punktgröße angibt, bei der Font‑Hinting durchgeführt wird. |
| [getMatch()](#getMatch--) | Liest oder setzt Dieses Feld MUSS ignoriert werden. |
| [setMatch(int value)](#setMatch-int-) | Liest oder setzt Dieses Feld MUSS ignoriert werden. |
| [getVendorId()](#getVendorId--) | Liest oder setzt Dieses Feld MUSS ignoriert werden. |
| [setVendorId(int value)](#setVendorId-int-) | Liest oder setzt Dieses Feld MUSS ignoriert werden. |
| [getCulture()](#getCulture--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF NULL gesetzt werden MUSS und die IGNORIERT werden MUSS. |
| [setCulture(int value)](#setCulture-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF NULL gesetzt werden MUSS und die IGNORIERT werden MUSS. |
| [getPanose()](#getPanose--) | Liest oder setzt ein Panose‑Objekt (Abschnitt 2.2.21), das die PANOSE‑Merkmale der logischen Schrift definiert. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Liest oder setzt ein Panose‑Objekt (Abschnitt 2.2.21), das die PANOSE‑Merkmale der logischen Schrift definiert. |
| [getPadding()](#getPadding--) | Liest oder setzt ein Feld, das nur zur Sicherstellung der 32‑Bit‑Ausrichtung dieser Struktur existiert. |
| [setPadding(short value)](#setPadding-short-) | Liest oder setzt ein Feld, das nur zur Sicherstellung der 32‑Bit‑Ausrichtung dieser Struktur existiert. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


Initialisiert eine neue Instanz der `EmfLogFontPanose`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | Die Basis‑Log‑Schrift. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Liest oder setzt eine Zeichenkette aus 64 Unicode‑Zeichen, die den vollständigen Namen der Schrift definiert. Ist die Länge dieser Zeichenkette kürzer als 64 Zeichen, MUSS ein abschließendes NULL‑Zeichen vorhanden sein, wonach der Rest dieses Feldes IGNORIERT werden MUSS.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Liest oder setzt eine Zeichenkette aus 64 Unicode‑Zeichen, die den vollständigen Namen der Schrift definiert. Ist die Länge dieser Zeichenkette kürzer als 64 Zeichen, MUSS ein abschließendes NULL‑Zeichen vorhanden sein, wonach der Rest dieses Feldes IGNORIERT werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Liest oder setzt eine Zeichenkette von 32 Unicode‑Zeichen, die den Stil der Schriftart definiert. Ist die Länge dieser Zeichenkette weniger als 32 Zeichen, MUSS ein abschließendes NULL‑Zeichen vorhanden sein, wonach der Rest dieses Feldes IGNORIERT werden MUSS.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Liest oder setzt eine Zeichenkette von 32 Unicode‑Zeichen, die den Stil der Schriftart definiert. Ist die Länge dieser Zeichenkette weniger als 32 Zeichen, MUSS ein abschließendes NULL‑Zeichen vorhanden sein, wonach der Rest dieses Feldes IGNORIERT werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liest oder setzt Dieses Feld MUSS ignoriert werden.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liest oder setzt Dieses Feld MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Punktgröße angibt, bei der Font‑Hinting durchgeführt wird. Wird sie auf Null gesetzt, erfolgt das Font‑Hinting bei der Punktgröße, die dem Height‑Feld im LogFont‑Objekt im LogFont‑Feld entspricht.

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Punktgröße angibt, bei der Font‑Hinting durchgeführt wird. Wird sie auf Null gesetzt, erfolgt das Font‑Hinting bei der Punktgröße, die dem Height‑Feld im LogFont‑Objekt im LogFont‑Feld entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Liest oder setzt Dieses Feld MUSS ignoriert werden.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Liest oder setzt Dieses Feld MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Liest oder setzt Dieses Feld MUSS ignoriert werden.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Liest oder setzt Dieses Feld MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF NULL gesetzt werden MUSS und die IGNORIERT werden MUSS.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF NULL gesetzt werden MUSS und die IGNORIERT werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Liest oder setzt ein Panose‑Objekt (Abschnitt 2.2.21), das die PANOSE‑Merkmale der logischen Schrift definiert. Sind alle Felder dieses Objekts Null, MUSS es ignoriert werden.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Liest oder setzt ein Panose‑Objekt (Abschnitt 2.2.21), das die PANOSE‑Merkmale der logischen Schrift definiert. Sind alle Felder dieses Objekts Null, MUSS es ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Liest oder setzt ein Feld, das nur zur Sicherstellung der 32‑Bit‑Ausrichtung dieser Struktur existiert. Es MUSS ignoriert werden.

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Liest oder setzt ein Feld, das nur zur Sicherstellung der 32‑Bit‑Ausrichtung dieser Struktur existiert. Es MUSS ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

