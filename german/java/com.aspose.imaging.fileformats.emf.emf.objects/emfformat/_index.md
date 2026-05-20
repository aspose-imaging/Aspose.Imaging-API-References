---
title: "EmfFormat"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmrFormat-Objekt enthält Informationen, die das Format von Bilddaten in einem EMR_COMMENT_MULTIFORMATS‑Datensatzabschnitt 2.3.3.4.3 identifizieren."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

Das EmrFormat‑Objekt enthält Informationen, die das Format von Bilddaten in einem EMR\_COMMENT\_MULTIFORMATS‑Datensatz (Abschnitt 2.3.3.4.3) identifizieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSignature()](#getSignature--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die das Format der Bilddaten angibt. |
| [setSignature(int value)](#setSignature-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die das Format der Bilddaten angibt. |
| [getVersion()](#getVersion--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Versionsnummer des Formats angibt. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Versionsnummer des Formats angibt. |
| [getSizeData()](#getSizeData--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Daten in Bytes angibt. |
| [setSizeData(int value)](#setSizeData-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Daten in Bytes angibt. |
| [getOffData()](#getOffData--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zu den Daten vom Beginn des Identifikatorfeldes in einem EMR\_COMMENT\_PUBLIC‑Datensatz (Abschnitt 2.3.3.4) angibt. |
| [setOffData(int value)](#setOffData-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zu den Daten vom Beginn des Identifikatorfeldes in einem EMR\_COMMENT\_PUBLIC‑Datensatz (Abschnitt 2.3.3.4) angibt. |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die das Format der Bilddaten angibt. Dieser Wert MUSS in der FormatSignature‑Aufzählung (Abschnitt 2.1.14) enthalten sein.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die das Format der Bilddaten angibt. Dieser Wert MUSS in der FormatSignature‑Aufzählung (Abschnitt 2.1.14) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Versionsnummer des Formats angibt. Wenn das Signaturfeld encapsulated PostScript (EPS) angibt, MUSS dieser Wert 0x00000001 sein; andernfalls MUSS dieser Wert ignoriert werden.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Versionsnummer des Formats angibt. Wenn das Signaturfeld encapsulated PostScript (EPS) angibt, MUSS dieser Wert 0x00000001 sein; andernfalls MUSS dieser Wert ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Daten in Bytes angibt.

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe der Daten in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zu den Daten vom Beginn des Identifikatorfeldes in einem EMR\_COMMENT\_PUBLIC‑Datensatz (Abschnitt 2.3.3.4) angibt. Der Offset MUSS 32‑Bit‑ausgerichtet sein.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Offset zu den Daten vom Beginn des Identifikatorfeldes in einem EMR\_COMMENT\_PUBLIC‑Datensatz (Abschnitt 2.3.3.4) angibt. Der Offset MUSS 32‑Bit‑ausgerichtet sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

