---
title: "EmfDibColors"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione DIBColors definisce come interpretare i valori nella tavola dei colori di un DIB."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfDibColors extends System.Enum
```

L'enumerazione DIBColors definisce come interpretare i valori nella tavola dei colori di un DIB.
## Campi

| Campo | Descrizione |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | La tabella dei colori contiene valori RGB letterali |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | La tabella dei colori è composta da un array di indici a 16 bit nell'oggetto LogPalette (sezione 2.2.17) attualmente definito nel contesto del dispositivo di riproduzione. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Non esiste alcuna tabella dei colori. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


La tabella dei colori contiene valori RGB letterali

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


La tabella dei colori è composta da un array di indici a 16 bit nell'oggetto LogPalette (sezione 2.2.17) attualmente definito nel contesto del dispositivo di riproduzione.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Non esiste alcuna tabella dei colori. I pixel nel DIB sono indici nella palette logica corrente nel contesto del dispositivo di riproduzione.

