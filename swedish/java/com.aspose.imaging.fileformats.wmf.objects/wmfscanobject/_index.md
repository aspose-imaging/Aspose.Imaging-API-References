---
title: "WmfScanObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "Scan-objektet specificerar en samling av scanlinjer."
type: docs
weight: 69
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

Scan-objektet specificerar en samling av scanlinjer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar eller anger antalet. |
| [setCount(int value)](#setCount-int-) | Hämtar eller anger antalet. |
| [getTop()](#getTop--) | Hämtar eller anger toppen. |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger toppen. |
| [getBottom()](#getBottom--) | Hämtar eller anger botten. |
| [setBottom(int value)](#setBottom-int-) | Hämtar eller anger botten. |
| [getScanLines()](#getScanLines--) | Hämtar eller anger scan‑linjerna. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | Hämtar eller anger scan‑linjerna. |
| [getCount2()](#getCount2--) | Hämtar eller anger count2. |
| [setCount2(int value)](#setCount2-int-) | Hämtar eller anger count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


Hämtar eller anger antalet.

Värde: Antalet horisontella (x‑axel) koordinater i `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`‑arrayen. Detta värde MÅSTE vara ett multipel av 2, eftersom vänstra och högra ändpunkterna krävs för att specificera varje scan‑linje.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Hämtar eller anger antalet.

Värde: Antalet horisontella (x‑axel) koordinater i `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`‑arrayen. Detta värde MÅSTE vara ett multipel av 2, eftersom vänstra och högra ändpunkterna krävs för att specificera varje scan‑linje.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Hämtar eller anger toppen.

Värde: Den vertikala (y‑axel) koordinaten, i logiska enheter, för den övre scan‑linjen.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Hämtar eller anger toppen.

Värde: Den vertikala (y‑axel) koordinaten, i logiska enheter, för den övre scan‑linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Hämtar eller anger botten.

Värde: Den vertikala (y‑axel) koordinaten, i logiska enheter, för den nedre scan‑linjen.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Hämtar eller anger botten.

Värde: Den vertikala (y‑axel) koordinaten, i logiska enheter, för den nedre scan‑linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


Hämtar eller anger scan‑linjerna.

Värde: En array av scan‑linjer, där varje specificeras av vänstra och högra horisontella (x‑axel) koordinater för dess ändpunkter.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


Hämtar eller anger scan‑linjerna.

Värde: En array av scan‑linjer, där varje specificeras av vänstra och högra horisontella (x‑axel) koordinater för dess ändpunkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


Hämtar eller anger count2.

Värde: Samma som värdet i fältet `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; det finns för att möjliggöra uppåtgående navigering i strukturen.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


Hämtar eller anger count2.

Värde: Samma som värdet i fältet `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`; det finns för att möjliggöra uppåtgående navigering i strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

