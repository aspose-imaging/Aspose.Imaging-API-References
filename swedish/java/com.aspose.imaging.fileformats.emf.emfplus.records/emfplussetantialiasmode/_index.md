---
title: "EmfPlusSetAntiAliasMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusSetAntiAliasMode-posten specificerar anti‑aliasing‑läget för textutmatning."
type: docs
weight: 54
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

Den EmfPlusSetAntiAliasMode-posten specificerar anti‑aliasing‑läget för textutmatning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSetAntiAliasMode`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Hämtar eller anger jämningsläget. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Hämtar eller anger jämningsläget. |
| [getAntiAliasing()](#getAntiAliasing--) | Hämtar eller anger ett värde som indikerar om [anti aliasing]. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Hämtar eller anger ett värde som indikerar om [anti aliasing]. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSetAntiAliasMode`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Hämtar eller anger jämningsläget. (7 bitar): Värdet för jämningsläget, från SmoothingMode‑enumerationen (avsnitt 2.1.1.28).

Värde: Jämningsläget.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Hämtar eller anger jämningsläget. (7 bitar): Värdet för jämningsläget, från SmoothingMode‑enumerationen (avsnitt 2.1.1.28).

Värde: Jämningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Hämtar eller anger ett värde som indikerar om [anti aliasing]. Om satt ska anti-aliasing UTFÖRAS. Om rensat ska anti-aliasing INTE UTFÖRAS.

Värde: `true` om [anti aliasing]; annars `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Hämtar eller anger ett värde som indikerar om [anti aliasing]. Om satt ska anti-aliasing UTFÖRAS. Om rensat ska anti-aliasing INTE UTFÖRAS.

Värde: `true` om [anti aliasing]; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

