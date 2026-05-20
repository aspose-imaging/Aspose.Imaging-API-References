---
title: "EmfRop4"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Une opération raster quaternaire qui spécifie des opérations raster ternaires pour les couleurs de premier plan et d'arrière-plan d'un bitmap."
type: docs
weight: 110
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

Une opération raster quaternaire, qui spécifie des opérations raster ternaires pour les couleurs de premier plan et d'arrière-plan d'un bitmap. Ces valeurs définissent comment les données couleur du rectangle source doivent être combinées avec les données couleur du rectangle de destination.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | Initialise une nouvelle instance de la classe `EmfRop4`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | Obtient le ROP3 d'arrière-plan. |
| [getForegroundRop3()](#getForegroundRop3--) | Obtient le ROP3 de premier plan. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


Initialise une nouvelle instance de la classe `EmfRop4`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dwordData | int | Les données dword. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


Obtient le ROP3 d'arrière-plan. Les 8 bits les plus significatifs non signés d'une valeur d'opération raster ternaire de 24 bits provenant de l'énumération WMF Ternary Raster Operation ([MS-WMF] section 2.1.1.31). Ce code définit comment combiner les données de couleur d'arrière-plan des bitmaps source et destination ainsi que le motif du pinceau.

Valeur : le ROP3 d'arrière-plan.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


Obtient le ROP3 de premier plan. Les 8 bits les plus significatifs non signés d'une valeur d'opération raster ternaire de 24 bits provenant de l'énumération WMF Ternary Raster Operation. Ce code définit comment combiner les données de couleur de premier plan des bitmaps source et destination ainsi que le motif du pinceau.

Valeur : le ROP3 de premier plan.

**Returns:**
byte
