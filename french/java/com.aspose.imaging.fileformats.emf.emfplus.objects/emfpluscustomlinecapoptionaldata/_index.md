---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmfPlusCustomLineCapOptionalData spécifie des données de remplissage et de contour optionnelles pour un bouchon de ligne personnalisé."
type: docs
weight: 37
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

L'objet EmfPlusCustomLineCapOptionalData spécifie des données de remplissage et de contour optionnelles pour un bouchon de ligne personnalisé.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillData()](#getFillData--) | Obtient ou définit l'objet optionnel EmfPlusFillPath (section 2.2.2.17) qui spécifie le chemin de remplissage d'une coiffe de ligne graphique personnalisée. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | Obtient ou définit l'objet optionnel EmfPlusFillPath (section 2.2.2.17) qui spécifie le chemin de remplissage d'une coiffe de ligne graphique personnalisée. |
| [getOutlineData()](#getOutlineData--) | Obtient ou définit l'objet optionnel EmfPlusLinePath (section 2.2.2.26) qui spécifie le chemin de contour d'une coiffe de ligne graphique personnalisée. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | Obtient ou définit l'objet optionnel EmfPlusLinePath (section 2.2.2.26) qui spécifie le chemin de contour d'une coiffe de ligne graphique personnalisée. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


Obtient ou définit l'objet optionnel EmfPlusFillPath (section 2.2.2.17) qui spécifie le chemin de remplissage d'une coiffe de ligne graphique personnalisée. Ce champ DOIT être présent si le drapeau CustomLineCapDataFillPath est défini dans le champ CustomLineCapDataFlags de l'objet EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


Obtient ou définit l'objet optionnel EmfPlusFillPath (section 2.2.2.17) qui spécifie le chemin de remplissage d'une coiffe de ligne graphique personnalisée. Ce champ DOIT être présent si le drapeau CustomLineCapDataFillPath est défini dans le champ CustomLineCapDataFlags de l'objet EmfPlusCustomLineCapData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


Obtient ou définit l'objet optionnel EmfPlusLinePath (section 2.2.2.26) qui spécifie le chemin de contour d'une coiffe de ligne graphique personnalisée. Ce champ DOIT être présent si le drapeau CustomLineCapDataLinePath est défini dans le champ CustomLineCapDataFlags de l'objet EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


Obtient ou définit l'objet optionnel EmfPlusLinePath (section 2.2.2.26) qui spécifie le chemin de contour d'une coiffe de ligne graphique personnalisée. Ce champ DOIT être présent si le drapeau CustomLineCapDataLinePath est défini dans le champ CustomLineCapDataFlags de l'objet EmfPlusCustomLineCapData.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |

