---
title: "EmfPlusBlendFactors"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusBlendFactors-Objekt gibt Positionen und Faktoren für das Blend‑Muster eines Farbverlaufspinsels an."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
```
public final class EmfPlusBlendFactors extends EmfPlusBlendBase
```

Das EmfPlusBlendFactors-Objekt gibt Positionen und Faktoren für das Blend‑Muster eines Farbverlaufspinsels an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlendFactors()](#getBlendFactors--) | Liest oder setzt ein Array von PositionCount 32‑Bit‑Gleitkommawerten, die die Farbanteile an den im Feld BlendPositions definierten Positionen angeben. |
| [setBlendFactors(float[] value)](#setBlendFactors-float---) | Liest oder setzt ein Array von PositionCount 32‑Bit‑Gleitkommawerten, die die Farbanteile an den im Feld BlendPositions definierten Positionen angeben. |
### EmfPlusBlendFactors() {#EmfPlusBlendFactors--}
```
public EmfPlusBlendFactors()
```


### getBlendFactors() {#getBlendFactors--}
```
public float[] getBlendFactors()
```


Liest oder setzt ein Array von PositionCount 32‑Bit‑Gleitkommawerten, die die Farbanteile an den im Feld BlendPositions definierten Positionen angeben. Jeder Wert MUST eine Zahl zwischen 0,0 und 1,0 (einschließlich) sein.

**Returns:**
float[]
### setBlendFactors(float[] value) {#setBlendFactors-float---}
```
public void setBlendFactors(float[] value)
```


Liest oder setzt ein Array von PositionCount 32‑Bit‑Gleitkommawerten, die die Farbanteile an den im Feld BlendPositions definierten Positionen angeben. Jeder Wert MUST eine Zahl zwischen 0,0 und 1,0 (einschließlich) sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] |  |

