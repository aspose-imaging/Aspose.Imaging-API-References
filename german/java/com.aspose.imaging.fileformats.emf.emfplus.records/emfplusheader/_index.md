---
title: "EmfPlusHeader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusHeader‑Datensatz gibt den Beginn der EMF‑Daten in der Metadatei an."
type: docs
weight: 40
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

Der EmfPlusHeader-Datensatz gibt den Beginn der EMF+-Daten in der Metadatei an. Der EmfPlusHeader-Datensatz MUSS in einem EMF EMR\_COMMENT\_EMFPLUS-Datensatz eingebettet sein, der DER Datensatz sein MUSS, der unmittelbar auf den EMF-Header in der Metadatei folgt. Der EMR\_COMMENT\_EMFPLUS-Datensatz ist in Abschnitt 2.3.3.2 von [MS-EMF] angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusHeader`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDualMode()](#getDualMode--) | Liest oder setzt einen Wert, der angibt, ob [dual mode] ist. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | Liest oder setzt einen Wert, der angibt, ob [dual mode] ist. |
| [getVideoDisplay()](#getVideoDisplay--) | Liest oder setzt einen Wert, der angibt, ob Videoanzeige. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | Liest oder setzt einen Wert, der angibt, ob Videoanzeige. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | Liest oder setzt die EMF‑plus‑Flags. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | Liest oder setzt die EMF‑plus‑Flags. |
| [getLogicalDpiX()](#getLogicalDpiX--) | Liest oder setzt das logische DPI‑x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | Liest oder setzt das logische DPI‑x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | Liest oder setzt das logische DPI‑y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | Liest oder setzt das logische DPI‑y. |
| [getVersion()](#getVersion--) | Liest oder setzt die Version. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | Liest oder setzt die Version. |
| [isValid()](#isValid--) | Liest einen Wert, der angibt, ob diese Instanz gültig ist. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusHeader`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


Liest oder setzt einen Wert, der angibt, ob [dual mode] ist. Ist er gesetzt, zeigt dieses Flag an, dass diese Metadatei \"dual-mode\" ist, was bedeutet, dass sie zwei Sätze von Datensätzen enthält, von denen jeder den Grafikinhalt vollständig spezifiziert. Ist er nicht gesetzt, wird der Grafikinhalt durch EMF+-Datensätze und ggf. EMF-Datensätze, die einem EmfPlusGetDC-Datensatz vorausgehen, angegeben. Ist dieses Flag gesetzt, sollten allein EMF-Datensätze ausreichen, um den Grafikinhalt zu definieren. Hinweis: Unabhängig davon, ob das \"dual-mode\"‑Flag gesetzt ist oder nicht, sind einige EMF-Datensätze immer vorhanden, nämlich EMF‑Steuerdatensätze und die EMF‑Datensätze, die EMF+-Datensätze enthalten. EMF‑Steuerdatensätze sind in Abschnitt 2.3.4 von [MS-EMF] angegeben.

Wert: `true`, wenn [dual mode]; andernfalls `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [dual mode] ist. Ist er gesetzt, zeigt dieses Flag an, dass diese Metadatei \"dual-mode\" ist, was bedeutet, dass sie zwei Sätze von Datensätzen enthält, von denen jeder den Grafikinhalt vollständig spezifiziert. Ist er nicht gesetzt, wird der Grafikinhalt durch EMF+-Datensätze und ggf. EMF-Datensätze, die einem EmfPlusGetDC-Datensatz vorausgehen, angegeben. Ist dieses Flag gesetzt, sollten allein EMF-Datensätze ausreichen, um den Grafikinhalt zu definieren. Hinweis: Unabhängig davon, ob das \"dual-mode\"‑Flag gesetzt ist oder nicht, sind einige EMF-Datensätze immer vorhanden, nämlich EMF‑Steuerdatensätze und die EMF‑Datensätze, die EMF+-Datensätze enthalten. EMF‑Steuerdatensätze sind in Abschnitt 2.3.4 von [MS-EMF] angegeben.

Wert: `true`, wenn [dual mode]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


Liest oder setzt einen Wert, der angibt, ob Videoanzeige. Ist er gesetzt, zeigt dieses Flag an, dass die Metadatei mit einem Referenzgeräte‑Kontext für eine Videoanzeige aufgezeichnet wurde. Ist er nicht gesetzt, wurde die Metadatei mit einem Referenzgeräte‑Kontext für einen Drucker aufgezeichnet.

Wert: `true`, wenn [video display]; andernfalls `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Videoanzeige. Ist er gesetzt, zeigt dieses Flag an, dass die Metadatei mit einem Referenzgeräte‑Kontext für eine Videoanzeige aufgezeichnet wurde. Ist er nicht gesetzt, wurde die Metadatei mit einem Referenzgeräte‑Kontext für einen Drucker aufgezeichnet.

Wert: `true`, wenn [video display]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


Liest oder setzt die EMF‑plus‑Flags. Ein 32‑Bit‑vorzeichenloser Integer, der Informationen darüber enthält, wie diese Metadatei aufgezeichnet wurde. Ist das 31. Bit des Feldes gesetzt, zeigt dieses Flag an, dass die Metadatei mit einem Referenzgeräte‑Kontext für eine Videoanzeige aufgezeichnet wurde. Ist es nicht gesetzt, wurde die Metadatei mit einem Referenzgeräte‑Kontext für einen Drucker aufgezeichnet.

Wert: Die EMF‑plus‑Flags.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


Liest oder setzt die EMF‑plus‑Flags. Ein 32‑Bit‑vorzeichenloser Integer, der Informationen darüber enthält, wie diese Metadatei aufgezeichnet wurde. Ist das 31. Bit des Feldes gesetzt, zeigt dieses Flag an, dass die Metadatei mit einem Referenzgeräte‑Kontext für eine Videoanzeige aufgezeichnet wurde. Ist es nicht gesetzt, wurde die Metadatei mit einem Referenzgeräte‑Kontext für einen Drucker aufgezeichnet.

Wert: Die EMF‑plus‑Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


Liest oder setzt das logische DPI‑x. Ein 32‑Bit‑vorzeichenloser Integer, der die horizontale Auflösung angibt, für die die Metadatei aufgezeichnet wurde, in Pixel pro Zoll.

Wert: Das logische DPI‑x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


Liest oder setzt das logische DPI‑x. Ein 32‑Bit‑vorzeichenloser Integer, der die horizontale Auflösung angibt, für die die Metadatei aufgezeichnet wurde, in Pixel pro Zoll.

Wert: Das logische DPI‑x.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


Liest oder setzt das logische DPI‑y. Ein 32‑Bit‑vorzeichenloser Integer, der die vertikale Auflösung angibt, für die die Metadatei aufgezeichnet wurde, in Zeilen pro Zoll.

Wert: Das logische DPI‑y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


Liest oder setzt das logische DPI‑y. Ein 32‑Bit‑vorzeichenloser Integer, der die vertikale Auflösung angibt, für die die Metadatei aufgezeichnet wurde, in Zeilen pro Zoll.

Wert: Das logische DPI‑y.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


Liest oder setzt die Version. Ein EmfPlusGraphicsVersion‑Objekt (Abschnitt 2.2.2.19), das die Version der Betriebssystemgrafik angibt, die zur Erstellung dieser Metadatei verwendet wurde.

Wert: Die Version.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


Liest oder setzt die Version. Ein EmfPlusGraphicsVersion‑Objekt (Abschnitt 2.2.2.19), das die Version der Betriebssystemgrafik angibt, die zur Erstellung dieser Metadatei verwendet wurde.

Wert: Die Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


Liest einen Wert, der angibt, ob diese Instanz gültig ist.

Wert: `true`, wenn diese Instanz gültig ist; andernfalls `false`.

**Returns:**
boolean
