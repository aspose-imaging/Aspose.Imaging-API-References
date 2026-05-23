---
title: "Classe EmfColorAdjustment"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | Inizializza una nuova istanza della classe EmfColorAdjustment |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n‑esima potenza per il <br/>            primario blu dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. <br/>            Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita. |
| luminosità | int | r/w | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di luminosità da applicare all'oggetto di origine. <br/>            Questo valore DOVREBBE essere nell'intervallo da –100 a 100.<br/>            Un valore zero indica che la regolazione della luminosità NON DEVE essere eseguita. |
| colorfullness | int | r/w | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di vividezza da applicare all'oggetto di origine. <br/>            Questo valore DOVREBBE essere nell'intervallo da –100 a 100. <br/>            Un valore zero indica che la regolazione della vividezza NON DEVE essere eseguita |
| contrasto | int | r/w | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di contrasto da applicare all'oggetto di origine. <br/>            Questo valore DOVREBBE essere nell'intervallo da –100 a 100. Un valore zero indica che la regolazione del contrasto NON DEVE essere eseguita. |
| green_gamma | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n‑esima potenza per il primario verde dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000. <br/>            Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita. |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il tipo di sorgente luminosa standard sotto la quale l'immagine è visualizzata, dall'enumerazione Illuminant (sezione 2.1.19). |
| red_gamma | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il valore di correzione gamma alla n‑esima potenza per il primario rosso dei colori di origine. Questo valore DOVREBBE essere nell'intervallo da 2.500 a 65.000.<br/>            Un valore di 10.000 indica che la correzione gamma NON DEVE essere eseguita. |
| red_green_tint | int | r/w | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di regolazione della tinta rossa o verde da applicare all'oggetto di origine. Questo valore DOVREBBE essere nell'intervallo da –100 a 100. <br/>            I numeri positivi regolano verso il rosso e i numeri negativi verso il verde. <br/>            Un valore zero indica che la regolazione della tinta NON DEVE essere eseguita |
| reference_black | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento nero per i colori di origine. <br/>            Qualsiasi colore più scuro di questo è trattato come nero. <br/>            Questo valore DOVREBBE essere nell'intervallo da zero a 4.000 |
| reference_white | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento bianco per i colori di origine. <br/>            Qualsiasi colore più chiaro di questo è trattato come bianco. <br/>            Questo valore DOVREBBE essere nell'intervallo da 6.000 a 10.000. |
| dimensione | int | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica la dimensione in byte di questo oggetto. Questo DEVE essere 0x0018. |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | Ottiene o imposta un intero senza segno a 16 bit che specifica come preparare l'immagine di output. Questo campo può essere <br/>            impostato a NULL o a qualsiasi combinazione di valori nell'enumerazione ColorAdjustment (sezione 2.1.5). |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

Inizializza una nuova istanza della classe EmfColorAdjustment

