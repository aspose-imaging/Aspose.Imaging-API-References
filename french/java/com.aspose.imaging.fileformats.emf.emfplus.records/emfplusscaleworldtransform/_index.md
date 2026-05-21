---
title: "EmfPlusScaleWorldTransform"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusScaleWorldTransform effectue un redimensionnement sur la transformation de l'espace mondial actuel."
type: docs
weight: 52
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusScaleWorldTransform effectue un redimensionnement sur la transformation de l'espace mondial actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusScaleWorldTransform`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtient une valeur indiquant si [post multiplied matrix]. |
| [getSx()](#getSx--) | Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle horizontal. |
| [setSx(float value)](#setSx-float-) | Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle horizontal. |
| [getSy()](#getSy--) | Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle vertical. |
| [setSy(float value)](#setSy-float-) | Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle vertical. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusScaleWorldTransform`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Obtient une valeur indiquant si [post multiplied matrix]. Si elle est définie, la matrice de transformation doit être post‑multipliée. Si elle est désactivée, elle doit être pré‑multipliée.

Valeur : `true` si [post multiplied matrix] ; sinon, `false`.

**Returns:**
boolean
### getSx() {#getSx--}
```
public float getSx()
```


Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle horizontal. Le redimensionnement est effectué en construisant une nouvelle matrice de transformation à partir des valeurs des champs Sx et Sy, comme le montre le tableau suivant. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figure 3 : Matrice de transformation d’échelle

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle horizontal. Le redimensionnement est effectué en construisant une nouvelle matrice de transformation à partir des valeurs des champs Sx et Sy, comme le montre le tableau suivant. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figure 3 : Matrice de transformation d’échelle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle vertical.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Obtient ou définit une valeur flottante de 32 bits qui définit le facteur d'échelle vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

