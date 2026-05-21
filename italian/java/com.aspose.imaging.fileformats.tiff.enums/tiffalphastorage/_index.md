---
title: "TiffAlphaStorage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica l'archiviazione alfa per i documenti tiff."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffAlphaStorage extends System.Enum
```

Specifica l'archiviazione alfa per i documenti tiff.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Unspecified](#Unspecified) | L'alpha non è specificato e viene memorizzato nel file tiff. |
| [Associated](#Associated) | Il valore alpha è memorizzato in forma premoltiplicata. |
| [Unassociated](#Unassociated) | Il valore alpha è memorizzato in forma non associata. |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


L'alpha non è specificato e viene memorizzato nel file tiff.

### Associated {#Associated}
```
public static final int Associated
```


Il valore alpha è memorizzato in forma premoltiplicata. Quando l'alpha viene ripristinato potrebbero verificarsi alcuni effetti di arrotondamento e il valore ripristinato potrebbe differire dall'originale.

### Unassociated {#Unassociated}
```
public static final int Unassociated
```


Il valore alfa è memorizzato in forma non associata. Ciò significa che l'alfa ripristinato è esattamente lo stesso di quello memorizzato nel tiff.

