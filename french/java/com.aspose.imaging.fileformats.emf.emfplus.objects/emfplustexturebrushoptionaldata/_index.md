---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusTextureBrushOptionalData spécifie des données optionnelles pour un pinceau de texture."
type: docs
weight: 78
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

L'objet EmfPlusTextureBrushOptionalData spécifie des données optionnelles pour un pinceau de texture.

Note Chaque champ de cet objet est facultatif et peut ne pas être présent dans le champ OptionalData d'un objet EmfPlusTextureBrushData (section 2.2.2.45), selon les indicateurs BrushData (section 2.1.2.1) définis dans son champ BrushDataFlags. Bien qu'il ne soit pas pratique de représenter chaque combinaison possible de champs présents ou absents, cette section spécifie leur ordre relatif dans l'objet. L'implémenteur est responsable de déterminer quels champs sont réellement présents dans un enregistrement de métafichier donné, et de désérialiser les données pour chaque champ séparément et de manière appropriée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de texture. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de texture. |
| [getImageObject()](#getImageObject--) | Obtient ou définit un objet EmfPlusImage optionnel (section 2.2.1.4) qui spécifie la texture du pinceau. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Obtient ou définit un objet EmfPlusImage optionnel (section 2.2.1.4) qui spécifie la texture du pinceau. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de texture. Ce champ DOIT être présent si le drapeau BrushDataTransform est défini dans le champ BrushDataFlags de l'objet EmfPlusTextureBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de texture. Ce champ DOIT être présent si le drapeau BrushDataTransform est défini dans le champ BrushDataFlags de l'objet EmfPlusTextureBrushData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Obtient ou définit un objet EmfPlusImage optionnel (section 2.2.1.4) qui spécifie la texture du pinceau. Ce champ DOIT être présent si la taille de l'enregistrement EmfPlusObject (section 2.3.5.1) qui définit ce pinceau de texture est suffisamment grande pour contenir un objet EmfPlusImage en plus des champs obligatoires de l'objet EmfPlusTextureBrushData et éventuellement un objet EmfPlusTransformMatrix.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Obtient ou définit un objet EmfPlusImage optionnel (section 2.2.1.4) qui spécifie la texture du pinceau. Ce champ DOIT être présent si la taille de l'enregistrement EmfPlusObject (section 2.3.5.1) qui définit ce pinceau de texture est suffisamment grande pour contenir un objet EmfPlusImage en plus des champs obligatoires de l'objet EmfPlusTextureBrushData et éventuellement un objet EmfPlusTransformMatrix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

