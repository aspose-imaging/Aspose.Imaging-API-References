---
title: "EmfExtTextOutOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione ExtTextOutOptions specifica i parametri che controllano vari aspetti dell'output del testo tramite i record EMR_SMALLTEXTOUTsection 2.3.5.37 e negli oggetti EmrText."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

L'enumerazione ExtTextOutOptions specifica i parametri che controllano vari aspetti dell'output di testo tramite i record EMR\_SMALLTEXTOUT (sezione 2.3.5.37) e negli oggetti EmrText.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | Questo bit indica che il colore di sfondo corrente DEVE essere usato per riempire il rettangolo. |
| [ETO_CLIPPED](#ETO-CLIPPED) | Questo bit indica che il testo DEVE essere ritagliato al rettangolo. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | Questo bit indica che i codici dei caratteri in una stringa di testo in output sono in realtà indici dei glifi dei caratteri in un font TrueType. |
| [ETO_RTLREADING](#ETO-RTLREADING) | Questo bit indica che il testo DEVE essere disposto in ordine di lettura da destra a sinistra, invece dell'ordine predefinito da sinistra a destra. |
| [ETO_NO_RECT](#ETO-NO-RECT) | Questo bit indica che il record non specifica un rettangolo di delimitazione per l'output del testo. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | Questo bit indica che i codici dei caratteri in una stringa di testo in output sono a 8 bit, derivati dai byte bassi dei codici Unicode UTF16-LE a 16 bit, in cui il byte alto è considerato 0. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | Questo bit indica che per visualizzare i numeri, le cifre appropriate alla locale DEVE essere usate. |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | Questo bit indica che per visualizzare i numeri, la cifra europea DEVE essere usata. |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | Questo bit indica che non deve essere eseguito alcun elaborazione speciale del sistema operativo per il posizionamento dei glifi su stringhe da destra a sinistra; cioè, tutto il posizionamento dei glifi DEVE essere gestito dai record di disegno e di stato nel metafile. |
| [ETO_PDY](#ETO-PDY) | Questo bit indica che i valori di spostamento orizzontale e verticale dei caratteri DEVONO essere forniti. |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | Questo bit è riservato e NON DEVE essere usato. |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


Questo bit indica che il colore di sfondo corrente DEVE essere usato per riempire il rettangolo.

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


Questo bit indica che il testo DEVE essere ritagliato al rettangolo.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


Questo bit indica che i codici dei caratteri in una stringa di testo in output sono in realtà indici dei glifi dei caratteri in un font TrueType. Gli indici dei glifi sono specifici del font, quindi per visualizzare i caratteri corretti durante la riproduzione, il font utilizzato DEVE essere identico al font usato per generare gli indici.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


Questo bit indica che il testo DEVE essere disposto in ordine di lettura da destra a sinistra, invece dell'ordine predefinito da sinistra a destra. Questo DEVE essere applicato solo quando il font selezionato nel contesto del dispositivo di riproduzione è ebraico o arabo.

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


Questo bit indica che il record non specifica un rettangolo di delimitazione per l'output del testo.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


Questo bit indica che i codici dei caratteri in una stringa di testo in output sono a 8 bit, derivati dai byte bassi dei codici Unicode UTF16-LE a 16 bit, in cui il byte alto è considerato 0.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


Questo bit indica che per visualizzare i numeri, le cifre appropriate alla locale DEVE essere usate.

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


Questo bit indica che per visualizzare i numeri, la cifra europea DEVE essere usata.

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


Questo bit indica che non deve essere eseguito alcun elaborazione speciale del sistema operativo per il posizionamento dei glifi su stringhe da destra a sinistra; cioè, tutto il posizionamento dei glifi DEVE essere gestito dai record di disegno e di stato nel metafile.

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


Questo bit indica che i valori di spostamento orizzontale e verticale dei caratteri DEVONO essere forniti.

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


Questo bit è riservato e NON DEVE essere usato.

