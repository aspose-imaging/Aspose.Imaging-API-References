---
title: "EmfPlusStringFormatFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I flag StringFormat specificano le opzioni per il layout del testo grafico, inclusi direzione, ritaglio e gestione dei font."
type: docs
weight: 50
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

I flag StringFormat specificano le opzioni per il layout del testo grafico, inclusi direzione, ritaglio e gestione dei font. Questi flag possono essere combinati per specificare più opzioni.
## Campi

| Campo | Descrizione |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | Se impostato, l'ordine di lettura della stringa DEVE essere da destra a sinistra. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | Se impostato, le singole righe di testo DEVE essere disegnate verticalmente sul dispositivo di visualizzazione. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | Se impostato, le parti dei caratteri DEVONO poter sporgere fuori dal rettangolo di layout del testo. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | Se impostato, i caratteri di controllo DEVONO apparire nell'output come glifi Unicode rappresentativi. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | Se impostato, un font alternativo DEVE essere usato per i caratteri non supportati nel font richiesto. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | Se impostato, lo spazio alla fine di ogni riga DEVE essere incluso nelle misurazioni della lunghezza della stringa. |
| [StringFormatNoWrap](#StringFormatNoWrap) | Se impostato, una stringa che si estende oltre la fine del rettangolo di layout del testo NON DEVE essere avvolta alla riga successiva. |
| [StringFormatLineLimit](#StringFormatLineLimit) | Se impostato, le intere righe di testo DEVONO essere emesse e NON DEVONO essere tagliate dal rettangolo di layout della stringa. |
| [StringFormatNoClip](#StringFormatNoClip) | Se impostato, il testo che si estende fuori dal rettangolo di layout della stringa DEVE essere consentito di mostrarsi. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | Questo flag PUÒ essere usato per specificare un processo specifico dell'implementazione per il rendering del testo. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


Se impostato, l'ordine di lettura della stringa DEVE essere da destra a sinistra. Per il testo orizzontale, ciò significa che i caratteri sono letti da destra a sinistra. Per il testo verticale, ciò significa che le colonne sono lette da destra a sinistra. Se non impostato, il testo orizzontale o verticale DEVE essere letto da sinistra a destra.

--------------------

Il layout del testo grafico è specificato dagli oggetti [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat).

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


Se impostato, le singole righe di testo DEVONO essere disegnate verticalmente sul dispositivo di visualizzazione. Se non impostato, le singole righe di testo DEVONO essere disegnate orizzontalmente, con ogni nuova riga sotto la precedente.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


Se impostato, le parti dei caratteri DEVONO poter sporgere fuori dal rettangolo di layout del testo. Se non impostato, i caratteri che sporgono oltre i confini del rettangolo di layout del testo DEVONO essere riposizionati per evitare la sporgenza. Un carattere in corsivo, "f", è un esempio di carattere che può avere parti sporgenti.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


Se impostato, i caratteri di controllo DEVONO apparire nell'output come glifi Unicode rappresentativi.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


Se impostato, un font alternativo DEVE essere usato per i caratteri non supportati nel font richiesto. Se non impostato, un carattere mancante nel font richiesto DEVE apparire come un carattere "font missing", che PUÒ essere un quadrato vuoto.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


Se impostato, lo spazio alla fine di ogni riga DEVE essere incluso nelle misurazioni della lunghezza della stringa. Se non impostato, lo spazio alla fine di ogni riga DEVE essere escluso dalle misurazioni della lunghezza della stringa.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


Se impostato, una stringa che si estende oltre la fine del rettangolo di layout del testo NON DEVE essere avvolta alla riga successiva. Se non impostato, una stringa che si estende oltre la fine del rettangolo di layout del testo DEVE essere interrotta all'ultimo confine di parola all'interno del rettangolo di delimitazione, e la parte rimanente della stringa DEVE essere avvolta alla riga successiva.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


Se impostato, le intere righe di testo DEVONO essere emesse e NON DEVONO essere tagliate dal rettangolo di layout della stringa. Se non impostato, il layout del testo DEVONO continuare fino a quando tutte le righe sono emesse, o fino a quando righe aggiuntive non sarebbero visibili a causa del ritaglio. Questo flag può essere usato sia per negare sia per consentire che una riga di testo sia parzialmente oscurata da un rettangolo di layout che non è un multiplo dell'altezza della riga. Per rendere tutto il testo visibile, il rettangolo di layout deve essere alto almeno quanto l'altezza di una riga.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


Se impostato, il testo che si estende fuori dal rettangolo di layout della stringa DEVE essere consentito di mostrarsi. Se non impostato, tutto il testo che si estende fuori dal rettangolo di layout DEVE essere tagliato.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


Questo flag PUÒ essere usato per specificare un processo specifico dell'implementazione per il rendering del testo.

