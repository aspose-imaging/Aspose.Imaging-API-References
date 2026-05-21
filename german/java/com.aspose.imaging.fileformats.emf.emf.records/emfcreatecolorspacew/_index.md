---
title: "EmfCreateColorSpaceW"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CREATECOLORSPACEW‑Datensatz erstellt ein logisches Farbraum‑Objekt aus einem Farbprofil, dessen Name aus Unicode‑Zeichen besteht."
type: docs
weight: 37
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

Der EMR\_CREATECOLORSPACEW-Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem Namen, der aus Unicode‑Zeichen besteht.

Das durch diesen Datensatz definierte logische Farbraumobjekt kann in den Wiedergabegeräte-Kontext durch einen EMR\_SETCOLORSPACE-Datensatz (Abschnitt 2.3.8.7) ausgewählt werden, der den logischen Farbraum für nachfolgende Grafikoperationen definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCreateColorSpaceW`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhCS()](#getIhCS--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Farbraumobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhCS(int value)](#setIhCS-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Farbraumobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getLcs()](#getLcs--) | Liest oder setzt ein WMF LogColorSpaceW-Objekt ([MS-WMF] Abschnitt 2.2.2.12), das den Namen eines Farbprofils in Unicode UTF16-LE-Zeichen angeben kann. |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | Liest oder setzt ein WMF LogColorSpaceW-Objekt ([MS-WMF] Abschnitt 2.2.2.12), das den Namen eines Farbprofils in Unicode UTF16-LE-Zeichen angeben kann. |
| [getDwFlags()](#getDwFlags--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Informationen über die Daten in diesem Datensatz liefert. |
| [setDwFlags(int value)](#setDwFlags-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Informationen über die Daten in diesem Datensatz liefert. |
| [getCbData()](#getCbData--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. |
| [setCbData(int value)](#setCbData-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt. |
| [getData()](#getData--) | Liest oder setzt ein optionales Byte‑Array, das Farbprofildaten angibt. |
| [setData(byte[] value)](#setData-byte---) | Liest oder setzt ein optionales Byte‑Array, das Farbprofildaten angibt. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCreateColorSpaceW`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Farbraumobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Farbraumobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


Liest oder setzt ein WMF LogColorSpaceW-Objekt ([MS-WMF] Abschnitt 2.2.2.12), das den Namen eines Farbprofils in Unicode UTF16-LE-Zeichen angeben kann.

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


Liest oder setzt ein WMF LogColorSpaceW-Objekt ([MS-WMF] Abschnitt 2.2.2.12), das den Namen eines Farbprofils in Unicode UTF16-LE-Zeichen angeben kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Informationen über die Daten in diesem Datensatz liefert.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Informationen über die Daten in diesem Datensatz liefert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe des Datenfeldes in Bytes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Liest oder setzt ein optionales Byte‑Array, das Farbprofildaten angibt.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Liest oder setzt ein optionales Byte‑Array, das Farbprofildaten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

