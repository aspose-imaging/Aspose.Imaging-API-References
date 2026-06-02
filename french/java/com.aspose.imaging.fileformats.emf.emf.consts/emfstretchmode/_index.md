---
title: "EmfStretchMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération StretchMode est utilisée pour spécifier comment les données de couleur sont ajoutées ou supprimées des images bitmap qui sont étirées ou compressées."
type: docs
weight: 43
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

L'énumération StretchMode est utilisée pour spécifier comment les données de couleur sont ajoutées ou supprimées des images bitmap qui sont étirées ou compressées.
## Champs

| Champ | Description |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Effectue une opération booléenne AND en utilisant les valeurs de couleur pour les pixels éliminés et existants. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Effectue une opération booléenne OR en utilisant les valeurs de couleur pour les pixels éliminés et existants. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Supprime les pixels. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Mappe les pixels du rectangle source en blocs de pixels dans le rectangle de destination. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Effectue une opération booléenne AND en utilisant les valeurs de couleur des pixels éliminés et existants. Si le bitmap est un bitmap monochrome, ce mode préserve les pixels noirs au détriment des pixels blancs.

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Effectue une opération booléenne OR en utilisant les valeurs de couleur des pixels éliminés et existants. Si le bitmap est un bitmap monochrome, ce mode préserve les pixels blancs au détriment des pixels noirs.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Supprime les pixels. Ce mode supprime toutes les lignes de pixels éliminées sans essayer de préserver leurs informations.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Mappe les pixels du rectangle source en blocs de pixels dans le rectangle de destination. La couleur moyenne du bloc de pixels de destination approxime la couleur des pixels source.

