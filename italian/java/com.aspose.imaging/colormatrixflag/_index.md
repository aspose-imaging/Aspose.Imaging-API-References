---
title: "ColorMatrixFlag"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica i tipi di immagini e colori che saranno influenzati dalle impostazioni di regolazione del colore e della scala di grigi di un ."
type: docs
weight: 27
url: /it/java/com.aspose.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Specifica i tipi di immagini e colori che saranno influenzati dalle impostazioni di regolazione del colore e della scala di grigi di un [ImageAttributes](../../com.aspose.imaging/imageattributes).
## Campi

| Campo | Descrizione |
| --- | --- |
| [Default](#Default) | Tutti i valori di colore, incluse le tonalità di grigio, sono regolati dalla stessa matrice di correzione del colore. |
| [SkipGrays](#SkipGrays) | Tutti i colori sono regolati, ma le tonalità di grigio non lo sono. |
| [AltGrays](#AltGrays) | Solo le tonalità di grigio sono regolate. |
### Default {#Default}
```
public static final int Default
```


Tutti i valori di colore, incluse le tonalità di grigio, sono regolati dalla stessa matrice di correzione del colore.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Tutti i colori sono regolati, ma le tonalità di grigio non lo sono. Una tonalità di grigio è qualsiasi colore che ha lo stesso valore per i componenti rosso, verde e blu.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Solo le tonalità di grigio sono regolate.

