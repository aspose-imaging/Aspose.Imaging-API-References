---
title: "EmfPlusTintEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet TintEffect spécifie l'ajout de noir ou de blanc à une teinte spécifiée dans une image."
type: docs
weight: 79
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusTintEffect extends EmfPlusImageEffectsObjectType
```

L'objet TintEffect spécifie l'ajout de noir ou de blanc à une teinte spécifiée dans une image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHue()](#getHue--) | Obtient ou définit un entier signé de 32 bits qui spécifie la teinte à laquelle l'effet de teinte est appliqué. |
| [setHue(int value)](#setHue-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la teinte à laquelle l'effet de teinte est appliqué. |
| [getAmount()](#getAmount--) | Obtient ou définit un entier signé de 32 bits qui indique dans quelle mesure la teinte est renforcée ou atténuée. |
| [setAmount(int value)](#setAmount-int-) | Obtient ou définit un entier signé de 32 bits qui indique dans quelle mesure la teinte est renforcée ou atténuée. |
### EmfPlusTintEffect() {#EmfPlusTintEffect--}
```
public EmfPlusTintEffect()
```


### getHue() {#getHue--}
```
public int getHue()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la teinte à laquelle l'effet de teinte est appliqué. -180 \\u2264 valeur < 0 La couleur à une rotation antihoraire spécifiée de la roue des couleurs, en partant du bleu. 0 Une valeur de 0 indique la couleur bleue sur la roue des couleurs. 0 < valeur \\u2264 180 La couleur à une rotation horaire spécifiée de la roue des couleurs, en partant du bleu

**Returns:**
int
### setHue(int value) {#setHue-int-}
```
public void setHue(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la teinte à laquelle l'effet de teinte est appliqué. -180 \\u2264 valeur < 0 La couleur à une rotation antihoraire spécifiée de la roue des couleurs, en partant du bleu. 0 Une valeur de 0 indique la couleur bleue sur la roue des couleurs. 0 < valeur \\u2264 180 La couleur à une rotation horaire spécifiée de la roue des couleurs, en partant du bleu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getAmount() {#getAmount--}
```
public int getAmount()
```


Obtient ou définit un entier signé de 32 bits qui indique dans quelle mesure la teinte est renforcée ou atténuée. -100 \\u2264 valeur < 0 Les valeurs négatives indiquent dans quelle mesure la teinte est atténuée, ce qui équivaut à l'ajout de noir. 0 Une valeur de 0 indique que la teinte NE DOIT PAS changer. 0 < valeur \\u2264 100 Les valeurs positives indiquent dans quelle mesure la teinte est renforcée, ce qui équivaut à l'ajout de blanc.

Valeur : la quantité.

**Returns:**
int
### setAmount(int value) {#setAmount-int-}
```
public void setAmount(int value)
```


Obtient ou définit un entier signé de 32 bits qui indique dans quelle mesure la teinte est renforcée ou atténuée. -100 \\u2264 valeur < 0 Les valeurs négatives indiquent dans quelle mesure la teinte est atténuée, ce qui équivaut à l'ajout de noir. 0 Une valeur de 0 indique que la teinte NE DOIT PAS changer. 0 < valeur \\u2264 100 Les valeurs positives indiquent dans quelle mesure la teinte est renforcée, ce qui équivaut à l'ajout de blanc.

Valeur : la quantité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

