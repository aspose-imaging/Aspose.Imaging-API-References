---
title: "EmfPlusLevelsEffect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet LevelsEffect spécifie les ajustements des hautes lumières, des tons moyens et des ombres d'une image."
type: docs
weight: 51
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

L'objet LevelsEffect spécifie les ajustements des hautes lumières, des tons moyens et des ombres d'une image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHighlight()](#getHighlight--) | Obtient ou définit le paramètre qui indique combien éclaircir les hautes lumières d'une image. |
| [setHighlight(int value)](#setHighlight-int-) | Obtient ou définit le paramètre qui indique combien éclaircir les hautes lumières d'une image. |
| [getMidTone()](#getMidTone--) | Obtient ou définit le paramètre qui indique combien éclaircir ou assombrir les tons moyens d'une image. |
| [setMidTone(int value)](#setMidTone-int-) | Obtient ou définit le paramètre qui indique combien éclaircir ou assombrir les tons moyens d'une image. |
| [getShadow()](#getShadow--) | Obtient ou définit le paramètre qui indique combien assombrir les ombres d'une image. |
| [setShadow(int value)](#setShadow-int-) | Obtient ou définit le paramètre qui indique combien assombrir les ombres d'une image. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


Obtient ou définit le paramètre qui indique combien éclaircir les hautes lumières d'une image. Les valeurs du canal de couleur à l'extrémité haute de la plage d'intensité sont modifiées davantage que les valeurs proches du milieu ou de l'extrémité basse, ce qui signifie qu'une image peut être éclaircie sans perdre le contraste entre les parties plus sombres de l'image. 0 \\u2264 valeur < Indique que les hautes lumières dont le pourcentage d'intensité dépasse ce seuil DOIVENT être augmentées. 100 Indique que les hautes lumières NE DOIVENT PAS changer.

Valeur: la lumière forte.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


Obtient ou définit le paramètre qui indique combien éclaircir les hautes lumières d'une image. Les valeurs du canal de couleur à l'extrémité haute de la plage d'intensité sont modifiées davantage que les valeurs proches du milieu ou de l'extrémité basse, ce qui signifie qu'une image peut être éclaircie sans perdre le contraste entre les parties plus sombres de l'image. 0 \\u2264 valeur < Indique que les hautes lumières dont le pourcentage d'intensité dépasse ce seuil DOIVENT être augmentées. 100 Indique que les hautes lumières NE DOIVENT PAS changer.

Valeur: la lumière forte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


Obtient ou définit le paramètre qui indique combien éclaircir ou assombrir les tons moyens d'une image. Les valeurs du canal de couleur au milieu de la plage d'intensité sont modifiées davantage que les valeurs proches des extrémités haute ou basse, ce qui signifie qu'une image peut être éclaircie ou assombrie sans perdre le contraste entre les parties les plus sombres et les plus claires de l'image. -100 \\u2264 valeur < 0 Indique que les tons moyens sont rendus plus sombres. 0 Indique que les tons moyens NE DOIVENT PAS changer. 0 < valeur \\u2264 100 Indique que les tons moyens sont rendus plus clairs.

Valeur: le ton moyen.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


Obtient ou définit le paramètre qui indique combien éclaircir ou assombrir les tons moyens d'une image. Les valeurs du canal de couleur au milieu de la plage d'intensité sont modifiées davantage que les valeurs proches des extrémités haute ou basse, ce qui signifie qu'une image peut être éclaircie ou assombrie sans perdre le contraste entre les parties les plus sombres et les plus claires de l'image. -100 \\u2264 valeur < 0 Indique que les tons moyens sont rendus plus sombres. 0 Indique que les tons moyens NE DOIVENT PAS changer. 0 < valeur \\u2264 100 Indique que les tons moyens sont rendus plus clairs.

Valeur: le ton moyen.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


Obtient ou définit le paramètre qui indique combien assombrir les ombres d'une image. Les valeurs du canal de couleur à l'extrémité basse de la plage d'intensité sont modifiées davantage que les valeurs proches du milieu ou de l'extrémité haute, ce qui signifie qu'une image peut être assombrie sans perdre le contraste entre les parties plus claires de l'image. 0 Indique que les ombres NE DOIVENT PAS changer. 0 < valeur \\u2264 100 Indique que les ombres dont le pourcentage d'intensité est inférieur à ce seuil sont rendues plus sombres.

Valeur: l'ombre.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


Obtient ou définit le paramètre qui indique combien assombrir les ombres d'une image. Les valeurs du canal de couleur à l'extrémité basse de la plage d'intensité sont modifiées davantage que les valeurs proches du milieu ou de l'extrémité haute, ce qui signifie qu'une image peut être assombrie sans perdre le contraste entre les parties plus claires de l'image. 0 Indique que les ombres NE DOIVENT PAS changer. 0 < valeur \\u2264 100 Indique que les ombres dont le pourcentage d'intensité est inférieur à ce seuil sont rendues plus sombres.

Valeur: l'ombre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

