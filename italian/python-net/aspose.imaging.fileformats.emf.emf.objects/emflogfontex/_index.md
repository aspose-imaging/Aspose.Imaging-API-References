---
title: "Classe EmfLogFontEx"
type: docs
weight: 140
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---

**Summary:** The LogFontEx object specifies the extended attributes of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontEx

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfLogFontEx(emf_log_font)](#EmfLogFontEx_emf_log_font_1) | Inizializza una nuova istanza della classe [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica l'insieme di glifi dei caratteri. Deve <br/>            essere un valore nell'enumerazione WMF CharacterSet ([MS-WMF] sezione 2.1.1.5). Se il <br/>            set di caratteri è sconosciuto, l'elaborazione del metafile NON DOVREBBE tentare di tradurre o interpretare <br/>            le stringhe rese con quel font. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di ritaglio. La <br/>            precisione di ritaglio definisce come ritagliare i caratteri che sono parzialmente fuori dalla regione di ritaglio. <br/>            Può essere una o più delle flag WMF ClipPrecision. |
| escapement | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, <br/>            tra il vettore di escapement e l'asse x del dispositivo. Il vettore di escapement è <br/>            parallelo alla linea di base di una riga di testo. |
| nome carattere | string | r/w | Ottiene o imposta un Facename (64 byte):  Una stringa di non più di 32 caratteri Unicode che specifica il <br/>            nome del tipo di carattere del font. Se la lunghezza di questa stringa è inferiore a 32 caratteri, un NULL terminatore DEVE essere presente, dopo il quale il resto di questo campo DEVE essere ignorato. |
| full_name | string | r/w | Ottiene o imposta una stringa di 64 caratteri Unicode che contiene il nome completo del font. Se <br/>            la lunghezza di questa stringa è inferiore a 64 caratteri, un NULL terminatore DEVE essere presente, dopo <br/>            il quale il resto di questo campo DEVE essere ignorato. |
| height | int | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica l'altezza, in unità logiche, della cella del carattere o del carattere del font. <br/>            Il valore dell'altezza del carattere, noto anche come dimensione em, è il valore dell'altezza della cella del carattere meno il valore del leading interno. <br/>            Il mapper del font DOVREBBE interpretare il valore specificato nel campo Height nel modo seguente. |
| corsivo | System.Byte | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica un font corsivo se impostato a 0x01; altrimenti, <br/>            DEVE essere impostato a 0x00. |
| orientamento | int | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, <br/>            tra la linea di base di ogni carattere e l'asse x del dispositivo. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica la precisione di output. La <br/>            precisione di output definisce quanto il font deve corrispondere esattamente all'altezza, larghezza, <br/>            orientamento del carattere, escapement, pitch e tipo di font richiesti. DEVE essere un valore dell'enumerazione WMF <br/>            OutPrecision. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Imposta o ottiene un oggetto WMF PitchAndFamily ([MS-WMF] sezione 2.2.2.14) che <br/>            specifica il pitch e la famiglia del font. Le famiglie di font descrivono l'aspetto di un font in modo generale. <br/>            Sono destinate a specificare un font quando il tipo di carattere specificato non è disponibile. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica la qualità di output. La qualità di output <br/>            definisce quanto cercare di far corrispondere gli attributi del font logico a quelli di un font fisico reale. DEVE essere uno dei valori dell'enumerazione WMF FontQuality ([MS-WMF] <br/>            sezione 2.1.1.10). |
| script | string | r/w | Imposta o ottiene una stringa di 32 caratteri Unicode che definisce il set di caratteri del font. <br/>            Se la lunghezza di questa stringa è inferiore a 32 caratteri, deve essere presente un NULL terminatore, <br/>            dopo il quale il resto di questo campo DEVE essere ignorato. |
| barrato | System.Byte | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica un font barrato se impostato a 0x01; <br/>            altrimenti, DEVE essere impostato a 0x00. |
| stile | string | r/w | Imposta o ottiene una stringa di 32 caratteri Unicode che definisce lo stile del font. Se la lunghezza di <br/>            questa stringa è inferiore a 32 caratteri, deve essere presente un NULL terminatore, dopo il quale <br/>            il resto di questo campo DEVE essere ignorato. |
| sottolineato | System.Byte | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica un font sottolineato se impostato a 0x01; <br/>            altrimenti, DEVE essere impostato a 0x00. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica il peso del font nell'intervallo <br/>            da zero a 1000. Per esempio, 400 è normale e 700 è grassetto. Se questo valore è zero, può essere usato un peso predefinito. |
| width | int | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica la larghezza media, in unità logiche, dei <br/>            caratteri del font. Se il valore del campo Width è zero, un valore appropriato DOVREBBE essere <br/>            calcolato dagli altri valori LogFont per trovare un font che abbia il rapporto d'aspetto previsto dal tipografo. |


### Constructor: EmfLogFontEx(emf_log_font) {#EmfLogFontEx_emf_log_font_1}


```
 EmfLogFontEx(emf_log_font) 
```

Inizializza una nuova istanza della classe [EmfLogFontEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontex/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | Il font di registro EMF. |

