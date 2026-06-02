---
title: "EmfPlusSharpenEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto SharpenEffect specifica un aumento della differenza di intensità tra i pixel di un'immagine."
type: docs
weight: 72
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto SharpenEffect specifica un aumento della differenza di intensità tra i pixel di un'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di nitidezza in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. |
| [setRadius(float value)](#setRadius-float-) | Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di nitidezza in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. |
| [getAmount()](#getAmount--) | Ottiene o imposta un numero a virgola mobile a 32 bit che specifica la differenza di intensità tra un dato pixel e i pixel circostanti. |
| [setAmount(float value)](#setAmount-float-) | Ottiene o imposta un numero a virgola mobile a 32 bit che specifica la differenza di intensità tra un dato pixel e i pixel circostanti. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di nitidezza in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. Man mano che questo valore aumenta, il numero di pixel coinvolti nel calcolo aumenta e la bitmap risultante DEVE diventare più nitida.

Valore: Il raggio.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Ottiene o imposta un numero a virgola mobile a 32 bit che specifica il raggio di nitidezza in pixel, il quale determina il numero di pixel coinvolti nel calcolo del nuovo valore di un dato pixel. Man mano che questo valore aumenta, il numero di pixel coinvolti nel calcolo aumenta e la bitmap risultante DEVE diventare più nitida.

Valore: Il raggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Ottiene o imposta un numero a virgola mobile a 32 bit che specifica la differenza di intensità tra un dato pixel e i pixel circostanti. 0 Specifica che la nitidezza NON DEVE essere eseguita. 0 < valore \\u2264 100 Man mano che questo valore aumenta, la differenza di intensità tra i pixel DEVE aumentare.

Valore: La quantità.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Ottiene o imposta un numero a virgola mobile a 32 bit che specifica la differenza di intensità tra un dato pixel e i pixel circostanti. 0 Specifica che la nitidezza NON DEVE essere eseguita. 0 < valore \\u2264 100 Man mano che questo valore aumenta, la differenza di intensità tra i pixel DEVE aumentare.

Valore: La quantità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

