---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I flag DriverStringOptions specificano le proprietà del posizionamento e del rendering del testo grafico."
type: docs
weight: 21
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

I flag DriverStringOptions specificano le proprietà del posizionamento e del rendering del testo grafico. Questi flag possono essere combinati per specificare più opzioni.

--------------------

L'output del testo grafico è specificato nei record [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring)
## Campi

| Campo | Descrizione |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | Se impostato, le posizioni dei glifi dei caratteri DEVONO essere specificate in una tabella di ricerca della mappa dei caratteri. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | Se impostato, la stringa DEVE essere renderizzata verticalmente. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | Se impostato, le posizioni dei glifi dei caratteri DEVONO essere calcolate rispetto alla posizione del primo glifo. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | Se impostato, DEVE essere utilizzata meno memoria per memorizzare nella cache i glifi antialias, il che produce un rendering del testo di qualità inferiore. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


Se impostato, le posizioni dei glifi dei caratteri DEVONO essere specificate in una tabella di ricerca della mappa dei caratteri. Se non impostato, le posizioni dei glifi DEVONO essere ottenute da un array di coordinate.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


Se impostato, la stringa DEVE essere renderizzata verticalmente. Se non impostato, la stringa DEVE essere renderizzata orizzontalmente.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


Se impostato, le posizioni dei glifi dei caratteri DEVONO essere calcolate rispetto alla posizione del primo glifo. Se non impostato, le posizioni dei glifi DEVONO essere ottenute da un array di coordinate.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


Se impostato, DEVE essere utilizzata meno memoria per memorizzare nella cache i glifi antialias, il che produce un rendering del testo di qualità inferiore. Se non impostato, DEVE essere utilizzata più memoria, il che produce un rendering del testo di qualità superiore.

