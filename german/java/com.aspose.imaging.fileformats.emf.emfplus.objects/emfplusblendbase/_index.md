---
title: "EmfPlusBlendBase"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Basisobjekt für Blend-Objekte"
type: docs
weight: 16
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Basisobjekt für Blend-Objekte
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Liest oder setzt Blendpositionen. Ein Array von PositionCount 32‑Bit-Gleitkommawerten, das die Proportionen der Distanz entlang der Verlaufs­linie angibt. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Liest oder setzt Blendpositionen. Ein Array von PositionCount 32‑Bit-Gleitkommawerten, das die Proportionen der Distanz entlang der Verlaufs­linie angibt. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Liest oder setzt Blendpositionen. Ein Array von PositionCount 32‑Bit-Gleitkommawerten, das die Proportionen der Distanz entlang der Verlaufs­linie angibt. Jedes Element MUSS eine Zahl zwischen 0,0 und 1,0 (einschließlich) sein. Für einen linearen Verlaufs‑Pinsel stellt 0,0 den Startpunkt und 1,0 den Endpunkt dar. Für einen Pfad‑Verlaufs‑Pinsel stellt 0,0 den Mittelpunkt und 1,0 einen Endpunkt dar.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Liest oder setzt Blendpositionen. Ein Array von PositionCount 32‑Bit-Gleitkommawerten, das die Proportionen der Distanz entlang der Verlaufs­linie angibt. Jedes Element MUSS eine Zahl zwischen 0,0 und 1,0 (einschließlich) sein. Für einen linearen Verlaufs‑Pinsel stellt 0,0 den Startpunkt und 1,0 den Endpunkt dar. Für einen Pfad‑Verlaufs‑Pinsel stellt 0,0 den Mittelpunkt und 1,0 einen Endpunkt dar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] |  |

