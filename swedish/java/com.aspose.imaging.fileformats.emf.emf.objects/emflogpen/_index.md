---
title: "EmfLogPen"
second_title: "Aspose.Imaging för Java API-referens"
description: "LogPen-objektet definierar stilbredden och färgen på en logisk penna."
type: docs
weight: 27
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

LogPen-objektet definierar stil, bredd och färg för en logisk penna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PenStyle. |
| [setPenStyle(int value)](#setPenStyle-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PenStyle. |
| [getWidth()](#getWidth--) | Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar pennens bredd enligt värdet i dess x-fält. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar pennens bredd enligt värdet i dess x-fält. |
| [getAffectWidth()](#getAffectWidth--) | Hämtar eller anger bredden på påverkan. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Hämtar eller anger bredden på påverkan. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar pennfärgens värde. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar pennfärgens värde. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PenStyle. Värdet MÅSTE definieras från PenStyle‑enumerationstabellen, specificerad i avsnitt 2.1.25.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar PenStyle. Värdet MÅSTE definieras från PenStyle‑enumerationstabellen, specificerad i avsnitt 2.1.25.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar pennens bredd enligt värdet i dess x-fält. Värdet i dess y-fält MÅSTE ignoreras.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


Hämtar eller anger ett WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar pennens bredd enligt värdet i dess x-fält. Värdet i dess y-fält MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Hämtar eller anger bredden på påverkan.

Värde: Bredden på påverkan.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Hämtar eller anger bredden på påverkan.

Värde: Bredden på påverkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar pennfärgens värde.

Värde: Den 32-bitars ARGB-färgen

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar pennfärgens värde.

Värde: Den 32-bitars ARGB-färgen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

