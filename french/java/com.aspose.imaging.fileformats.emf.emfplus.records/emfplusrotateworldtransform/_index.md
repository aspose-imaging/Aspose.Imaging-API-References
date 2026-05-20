---
title: "EmfPlusRotateWorldTransform"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusRotateWorldTransform effectue une rotation sur la transformation de l'espace mondial actuel."
type: docs
weight: 50
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusRotateWorldTransform effectue une rotation sur la transformation de l'espace mondial actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusRotateWorldTransform`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtient une valeur indiquant si [post multiplied matrix]. |
| [getAngle()](#getAngle--) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie l'angle de rotation en degrés. |
| [setAngle(float value)](#setAngle-float-) | Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie l'angle de rotation en degrés. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusRotateWorldTransform`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Obtient une valeur indiquant si [post multiplied matrix]. Si défini, la matrice de transformation doit être post‑multipliée. Si non défini, elle doit être pré‑multipliée.

Valeur : `true` si [post multiplied matrix] ; sinon, `false`.

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie l'angle de rotation en degrés. L'opération est effectuée en construisant une nouvelle matrice de transformation à partir du diagramme suivant : ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Figure 2 : Matrice de transformation de rotation La transformation de l'espace mondial actuel est multipliée par cette matrice, et le résultat devient la nouvelle transformation de l'espace mondial actuel. Le champ Flags détermine l'ordre de multiplication.

Valeur : l'angle.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Obtient ou définit une valeur à virgule flottante de 32 bits qui spécifie l'angle de rotation en degrés. L'opération est effectuée en construisant une nouvelle matrice de transformation à partir du diagramme suivant : ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Figure 2 : Matrice de transformation de rotation La transformation de l'espace mondial actuel est multipliée par cette matrice, et le résultat devient la nouvelle transformation de l'espace mondial actuel. Le champ Flags détermine l'ordre de multiplication.

Valeur : l'angle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

