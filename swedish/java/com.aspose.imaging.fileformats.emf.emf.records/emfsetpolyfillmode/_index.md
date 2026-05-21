---
title: "EmfSetPolyFillMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETPOLYFILLMODE-posten definierar polygonfyllnadsläget."
type: docs
weight: 136
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

EMR\\_SETPOLYFILLMODE-posten definierar polygonfyllningsläge.

I allmänhet skiljer sig lägena endast i fall där en komplex, överlappande polygon MÅSTE fyllas; till exempel en femsidig polygon som bildar en femspetsig stjärna med en pentagon i mitten. I sådana fall SKA ALTERNATE‑läget fylla varannan innesluten region inom polygonen (stjärnans spetsar), men WINDING‑läget SKA fylla alla regioner (stjärnens spetsar och pentagonen). När fyllnadsläget är ALTERNATE SKA området mellan udda och jämna polygon‑sidor på varje skanningslinje fyllas. Det vill säga, området mellan den första och andra sidan SKA fyllas, och mellan den tredje och fjärde sidan, och så vidare. När fyllnadsläget är WINDING SKA alla regioner som har ett icke‑noll winding‑värde fyllas. Winding‑värdet är antalet gånger en penna som används för att rita polygonen skulle gå runt regionen. Riktningen för varje kant i polygonen är betydelsefull.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | Initierar en ny instans av klassen `EmfSetPolyFillMode`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar polygonfyllnadsläget och MÅSTE finnas i PolygonFillMode (avsnitt 2.1.27) enumerationen. |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar polygonfyllnadsläget och MÅSTE finnas i PolygonFillMode (avsnitt 2.1.27) enumerationen. |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetPolyFillMode`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


Initierar en ny instans av klassen `EmfSetPolyFillMode`.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar polygonfyllnadsläget och MÅSTE finnas i PolygonFillMode (avsnitt 2.1.27) enumerationen.

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar polygonfyllnadsläget och MÅSTE finnas i PolygonFillMode (avsnitt 2.1.27) enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

