---
title: "EmfGradientFill"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_GRADIENTFILL-posten specificerar fyllning av rektanglar eller trianglar med färggradienter."
type: docs
weight: 65
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

Den EMR_GRADIENTFILL-posten specificerar fyllning av rektanglar eller trianglar med färggradienter.

En EMR\_GRADIENTFILL-post som specificerar att de tre hörnen i en triangel SKALL fylla figuren med mjuka färggradienter.[85] En EMR\_GRADIENTFILL-post som specificerar att de övre vänstra och nedre högra hörnen i en rektangel SKALL fylla figuren med mjuka färggradienter. Det finns två gradientfyllningslägen i GradientFill‑enumerationen som kan användas vid ritning av en rektangel. I läget GRADIENT\_FILL\_RECT\_H fylls rektangeln från vänster till höger. I läget GRADIENT\_FILL\_RECT\_V fylls rektangeln från topp till botten. Obs! En EMR\_GRADIENTFILL-post MÅSTE ignorera Alpha‑fälten i TriVertex‑objekten. En EMR\_ALPHABLEND-post (avsnitt 2.3.1.1) som omedelbart följer EMR\_GRADIENTFILL-posten kan användas för att applicera en alfa‑transparensgradient på det fyllda området.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfGradientFill`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar en omgivande rektangel, i inklusiva‑inklusiva enhetsenheter. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar en omgivande rektangel, i inklusiva‑inklusiva enhetsenheter. |
| [getNVer()](#getNVer--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet hörn. |
| [setNVer(int value)](#setNVer-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet hörn. |
| [getNTri()](#getNTri--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet rektanglar eller trianglar att fylla. |
| [setNTri(int value)](#setNTri-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet rektanglar eller trianglar att fylla. |
| [getUlMode()](#getUlMode--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar gradientfyllningsläget. |
| [setUlMode(int value)](#setUlMode-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar gradientfyllningsläget. |
| [getVertexData()](#getVertexData--) | Hämtar eller anger objekt som specificerar hörnen för antingen rektanglar eller trianglar samt färgerna som motsvarar dem. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Hämtar eller anger objekt som specificerar hörnen för antingen rektanglar eller trianglar samt färgerna som motsvarar dem. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


Initierar en ny instans av klassen `EmfGradientFill`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar en omgivande rektangel, i inklusiva‑inklusiva enhetsenheter.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar en omgivande rektangel, i inklusiva‑inklusiva enhetsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet hörn.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet hörn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet rektanglar eller trianglar att fylla.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet rektanglar eller trianglar att fylla.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar gradientfyllnadsläget. Värdet MÅSTE finnas i GradientFill‑enumerationen (avsnitt 2.1.15).

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar gradientfyllnadsläget. Värdet MÅSTE finnas i GradientFill‑enumerationen (avsnitt 2.1.15).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Hämtar eller anger objekt som specificerar hörnen för antingen rektanglar eller trianglar samt färgerna som motsvarar dem.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Hämtar eller anger objekt som specificerar hörnen för antingen rektanglar eller trianglar samt färgerna som motsvarar dem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

