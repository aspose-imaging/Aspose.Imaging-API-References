---
title: EmfColorAdjustment
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto ColorAdjustment definisce i valori per la regolazione dei colori nelle bitmap di origine nei trasferimenti a blocchi di bit.
type: docs
weight: 2930
url: /it/net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

L'oggetto ColorAdjustment definisce i valori per la regolazione dei colori nelle bitmap di origine nei trasferimenti a blocchi di bit.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma) { get; set; } | Ottiene o imposta un numero intero senza segno a 16 bit che specifica l'ennesimo valore di correzione gamma di potenza per il blu primario dei colori di origine. Questo valore DOVREBBE essere compreso tra 2.500 e 65.000. Un valore di 10.000 significa che la correzione gamma NON DEVE essere eseguita. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness) { get; set; } | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di luminosità da applicare all'oggetto di origine. Questo valore DEVE essere compreso tra –100 e 100. Un valore zero significa che la regolazione della luminosità NON DEVE essere eseguita. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness) { get; set; } | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di vivacità da applicare all'oggetto di origine. Questo valore DEVE essere compreso tra –100 e 100. Un valore pari a zero significa che la regolazione della vivacità NON DEVE essere eseguita |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast) { get; set; } | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di contrasto da applicare all'oggetto di origine. Questo valore DEVE essere compreso tra –100 e 100. Un valore zero significa che la regolazione del contrasto NON DEVE essere eseguita. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica l'ennesimo valore di correzione gamma di potenza per il verde primario dei colori di origine. Questo valore DOVREBBE essere compreso tra 2.500 e 65.000. Un valore di 10.000 significa che la correzione gamma NON DEVE essere eseguita. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex) { get; set; } | Ottiene o imposta un numero intero senza segno a 16 bit che specifica il tipo di sorgente luminosa standard in base alla quale viene visualizzata l'immagine , dall'enumerazione degli illuminanti (sezione 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica l'ennesimo valore di correzione gamma di potenza per il rosso primario dei colori di origine. Questo valore DEVE essere compreso tra 2.500 e 65.000. Un valore di 10.000 significa che la correzione gamma NON DEVE essere eseguita. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint) { get; set; } | Ottiene o imposta un intero con segno a 16 bit che specifica la quantità di regolazione della tinta rossa o verde da applicare all'oggetto di origine. Questo valore DOVREBBE essere compreso tra –100 e 100. I numeri positivi si orientano verso il rosso ei numeri negativi si orientano verso il verde. Un valore zero significa che la regolazione della tinta NON DEVE essere eseguita |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento nero per i colori di origine. Tutti i colori più scuri di questo vengono trattati come neri. Questo valore DOVREBBE essere compreso tra zero e 4.000 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica il riferimento bianco per i colori di origine. Tutti i colori più chiari di questo vengono trattati come bianchi. Questo valore DOVREBBE essere compreso tra 6.000 e 10.000. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica la dimensione in byte di questo oggetto. Questo DEVE essere 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che specifica come preparare l'immagine di output. Questo campo può essere impostato su NULL o su qualsiasi combinazione di valori nell'enumerazione ColorAdjustment (sezione 2.1.5). |

### Guarda anche

* class [EmfObject](../emfobject)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
