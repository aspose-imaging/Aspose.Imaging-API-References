---
title: "EmfVertexData"
second_title: "Aspose.Imaging för Java API-referens"
description: "Objekt som specificerar hörnen för antingen rektanglar eller trianglar samt de färger som motsvarar dem."
type: docs
weight: 155
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Objekt som specificerar hörnen för antingen rektanglar eller trianglar samt de färger som motsvarar dem.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | Hämtar eller anger en array av nVer TriVertex-objekt (avsnitt 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | Hämtar eller anger en array av nVer TriVertex-objekt (avsnitt 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | Hämtar eller anger en array av nTri GradientRectangle-objekt (avsnitt 2.2.7) eller GradientTriangle-objekt (avsnitt 2.2.8), beroende på värdet i ulMode-fältet. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | Hämtar eller anger en array av nTri GradientRectangle-objekt (avsnitt 2.2.7) eller GradientTriangle-objekt (avsnitt 2.2.8), beroende på värdet i ulMode-fältet. |
| [getVertexPadding()](#getVertexPadding--) | Hämtar eller anger en valfri variabel‑längd array av nTri gånger fyra byte som MÅSTE finnas om värdet i ulMode-fältet indikerar GradientRectangle-objekt (avsnitt 2.2.7). |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | Hämtar eller anger en valfri variabel‑längd array av nTri gånger fyra byte som MÅSTE finnas om värdet i ulMode-fältet indikerar GradientRectangle-objekt (avsnitt 2.2.7). |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


Hämtar eller anger en array av nVer TriVertex-objekt (avsnitt 2.2.26). Varje objekt specificerar positionen och färgen på en vertex av antingen en rektangel eller en triangel, beroende på värdet i ulMode-fältet.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


Hämtar eller anger en array av nVer TriVertex-objekt (avsnitt 2.2.26). Varje objekt specificerar positionen och färgen på en vertex av antingen en rektangel eller en triangel, beroende på värdet i ulMode-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


Hämtar eller anger en array av nTri GradientRectangle-objekt (avsnitt 2.2.7) eller GradientTriangle-objekt (avsnitt 2.2.8), beroende på värdet i ulMode-fältet. Varje objekt specificerar index i arrayen av TriVertex-objekt i VertexObjects-fältet.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


Hämtar eller anger en array av nTri GradientRectangle-objekt (avsnitt 2.2.7) eller GradientTriangle-objekt (avsnitt 2.2.8), beroende på värdet i ulMode-fältet. Varje objekt specificerar index i arrayen av TriVertex-objekt i VertexObjects-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


Hämtar eller anger en valfri variabel‑längd array av nTri gånger fyra byte som MÅSTE finnas om värdet i ulMode-fältet indikerar GradientRectangle-objekt (avsnitt 2.2.7). Om värdet i ulMode-fältet indikerar GradientTriangle-objekt (avsnitt 2.2.8) finns ingen VertexPadding. Detta fält MÅSTE ignoreras.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


Hämtar eller anger en valfri variabel‑längd array av nTri gånger fyra byte som MÅSTE finnas om värdet i ulMode-fältet indikerar GradientRectangle-objekt (avsnitt 2.2.7). Om värdet i ulMode-fältet indikerar GradientTriangle-objekt (avsnitt 2.2.8) finns ingen VertexPadding. Detta fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

