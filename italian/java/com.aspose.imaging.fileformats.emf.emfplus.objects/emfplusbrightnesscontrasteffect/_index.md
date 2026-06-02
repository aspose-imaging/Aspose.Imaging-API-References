---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto BrightnessContrastEffect specifica un'espansione o una contrazione delle aree più chiare e più scure di un'immagine."
type: docs
weight: 23
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto BrightnessContrastEffect specifica un'espansione o una contrazione delle aree più chiare e più scure di un'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Ottiene o imposta un intero con segno a 32 bit che specifica il livello di luminosità. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il livello di luminosità. |
| [getContrastLevel()](#getContrastLevel--) | Ottiene o imposta un intero con segno a 32 bit che specifica il livello di contrasto. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica il livello di contrasto. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il livello di luminosità. Questo valore DEVE essere nell'intervallo da -255 a 255, con gli effetti seguenti: -255 ≤ valore < 0 Man mano che il valore diminuisce, la luminosità dell'immagine DOVREBBE diminuire. 0 Un valore pari a 0 specifica che la luminosità NON DEVE cambiare. 0 < valore ≤ 255 Man mano che il valore aumenta, la luminosità dell'immagine DOVREBBE aumentare.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il livello di luminosità. Questo valore DEVE essere nell'intervallo da -255 a 255, con gli effetti seguenti: -255 ≤ valore < 0 Man mano che il valore diminuisce, la luminosità dell'immagine DOVREBBE diminuire. 0 Un valore pari a 0 specifica che la luminosità NON DEVE cambiare. 0 < valore ≤ 255 Man mano che il valore aumenta, la luminosità dell'immagine DOVREBBE aumentare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Ottiene o imposta un intero con segno a 32 bit che specifica il livello di contrasto. Questo valore DEVE essere nell'intervallo da -100 a 100, con gli effetti seguenti: -100 ≤ valore < 0 Man mano che il valore diminuisce, il contrasto dell'immagine DOVREBBE diminuire. 0 Un valore pari a 0 specifica che il contrasto NON DEVE cambiare. 0 < valore ≤ 100 Man mano che il valore aumenta, il contrasto dell'immagine DOVREBBE aumentare.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica il livello di contrasto. Questo valore DEVE essere nell'intervallo da -100 a 100, con gli effetti seguenti: -100 ≤ valore < 0 Man mano che il valore diminuisce, il contrasto dell'immagine DOVREBBE diminuire. 0 Un valore pari a 0 specifica che il contrasto NON DEVE cambiare. 0 < valore ≤ 100 Man mano che il valore aumenta, il contrasto dell'immagine DOVREBBE aumentare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

