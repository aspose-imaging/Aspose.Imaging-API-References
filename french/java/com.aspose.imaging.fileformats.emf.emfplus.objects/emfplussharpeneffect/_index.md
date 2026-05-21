---
title: "EmfPlusSharpenEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet SharpenEffect spécifie une augmentation de la différence d'intensité entre les pixels d'une image."
type: docs
weight: 72
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusSharpenEffect extends EmfPlusImageEffectsObjectType
```

L'objet SharpenEffect spécifie une augmentation de la différence d'intensité entre les pixels d'une image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de netteté en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. |
| [setRadius(float value)](#setRadius-float-) | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de netteté en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. |
| [getAmount()](#getAmount--) | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie la différence d'intensité entre un pixel donné et les pixels environnants. |
| [setAmount(float value)](#setAmount-float-) | Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie la différence d'intensité entre un pixel donné et les pixels environnants. |
### EmfPlusSharpenEffect() {#EmfPlusSharpenEffect--}
```
public EmfPlusSharpenEffect()
```


### getRadius() {#getRadius--}
```
public float getRadius()
```


Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de netteté en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. À mesure que cette valeur augmente, le nombre de pixels impliqués dans le calcul augmente, et le bitmap résultant DOIT devenir plus net.

Valeur : le rayon.

**Returns:**
float
### setRadius(float value) {#setRadius-float-}
```
public void setRadius(float value)
```


Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie le rayon de netteté en pixels, ce qui détermine le nombre de pixels impliqués dans le calcul de la nouvelle valeur d'un pixel donné. À mesure que cette valeur augmente, le nombre de pixels impliqués dans le calcul augmente, et le bitmap résultant DOIT devenir plus net.

Valeur : le rayon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getAmount() {#getAmount--}
```
public float getAmount()
```


Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie la différence d'intensité entre un pixel donné et les pixels environnants. 0 indique que la netteté NE DOIT PAS être effectuée. 0 < valeur \\u2264 100 À mesure que cette valeur augmente, la différence d'intensité entre les pixels DOIT augmenter.

Valeur : la quantité.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public void setAmount(float value)
```


Obtient ou définit un nombre à virgule flottante de 32 bits qui spécifie la différence d'intensité entre un pixel donné et les pixels environnants. 0 indique que la netteté NE DOIT PAS être effectuée. 0 < valeur \\u2264 100 À mesure que cette valeur augmente, la différence d'intensité entre les pixels DOIT augmenter.

Valeur : la quantité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

