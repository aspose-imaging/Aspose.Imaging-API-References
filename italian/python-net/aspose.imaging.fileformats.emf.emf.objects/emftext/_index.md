---
title: "Classe EmfText"
type: docs
weight: 260
url: /it/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfText()](#EmfText__1) | Inizializza una nuova istanza della classe EmfText |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| chars | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nella stringa |
| dx_buffer | int[] | r/w | Ottiene o imposta il buffer opzionale di spaziatura dei caratteri<br/>            UndefinedSpace2 (variabile): Un numero opzionale di byte inutilizzati. Il campo OutputDx non è obbligatorio <br/>            seguire immediatamente la parte precedente di questa struttura.<br/>            OutputDx (variabile): Un array di interi senza segno a 32 bit che specificano la spaziatura di output tra <br/>            le origini delle celle di caratteri adiacenti in unità logiche. La posizione di questo campo è specificata dal <br/>            valore di offDx in byte dall'inizio di questo record. Se la spaziatura è definita, questo campo contiene <br/>            lo stesso numero di valori dei caratteri nella stringa di output. Se il campo Options dell'oggetto EmrText <br/>            contiene il flag ETO_PDY, allora questo buffer contiene il doppio dei valori rispetto ai caratteri nella <br/>            stringa di output, un offset orizzontale e uno verticale per ciascuno, in quest'ordine. Se è specificato ETO_RTLREADING, <br/>            i caratteri sono disposti da destra a sinistra invece che da sinistra a destra. Nessun'altra opzione influisce sull'interpretazione di questo campo. |
| glyph_index_buffer | int[] | r/w | Ottiene o imposta il buffer opzionale degli indici dei glifi.<br/>            Se le opzioni hanno il flag ETO_GLYPH_INDEX, allora i codici dei caratteri in una stringa di testo di output sono in realtà indici<br/>            dei glifi dei caratteri in un font TrueType (enumerazione ExtTextOutOptions 2.1.11). Gli indici dei glifi sono specifici del font,<br/>            quindi per visualizzare correttamente i caratteri durante la riproduzione, il font utilizzato DEVE essere identico al font usato per<br/>            generare gli indici. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come utilizzare il rettangolo specificato nel campo <br/>            Rectangle. Questo campo può essere una combinazione di più valori dell'enumerazione ExtTextOutOptions <br/>            (sezione 2.1.11). |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL opzionale ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di ritaglio <br/>            e/o di opacizzazione in unità logiche. Questo rettangolo è applicato all'output di testo <br/>            eseguito dal record contenitore. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica le coordinate del <br/>            punto di riferimento usato per posizionare la stringa. Il punto di riferimento è definito dall'ultimo <br/>            record EMR_SETTEXTALIGN (sezione 2.3.11.25). Se non è stato impostato alcun record del genere, <br/>            l'allineamento predefinito è TA_LEFT,TA_TOP. |
| string_buffer | string | r/w | Ottiene o imposta il buffer della stringa di caratteri<br/>            UndefinedSpace1 (variabile): Un numero opzionale di byte inutilizzati. <br/>            Il campo OutputString non è obbligatorio seguire immediatamente la parte precedente di questa struttura.<br/>            OutputString (variabile): Un array di caratteri che specificano la stringa da outputtare. <br/>            La posizione di questo campo è specificata dal valore di offString in byte dall'inizio di questo record. <br/>            Il numero di caratteri è specificato dal valore di Chars. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

Inizializza una nuova istanza della classe EmfText

