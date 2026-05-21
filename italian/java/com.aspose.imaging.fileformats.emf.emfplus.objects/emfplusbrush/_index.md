---
title: "EmfPlusBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusBrush specifica un pennello grafico per riempire le regioni."
type: docs
weight: 24
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

L'oggetto EmfPlusBrush specifica un pennello grafico per riempire le regioni.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrushData()](#getBrushData--) | Ottiene o imposta i dati del Brush, dati a lunghezza variabile che definiscono l'oggetto brush specificato nel campo Type. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Ottiene o imposta i dati del Brush, dati a lunghezza variabile che definiscono l'oggetto brush specificato nel campo Type. |
| [getType()](#getType--) | Ottiene o imposta il tipo. |
| [setType(int value)](#setType-int-) | Ottiene o imposta il tipo. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Ottiene o imposta i dati del Brush, dati a lunghezza variabile che definiscono l'oggetto brush specificato nel campo Type. Il contenuto e il formato dei dati possono variare per ogni tipo di brush. EmfPlusHatchBrushData (sezione 2.2.2.20) (completato) EmfPlusLinearGradientBrushData object (sezione 2.2.2.24) (completato) EmfPlusPathGradientBrushData object (sezione 2.2.2.29) (completato) EmfPlusSolidBrushData object (sezione 2.2.2.43) (completato) EmfPlusTextureBrushData object (sezione 2.2.2.45) (completato)

Valore: I dati del brush.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Ottiene o imposta i dati del Brush, dati a lunghezza variabile che definiscono l'oggetto brush specificato nel campo Type. Il contenuto e il formato dei dati possono variare per ogni tipo di brush. EmfPlusHatchBrushData (sezione 2.2.2.20) (completato) EmfPlusLinearGradientBrushData object (sezione 2.2.2.24) (completato) EmfPlusPathGradientBrushData object (sezione 2.2.2.29) (completato) EmfPlusSolidBrushData object (sezione 2.2.2.43) (completato) EmfPlusTextureBrushData object (sezione 2.2.2.45) (completato)

Valore: I dati del brush.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Ottiene o imposta il tipo.

Valore: Un intero senza segno a 32 bit che specifica il tipo di brush, il quale determina il contenuto del campo BrushData. Questo valore DEVE essere definito nell'enumerazione `EmfPlusBrushType`.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Ottiene o imposta il tipo.

Valore: Un intero senza segno a 32 bit che specifica il tipo di brush, il quale determina il contenuto del campo BrushData. Questo valore DEVE essere definito nell'enumerazione `EmfPlusBrushType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

