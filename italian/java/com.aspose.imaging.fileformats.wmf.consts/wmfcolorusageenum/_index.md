---
title: "WmfColorUsageEnum"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione ColorUsage specifica se una tavola dei colori esiste in un bitmap indipendente dal dispositivo (DIB) e come interpretare i suoi valori."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

L'enumerazione ColorUsage specifica se una tavola dei colori esiste in un bitmap indipendente dal dispositivo (DIB) e come interpretare i suoi valori.
## Campi

| Campo | Descrizione |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | La tavola dei colori contiene valori RGB specificati da oggetti RGBQuad (sezione 2.2.2.20). |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | La tavola dei colori contiene indici a 16 bit nella palette logica corrente nel contesto del dispositivo di riproduzione. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | Non esiste alcuna tabella dei colori. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


La tavola dei colori contiene valori RGB specificati da oggetti RGBQuad (sezione 2.2.2.20).

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


La tavola dei colori contiene indici a 16 bit nella palette logica corrente nel contesto del dispositivo di riproduzione.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


Non esiste alcuna tabella dei colori. I pixel nel DIB sono indici nella palette logica corrente nel contesto del dispositivo di riproduzione.

