---
title: "EmfPlusBlendBase"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Objet de base pour les objets de fusion"
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Objet de base pour les objets de fusion
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Obtient ou définit les positions de mélange un tableau de PositionCount valeurs à virgule flottante de 32 bits qui spécifient les proportions de distance le long de la ligne de dégradé. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Obtient ou définit les positions de mélange un tableau de PositionCount valeurs à virgule flottante de 32 bits qui spécifient les proportions de distance le long de la ligne de dégradé. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Obtient ou définit les positions de mélange un tableau de PositionCount valeurs à virgule flottante de 32 bits qui spécifient les proportions de distance le long de la ligne de dégradé. Chaque élément DOIT être un nombre compris entre 0,0 et 1,0 inclus. Pour un pinceau de dégradé linéaire, 0,0 représente le point de départ et 1,0 représente le point d'arrivée. Pour un pinceau de dégradé de tracé, 0,0 représente le point médian et 1,0 représente un point final.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Obtient ou définit les positions de mélange un tableau de PositionCount valeurs à virgule flottante de 32 bits qui spécifient les proportions de distance le long de la ligne de dégradé. Chaque élément DOIT être un nombre compris entre 0,0 et 1,0 inclus. Pour un pinceau de dégradé linéaire, 0,0 représente le point de départ et 1,0 représente le point d'arrivée. Pour un pinceau de dégradé de tracé, 0,0 représente le point médian et 1,0 représente un point final.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] |  |

