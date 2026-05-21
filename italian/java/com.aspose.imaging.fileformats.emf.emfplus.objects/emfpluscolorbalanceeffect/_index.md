---
title: "EmfPlusColorBalanceEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto ColorBalanceEffect specifica le regolazioni delle quantità relative di rosso, verde e blu in un'immagine."
type: docs
weight: 26
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto ColorBalanceEffect specifica regolazioni delle quantità relative di rosso, verde e blu in un'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di rosso nell'immagine. |
| [setCyanRed(int value)](#setCyanRed-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di rosso nell'immagine. |
| [getMagentaGreen()](#getMagentaGreen--) | Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di verde nell'immagine. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di verde nell'immagine. |
| [getYellowBlue()](#getYellowBlue--) | Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di blu nell'immagine. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di blu nell'immagine. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di rosso nell'immagine. Questo valore DEVE essere nell'intervallo -100 a 100, con gli effetti seguenti: -100 \\u2264 valore < 0 Man mano che il valore diminuisce, la quantità di rosso nell'immagine DOVREBBE diminuire e la quantità di ciano DOVREBBE aumentare. 0 Un valore di 0 specifica che le quantità di rosso e ciano NON DEVONO cambiare. 0 < valore \\u2264 100 Man mano che il valore aumenta, la quantità di rosso nell'immagine DOVREBBE aumentare e la quantità di ciano DOVREBBE diminuire.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di rosso nell'immagine. Questo valore DEVE essere nell'intervallo -100 a 100, con gli effetti seguenti: -100 \\u2264 valore < 0 Man mano che il valore diminuisce, la quantità di rosso nell'immagine DOVREBBE diminuire e la quantità di ciano DOVREBBE aumentare. 0 Un valore di 0 specifica che le quantità di rosso e ciano NON DEVONO cambiare. 0 < valore \\u2264 100 Man mano che il valore aumenta, la quantità di rosso nell'immagine DOVREBBE aumentare e la quantità di ciano DOVREBBE diminuire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di verde nell'immagine. Questo valore DEVE essere nell'intervallo -100 a 100, con gli effetti seguenti: -100 \\u2264 valore < 0 Man mano che il valore diminuisce, la quantità di verde nell'immagine DOVREBBE diminuire e la quantità di magenta DOVREBBE aumentare. 0 Un valore di 0 specifica che le quantità di verde e magenta NON DEVONO cambiare. 0 < valore \\u2264 100 Man mano che il valore aumenta, la quantità di verde nell'immagine DOVREBBE aumentare e la quantità di magenta DOVREBBE diminuire.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di verde nell'immagine. Questo valore DEVE essere nell'intervallo -100 a 100, con gli effetti seguenti: -100 \\u2264 valore < 0 Man mano che il valore diminuisce, la quantità di verde nell'immagine DOVREBBE diminuire e la quantità di magenta DOVREBBE aumentare. 0 Un valore di 0 specifica che le quantità di verde e magenta NON DEVONO cambiare. 0 < valore \\u2264 100 Man mano che il valore aumenta, la quantità di verde nell'immagine DOVREBBE aumentare e la quantità di magenta DOVREBBE diminuire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di blu nell'immagine. Questo valore DEVE essere nell'intervallo -100 a 100, con gli effetti seguenti: -100 \\u2264 valore < 0 Man mano che il valore diminuisce, la quantità di blu nell'immagine DOVREBBE diminuire e la quantità di giallo DOVREBBE aumentare. 0 Un valore di 0 specifica che le quantità di blu e giallo NON DEVONO cambiare. 0 < valore \\u2264 100 Man mano che il valore aumenta, la quantità di blu nell'immagine DOVREBBE aumentare e la quantità di giallo DOVREBBE diminuire.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica una variazione della quantità di blu nell'immagine. Questo valore DEVE essere nell'intervallo -100 a 100, con gli effetti seguenti: -100 \\u2264 valore < 0 Man mano che il valore diminuisce, la quantità di blu nell'immagine DOVREBBE diminuire e la quantità di giallo DOVREBBE aumentare. 0 Un valore di 0 specifica che le quantità di blu e giallo NON DEVONO cambiare. 0 < valore \\u2264 100 Man mano che il valore aumenta, la quantità di blu nell'immagine DOVREBBE aumentare e la quantità di giallo DOVREBBE diminuire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

