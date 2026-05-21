---
title: "EmfPlusRedEyeCorrectionEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet RedEyeCorrectionEffect spécifie les zones d'une image auxquelles une correction des yeux rouges est appliquée."
type: docs
weight: 67
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusredeyecorrectioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusRedEyeCorrectionEffect extends EmfPlusImageEffectsObjectType
```

L'objet RedEyeCorrectionEffect spécifie les zones d'une image auxquelles une correction des yeux rouges est appliquée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusRedEyeCorrectionEffect()](#EmfPlusRedEyeCorrectionEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNumberOfAreas()](#getNumberOfAreas--) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de rectangles dans le champ Areas. |
| [setNumberOfAreas(int value)](#setNumberOfAreas-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de rectangles dans le champ Areas. |
| [getAreas()](#getAreas--) | Obtient ou définit un tableau d'objets NumberOfAreas WMF RectL, spécifié dans la section 2.2.2.19 de [MS-WMF]. |
| [setAreas(Rectangle[] value)](#setAreas-com.aspose.imaging.Rectangle---) | Obtient ou définit un tableau d'objets NumberOfAreas WMF RectL, spécifié dans la section 2.2.2.19 de [MS-WMF]. |
### EmfPlusRedEyeCorrectionEffect() {#EmfPlusRedEyeCorrectionEffect--}
```
public EmfPlusRedEyeCorrectionEffect()
```


### getNumberOfAreas() {#getNumberOfAreas--}
```
public int getNumberOfAreas()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de rectangles dans le champ Areas.

Valeur : le nombre de zones.

**Returns:**
int
### setNumberOfAreas(int value) {#setNumberOfAreas-int-}
```
public void setNumberOfAreas(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de rectangles dans le champ Areas.

Valeur : le nombre de zones.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getAreas() {#getAreas--}
```
public Rectangle[] getAreas()
```


Obtient ou définit le tableau d'objets NumberOfAreas WMF RectL, spécifié dans la section 2.2.2.19 de [MS-WMF]. Chaque rectangle spécifie une zone de l'image bitmap à laquelle l'effet de correction des yeux rouges DOIT être appliqué.

Valeur : les zones.

**Returns:**
com.aspose.imaging.Rectangle[]
### setAreas(Rectangle[] value) {#setAreas-com.aspose.imaging.Rectangle---}
```
public void setAreas(Rectangle[] value)
```


Obtient ou définit le tableau d'objets NumberOfAreas WMF RectL, spécifié dans la section 2.2.2.19 de [MS-WMF]. Chaque rectangle spécifie une zone de l'image bitmap à laquelle l'effet de correction des yeux rouges DOIT être appliqué.

Valeur : les zones.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

