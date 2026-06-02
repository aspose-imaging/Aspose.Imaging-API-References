---
title: "EmfPlusStringFormatFlags Enumerazione"
type: docs
weight: 410
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

I flag StringFormat specificano le opzioni per il layout del testo grafico, includendo direzione, ritaglio e gestione dei font. Questi flag possono essere combinati per specificare più opzioni.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | Questo flag PUÒ essere usato per specificare un processo specifico dell'implementazione per il rendering del testo. |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | Se impostato, l'ordine di lettura della stringa DOVREBBE essere da destra a sinistra. Per il testo orizzontale, ciò significa che i caratteri sono letti da destra a sinistra. Per il testo verticale, ciò significa che le colonne sono lette da destra a sinistra.<br/>            Se cancellato, il testo orizzontale o verticale DOVREBBE essere letto da sinistra a destra. |
| STRING_FORMAT_DIRECTION_VERTICAL | Se impostato, le singole linee di testo DOVREBBE essere disegnate verticalmente sul dispositivo di visualizzazione.<br/>            Se cancellato, le singole linee di testo DOVREBBE essere disegnate orizzontalmente, con ogni nuova linea sotto la linea precedente. |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | Se impostato, i caratteri di controllo DOVREBBE apparire nell'output come glifi Unicode rappresentativi. |
| STRING_FORMAT_LINE_LIMIT | Se impostato, le linee intere di testo DOVREBBE essere emesse e NON DOVREBBE essere ritagliate dal rettangolo di layout della stringa.<br/>            Se cancellato, il layout del testo DOVREBBE continuare fino a quando tutte le linee sono emesse, o fino a quando linee aggiuntive non sarebbero visibili a causa del ritaglio.<br/>            Questo flag può essere usato sia per negare sia per consentire che una linea di testo sia parzialmente oscurata da un rettangolo di layout che non è un multiplo dell'altezza della linea. Per rendere tutto il testo visibile, il rettangolo di layout deve essere alto almeno quanto l'altezza di una linea. |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | Se impostato, lo spazio alla fine di ogni riga DEVE essere incluso nelle misurazioni della lunghezza della stringa.<br/>            Se non impostato, lo spazio alla fine di ogni riga DEVE essere escluso dalle misurazioni della lunghezza della stringa. |
| STRING_FORMAT_NO_CLIP | Se impostato, il testo che si estende al di fuori del rettangolo di layout della stringa DOVREBBE essere visualizzato.<br/>            Se non impostato, tutto il testo che si estende al di fuori del rettangolo di layout DOVREBBE essere tagliato. |
| STRING_FORMAT_NO_FIT_BLACK_BOX | Se impostato, le parti dei caratteri DEVONO essere consentite di sporgere fuori dal rettangolo di layout del testo.<br/>            Se non impostato, i caratteri che sporgono oltre i confini del rettangolo di layout del testo DEVONO essere riposizionati per evitare la sporgenza.<br/>            Una \"f\" in corsivo è un esempio di carattere che può avere parti sporgenti. |
| STRING_FORMAT_NO_FONT_FALLBACK | Se impostato, un font alternativo DOVREBBE essere usato per i caratteri non supportati nel font richiesto.<br/>            Se non impostato, un carattere mancante nel font richiesto DOVREBBE apparire come un carattere \"font mancante\", che POTREBBE essere un quadrato vuoto. |
| STRING_FORMAT_NO_WRAP | Se impostato, una stringa che si estende oltre la fine del rettangolo di layout del testo NON DEVE essere avvolta alla riga successiva.<br/>            Se non impostato, una stringa che si estende oltre la fine del rettangolo di layout del testo DEVE essere interrotta all'ultimo confine di parola all'interno del rettangolo di delimitazione, e il resto della stringa DEVE essere avvolto alla riga successiva. |
