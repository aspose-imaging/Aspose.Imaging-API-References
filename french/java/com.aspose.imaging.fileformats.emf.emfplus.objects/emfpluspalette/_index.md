---
title: "EmfPlusPalette"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusPalette spécifie les couleurs qui composent une palette."
type: docs
weight: 57
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

L'objet EmfPlusPalette spécifie les couleurs qui composent une palette.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Obtient ou définit les indicateurs de style de la palette. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Obtient ou définit les indicateurs de style de la palette. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtient ou définit les entrées de la palette. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Obtient ou définit les entrées de la palette. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Obtient ou définit les indicateurs de style de la palette.

Valeur : PaletteStyleFlags (4 octets) : Un entier non signé de 32 bits qui spécifie les attributs des données dans la palette. Cette valeur DOIT être composée des indicateurs `EmfPlusPaletteStyleFlags`.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Obtient ou définit les indicateurs de style de la palette.

Valeur : PaletteStyleFlags (4 octets) : Un entier non signé de 32 bits qui spécifie les attributs des données dans la palette. Cette valeur DOIT être composée des indicateurs `EmfPlusPaletteStyleFlags`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Obtient ou définit les entrées de la palette.

Valeur : PaletteEntries (variable) : Un tableau de PaletteCount objets ARGB de 32 bits qui spécifient les données de la palette.

**Returns:**
int[] – La copie des entrées de la palette.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Obtient ou définit les entrées de la palette.

Valeur : PaletteEntries (variable) : Un tableau de PaletteCount objets ARGB de 32 bits qui spécifient les données de la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

