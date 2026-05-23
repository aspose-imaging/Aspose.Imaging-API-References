---
title: "EmfPlusStringFormat Classe"
type: docs
weight: 650
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | Inizializza una nuova istanza della classe EmfPlusStringFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier che specifica la<br/>            lingua da usare per le cifre numeriche nella stringa.<br/>            Ad esempio, se questa stringa contiene cifre arabe,<br/>            questo campo DEVE contenere un identificatore di lingua che<br/>            specifichi una lingua araba |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come sostituire<br/>            le cifre numeriche nella stringa in base a una locale o lingua.<br/>            Questo valore DEVE essere definito nell'enumerazione StringDigitSubstitution<br/>            (sezione 2.1.1.30). |
| first_tab_offset | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il numero<br/>            di spazi tra l'inizio di una riga di testo e<br/>            la prima tabulazione |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il tipo di<br/>            elaborazione eseguita su una stringa quando viene incontrato un prefisso di scorciatoia da tastiera (cioè, un e commerciale).<br/>            In pratica, questo campo specifica se visualizzare<br/>            i prefissi delle scorciatoie da tastiera relativi al testo.<br/>            Il valore DEVE essere definito nell'enumerazione HotkeyPrefix<br/>            (sezione 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Ottiene o imposta un oggetto EmfPlusLanguageIdentifier (sezione 2.2.2.23)<br/>            che specifica la lingua da utilizzare per la stringa |
| leading_margin | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza<br/>            dello spazio da aggiungere alla posizione iniziale di una stringa.<br/>            Il valore predefinito è 1/6 di pollice; per i caratteri tipografici, il<br/>            valore predefinito è 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come<br/>            allineare verticalmente la stringa nel rettangolo di layout.<br/>            Questo valore DEVE essere definito nell'enumerazione StringAlignment. |
| range_count | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di oggetti EmfPlusCharacterRange<br/>            (sezione 2.2.2.8) definiti nel campo StringFormatData. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come<br/>            allineare orizzontalmente la stringa nel rettangolo di layout.<br/>            Questo valore DEVE essere definito nell'enumerazione StringAlignment<br/>            (sezione 2.1.1.29). |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Ottiene o imposta un oggetto EmfPlusStringFormatData (sezione 2.2.2.44)<br/>            che specifica i dati opzionali di layout del testo. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di layout del testo<br/>            per la formattazione, il ritaglio e la gestione dei caratteri.<br/>            Questo valore DEVE essere composto da flag StringFormat<br/>            (sezione 2.1.2.8). |
| tabstop_count | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica il numero di tabulazioni<br/>            definite nel campo StringFormatData. |
| tracking | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica il rapporto<br/>            dello spazio orizzontale assegnato a ciascun carattere in<br/>            una stringa specificata rispetto alla larghezza definita dal carattere.<br/>            Valori elevati per questa proprietà indicano ampio<br/>            spazio tra i caratteri; valori inferiori a 1 possono produrre<br/>            sovrapposizione di caratteri. Il valore predefinito è 1.03; per i caratteri tipografici, il valore predefinito è 1.00. |
| trailing_margin | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la lunghezza<br/>            dello spazio da lasciare dopo una stringa. Il valore predefinito<br/>            è 1/6 di pollice; per i caratteri tipografici, il valore predefinito è 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Ottiene o imposta specifica come tagliare i caratteri da una stringa che è<br/>            troppo grande per entrare in un rettangolo di layout. Questo valore<br/>            DEVE essere definito nell'enumerazione StringTrimming (sezione 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Ottiene o imposta la versione. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

Inizializza una nuova istanza della classe EmfPlusStringFormat

