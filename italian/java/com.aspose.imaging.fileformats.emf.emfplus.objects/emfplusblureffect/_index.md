---
title: "EmfPlusBlurEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto BlurEffect specifica una diminuzione della differenza di intensità tra i pixel in un'immagine."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto BlurEffect specifica una diminuzione della differenza di intensità tra i pixel in un'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di sfocatura in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di sfocatura in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. |
| [getExpandEdge()](#getExpandEdge--) | Ottiene o imposta un valore Boolean a 32 bit che specifica se il bitmap si espande di una quantità pari al valore di BlurRadius per produrre bordi morbidi. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | Ottiene o imposta un valore Boolean a 32 bit che specifica se il bitmap si espande di una quantità pari al valore di BlurRadius per produrre bordi morbidi. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di sfocatura in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. Questo valore MUST essere nell'intervallo da 0,0 a 255,0.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di sfocatura in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. Questo valore MUST essere nell'intervallo da 0,0 a 255,0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


Ottiene o imposta un valore Boolean a 32 bit che specifica se il bitmap si espande di una quantità pari al valore di BlurRadius per produrre bordi morbidi. Questo valore MUST essere uno dei seguenti: FALSE 0x00000000 La dimensione del bitmap NON DEVE cambiare, e i suoi bordi morbidi SHOULD be clipped to the size of the BlurRadius. TRUE 0x00000001 La dimensione del bitmap SHOULD expand by an amount equal to the BlurRadius to produce soft edges.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


Ottiene o imposta un valore Boolean a 32 bit che specifica se il bitmap si espande di una quantità pari al valore di BlurRadius per produrre bordi morbidi. Questo valore MUST essere uno dei seguenti: FALSE 0x00000000 La dimensione del bitmap NON DEVE cambiare, e i suoi bordi morbidi SHOULD be clipped to the size of the BlurRadius. TRUE 0x00000001 La dimensione del bitmap SHOULD expand by an amount equal to the BlurRadius to produce soft edges.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

