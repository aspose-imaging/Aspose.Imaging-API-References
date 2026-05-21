---
title: "EmfPlusHatchBrushData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusHatchBrushData-objektet specificerar ett hatch-mönster för en grafikpensel."
type: docs
weight: 45
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

EmfPlusHatchBrushData-objektet specificerar ett hatch-mönster för en grafikpensel.

Grafikpenslar specificeras av `EmfPlusBrush`‑objekt (avsnitt 2.2.1.1). En hatch‑penna målar en bakgrund och ritar ett mönster av linjer, punkter, streck, fyrkanter och korshatch‑linjer över denna bakgrund. Hatch‑pennan definierar två färger: en för bakgrunden och en för mönstret över bakgrunden. Färgen på bakgrunden kallas bakgrundsfärg, och färgen på mönstret kallas förgrundsfärg.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att måla bakgrunden av hatch‑mönstret. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att måla bakgrunden av hatch‑mönstret. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att rita linjerna i hatch‑mönstret. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att rita linjerna i hatch‑mönstret. |
| [getHatchStyle()](#getHatchStyle--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar penselns hatch‑stil. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar penselns hatch‑stil. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att måla bakgrunden av hatch‑mönstret.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att måla bakgrunden av hatch‑mönstret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att rita linjerna i hatch‑mönstret.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Hämtar eller anger ett 32‑bitars EmfPlusArgb‑objekt som specificerar färgen som används för att rita linjerna i hatch‑mönstret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar penselns hatch‑stil. Det MÅSTE vara definierat i `EmfPlusHatchStyle`‑enumerationen.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar penselns hatch‑stil. Det MÅSTE vara definierat i `EmfPlusHatchStyle`‑enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

