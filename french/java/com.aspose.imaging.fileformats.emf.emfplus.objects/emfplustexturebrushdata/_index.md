---
title: "EmfPlusTextureBrushData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusTextureBrushData spécifie une image de texture pour un pinceau graphique."
type: docs
weight: 77
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

L'objet EmfPlusTextureBrushData spécifie une image de texture pour un pinceau graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. |
| [getWrapMode()](#getWrapMode--) | Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie comment répéter l'image de texture sur une forme, lorsque l'image est plus petite que la zone à remplir. |
| [setWrapMode(int value)](#setWrapMode-int-) | Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie comment répéter l'image de texture sur une forme, lorsque l'image est plus petite que la zone à remplir. |
| [getOptionalData()](#getOptionalData--) | Obtient ou définit un objet optionnel EmfPlusTextureBrushOptionalData (section 2.2.2.46) qui spécifie des données supplémentaires pour le pinceau de texture. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Obtient ou définit un objet optionnel EmfPlusTextureBrushOptionalData (section 2.2.2.46) qui spécifie des données supplémentaires pour le pinceau de texture. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée des drapeaux BrushData (section 2.1.2.1). Les drapeaux suivants sont pertinents pour un pinceau de texture : BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les données dans le champ OptionalData. Cette valeur DOIT être composée des drapeaux BrushData (section 2.1.2.1). Les drapeaux suivants sont pertinents pour un pinceau de texture : BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie comment répéter l'image de texture sur une forme, lorsque l'image est plus petite que la zone à remplir.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Obtient ou définit un entier signé de 32 bits provenant de l'énumération WrapMode (section 2.1.1.34) qui spécifie comment répéter l'image de texture sur une forme, lorsque l'image est plus petite que la zone à remplir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Obtient ou définit un objet optionnel EmfPlusTextureBrushOptionalData (section 2.2.2.46) qui spécifie des données supplémentaires pour le pinceau de texture. Le contenu spécifique de ce champ est déterminé par la valeur du champ BrushDataFlags.

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Obtient ou définit un objet optionnel EmfPlusTextureBrushOptionalData (section 2.2.2.46) qui spécifie des données supplémentaires pour le pinceau de texture. Le contenu spécifique de ce champ est déterminé par la valeur du champ BrushDataFlags.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

