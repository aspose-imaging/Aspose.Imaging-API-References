---
title: "EmfColorMatchToTargetW"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_COLORMATCHTOTargetW-Datensatz gibt an, ob eine Farbabstimmung mit einem Farbprofil durchgeführt werden soll, das in einer Datei mit einem Namen aus Unicode‑Zeichen angegeben ist."
type: docs
weight: 24
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

Der EMR\_COLORMATCHTOTargetW-Datensatz gibt an, ob eine Farbabstimmung mit einem Farbprofil durchgeführt werden soll, das in einer Datei mit einem aus Unicode‑Zeichen bestehenden Namen angegeben ist.

Ein EMR\_COLORMATCHTOTargetW-Datensatz kann verwendet werden, um zu steuern, ob die aktuelle Farbtransformation im Wiedergabegeräte‑Kontext angewendet wird. Wenn der dwAction‑Wert CS\_ENABLE ist, ist die Farbabstimmung aktiviert, und die aktuelle Farbtransformation SOLLTE auf nachfolgende Grafikoperationen angewendet werden. Wenn dwAction auf CS\_DISABLE gesetzt ist, SOLLTE die Farbtransformation NICHT angewendet werden. Während die Farbabstimmung zum Ziel durch einen dwAction‑Wert von CS\_ENABLE aktiviert ist, werden Änderungen am Farbraum oder an der Farbumfangsabstimmung nicht angewendet. Diese Änderungen MÜSSEN jedoch wirksam werden, wenn die Farbabstimmung zum Ziel deaktiviert wird. Das dwAction‑Feld SOLLTE NICHT auf CS\_DELETE\_TRANSFORM gesetzt werden, es sei denn, das Farbmanagement wurde bereits mit einem EMR\_SETICMMODE‑Datensatz (Abschnitt 2.3.11.14) aktiviert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfColorMatchToTargetW`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDwAction()](#getDwAction--) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorSpace‑Aufzählung (Abschnitt 2.1.7) angibt. |
| [setDwAction(int value)](#setDwAction-int-) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorSpace‑Aufzählung (Abschnitt 2.1.7) angibt. |
| [getDwFlags()](#getDwFlags--) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorMatchToTarget‑Aufzählung (Abschnitt 2.1.6) angibt. |
| [setDwFlags(int value)](#setDwFlags-int-) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorMatchToTarget‑Aufzählung (Abschnitt 2.1.6) angibt. |
| [getCbName()](#getCbName--) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt. |
| [setCbName(int value)](#setCbName-int-) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt. |
| [getCbData()](#getCbData--) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Größe der Rohdaten des Ziel‑Farbprofils angibt, falls sie im Data‑Feld enthalten ist. |
| [setCbData(int value)](#setCbData-int-) | Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Größe der Rohdaten des Ziel‑Farbprofils angibt, falls sie im Data‑Feld enthalten ist. |
| [getData()](#getData--) | Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt. |
| [getName()](#getName--) | Ruft den Namen ab. |
| [getRawData()](#getRawData--) | Ruft die Rohdaten ab. |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfColorMatchToTargetW`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorSpace‑Aufzählung (Abschnitt 2.1.7) angibt.

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorSpace‑Aufzählung (Abschnitt 2.1.7) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorMatchToTarget‑Aufzählung (Abschnitt 2.1.6) angibt.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der einen Wert aus der ColorMatchToTarget‑Aufzählung (Abschnitt 2.1.6) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Anzahl der Bytes im Unicode‑UTF16‑LE‑Namen des gewünschten Farbprofils angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Größe der Rohdaten des Ziel‑Farbprofils angibt, falls sie im Data‑Feld enthalten ist.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Liest oder setzt eine 32‑Bit‑unsigned‑Integer, der die Größe der Rohdaten des Ziel‑Farbprofils angibt, falls sie im Data‑Feld enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Liest oder setzt ein Array der Größe (cbName + cbData) in Bytes, das den UTF16-LE-Namen und die Rohdaten des gewünschten Farbprofils angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Ruft den Namen ab.

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Ruft die Rohdaten ab.

**Returns:**
byte[]
