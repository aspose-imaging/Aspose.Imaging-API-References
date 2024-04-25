---
title: EmfPlusStringFormat
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto EmfPlusStringFormat specifica il layout del testo le manipolazioni di visualizzazione e lidentificazione della lingua
type: docs
weight: 5780
url: /it/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

L'oggetto EmfPlusStringFormat specifica il layout del testo, le manipolazioni di visualizzazione e l'identificazione della lingua

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier che specifica la lingua da utilizzare per le cifre numeriche nella stringa. Ad esempio, se questa stringa contiene cifre arabe, questo campo DEVE contenere un identificatore di lingua che specifica una lingua araba |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come sostituire cifre numeriche nella stringa in base a una locale o lingua. Questo valore DEVE essere definito nell'enumerazione StringDigitSubstitution (sezione 2.1.1.30). |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | Ottiene o imposta un numero intero con segno a 32 bit che specifica il tipo di elaborazione eseguita su una stringa quando viene rilevato un prefisso di scelta rapida da tastiera (ovvero una e commerciale). Fondamentalmente, questo campo specifica se visualizzare i prefissi di scelta rapida da tastiera che si riferiscono al testo. Il valore DEVE essere definito nell'enumerazione HotkeyPrefix (sezione 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier (sezione 2.2.2.23) che specifica la lingua da utilizzare per la stringa |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da aggiungere alla posizione iniziale di una stringa. Il valore predefinito è 1/6 di pollice; per i caratteri tipografici, il valore predefinito di è 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare la stringa verticalmente nel rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringAlignment. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di oggetti EmfPlusCharacterRange (sezione 2.2.2.8) definiti nel campo StringFormatData. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come allineare la stringa orizzontalmente nel rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringAlignment (sezione 2.1.1.29). |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | Ottiene o imposta un oggetto EmfPlusStringFormatData (sezione 2.2.2.44) che specifica i dati di layout del testo opzionali. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di layout del testo per la formattazione, il ritaglio e la gestione dei caratteri. Questo valore DEVE essere composto da flag StringFormat (sezione 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di tabulazioni definito nel campo StringFormatData. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il rapporto dello spazio orizzontale assegnato a ciascun carattere in una stringa specificata rispetto alla larghezza definita dal carattere del carattere . Valori grandi per questa proprietà specificano ampio spazio tra i caratteri; valori inferiori a 1 possono produrre sovrapposizione di caratteri. L'impostazione predefinita è 1,03; per i caratteri tipografici , il valore predefinito è 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza dello spazio da lasciare dopo una stringa. Il valore predefinito è 1/6 di pollice; per i caratteri tipografici, il valore predefinito è 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Ottiene o imposta come ritagliare i caratteri da una stringa che è troppo grande per rientrare in un rettangolo di layout. Questo valore DEVE essere definito nell'enumerazione StringTrimming (sezione 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Ottiene o imposta la versione. |

### Guarda anche

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
