---
title: "EmfCreateColorSpace"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CREATECOLORSPACE-Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem Namen, der aus ASCII-Zeichen besteht."
type: docs
weight: 36
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

Der EMR\_CREATECOLORSPACE-Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem Namen, der aus ASCII‑Zeichen besteht.

Das durch diesen Datensatz definierte logische Farbraumobjekt kann in den Wiedergabegeräte-Kontext durch einen EMR\_SETCOLORSPACE-Datensatz (Abschnitt 2.3.8.7) ausgewählt werden, der den logischen Farbraum für nachfolgende Grafikoperationen definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCreateColorSpace`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhCS()](#getIhCS--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Farbraumobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhCS(int value)](#setIhCS-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Farbraumobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getLcs()](#getLcs--) | Liest oder setzt ein WMF LogColorSpace-Objekt ([MS-WMF] Abschnitt 2.2.2.11), das den Namen eines Farbprofils in ASCII‑Zeichen angeben kann. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | Liest oder setzt ein WMF LogColorSpace-Objekt ([MS-WMF] Abschnitt 2.2.2.11), das den Namen eines Farbprofils in ASCII‑Zeichen angeben kann. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCreateColorSpace`-Klasse.

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
public WmfLogColorSpace getLcs()
```


Liest oder setzt ein WMF LogColorSpace-Objekt ([MS-WMF] Abschnitt 2.2.2.11), das den Namen eines Farbprofils in ASCII‑Zeichen angeben kann.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


Liest oder setzt ein WMF LogColorSpace-Objekt ([MS-WMF] Abschnitt 2.2.2.11), das den Namen eines Farbprofils in ASCII‑Zeichen angeben kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

