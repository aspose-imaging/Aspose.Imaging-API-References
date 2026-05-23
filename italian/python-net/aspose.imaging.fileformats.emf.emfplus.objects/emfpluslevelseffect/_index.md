---
title: "Classe EmfPlusLevelsEffect"
type: docs
weight: 420
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | Inizializza una nuova istanza della classe EmfPlusLevelsEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| highlight | int | r/w | Ottiene o imposta il valore che specifica quanto schiarire le alte luci di un'immagine. I valori del canale colore all'estremità alta dell'intervallo di intensità vengono modificati più dei valori vicino al<br/>            centro o alle estremità basse, il che significa che un'immagine può essere schiarita senza perdere il contrasto<br/>            tra le parti più scure dell'immagine.<br/>            0 ≤ value &lt; Specifica che le alte luci con una percentuale di intensità sopra questa soglia DEVONO<br/>            100 essere aumentate.<br/>            100 Specifica che le alte luci NON DEVONO cambiare. |
| mid_tone | int | r/w | Ottiene o imposta il valore che specifica quanto schiarire o scurire le mezzitoni di un'immagine. I valori del canale colore al centro dell'intervallo di intensità vengono modificati più dei valori vicino alle estremità alta<br/>            o bassa, il che significa che un'immagine può essere schiarita o scurita senza perdere il contrasto<br/>            tra le parti più scure e più chiare dell'immagine.<br/>            -100 ≤ value &lt; 0 Specifica che le mezzitoni vengono rese più scure.<br/>            0 Specifica che le mezzitoni NON DEVONO cambiare.<br/>            0 &lt; value ≤ 100 Specifica che le mezzitoni vengono rese più chiare. |
| shadow | int | r/w | Ottiene o imposta il valore che specifica quanto scurire le ombre di un'immagine. I valori del canale colore all'estremità bassa dell'intervallo di intensità vengono modificati più dei valori vicino al centro o alle estremità alte, il che significa che un'immagine può essere scurita senza perdere il contrasto tra le<br/>            parti più chiare dell'immagine.<br/>            0 Specifica che le ombre NON DEVONO cambiare.<br/>            0 &lt; value ≤ 100<br/>            Specifica che le ombre con una percentuale di intensità al di sotto di questa soglia vengono rese<br/>            più scure. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

Inizializza una nuova istanza della classe EmfPlusLevelsEffect

