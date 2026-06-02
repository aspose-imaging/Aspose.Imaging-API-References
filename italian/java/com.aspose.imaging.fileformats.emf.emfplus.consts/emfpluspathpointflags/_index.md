---
title: "EmfPlusPathPointFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto."
type: docs
weight: 38
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

Un intero senza segno a 32 bit che specifica come interpretare i punti e i tipi di punto associati definiti da questo oggetto. C (1 bit): Se impostato, l'array PathPoints specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, l'array PathPoints specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota Se il flag P (sotto) è impostato, questo flag PUÒ essere non impostato e DEVE essere ignorato. R (1 bit): Se impostato, i tipi di punto nell'array PathPointTypes sono specificati da oggetti EmfPlusPathPointTypeRle (sezione 2.2.2.32), che utilizzano la compressione run-length encoding (RLE), e/o da oggetti EmfPlusPathPointType (sezione 2.2.2.31). Vedere la sezione [MS-WMF] 3.1.6 per ulteriori informazioni sulla compressione RLE. Se non impostato, i tipi di punto nell'array PathPointTypes sono specificati da oggetti EmfPlusPathPointType. P (1 bit): Se impostato, ogni elemento dell'array PathPoints specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente dell'array. Nel caso del primo elemento in PathPoints, si assume una posizione precedente alle coordinate (0,0). Se non impostato, ogni elemento dell'array PathPoints specifica una posizione assoluta.
## Campi

| Campo | Descrizione |
| --- | --- |
| [C](#C) | Il flag c |
| [R](#R) | Il flag r |
| [P](#P) | Il flag p |
### C {#C}
```
public static final short C
```


Il flag c

### R {#R}
```
public static final short R
```


Il flag r

### P {#P}
```
public static final short P
```


Il flag p

