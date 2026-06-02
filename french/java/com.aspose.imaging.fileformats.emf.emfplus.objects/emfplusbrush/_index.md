---
title: "EmfPlusBrush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusBrush spécifie un pinceau graphique pour remplir des régions."
type: docs
weight: 24
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

L'objet EmfPlusBrush spécifie un pinceau graphique pour remplir des régions.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBrushData()](#getBrushData--) | Obtient ou définit les données du pinceau, des données de longueur variable qui définissent l'objet pinceau spécifié dans le champ Type. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Obtient ou définit les données du pinceau, des données de longueur variable qui définissent l'objet pinceau spécifié dans le champ Type. |
| [getType()](#getType--) | Obtient ou définit le type. |
| [setType(int value)](#setType-int-) | Obtient ou définit le type. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Obtient ou définit les données du pinceau. Données de longueur variable qui définissent l'objet pinceau spécifié dans le champ Type. Le contenu et le format des données peuvent varier selon chaque type de pinceau. EmfPlusHatchBrushData (section 2.2.2.20) (fait) EmfPlusLinearGradientBrushData object (section 2.2.2.24) (fait) EmfPlusPathGradientBrushData object (section 2.2.2.29) (fait) EmfPlusSolidBrushData object (section 2.2.2.43) (fait) EmfPlusTextureBrushData object (section 2.2.2.45) (fait)

Valeur : les données du pinceau.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Obtient ou définit les données du pinceau. Données de longueur variable qui définissent l'objet pinceau spécifié dans le champ Type. Le contenu et le format des données peuvent varier selon chaque type de pinceau. EmfPlusHatchBrushData (section 2.2.2.20) (fait) EmfPlusLinearGradientBrushData object (section 2.2.2.24) (fait) EmfPlusPathGradientBrushData object (section 2.2.2.29) (fait) EmfPlusSolidBrushData object (section 2.2.2.43) (fait) EmfPlusTextureBrushData object (section 2.2.2.45) (fait)

Valeur : les données du pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Obtient ou définit le type.

Valeur : un entier non signé de 32 bits qui spécifie le type de pinceau, ce qui détermine le contenu du champ BrushData. Cette valeur DOIT être définie dans l'énumération `EmfPlusBrushType`.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Obtient ou définit le type.

Valeur : un entier non signé de 32 bits qui spécifie le type de pinceau, ce qui détermine le contenu du champ BrushData. Cette valeur DOIT être définie dans l'énumération `EmfPlusBrushType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

