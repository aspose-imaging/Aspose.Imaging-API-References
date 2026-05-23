---
title: "EmfPlusColorCurveEffect Class"
type: docs
weight: 180
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | Inizializza una nuova istanza della classe EmfPlusColorCurveEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | Ottiene o imposta un intero a 32 bit con segno che specifica l'intensità della<br/>            regolazione della curva sul canale colore specificato da CurveChannel. Gli intervalli di valori significativi<br/>            per questo campo variano in base al valore di CurveAdjustment, come segue:<br/>            Intervallo di regolazione dell'esposizione:<br/>            -255 ≤ value &lt; 0 Man mano che il valore diminuisce, l'esposizione dell'immagine DOVREBBE diminuire.<br/>            0 Un valore di 0 specifica che l'esposizione NON DEVE cambiare.<br/>            0 &lt; value ≤ 255 Man mano che il valore aumenta, l'esposizione dell'immagine DOVREBBE aumentare.<br/>            Intervallo di regolazione della densità:<br/>            -255 ≤ value &lt; 0<br/>            Man mano che il valore diminuisce, la densità dell'immagine DOVREBBE diminuire, risultando in<br/>            un'immagine più scura.<br/>            0 Un valore di 0 specifica che la densità NON DEVE cambiare.<br/>            0 &lt; value ≤ 255<br/>            Man mano che il valore aumenta, la densità dell'immagine DOVREBBE aumentare.<br/>            Intervallo di regolazione del contrasto:<br/>            -100 ≤ value &lt; 0 Man mano che il valore diminuisce, il contrasto dell'immagine DOVREBBE diminuire.<br/>            0 Un valore di 0 specifica che il contrasto NON DEVE cambiare.<br/>            0 &lt; value ≤ 100 Man mano che il valore aumenta, il contrasto dell'immagine DOVREBBE aumentare.<br/>            Intervallo di regolazione delle alte luci:<br/>            -100 ≤ value &lt; 0 Man mano che il valore diminuisce, le aree chiare dell'immagine DOVREBBE apparire più scure.<br/>            0 Un valore di 0 specifica che le alte luci NON DEVE cambiare.<br/>            0 &lt; value ≤ 100 Man mano che il valore aumenta, le aree chiare dell'immagine DOVREBBE apparire più chiare.<br/>            Intervallo di regolazione delle ombre:<br/>            -100 ≤ value &lt; 0 Man mano che il valore diminuisce, le aree scure dell'immagine DOVREBBE apparire più scure.<br/>            0 Un valore di 0 specifica che le ombre NON DEVE cambiare.<br/>            0 &lt; value ≤ 100 Man mano che il valore aumenta, le aree scure dell'immagine DOVREBBE apparire più chiare.<br/>            Intervallo di regolazione della saturazione del bianco:<br/>            0 — 255 Man mano che il valore aumenta, il limite superiore dell'intervallo di intensità del canale colore aumenta.<br/>            Intervallo di regolazione della saturazione del nero:<br/>            0 — 255 Man mano che il valore aumenta, il limite inferiore dell'intervallo di intensità del canale colore aumenta. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la regolazione della curva da<br/>            applicare ai colori nel bitmap. Questo valore DEVE essere definito nell'enumerazione CurveAdjustments<br/>            (sezione 2.1.1.7). |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il canale colore a cui<br/>            si applica la regolazione della curva. Questo valore DEVE essere definito nell'enumerazione CurveChannel<br/>            (sezione 2.1.1.8). |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

Inizializza una nuova istanza della classe EmfPlusColorCurveEffect

