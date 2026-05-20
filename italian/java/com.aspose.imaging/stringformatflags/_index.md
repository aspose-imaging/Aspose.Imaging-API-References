---
title: "StringFormatFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica le informazioni di visualizzazione e layout per le stringhe di testo."
type: docs
weight: 113
url: /it/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Specifica le informazioni di visualizzazione e layout per le stringhe di testo.
## Campi

| Campo | Descrizione |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Il testo è visualizzato da destra a sinistra. |
| [DirectionVertical](#DirectionVertical) | Il testo è allineato verticalmente. |
| [FitBlackBox](#FitBlackBox) | Le parti dei caratteri possono sporgere dal rettangolo di layout della stringa. |
| [DisplayFormatControl](#DisplayFormatControl) | I caratteri di controllo, come il segno da sinistra a destra, sono mostrati nell'output con un glifo rappresentativo. |
| [NoFontFallback](#NoFontFallback) | Il ricorso a font alternativi per i caratteri non supportati nel font richiesto è disabilitato. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Include lo spazio finale alla fine di ogni riga. |
| [NoWrap](#NoWrap) | L'andare a capo del testo tra le righe durante la formattazione all'interno di un rettangolo è disabilitato. |
| [LineLimit](#LineLimit) | Solo le righe intere vengono disposte nel rettangolo di formattazione. |
| [NoClip](#NoClip) | Le parti sporgenti dei glifi e il testo non a capo che si estende fuori dal rettangolo di formattazione possono essere visualizzati. |
| [ExactAlignment](#ExactAlignment) | L'allineamento esatto, il corretto padding GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Il testo è visualizzato da destra a sinistra.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Il testo è allineato verticalmente.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Le parti dei caratteri possono sporgere dal rettangolo di layout della stringa. Per impostazione predefinita, i caratteri vengono riposizionati per evitare qualsiasi sporgenza.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


I caratteri di controllo, come il segno da sinistra a destra, sono mostrati nell'output con un glifo rappresentativo.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Il ricorso a font alternativi per i caratteri non supportati nel font richiesto è disabilitato. Qualsiasi carattere mancante viene visualizzato con il glifo mancante del font, solitamente un quadrato vuoto.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Include lo spazio finale alla fine di ogni riga. Per impostazione predefinita il rettangolo di confine restituito dal metodo MeasureString esclude lo spazio alla fine di ogni riga. Imposta questo flag per includere quello spazio nella misurazione.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


L'andare a capo del testo tra le righe durante la formattazione all'interno di un rettangolo è disabilitato. Questo flag è implicito quando viene passato un punto invece di un rettangolo, o quando il rettangolo specificato ha una lunghezza di linea zero.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Solo le righe intere vengono disposte nel rettangolo di formattazione. Per impostazione predefinita il layout continua fino alla fine del testo, o fino a quando non sono più visibili altre righe a causa del ritaglio, a seconda di quale evento si verifichi per primo. Nota che le impostazioni predefinite consentono all'ultima riga di essere parzialmente oscurata da un rettangolo di formattazione che non è un multiplo intero dell'altezza della riga. Per garantire che vengano visualizzate solo righe intere, specifica questo valore e fai attenzione a fornire un rettangolo di formattazione alto almeno quanto l'altezza di una riga.

### NoClip {#NoClip}
```
public static final int NoClip
```


Le parti sporgenti dei glifi e il testo non a capo che si estende fuori dal rettangolo di formattazione possono essere visualizzati. Per impostazione predefinita, tutto il testo e le parti dei glifi che si estendono fuori dal rettangolo di formattazione vengono ritagliati.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


L'allineamento esatto, il corretto padding GDI+

