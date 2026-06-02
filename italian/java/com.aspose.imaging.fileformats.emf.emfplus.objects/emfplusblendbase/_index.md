---
title: "EmfPlusBlendBase"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Oggetto base per oggetti di fusione"
type: docs
weight: 16
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Oggetto base per oggetti di fusione
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Ottiene o imposta le posizioni di fusione, un array di valori a virgola mobile a 32 bit PositionCount che specificano le proporzioni della distanza lungo la linea del gradiente. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Ottiene o imposta le posizioni di fusione, un array di valori a virgola mobile a 32 bit PositionCount che specificano le proporzioni della distanza lungo la linea del gradiente. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Ottiene o imposta le posizioni di fusione, un array di valori a virgola mobile a 32 bit PositionCount che specificano le proporzioni della distanza lungo la linea del gradiente. Ogni elemento DEVE essere un numero compreso tra 0.0 e 1.0 inclusi. Per un pennello a gradiente lineare, 0.0 rappresenta il punto iniziale e 1.0 rappresenta il punto finale. Per un pennello a gradiente di percorso, 0.0 rappresenta il punto medio e 1.0 rappresenta un punto finale.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Ottiene o imposta le posizioni di fusione, un array di valori a virgola mobile a 32 bit PositionCount che specificano le proporzioni della distanza lungo la linea del gradiente. Ogni elemento DEVE essere un numero compreso tra 0.0 e 1.0 inclusi. Per un pennello a gradiente lineare, 0.0 rappresenta il punto iniziale e 1.0 rappresenta il punto finale. Per un pennello a gradiente di percorso, 0.0 rappresenta il punto medio e 1.0 rappresenta un punto finale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] |  |

