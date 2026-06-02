---
title: "WmfSetMapperFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_SETMAPPERFLAGS définit l'algorithme que le mapper de polices utilise lorsqu'il associe des polices logiques à des polices physiques."
type: docs
weight: 78
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

L'enregistrement META\_SETMAPPERFLAGS définit l'algorithme que le mappeur de polices utilise lorsqu'il associe des polices logiques à des polices physiques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | Obtient ou définit les valeurs du mapper. |
| [setMapperValues(int value)](#setMapperValues-int-) | Obtient ou définit les valeurs du mapper. |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


Obtient ou définit les valeurs du mapper.

Valeur : Le mapper de polices tente d'associer le rapport d'aspect d'une police au rapport d'aspect du dispositif actuel. Si le bit zéro est défini, le mapper ne sélectionne que les polices correspondantes.

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


Obtient ou définit les valeurs du mapper.

Valeur : Le mapper de polices tente d'associer le rapport d'aspect d'une police au rapport d'aspect du dispositif actuel. Si le bit zéro est défini, le mapper ne sélectionne que les polices correspondantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

