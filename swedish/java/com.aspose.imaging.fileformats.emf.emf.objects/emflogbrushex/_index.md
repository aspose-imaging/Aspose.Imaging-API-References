---
title: "EmfLogBrushEx"
second_title: "Aspose.Imaging för Java API-referens"
description: "LogBrushEx-objektet definierar stilfärgen och mönstret för en enhetsoberoende pensel."
type: docs
weight: 21
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

LogBrushEx-objektet definierar stilen, färgen och mönstret för en enhetsoberoende pensel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselstilen. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselstilen. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Hämtar eller anger ett 32-bitars WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar en färg. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Hämtar eller anger ett 32-bitars WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar en färg. |
| [getBrushHatch()](#getBrushHatch--) | Hämtar eller anger ett 32-bitars osignerat fält som innehåller penselns hatch-data. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Hämtar eller anger ett 32-bitars osignerat fält som innehåller penselns hatch-data. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselstilen. Värdet MÅSTE vara en enumeration från WMF BrushStyle enumeration ([MS-WMF] avsnitt 2.1.1.4). Stilvärdena som stöds i denna struktur listas senare i detta avsnitt. BS\_NULL-stilen SKA användas för att specificera en pensel som inte har någon effekt.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselstilen. Värdet MÅSTE vara en enumeration från WMF BrushStyle enumeration ([MS-WMF] avsnitt 2.1.1.4). Stilvärdena som stöds i denna struktur listas senare i detta avsnitt. BS\_NULL-stilen SKA användas för att specificera en pensel som inte har någon effekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Hämtar eller anger ett 32-bitars WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar en färg. Tolkningen av detta fält beror på värdet av BrushStyle, enligt förklaringen i följande tabell.

Värde: Den 32-bitars ARGB-färgen

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Hämtar eller anger ett 32-bitars WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar en färg. Tolkningen av detta fält beror på värdet av BrushStyle, enligt förklaringen i följande tabell.

Värde: Den 32-bitars ARGB-färgen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Hämtar eller anger ett 32-bitars osignerat fält som innehåller penselns hatch-data. Dess tolkning beror på värdet av BrushStyle,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Hämtar eller anger ett 32-bitars osignerat fält som innehåller penselns hatch-data. Dess tolkning beror på värdet av BrushStyle,

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

