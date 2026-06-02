---
title: "EmfPlusLevelsEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LevelsEffect specifica le regolazioni delle luci, delle mezzitoni e delle ombre di un'immagine."
type: docs
weight: 51
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto LevelsEffect specifica le regolazioni delle alte luci, dei mezzitoni e delle ombre di un'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHighlight()](#getHighlight--) | Ottiene o imposta il valore che specifica quanto schiarire le luci di un'immagine. |
| [setHighlight(int value)](#setHighlight-int-) | Ottiene o imposta il valore che specifica quanto schiarire le luci di un'immagine. |
| [getMidTone()](#getMidTone--) | Ottiene o imposta il valore che specifica quanto schiarire o scurire le mezzitoni di un'immagine. |
| [setMidTone(int value)](#setMidTone-int-) | Ottiene o imposta il valore che specifica quanto schiarire o scurire le mezzitoni di un'immagine. |
| [getShadow()](#getShadow--) | Ottiene o imposta il valore che specifica quanto scurire le ombre di un'immagine. |
| [setShadow(int value)](#setShadow-int-) | Ottiene o imposta il valore che specifica quanto scurire le ombre di un'immagine. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


Ottiene o imposta il valore che specifica quanto schiarire le luci di un'immagine. I valori del canale colore all'estremità alta dell'intervallo di intensità vengono modificati più dei valori vicino al centro o alle estremità basse, il che significa che un'immagine può essere schiarita senza perdere il contrasto tra le parti più scure dell'immagine. 0 \\u2264 value < Specifica che le luci con una percentuale di intensità sopra questa soglia DEVONO essere aumentate. 100 Specifica che le luci NON DEVONO cambiare.

Valore: La luce.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


Ottiene o imposta il valore che specifica quanto schiarire le luci di un'immagine. I valori del canale colore all'estremità alta dell'intervallo di intensità vengono modificati più dei valori vicino al centro o alle estremità basse, il che significa che un'immagine può essere schiarita senza perdere il contrasto tra le parti più scure dell'immagine. 0 \\u2264 value < Specifica che le luci con una percentuale di intensità sopra questa soglia DEVONO essere aumentate. 100 Specifica che le luci NON DEVONO cambiare.

Valore: La luce.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


Ottiene o imposta il valore che specifica quanto schiarire o scurire le mezzitoni di un'immagine. I valori del canale colore al centro dell'intervallo di intensità vengono modificati più dei valori vicino alle estremità alta o bassa, il che significa che un'immagine può essere schiarita o scurita senza perdere il contrasto tra le parti più scure e più chiare dell'immagine. -100 \\u2264 value < 0 Specifica che le mezzitoni vengono rese più scure. 0 Specifica che le mezzitoni NON DEVONO cambiare. 0 < value \\u2264 100 Specifica che le mezzitoni vengono rese più chiare.

Valore: La mezzitono.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


Ottiene o imposta il valore che specifica quanto schiarire o scurire le mezzitoni di un'immagine. I valori del canale colore al centro dell'intervallo di intensità vengono modificati più dei valori vicino alle estremità alta o bassa, il che significa che un'immagine può essere schiarita o scurita senza perdere il contrasto tra le parti più scure e più chiare dell'immagine. -100 \\u2264 value < 0 Specifica che le mezzitoni vengono rese più scure. 0 Specifica che le mezzitoni NON DEVONO cambiare. 0 < value \\u2264 100 Specifica che le mezzitoni vengono rese più chiare.

Valore: La mezzitono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


Ottiene o imposta il valore che specifica quanto scurire le ombre di un'immagine. I valori del canale colore all'estremità bassa dell'intervallo di intensità vengono modificati più dei valori vicino al centro o alle estremità alte, il che significa che un'immagine può essere scurita senza perdere il contrasto tra le parti più chiare dell'immagine. 0 Specifica che le ombre NON DEVONO cambiare. 0 < value \\u2264 100 Specifica che le ombre con una percentuale di intensità al di sotto di questa soglia vengono rese più scure.

Valore: L'ombra.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


Ottiene o imposta il valore che specifica quanto scurire le ombre di un'immagine. I valori del canale colore all'estremità bassa dell'intervallo di intensità vengono modificati più dei valori vicino al centro o alle estremità alte, il che significa che un'immagine può essere scurita senza perdere il contrasto tra le parti più chiare dell'immagine. 0 Specifica che le ombre NON DEVONO cambiare. 0 < value \\u2264 100 Specifica che le ombre con una percentuale di intensità al di sotto di questa soglia vengono rese più scure.

Valore: L'ombra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

