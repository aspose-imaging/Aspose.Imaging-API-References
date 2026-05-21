---
title: "EmfPlusPath"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusPath-objektet specificerar en serie av linje- och kurvsegment som bildar en grafikväg."
type: docs
weight: 58
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

EmfPlusPath-objektet specificerar en serie av linje- och kurvsegment som bildar en grafikbana. Ordningen för Bezier-datapunkter är startpunkt, kontrollpunkt 1, kontrollpunkt 2 och slutpunkt. För mer information, se [MSDN - DrawBeziers].
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Hämtar eller anger Path-punkternas antal, ett 32-bitars osignerat heltal som specificerar hur punkterna och tillhörande puntktyper som definieras av detta objekt ska tolkas. |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Hämtar eller anger Path-punkternas antal, ett 32-bitars osignerat heltal som specificerar hur punkterna och tillhörande puntktyper som definieras av detta objekt ska tolkas. |
| [getPathPoints()](#getPathPoints--) | Hämtar eller anger en matris av path-punkter. En matris med PathPointCount-punkter som specificerar banan. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Hämtar eller anger en matris av path-punkter. En matris med PathPointCount-punkter som specificerar banan. |
| [getPathPointTypes()](#getPathPointTypes--) | Hämtar eller anger en matris som specificerar hur punkterna i PathPoints-fältet används för att rita banan. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | Hämtar eller anger en matris som specificerar hur punkterna i PathPoints-fältet används för att rita banan. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Hämtar eller anger Path-punkternas antal, ett 32-bitars osignerat heltal som specificerar hur punkterna och tillhörande puntktyper som definieras av detta objekt ska tolkas.

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Hämtar eller anger Path-punkternas antal, ett 32-bitars osignerat heltal som specificerar hur punkterna och tillhörande puntktyper som definieras av detta objekt ska tolkas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Hämtar eller anger en matris av path-punkter. En matris med PathPointCount-punkter som specificerar banan. Objektens typ i denna matris anges av fältet PathPointFlags, enligt följande: Om P-flaggan är satt, är punkterna relativa positioner som anges av EmfPlusPointR-objekt (avsnitt 2.2.2.37). Om P-flaggan är rensad och C-flaggan är satt, är punkterna absoluta positioner som anges av EmfPlusPoint-objekt (avsnitt 2.2.2.35). Om både P- och C-flaggan är rensade, är punkterna absoluta positioner som anges av EmfPlusPointF-objekt (avsnitt 2.2.2.36).

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Hämtar eller anger en matris av path-punkter. En matris med PathPointCount-punkter som specificerar banan. Objektens typ i denna matris anges av fältet PathPointFlags, enligt följande: Om P-flaggan är satt, är punkterna relativa positioner som anges av EmfPlusPointR-objekt (avsnitt 2.2.2.37). Om P-flaggan är rensad och C-flaggan är satt, är punkterna absoluta positioner som anges av EmfPlusPoint-objekt (avsnitt 2.2.2.35). Om både P- och C-flaggan är rensade, är punkterna absoluta positioner som anges av EmfPlusPointF-objekt (avsnitt 2.2.2.36).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


Hämtar eller anger en matris som specificerar hur punkterna i PathPoints-fältet används för att rita banan. Objektens typ i denna matris anges av R-flaggan i fältet PathPointFlags.

Värde: Sökvägspunkttyperna.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


Hämtar eller anger en matris som specificerar hur punkterna i PathPoints-fältet används för att rita banan. Objektens typ i denna matris anges av R-flaggan i fältet PathPointFlags.

Värde: Sökvägspunkttyperna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

