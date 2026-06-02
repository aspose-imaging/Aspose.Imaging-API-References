---
title: "WmfFillRegion"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_FILLREGION remplit une région en utilisant un pinceau spécifié."
type: docs
weight: 37
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

L'enregistrement META\_FILLREGION remplit une région en utilisant une brosse spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | Initialise une nouvelle instance de la classe `WmfFillRegion`. |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | Initialise une nouvelle instance de la classe `WmfFillRegion`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | Obtient ou définit l'index de la région. |
| [setRegionIndex(int value)](#setRegionIndex-int-) | Obtient ou définit l'index de la région. |
| [getBrushIndex()](#getBrushIndex--) | Obtient ou définit l'index du pinceau. |
| [setBrushIndex(int value)](#setBrushIndex-int-) | Obtient ou définit l'index du pinceau. |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


Initialise une nouvelle instance de la classe `WmfFillRegion`.

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


Initialise une nouvelle instance de la classe `WmfFillRegion`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | La région. |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Le pinceau. |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


Obtient ou définit l'index de la région.

Valeur : Index dans la table d'objets WMF pour obtenir la région à remplir.

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


Obtient ou définit l'index de la région.

Valeur : Index dans la table d'objets WMF pour obtenir la région à remplir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


Obtient ou définit l'index du pinceau.

Valeur : Index dans la table d'objets WMF pour obtenir le pinceau à utiliser pour remplir la région.

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


Obtient ou définit l'index du pinceau.

Valeur : Index dans la table d'objets WMF pour obtenir le pinceau à utiliser pour remplir la région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

