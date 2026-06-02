---
title: "TiffAlphaStorage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie le stockage alpha pour les documents tiff."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffAlphaStorage extends System.Enum
```

Spécifie le stockage alpha pour les documents tiff.
## Champs

| Champ | Description |
| --- | --- |
| [Unspecified](#Unspecified) | L'alpha n'est pas spécifié et est stocké dans le fichier tiff. |
| [Associated](#Associated) | La valeur alpha est stockée sous forme prémultipliée. |
| [Unassociated](#Unassociated) | La valeur alpha est stockée sous forme non associée. |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


L'alpha n'est pas spécifié et est stocké dans le fichier tiff.

### Associated {#Associated}
```
public static final int Associated
```


La valeur alpha est stockée sous forme prémultipliée. Lorsqu'alpha est restauré, il peut y avoir des effets d'arrondi et la valeur restaurée peut différer de l'original.

### Unassociated {#Unassociated}
```
public static final int Unassociated
```


La valeur alpha est stockée sous forme non associée. Cela signifie que l'alpha restauré est exactement le même que celui qui a été stocké dans le tiff.

