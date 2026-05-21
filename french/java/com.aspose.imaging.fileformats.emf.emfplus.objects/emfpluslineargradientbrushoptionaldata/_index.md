---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusLinearGradientBrushOptionalData spécifie des données optionnelles pour une brosse à dégradé linéaire."
type: docs
weight: 54
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

L'objet EmfPlusLinearGradientBrushOptionalData spécifie des données optionnelles pour une brosse à dégradé linéaire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de dégradé linéaire. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de dégradé linéaire. |
| [getBlendPattern()](#getBlendPattern--) | Obtient ou définit un motif de mélange optionnel pour le pinceau de dégradé linéaire. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Obtient ou définit un motif de mélange optionnel pour le pinceau de dégradé linéaire. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Obtient le motif de mélange sous forme de couleurs prédéfinies. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Obtient le motif de mélange sous forme de facteurs de mélange h. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Obtient le motif de mélange sous forme de facteurs de mélange v. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de dégradé linéaire. Ce champ DOIT être présent si le drapeau BrushDataTransform est défini dans le champ BrushDataFlags de l'objet EmfPlusLinearGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Obtient ou définit un objet optionnel EmfPlusTransformMatrix (section 2.2.2.47) qui spécifie une transformation de l'espace mondial vers l'espace dispositif pour le pinceau de dégradé linéaire. Ce champ DOIT être présent si le drapeau BrushDataTransform est défini dans le champ BrushDataFlags de l'objet EmfPlusLinearGradientBrushData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Obtient ou définit un motif de mélange optionnel pour le pinceau de dégradé linéaire. Si ce champ est présent, il DOIT contenir soit un objet EmfPlusBlendColors (section 2.2.2.4), soit un ou deux objets EmfPlusBlendFactors (section 2.2.2.5), mais il NE DOIT PAS contenir les deux. Le tableau ci‑dessous montre les combinaisons valides des drapeaux BrushData de EmfPlusLinearGradientBrushData et les motifs de mélange correspondants : EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Obtient ou définit un motif de mélange optionnel pour le pinceau de dégradé linéaire. Si ce champ est présent, il DOIT contenir soit un objet EmfPlusBlendColors (section 2.2.2.4), soit un ou deux objets EmfPlusBlendFactors (section 2.2.2.5), mais il NE DOIT PAS contenir les deux. Le tableau ci‑dessous montre les combinaisons valides des drapeaux BrushData de EmfPlusLinearGradientBrushData et les motifs de mélange correspondants : EmfPlusBlendFactors

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Obtient le motif de mélange sous forme de couleurs prédéfinies.

Valeur : Le motif de mélange sous forme de couleurs prédéfinies.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Obtient le motif de mélange sous forme de facteurs de mélange h.

Valeur : Le motif de mélange sous forme de facteurs de mélange h.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Obtient le motif de mélange sous forme de facteurs de mélange v.

Valeur : Le motif de mélange sous forme de facteurs de mélange v.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
