---
title: "EmfRegionData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das RegionData‑Objekt gibt Daten an, die eine Region definieren, die aus nicht überlappenden Rechtecken besteht."
type: docs
weight: 33
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

Das RegionData‑Objekt gibt Daten an, die eine Region definieren, die aus nicht überlappenden Rechtecken besteht.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Initialisiert eine neue Instanz der `EmfRegionData`-Klasse. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Initialisiert eine neue Instanz der `EmfRegionData`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Ruft ein 256‑Bit‑RegionDataHeader‑Objekt ab, das die folgenden Daten beschreibt. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Legt ein 256‑Bit‑RegionDataHeader‑Objekt fest, das die folgenden Daten beschreibt. |
| [getData()](#getData--) | Ruft ein Array von WMF‑RectL‑Objekten ([MS-WMF] Abschnitt 2.2.2.19) ab; die Objekte werden zusammengeführt, um die Region zu erstellen. |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | Legt ein Array von WMF‑RectL‑Objekten ([MS-WMF] Abschnitt 2.2.2.19) fest; die Objekte werden zusammengeführt, um die Region zu erstellen. |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Initialisiert eine neue Instanz der `EmfRegionData`-Klasse.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Initialisiert eine neue Instanz der `EmfRegionData`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Ruft ein 256‑Bit‑RegionDataHeader‑Objekt ab, das die folgenden Daten beschreibt.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Legt ein 256‑Bit‑RegionDataHeader‑Objekt fest, das die folgenden Daten beschreibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


Ruft ein Array von WMF‑RectL‑Objekten ([MS-WMF] Abschnitt 2.2.2.19) ab; die Objekte werden zusammengeführt, um die Region zu erstellen.

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


Legt ein Array von WMF‑RectL‑Objekten ([MS-WMF] Abschnitt 2.2.2.19) fest; die Objekte werden zusammengeführt, um die Region zu erstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

