---
title: "EmfPlusBlurEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet BlurEffect spécifie une diminution de la différence d'intensité entre les pixels d'une image."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBlurEffect extends EmfPlusImageEffectsObjectType
```

L'objet BlurEffect spécifie une diminution de la différence d'intensité entre les pixels d'une image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de flou en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. |
| [setBlurRadius(float value)](#setBlurRadius-float-) | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de flou en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. |
| [getExpandEdge()](#getExpandEdge--) | Obtient ou définit une valeur booléenne de 32 bits qui indique si le bitmap s'étend d'une quantité égale à la valeur de BlurRadius pour produire des bords doux. |
| [setExpandEdge(boolean value)](#setExpandEdge-boolean-) | Obtient ou définit une valeur booléenne de 32 bits qui indique si le bitmap s'étend d'une quantité égale à la valeur de BlurRadius pour produire des bords doux. |
### EmfPlusBlurEffect() {#EmfPlusBlurEffect--}
```
public EmfPlusBlurEffect()
```


### getBlurRadius() {#getBlurRadius--}
```
public float getBlurRadius()
```


Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de flou en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. Cette valeur DOIT être comprise entre 0,0 et 255,0.

**Returns:**
float
### setBlurRadius(float value) {#setBlurRadius-float-}
```
public void setBlurRadius(float value)
```


Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de flou en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. Cette valeur DOIT être comprise entre 0,0 et 255,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getExpandEdge() {#getExpandEdge--}
```
public boolean getExpandEdge()
```


Obtient ou définit une valeur booléenne de 32 bits qui indique si le bitmap s'étend d'une quantité égale à la valeur de BlurRadius pour produire des bords doux. Cette valeur DOIT être l'une des suivantes : FALSE 0x00000000 La taille du bitmap NE DOIT PAS changer, et ses bords doux DOIVENT être découpés à la taille de BlurRadius. TRUE 0x00000001 La taille du bitmap DOIT s'étendre d'une quantité égale à BlurRadius pour produire des bords doux.

**Returns:**
boolean
### setExpandEdge(boolean value) {#setExpandEdge-boolean-}
```
public void setExpandEdge(boolean value)
```


Obtient ou définit une valeur booléenne de 32 bits qui indique si le bitmap s'étend d'une quantité égale à la valeur de BlurRadius pour produire des bords doux. Cette valeur DOIT être l'une des suivantes : FALSE 0x00000000 La taille du bitmap NE DOIT PAS changer, et ses bords doux DOIVENT être découpés à la taille de BlurRadius. TRUE 0x00000001 La taille du bitmap DOIT s'étendre d'une quantité égale à BlurRadius pour produire des bords doux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

