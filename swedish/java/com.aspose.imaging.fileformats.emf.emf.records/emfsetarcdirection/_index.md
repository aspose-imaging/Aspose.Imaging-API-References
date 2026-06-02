---
title: "EmfSetArcDirection"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETARCDIRECTION-posten specificerar den ritningsriktning som ska användas för båg- och rektangelutdata."
type: docs
weight: 118
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

EMR\_SETARCDIRECTION-posten specificerar ritningsriktningen som ska användas för båg- och rektangelutdata.

EMR\_SETARCDIRECTION-posten påverkar den riktning i vilken följande poster ritar: - EMR\_ARC (avsnitt 2.3.5.2) - EMR\_ARCTO (avsnitt 2.3.5.3) - EMR\_CHORD (avsnitt 2.3.5.4) - EMR\_ELLIPSE (avsnitt 2.3.5.5) - EMR\_PIE (avsnitt 2.3.5.15) - EMR\_RECTANGLE (avsnitt 2.3.5.34) - EMR\_ROUNDRECT (avsnitt 2.3.5.35)
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetArcDirection`. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Initierar en ny instans av klassen `EmfSetArcDirection`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bågens riktning. |
| [setArcDirection(int value)](#setArcDirection-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bågens riktning. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetArcDirection`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Initierar en ny instans av klassen `EmfSetArcDirection`.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bågens riktning. Värdet MÅSTE finnas i ArcDirection‑enumerationen (avsnitt 2.1.2). Standardriktningen är moturs.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bågens riktning. Värdet MÅSTE finnas i ArcDirection‑enumerationen (avsnitt 2.1.2). Standardriktningen är moturs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

