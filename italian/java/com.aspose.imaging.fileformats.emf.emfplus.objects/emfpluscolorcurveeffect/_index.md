---
title: "EmfPlusColorCurveEffect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto ColorCurveEffect specifica una delle otto regolazioni della curva colore di un'immagine."
type: docs
weight: 27
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorCurveEffect extends EmfPlusImageEffectsObjectType
```

L'oggetto ColorCurveEffect specifica una delle otto regolazioni della curva colore di un'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCurveAdjustment()](#getCurveAdjustment--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la regolazione della curva da applicare ai colori nel bitmap. |
| [setCurveAdjustment(int value)](#setCurveAdjustment-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la regolazione della curva da applicare ai colori nel bitmap. |
| [getCurveChannel()](#getCurveChannel--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il canale colore a cui si applica la regolazione della curva. |
| [setCurveChannel(int value)](#setCurveChannel-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il canale colore a cui si applica la regolazione della curva. |
| [getAdjustmentIntensity()](#getAdjustmentIntensity--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'intensità della regolazione della curva sul canale colore specificato da CurveChannel. |
| [setAdjustmentIntensity(int value)](#setAdjustmentIntensity-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'intensità della regolazione della curva sul canale colore specificato da CurveChannel. |
### EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect--}
```
public EmfPlusColorCurveEffect()
```


### getCurveAdjustment() {#getCurveAdjustment--}
```
public int getCurveAdjustment()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la regolazione della curva da applicare ai colori nel bitmap. Questo valore DEVE essere definito nell'enumerazione CurveAdjustments (sezione 2.1.1.7).

**Returns:**
int
### setCurveAdjustment(int value) {#setCurveAdjustment-int-}
```
public void setCurveAdjustment(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la regolazione della curva da applicare ai colori nel bitmap. Questo valore DEVE essere definito nell'enumerazione CurveAdjustments (sezione 2.1.1.7).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCurveChannel() {#getCurveChannel--}
```
public int getCurveChannel()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il canale colore a cui si applica la regolazione della curva. Questo valore DEVE essere definito nell'enumerazione CurveChannel (sezione 2.1.1.8).

**Returns:**
int
### setCurveChannel(int value) {#setCurveChannel-int-}
```
public void setCurveChannel(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il canale colore a cui si applica la regolazione della curva. Questo valore DEVE essere definito nell'enumerazione CurveChannel (sezione 2.1.1.8).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getAdjustmentIntensity() {#getAdjustmentIntensity--}
```
public int getAdjustmentIntensity()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'intensità della regolazione della curva sul canale colore specificato da CurveChannel. Gli intervalli di valori significativi per questo campo variano in base al valore CurveAdjustment, come segue: Intervallo di regolazione dell'esposizione: -255 \\u2264 value < 0 Man mano che il valore diminuisce, l'esposizione dell'immagine DOVREBBE diminuire. 0 Un valore di 0 specifica che l'esposizione NON DEVE cambiare. 0 < value \\u2264 255 Man mano che il valore aumenta, l'esposizione dell'immagine DOVREBBE aumentare. Intervallo di regolazione della densità: -255 \\u2264 value < 0 Man mano che il valore diminuisce, la densità dell'immagine DOVREBBE diminuire, risultando in un'immagine più scura. 0 Un valore di 0 specifica che la densità NON DEVE cambiare. 0 < value \\u2264 255 Man mano che il valore aumenta, la densità dell'immagine DOVREBBE aumentare. Intervallo di regolazione del contrasto: -100 \\u2264 value < 0 Man mano che il valore diminuisce, il contrasto dell'immagine DOVREBBE diminuire. 0 Un valore di 0 specifica che il contrasto NON DEVE cambiare. 0 < value \\u2264 100 Man mano che il valore aumenta, il contrasto dell'immagine DOVREBBE aumentare. Intervallo di regolazione delle luci: -100 \\u2264 value < 0 Man mano che il valore diminuisce, le aree luminose dell'immagine DOVREBBE apparire più scure. 0 Un valore di 0 specifica che le luci NON DEVONO cambiare. 0 < value \\u2264 100 Man mano che il valore aumenta, le aree luminose dell'immagine DOVREBBE apparire più chiare. Intervallo di regolazione delle ombre: -100 \\u2264 value < 0 Man mano che il valore diminuisce, le aree scure dell'immagine DOVREBBE apparire più scure. 0 Un valore di 0 specifica che le ombre NON DEVONO cambiare. 0 < value \\u2264 100 Man mano che il valore aumenta, le aree scure dell'immagine DOVREBBE apparire più chiare. Intervallo di regolazione della saturazione del bianco: 0 \\u2014 255 Man mano che il valore aumenta, il limite superiore dell'intervallo di intensità del canale colore aumenta. Intervallo di regolazione della saturazione del nero: 0 \\u2014 255 Man mano che il valore aumenta, il limite inferiore dell'intervallo di intensità del canale colore aumenta.

**Returns:**
int
### setAdjustmentIntensity(int value) {#setAdjustmentIntensity-int-}
```
public void setAdjustmentIntensity(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'intensità della regolazione della curva sul canale colore specificato da CurveChannel. Gli intervalli di valori significativi per questo campo variano in base al valore CurveAdjustment, come segue: Intervallo di regolazione dell'esposizione: -255 \\u2264 value < 0 Man mano che il valore diminuisce, l'esposizione dell'immagine DOVREBBE diminuire. 0 Un valore di 0 specifica che l'esposizione NON DEVE cambiare. 0 < value \\u2264 255 Man mano che il valore aumenta, l'esposizione dell'immagine DOVREBBE aumentare. Intervallo di regolazione della densità: -255 \\u2264 value < 0 Man mano che il valore diminuisce, la densità dell'immagine DOVREBBE diminuire, risultando in un'immagine più scura. 0 Un valore di 0 specifica che la densità NON DEVE cambiare. 0 < value \\u2264 255 Man mano che il valore aumenta, la densità dell'immagine DOVREBBE aumentare. Intervallo di regolazione del contrasto: -100 \\u2264 value < 0 Man mano che il valore diminuisce, il contrasto dell'immagine DOVREBBE diminuire. 0 Un valore di 0 specifica che il contrasto NON DEVE cambiare. 0 < value \\u2264 100 Man mano che il valore aumenta, il contrasto dell'immagine DOVREBBE aumentare. Intervallo di regolazione delle luci: -100 \\u2264 value < 0 Man mano che il valore diminuisce, le aree luminose dell'immagine DOVREBBE apparire più scure. 0 Un valore di 0 specifica che le luci NON DEVONO cambiare. 0 < value \\u2264 100 Man mano che il valore aumenta, le aree luminose dell'immagine DOVREBBE apparire più chiare. Intervallo di regolazione delle ombre: -100 \\u2264 value < 0 Man mano che il valore diminuisce, le aree scure dell'immagine DOVREBBE apparire più scure. 0 Un valore di 0 specifica che le ombre NON DEVONO cambiare. 0 < value \\u2264 100 Man mano che il valore aumenta, le aree scure dell'immagine DOVREBBE apparire più chiare. Intervallo di regolazione della saturazione del bianco: 0 \\u2014 255 Man mano che il valore aumenta, il limite superiore dell'intervallo di intensità del canale colore aumenta. Intervallo di regolazione della saturazione del nero: 0 \\u2014 255 Man mano che il valore aumenta, il limite inferiore dell'intervallo di intensità del canale colore aumenta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

