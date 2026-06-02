---
title: "Enumerazione EmfExtTextOutOptions"
type: docs
weight: 100
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---

L'enumerazione ExtTextOutOptions specifica i parametri che controllano vari aspetti del<br/>            output del testo tramite i record EMR_SMALLTEXTOUT (sezione 2.3.5.37) e negli oggetti EmrText.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfExtTextOutOptions

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| ETO_CLIPPED | Questo bit indica che il testo DEVE essere ritagliato al rettangolo. |
| ETO_GLYPH_INDEX | Questo bit indica che i codici per i caratteri in una stringa di testo in output sono in realtà <br/>            indici dei glifi dei caratteri in un font TrueType. Gli indici dei glifi sono specifici del font, <br/>            quindi per visualizzare i caratteri corretti durante la riproduzione, il font utilizzato DEVE essere <br/>            identico al font usato per generare gli indici. |
| ETO_IGNORELANGUAGE | Questo bit indica che nessuna elaborazione speciale del sistema operativo per il posizionamento dei glifi dovrebbe essere <br/>            eseguita su stringhe da destra a sinistra; cioè, tutto il posizionamento dei glifi DEVE essere gestito da <br/>            disegni e registri di stato nel metafile. |
| ETO_NO_RECT | Questo bit indica che il record non specifica un rettangolo di delimitazione per l'output del testo. |
| ETO_NUMERICSLATIN | Questo bit indica che per visualizzare i numeri, devono essere utilizzate cifre europee. |
| ETO_NUMERICSLOCAL | Questo bit indica che per visualizzare i numeri, devono essere utilizzate cifre appropriate alla locale. |
| ETO_OPAQUE | Questo bit indica che il colore di sfondo corrente DEVE essere usato per riempire il rettangolo. |
| ETO_PDY | Questo bit indica che devono essere forniti sia i valori di spostamento orizzontale che verticale dei caratteri. |
| ETO_REVERSE_INDEX_MAP | Questo bit è riservato e NON DEVE essere utilizzato |
| ETO_RTLREADING | Questo bit indica che il testo DEVE essere disposto in ordine di lettura da destra a sinistra, <br/>            invece dell'ordine predefinito da sinistra a destra. Questo DEVE essere applicato solo quando il carattere<br/>            selezionato nel contesto del dispositivo di riproduzione è ebraico o arabo |
| ETO_SMALL_CHARS | Questo bit indica che i codici per i caratteri in una stringa di testo in output sono a 8 bit, <br/>            derivati dai byte bassi dei codici di carattere Unicode UTF16-LE a 16 bit, <br/>            in cui il byte alto è considerato 0. |
