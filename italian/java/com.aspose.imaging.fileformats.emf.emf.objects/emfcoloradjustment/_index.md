---
title: "EmfColorAdjustment"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto ColorAdjustment definisce i valori per regolare i colori nei bitmap di origine nei trasferimenti a blocchi di bit."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

L'oggetto ColorAdjustment definisce i valori per regolare i colori nei bitmap di origine nei trasferimenti a blocchi di bit.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Ottiene o imposta un intero senza segno a 16 bit che specifica la dimensione in byte di questo oggetto. |
| [setSize(short value)](#setSize-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica la dimensione in byte di questo oggetto. |
| [getValues()](#getValues--) | Ottiene o imposta un intero senza segno a 16 bit che specifica come preparare l'immagine di output. |
| [setValues(int value)](#setValues-int-) | Ottiene o imposta un intero senza segno a 16 bit che specifica come preparare l'immagine di output. |
| [getIlluminantIndex()](#getIlluminantIndex--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il tipo di sorgente luminosa standard sotto la quale l'immagine è visualizzata, dall'enumerazione Illuminant (sezione 2.1.19). |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il tipo di sorgente luminosa standard sotto la quale l'immagine è visualizzata, dall'enumerazione Illuminant (sezione 2.1.19). |
| [getRedGamma()](#getRedGamma--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n-esima potenza per il primario rosso dei colori sorgente. |
| [setRedGamma(short value)](#setRedGamma-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n-esima potenza per il primario rosso dei colori sorgente. |
| [getGreenGamma()](#getGreenGamma--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n-esima potenza per il primario verde dei colori sorgente. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n-esima potenza per il primario verde dei colori sorgente. |
| [getBlueGamma()](#getBlueGamma--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n-esima potenza per il primario blu dei colori sorgente. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n-esima potenza per il primario blu dei colori sorgente. |
| [getReferenceBlack()](#getReferenceBlack--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento nero per i colori sorgente. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento nero per i colori sorgente. |
| [getReferenceWhite()](#getReferenceWhite--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento bianco per i colori sorgente. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento bianco per i colori sorgente. |
| [getContrast()](#getContrast--) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di contrasto da applicare all'oggetto sorgente. |
| [setContrast(short value)](#setContrast-short-) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di contrasto da applicare all'oggetto sorgente. |
| [getBrightness()](#getBrightness--) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di luminosità da applicare all'oggetto di origine. |
| [setBrightness(short value)](#setBrightness-short-) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di luminosità da applicare all'oggetto di origine. |
| [getColorfullness()](#getColorfullness--) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di vividezza da applicare all'oggetto di origine. |
| [setColorfullness(short value)](#setColorfullness-short-) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di vividezza da applicare all'oggetto di origine. |
| [getRedGreenTint()](#getRedGreenTint--) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di regolazione della tinta rossa o verde da applicare all'oggetto di origine. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di regolazione della tinta rossa o verde da applicare all'oggetto di origine. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica la dimensione in byte di questo oggetto. Questo DEVE essere 0x0018.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica la dimensione in byte di questo oggetto. Questo DEVE essere 0x0018.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica come preparare l'immagine di output. Questo campo può essere impostato a NULL o a qualsiasi combinazione di valori nell'enumerazione ColorAdjustment (sezione 2.1.5).

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica come preparare l'immagine di output. Questo campo può essere impostato a NULL o a qualsiasi combinazione di valori nell'enumerazione ColorAdjustment (sezione 2.1.5).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il tipo di sorgente luminosa standard sotto la quale l'immagine è visualizzata, dall'enumerazione Illuminant (sezione 2.1.19).

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il tipo di sorgente luminosa standard sotto la quale l'immagine è visualizzata, dall'enumerazione Illuminant (sezione 2.1.19).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma di n‑esima potenza per il primario rosso dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma di n‑esima potenza per il primario rosso dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma di n‑esima potenza per il primario verde dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma di n‑esima potenza per il primario verde dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma di n‑esima potenza per il primario blu dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma di n‑esima potenza per il primario blu dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento del nero per i colori di origine. Qualsiasi colore più scuro di questo viene trattato come nero. Questo valore DOVREBBE essere nell'intervallo da zero a 4.000.

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento del nero per i colori di origine. Qualsiasi colore più scuro di questo viene trattato come nero. Questo valore DOVREBBE essere nell'intervallo da zero a 4.000.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento del bianco per i colori di origine. Qualsiasi colore più chiaro di questo viene trattato come bianco. Questo valore DOVREBBE essere nell'intervallo da 6.000 a 10.000.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento del bianco per i colori di origine. Qualsiasi colore più chiaro di questo viene trattato come bianco. Questo valore DOVREBBE essere nell'intervallo da 6.000 a 10.000.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di contrasto da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. Un valore zero indica che la regolazione del contrasto NON DEVE essere eseguita.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di contrasto da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. Un valore zero indica che la regolazione del contrasto NON DEVE essere eseguita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di luminosità da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. Un valore zero indica che la regolazione della luminosità NON DEVE essere eseguita.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di luminosità da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. Un valore zero indica che la regolazione della luminosità NON DEVE essere eseguita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di vividezza da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. Un valore zero indica che la regolazione della vividezza NON DEVE essere eseguita.

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di vividezza da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. Un valore zero indica che la regolazione della vividezza NON DEVE essere eseguita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di regolazione della tinta rossa o verde da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. I numeri positivi regolano verso il rosso e i numeri negativi verso il verde. Un valore zero indica che la regolazione della tinta NON DEVE essere eseguita.

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di regolazione della tinta rossa o verde da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. I numeri positivi regolano verso il rosso e i numeri negativi verso il verde. Un valore zero indica che la regolazione della tinta NON DEVE essere eseguita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

