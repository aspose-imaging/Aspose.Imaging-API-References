---
title: "EmfPlusBrightnessContrastEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet BrightnessContrastEffect spécifie une expansion ou une contraction des zones les plus claires et les plus sombres d'une image."
type: docs
weight: 23
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusBrightnessContrastEffect extends EmfPlusImageEffectsObjectType
```

L'objet BrightnessContrastEffect spécifie une expansion ou une contraction des zones les plus claires et les plus sombres d'une image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBrightnessContrastEffect()](#EmfPlusBrightnessContrastEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrightnessLevel()](#getBrightnessLevel--) | Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de luminosité. |
| [setBrightnessLevel(int value)](#setBrightnessLevel-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de luminosité. |
| [getContrastLevel()](#getContrastLevel--) | Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de contraste. |
| [setContrastLevel(int value)](#setContrastLevel-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de contraste. |
### EmfPlusBrightnessContrastEffect() {#EmfPlusBrightnessContrastEffect--}
```
public EmfPlusBrightnessContrastEffect()
```


### getBrightnessLevel() {#getBrightnessLevel--}
```
public int getBrightnessLevel()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de luminosité. Cette valeur DOIT être dans la plage -255 à 255, avec les effets suivants : -255 \\u2264 valeur < 0 À mesure que la valeur diminue, la luminosité de l'image DOIT diminuer. 0 Une valeur de 0 indique que la luminosité NE DOIT PAS changer. 0 < valeur \\u2264 255 À mesure que la valeur augmente, la luminosité de l'image DOIT augmenter.

**Returns:**
int
### setBrightnessLevel(int value) {#setBrightnessLevel-int-}
```
public void setBrightnessLevel(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de luminosité. Cette valeur DOIT être dans la plage -255 à 255, avec les effets suivants : -255 \\u2264 valeur < 0 À mesure que la valeur diminue, la luminosité de l'image DOIT diminuer. 0 Une valeur de 0 indique que la luminosité NE DOIT PAS changer. 0 < valeur \\u2264 255 À mesure que la valeur augmente, la luminosité de l'image DOIT augmenter.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getContrastLevel() {#getContrastLevel--}
```
public int getContrastLevel()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de contraste. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, le contraste de l'image DOIT diminuer. 0 Une valeur de 0 indique que le contraste NE DOIT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, le contraste de l'image DOIT augmenter.

**Returns:**
int
### setContrastLevel(int value) {#setContrastLevel-int-}
```
public void setContrastLevel(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le niveau de contraste. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, le contraste de l'image DOIT diminuer. 0 Une valeur de 0 indique que le contraste NE DOIT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, le contraste de l'image DOIT augmenter.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

