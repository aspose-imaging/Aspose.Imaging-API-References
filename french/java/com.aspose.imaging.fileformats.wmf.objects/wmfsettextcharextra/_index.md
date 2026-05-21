---
title: "WmfSetTextCharExtra"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_SETTEXTCHAREXTRA définit l'espacement inter-caractères pour la justification du texte dans le contexte du dispositif de lecture."
type: docs
weight: 86
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

L'enregistrement META\_SETTEXTCHAREXTRA définit l'espacement inter-caractères pour la justification du texte dans le contexte du dispositif de lecture. L'espacement est ajouté à l'espace blanc entre chaque caractère, y compris les caractères ``, lorsqu'une ligne de texte justifié est produite.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Obtient ou définit l'extra de caractère. |
| [setCharExtra(int value)](#setCharExtra-int-) | Obtient ou définit l'extra de caractère. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Obtient ou définit l'extra de caractère.

Valeur : La quantité d'espace supplémentaire, en unités logiques, à ajouter à chaque caractère. Si le mode de cartographie actuel n'est pas MM\_TEXT, cette valeur est transformée et arrondie au pixel le plus proche. Pour plus de détails sur la définition du mode de cartographie, voir META\_SETMAPMODE (section 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Obtient ou définit l'extra de caractère.

Valeur : La quantité d'espace supplémentaire, en unités logiques, à ajouter à chaque caractère. Si le mode de cartographie actuel n'est pas MM\_TEXT, cette valeur est transformée et arrondie au pixel le plus proche. Pour plus de détails sur la définition du mode de cartographie, voir META\_SETMAPMODE (section 2.3.5.17).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

