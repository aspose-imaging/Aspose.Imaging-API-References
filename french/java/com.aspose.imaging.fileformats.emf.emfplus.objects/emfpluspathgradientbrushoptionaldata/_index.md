---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusPathGradientBrushOptionalData spécifie des données optionnelles pour une brosse à dégradé de chemin."
type: docs
weight: 60
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

L'objet EmfPlusPathGradientBrushOptionalData spécifie des données optionnelles pour une brosse à dégradé de chemin.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de dégradé de chemin. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtient ou définit un objet EmfPlusTransformMatrix optionnel (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de dégradé de chemin. |
| [getBlendPattern()](#getBlendPattern--) | Obtient ou définit un motif de fusion facultatif pour la brosse de dégradé de chemin. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Obtient ou définit un motif de fusion facultatif pour la brosse de dégradé de chemin. |
| [getFocusScaleData()](#getFocusScaleData--) | Obtient ou définit un objet EmfPlusFocusScaleData facultatif (section 2.2.2.18) qui spécifie les échelles de mise au point pour la brosse de dégradé de chemin. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Obtient ou définit un objet EmfPlusFocusScaleData facultatif (section 2.2.2.18) qui spécifie les échelles de mise au point pour la brosse de dégradé de chemin. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtient ou définit un objet EmfPlusTransformMatrix facultatif (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour la brosse de dégradé de chemin. Ce champ DOIT être présent si le drapeau BrushDataTransform est défini dans le champ BrushDataFlags de l'objet EmfPlusPathGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtient ou définit un objet EmfPlusTransformMatrix facultatif (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour la brosse de dégradé de chemin. Ce champ DOIT être présent si le drapeau BrushDataTransform est défini dans le champ BrushDataFlags de l'objet EmfPlusPathGradientBrushData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Obtient ou définit un motif de fusion facultatif pour la brosse de dégradé de chemin. Si ce champ est présent, il DOIT contenir soit un objet EmfPlusBlendColors (section 2.2.2.4), soit un objet EmfPlusBlendFactors (section 2.2.2.5), mais il NE DOIT PAS contenir les deux. Le tableau ci‑dessous montre les combinaisons valides des drapeaux BrushData de EmfPlusPathGradientBrushData et les motifs de fusion correspondants :

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Obtient ou définit un motif de fusion facultatif pour la brosse de dégradé de chemin. Si ce champ est présent, il DOIT contenir soit un objet EmfPlusBlendColors (section 2.2.2.4), soit un objet EmfPlusBlendFactors (section 2.2.2.5), mais il NE DOIT PAS contenir les deux. Le tableau ci‑dessous montre les combinaisons valides des drapeaux BrushData de EmfPlusPathGradientBrushData et les motifs de fusion correspondants :

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Obtient ou définit un objet EmfPlusFocusScaleData facultatif (section 2.2.2.18) qui spécifie les échelles de mise au point pour la brosse de dégradé de chemin. Ce champ DOIT être présent si le drapeau BrushDataFocusScales est défini dans le champ BrushDataFlags de l'objet EmfPlusPathGradientBrushData.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Obtient ou définit un objet EmfPlusFocusScaleData facultatif (section 2.2.2.18) qui spécifie les échelles de mise au point pour la brosse de dégradé de chemin. Ce champ DOIT être présent si le drapeau BrushDataFocusScales est défini dans le champ BrushDataFlags de l'objet EmfPlusPathGradientBrushData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

