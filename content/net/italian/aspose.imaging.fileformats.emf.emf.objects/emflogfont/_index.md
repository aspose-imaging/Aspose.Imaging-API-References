---
title: EmfLogFont
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto LogFont specifica gli attributi di base di un font logico.
type: docs
weight: 3030
url: /it/aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
## EmfLogFont class

L'oggetto LogFont specifica gli attributi di base di un font logico.

```csharp
public class EmfLogFont : EmfObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfLogFont](emflogfont)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica il set di caratteri glifi. DEVE essere un valore nell'enumerazione WMF CharacterSet ([MS-WMF] sezione 2.1.1.5). Se il set di caratteri è sconosciuto, l'elaborazione del metafile NON DOVREBBE tentare di tradurre o interpretare stringhe renderizzate con quel font. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di ritaglio. La precisione di ritaglio definisce come ritagliare i caratteri che sono parzialmente al di fuori dell'area di ritaglio. Può essere uno o più flag WMF ClipPrecision |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di gradi, tra il vettore di scappamento e l'asse x del dispositivo. Il vettore di scappamento è parallelo alla linea di base di una riga di testo. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Ottiene o imposta un Facename (64 byte): una stringa di non più di 32 caratteri Unicode che specifica il nome del carattere tipografico del font. Se la lunghezza di questa stringa è inferiore a 32 caratteri, DEVE essere presente un NULL finale, dopodiché il resto di questo campo DEVE essere ignorato. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza, in unità logiche, della cella o del carattere del font. Il valore dell'altezza del carattere, noto anche come dimensione em, è il valore dell'altezza della cella del carattere meno il valore iniziale interno. Il font mapper DOVREBBE interpretare il valore specificato nel campo Altezza nel modo seguente. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica un carattere corsivo se impostato su 0x01; in caso contrario, DEVE essere impostato a 0x00. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di gradi, tra la linea di base di ciascun carattere e l'asse x del dispositivo. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di output. La precisione di output di definisce quanto il carattere è richiesto per abbinare l'altezza, la larghezza, l'orientamento del carattere , lo scappamento, l'altezza e il tipo di carattere richiesti. DEVE essere un valore dall'enumerazione WMF OutPrecision |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | Ottiene o imposta un oggetto WMF PitchAndFamily ([MS-WMF] sezione 2.2.2.14) che specifica il passo e la famiglia del carattere. Le famiglie di caratteri descrivono l'aspetto di un carattere in un modo generale . Servono per specificare un carattere quando il carattere tipografico specificato non è disponibile. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica la qualità dell'output. La qualità di output definisce quanto cercare di far corrispondere gli attributi del font logico a quelli di un font fisico effettivo. DEVE essere uno dei valori nell'enumerazione WMF FontQuality ([MS-WMF] sezione 2.1.1.10). |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica un carattere barrato se impostato su 0x01; altrimenti, DEVE essere impostato su 0x00. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | Ottiene o imposta un intero senza segno a 8 bit che specifica un carattere sottolineato se impostato su 0x01; altrimenti DEVE essere impostato a 0x00. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica lo spessore del carattere nell'intervallo da da zero a 1000. Ad esempio, 400 è normale e 700 è grassetto. Se questo valore è zero, è possibile utilizzare un peso predefinito . |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza media, in unità logiche, di caratteri nel font. Se il valore del campo Larghezza è zero, un valore appropriato DOVREBBE essere calcolato da altri valori LogFont per trovare un font che abbia le proporzioni previste dal tipografo |

### Guarda anche

* class [EmfObject](../emfobject)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
