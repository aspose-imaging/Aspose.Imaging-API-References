---
title: "Classe EmfPlusStringFormatData"
type: docs
weight: 660
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---

**Summary:** The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData__1) | Inizializza una nuova istanza della classe EmfPlusStringFormatData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| char_range | [EmfPlusCharacterRange[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange/) | r/w | Ottiene o imposta un array opzionale di RangeCount EmfPlusCharacterRange <br/>            oggetti che specificano l'intervallo di posizioni dei caratteri <br/>            all'interno di una stringa di testo. La regione di delimitazione è definita<br/>            dall'area di visualizzazione occupata da un gruppo <br/>            di caratteri specificati dall'intervallo di caratteri.<br/>            Questo campo DEVE essere presente se il valore del campo RangeCount<br/>            nell'oggetto EmfPlusStringFormat è maggiore di 0. |
| tabulazioni | float[] | r/w | Ottiene o imposta un array opzionale di valori a virgola mobile che specificano <br/>            le posizioni opzionali delle tabulazioni per questo oggetto. Ogni valore di <br/>            tabulazione rappresenta il numero di spazi tra le tabulazioni o, per la prima tabulazione, il numero di spazi <br/>            tra l'inizio di una riga di testo e la prima tabulazione. <br/>            Questo campo DEVE essere presente se il valore del campo TabStopCount <br/>            nell'oggetto EmfPlusStringFormat è maggiore di 0. |


### Constructor: EmfPlusStringFormatData() {#EmfPlusStringFormatData__1}


```
 EmfPlusStringFormatData() 
```

Inizializza una nuova istanza della classe EmfPlusStringFormatData

