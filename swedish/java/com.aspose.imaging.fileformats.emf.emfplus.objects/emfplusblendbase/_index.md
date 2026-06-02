---
title: "EmfPlusBlendBase"
second_title: "Aspose.Imaging för Java API-referens"
description: "Basobjekt för blandningsobjekt."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Basobjekt för blandningsobjekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Hämtar eller anger blandningspositioner En array av PositionCount 32-bitars flyttal som specificerar proportioner av avstånd längs gradientlinjen. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Hämtar eller anger blandningspositioner En array av PositionCount 32-bitars flyttal som specificerar proportioner av avstånd längs gradientlinjen. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Hämtar eller anger blandningspositioner En array av PositionCount 32-bitars flyttal som specificerar proportioner av avstånd längs gradientlinjen. Varje element MÅSTE vara ett tal mellan 0.0 och 1.0 inclusive. För en linjär gradientpensel representerar 0.0 startpunkten och 1.0 slutpunkten. För en bangradientpensel representerar 0.0 mittpunkten och 1.0 ett slutpunkt.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Hämtar eller anger blandningspositioner En array av PositionCount 32-bitars flyttal som specificerar proportioner av avstånd längs gradientlinjen. Varje element MÅSTE vara ett tal mellan 0.0 och 1.0 inclusive. För en linjär gradientpensel representerar 0.0 startpunkten och 1.0 slutpunkten. För en bangradientpensel representerar 0.0 mittpunkten och 1.0 ett slutpunkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] |  |

