---
title: "TiffAlphaStorage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica el almacenamiento alfa para documentos tiff."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffAlphaStorage extends System.Enum
```

Especifica el almacenamiento alfa para documentos tiff.
## Campos

| Campo | Descripción |
| --- | --- |
| [Unspecified](#Unspecified) | El alfa no está especificado y se almacena en el archivo tiff. |
| [Associated](#Associated) | El valor alfa se almacena en forma premultiplicada. |
| [Unassociated](#Unassociated) | El valor alfa se almacena en forma no asociada. |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


El alfa no está especificado y se almacena en el archivo tiff.

### Associated {#Associated}
```
public static final int Associated
```


El valor alfa se almacena en forma premultiplicada. Cuando se restaura el alfa, pueden producirse algunos efectos de redondeo y el valor restaurado puede ser diferente del original.

### Unassociated {#Unassociated}
```
public static final int Unassociated
```


El valor alfa se almacena en forma no asociada. Eso significa que el alfa restaurado es exactamente el mismo que se almacenó en el tiff.

