---
title: "Classe EmfLogFontPanose"
type: docs
weight: 160
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---

**Summary:** The LogFontPanose object specifies the PANOSE characteristics of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontPanose

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfLogFontPanose(emf_log_font)](#EmfLogFontPanose_emf_log_font_1) | Inizializza una nuova istanza della classe [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica l'insieme di glifi dei caratteri. Deve <br/>            essere un valore nell'enumerazione WMF CharacterSet ([MS-WMF] sezione 2.1.1.5). Se il <br/>            set di caratteri è sconosciuto, l'elaborazione del metafile NON DOVREBBE tentare di tradurre o interpretare <br/>            le stringhe rese con quel font. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Ottiene o imposta un intero senza segno a 8 bit che specifica la precisione di ritaglio. La <br/>            precisione di ritaglio definisce come ritagliare i caratteri che sono parzialmente fuori dalla regione di ritaglio. <br/>            Può essere una o più delle flag WMF ClipPrecision. |
| culture | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che DEVE essere impostato a zero e DEVE essere ignorato. |
| escapement | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, <br/>            tra il vettore di escapement e l'asse x del dispositivo. Il vettore di escapement è <br/>            parallelo alla linea di base di una riga di testo. |
| nome carattere | string | r/w | Ottiene o imposta un Facename (64 byte):  Una stringa di non più di 32 caratteri Unicode che specifica il <br/>            nome del tipo di carattere del font. Se la lunghezza di questa stringa è inferiore a 32 caratteri, un NULL terminatore DEVE essere presente, dopo il quale il resto di questo campo DEVE essere ignorato. |
| full_name | string | r/w | Ottiene o imposta una stringa di 64 caratteri Unicode che definisce il nome completo del carattere. Se <br/>            la lunghezza di questa stringa è inferiore a 64 caratteri, deve essere presente un NULL terminatore, dopo <br/>            il quale il resto di questo campo DEVE essere ignorato. |
| height | int | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica l'altezza, in unità logiche, della cella del carattere o del carattere del font. <br/>            Il valore dell'altezza del carattere, noto anche come dimensione em, è il valore dell'altezza della cella del carattere meno il valore del leading interno. <br/>            Il mapper del font DOVREBBE interpretare il valore specificato nel campo Height nel modo seguente. |
| corsivo | System.Byte | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica un font corsivo se impostato a 0x01; altrimenti, <br/>            DEVE essere impostato a 0x00. |
| match | int | r/w | Ottiene o imposta Questo campo DEVE essere ignorato. |
| orientamento | int | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica l'angolo, in decimi di grado, <br/>            tra la linea di base di ogni carattere e l'asse x del dispositivo. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica la precisione di output. La <br/>            precisione di output definisce quanto il font deve corrispondere esattamente all'altezza, larghezza, <br/>            orientamento del carattere, escapement, pitch e tipo di font richiesti. DEVE essere un valore dell'enumerazione WMF <br/>            OutPrecision. |
| padding | int | r/w | Ottiene o imposta un campo che esiste solo per garantire l'allineamento a 32 bit di questa struttura. Deve essere ignorato |
| panose | [EmfPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpanose/) | r/w | Ottiene o imposta un oggetto Panose (sezione 2.2.21) che specifica le caratteristiche PANOSE <br/>            del carattere logico. Se tutti i campi di questo oggetto sono zero, DEVE essere ignorato. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Imposta o ottiene un oggetto WMF PitchAndFamily ([MS-WMF] sezione 2.2.2.14) che <br/>            specifica il pitch e la famiglia del font. Le famiglie di font descrivono l'aspetto di un font in modo generale. <br/>            Sono destinate a specificare un font quando il tipo di carattere specificato non è disponibile. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica la qualità di output. La qualità di output <br/>            definisce quanto cercare di far corrispondere gli attributi del font logico a quelli di un font fisico reale. DEVE essere uno dei valori dell'enumerazione WMF FontQuality ([MS-WMF] <br/>            sezione 2.1.1.10). |
| barrato | System.Byte | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica un font barrato se impostato a 0x01; <br/>            altrimenti, DEVE essere impostato a 0x00. |
| stile | string | r/w | Imposta o ottiene una stringa di 32 caratteri Unicode che definisce lo stile del font. Se la lunghezza di <br/>            questa stringa è inferiore a 32 caratteri, deve essere presente un NULL terminatore, dopo il quale <br/>            il resto di questo campo DEVE essere ignorato. |
| style_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in punti a cui viene eseguito il hinting del carattere <br/>            . Se impostato a zero, il hinting del carattere viene eseguito alla dimensione in punti corrispondente <br/>            al campo Height nell'oggetto LogFont nel campo LogFont. |
| sottolineato | System.Byte | r/w | Imposta o ottiene un intero senza segno a 8 bit che specifica un font sottolineato se impostato a 0x01; <br/>            altrimenti, DEVE essere impostato a 0x00. |
| vendor_id | int | r/w | Ottiene o imposta Questo campo DEVE essere ignorato. |
| versione | int | r/w | Ottiene o imposta Questo campo DEVE essere ignorato. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica il peso del font nell'intervallo <br/>            da zero a 1000. Per esempio, 400 è normale e 700 è grassetto. Se questo valore è zero, può essere usato un peso predefinito. |
| width | int | r/w | Imposta o ottiene un intero con segno a 32 bit che specifica la larghezza media, in unità logiche, dei <br/>            caratteri del font. Se il valore del campo Width è zero, un valore appropriato DOVREBBE essere <br/>            calcolato dagli altri valori LogFont per trovare un font che abbia il rapporto d'aspetto previsto dal tipografo. |


### Constructor: EmfLogFontPanose(emf_log_font) {#EmfLogFontPanose_emf_log_font_1}


```
 EmfLogFontPanose(emf_log_font) 
```

Inizializza una nuova istanza della classe [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | Il carattere base del log. |

