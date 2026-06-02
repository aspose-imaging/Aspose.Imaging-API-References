---
title: "EmfPlusTintEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto TintEffect specifica l'aggiunta di nero o bianco a una tonalità specificata in un'immagine."
type: docs
weight: 79
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto TintEffect specifica l'aggiunta di nero o bianco a una tonalità specificata in un'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHue()](#getHue--) | Ottiene o imposta un intero con segno a 32 bit che specifica la tonalità a cui viene applicato l'effetto tinta. |
| [setHue(int value)](#setHue-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la tonalità a cui viene applicato l'effetto tinta. |
| [getAmount()](#getAmount--) | Ottiene o imposta un intero con segno a 32 bit che specifica di quanto la tonalità è rafforzata o attenuata. |
| [setAmount(int value)](#setAmount-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica di quanto la tonalità è rafforzata o attenuata. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la tonalità a cui viene applicato l'effetto tinta. -180 \\u2264 valore < 0 Il colore a una rotazione antioraria specificata della ruota dei colori, a partire dal blu. 0 Un valore di 0 specifica il colore blu sulla ruota dei colori. 0 < valore \\u2264 180 Il colore a una rotazione oraria specificata della ruota dei colori, a partire dal blu

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la tonalità a cui viene applicato l'effetto tinta. -180 \\u2264 valore < 0 Il colore a una rotazione antioraria specificata della ruota dei colori, a partire dal blu. 0 Un valore di 0 specifica il colore blu sulla ruota dei colori. 0 < valore \\u2264 180 Il colore a una rotazione oraria specificata della ruota dei colori, a partire dal blu

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Ottiene o imposta un intero con segno a 32 bit che specifica di quanto la tonalità è rafforzata o attenuata. -100 \\u2264 valore < 0 I valori negativi specificano di quanto la tonalità è attenuata, il che equivale all'aggiunta di nero. 0 Un valore di 0 specifica che la tinta NON DEVE cambiare. 0 < valore \\u2264 100 I valori positivi specificano di quanto la tonalità è rafforzata, il che equivale all'aggiunta di bianco.

Valore: La quantità.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica di quanto la tonalità è rafforzata o attenuata. -100 \\u2264 valore < 0 I valori negativi specificano di quanto la tonalità è attenuata, il che equivale all'aggiunta di nero. 0 Un valore di 0 specifica che la tinta NON DEVE cambiare. 0 < valore \\u2264 100 I valori positivi specificano di quanto la tonalità è rafforzata, il che equivale all'aggiunta di bianco.

Valore: La quantità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

