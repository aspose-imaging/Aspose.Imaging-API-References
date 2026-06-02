---
title: "Classe EmfPlusPenOptionalData"
type: docs
weight: 560
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | Inizializza una nuova istanza della classe EmfPlusPenOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | Ottiene o imposta l'oggetto opzionale EmfPlusCompoundLineData (sezione 2.2.2.9) <br/>            che specifica un array di valori in virgola mobile che definiscono <br/>            la linea composta di una penna, costituita da linee parallele <br/>            e spazi. Questo campo DEVE essere presente se il <br/>            flag PenDataCompoundLine è impostato nel campo PenDataFlags <br/>            dell'oggetto EmfPlusPenData |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | Ottiene o imposta l'oggetto opzionale EmfPlusCustomEndCapData (sezione 2.2.2.11) <br/>            che definisce la forma del cappuccio finale personalizzato, ovvero la forma da <br/>            utilizzare alla fine di una linea disegnata con questa penna. Può essere una delle <br/>            varie forme, come un quadrato, un cerchio o un diamante. Questo <br/>            campo DEVE essere presente se il flag PenDataCustomEndCap è <br/>            impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | Ottiene o imposta l'oggetto opzionale EmfPlusCustomStartCapData (sezione 2.2.2.15) <br/>            che definisce la forma del cappuccio iniziale personalizzato, ovvero la forma da <br/>            utilizzare all'inizio di una linea disegnata con questa penna. Può essere una delle <br/>            varie forme, come un quadrato, un cerchio o un diamante. <br/>            Questo campo DEVE essere presente se il flag PenDataCustomStartCap è <br/>            impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData |
| dash_offset | float | r/w | Ottiene o imposta un valore opzionale a virgola mobile a 32 bit che specifica la <br/>            distanza dall'inizio di una linea all'inizio del <br/>            primo spazio in un modello di linea tratteggiata. Questo campo DEVE essere <br/>            presente se il flag PenDataDashedLineOffset è impostato nel <br/>            campo PenDataFlags dell'oggetto EmfPlusPenData. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | Ottiene o imposta un intero opzionale con segno a 32 bit che specifica la forma per <br/>            entrambe le estremità di ogni tratto in una linea tratteggiata. Questo campo DEVE essere <br/>            presente se il flag PenDataDashedLineCap è impostato nel <br/>            campo PenDataFlags dell'oggetto EmfPlusPenData, e il <br/>            valore DEVE essere definito nell'enumerazione DashedLineCapType <br/>            (sezione 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | Ottiene o imposta l'oggetto opzionale EmfPlusDashedLineData (sezione 2.2.2.16) <br/>            che specifica le lunghezze dei tratti e degli spazi in una linea tratteggiata personalizzata. Questo campo DEVE essere presente se il flag PenDataDashedLine <br/>            è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData. |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Ottiene o imposta un intero opzionale con segno a 32 bit che specifica la forma<br/>             per l'estremità di una linea nel campo CustomEndCapData. Questo <br/>            campo DEVE essere presente se il flag PenDataEndCap è impostato nel <br/>            campo PenDataFlags dell'oggetto EmfPlusPenData, e il valore <br/>            DEVE essere definito nell'enumerazione LineCapType |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica come unire<br/>             due linee disegnate dalla stessa penna e le cui estremità si incontrano. <br/>            Questo campo DEVE essere presente se il flag PenDataJoin è impostato nel <br/>            campo PenDataFlags dell'oggetto EmfPlusPenData, e il <br/>            valore DEVE essere definito nell'enumerazione LineJoinType <br/>            (sezione 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | Ottiene o imposta un intero opzionale a 32 bit con segno che specifica lo stile <br/>            utilizzato per le linee disegnate con questo oggetto penna. Questo campo DEVE <br/>            essere presente se il flag PenDataLineStyle è impostato nel <br/>            campo PenDataFlags dell'oggetto EmfPlusPenData, e il <br/>            valore DEVE essere definito nell'enumerazione LineStyle <br/>            (sezione 2.1.1.20). |
| miter_limit | float | r/w | Ottiene o imposta un valore opzionale a virgola mobile a 32 bit che specifica il limite del giunto <br/>            (miter), che è il rapporto massimo consentito tra la lunghezza del giunto e<br/>            la larghezza della linea. La lunghezza del giunto è la distanza dalla<br/>            intersezione delle pareti della linea all'interno dell'unione alla <br/>            intersezione delle pareti della linea all'esterno dell'unione. <br/>            La lunghezza del giunto può essere grande quando l'angolo tra due <br/>            linee è piccolo. Questo campo DEVE essere presente se il <br/>            flag PenDataMiterLimit è impostato nel campo PenDataFlags <br/>            dell'oggetto EmfPlusPenData. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | Ottiene o imposta un intero firmato opzionale a 32 bit che specifica la <br/>            distribuzione della larghezza della penna rispetto alle <br/>            coordinate della linea disegnata. Questo campo DEVE <br/>            essere presente se il flag PenDataNonCenter è impostato nel <br/>            campo PenDataFlags dell'oggetto EmfPlusPenData, e <br/>            il valore DEVE essere definito nell'enumerazione PenAlignment <br/>            (sezione 2.1.1.24). |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Ottiene o imposta un intero firmato opzionale a 32 bit che specifica la forma per<br/>            l'inizio di una linea nel campo CustomStartCapData. <br/>            Questo campo DEVE essere presente se il flag PenDataStartCap è impostato <br/>            nel campo PenDataFlags dell'oggetto EmfPlusPenData, e il<br/>            valore DEVE essere definito nell'enumerazione LineCapType <br/>            (sezione 2.1.1.18). |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) <br/>            che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per <br/>            la penna. Questo campo DEVE essere presente se il flag PenDataTransform <br/>            è impostato nel campo PenDataFlags dell'oggetto EmfPlusPenData <br/>            . |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

Inizializza una nuova istanza della classe EmfPlusPenOptionalData

