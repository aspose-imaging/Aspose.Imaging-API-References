---
title: "EmfPlusColorBalanceEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet ColorBalanceEffect spécifie les ajustements des quantités relatives de rouge, vert et bleu dans une image."
type: docs
weight: 26
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

L'objet ColorBalanceEffect spécifie des ajustements des quantités relatives de rouge, vert et bleu dans une image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de rouge dans l'image. |
| [setCyanRed(int value)](#setCyanRed-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de rouge dans l'image. |
| [getMagentaGreen()](#getMagentaGreen--) | Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de vert dans l'image. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de vert dans l'image. |
| [getYellowBlue()](#getYellowBlue--) | Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de bleu dans l'image. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de bleu dans l'image. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de rouge dans l'image. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, la quantité de rouge dans l'image DOIT diminuer et la quantité de cyan DOIT augmenter. 0 Une valeur de 0 indique que les quantités de rouge et de cyan NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, la quantité de rouge dans l'image DOIT augmenter et la quantité de cyan DOIT diminuer.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de rouge dans l'image. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, la quantité de rouge dans l'image DOIT diminuer et la quantité de cyan DOIT augmenter. 0 Une valeur de 0 indique que les quantités de rouge et de cyan NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, la quantité de rouge dans l'image DOIT augmenter et la quantité de cyan DOIT diminuer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de vert dans l'image. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, la quantité de vert dans l'image DOIT diminuer et la quantité de magenta DOIT augmenter. 0 Une valeur de 0 indique que les quantités de vert et de magenta NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, la quantité de vert dans l'image DOIT augmenter et la quantité de magenta DOIT diminuer.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de vert dans l'image. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, la quantité de vert dans l'image DOIT diminuer et la quantité de magenta DOIT augmenter. 0 Une valeur de 0 indique que les quantités de vert et de magenta NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, la quantité de vert dans l'image DOIT augmenter et la quantité de magenta DOIT diminuer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de bleu dans l'image. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, la quantité de bleu dans l'image DOIT diminuer et la quantité de jaune DOIT augmenter. 0 Une valeur de 0 indique que les quantités de bleu et de jaune NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, la quantité de bleu dans l'image DOIT augmenter et la quantité de jaune DOIT diminuer.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie une variation de la quantité de bleu dans l'image. Cette valeur DOIT être dans la plage -100 à 100, avec les effets suivants : -100 \\u2264 valeur < 0 À mesure que la valeur diminue, la quantité de bleu dans l'image DOIT diminuer et la quantité de jaune DOIT augmenter. 0 Une valeur de 0 indique que les quantités de bleu et de jaune NE DOIVENT PAS changer. 0 < valeur \\u2264 100 À mesure que la valeur augmente, la quantité de bleu dans l'image DOIT augmenter et la quantité de jaune DOIT diminuer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

