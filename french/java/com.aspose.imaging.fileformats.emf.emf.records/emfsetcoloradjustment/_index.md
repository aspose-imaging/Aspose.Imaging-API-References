---
title: "EmfSetColorAdjustment"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETCOLORADJUSTMENT spécifie les propriétés d'ajustement des couleurs dans le contexte du dispositif de lecture."
type: docs
weight: 122
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

L'enregistrement EMR\_SETCOLORADJUSTMENT spécifie les propriétés d'ajustement des couleurs dans le contexte de dispositif de lecture.

Les valeurs d'ajustement des couleurs sont utilisées pour ajuster la couleur d'entrée du bitmap source lors des opérations graphiques effectuées par les enregistrements EMR\_STRETCHBLT et EMR\_STRETCHDIBITS lorsque le mode STRETCH\_HALFTONE est défini à partir de l'énumération StretchMode (section 2.1.32). L'objet ColorAdjustment spécifié par cet enregistrement DOIT être utilisé dans les opérations graphiques qui nécessitent un objet ColorAdjustment, jusqu'à ce qu'un autre objet ColorAdjustment soit spécifié par un autre enregistrement EMR\_SETCOLORADJUSTMENT, ou jusqu'à ce que l'objet soit supprimé par un enregistrement EMR\_DELETEOBJECT.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetColorAdjustment`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Obtient ou définit un objet ColorAdjustment (section 2.2.2) qui spécifie les valeurs d'ajustement des couleurs. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Obtient ou définit un objet ColorAdjustment (section 2.2.2) qui spécifie les valeurs d'ajustement des couleurs. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetColorAdjustment`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Obtient ou définit un objet ColorAdjustment (section 2.2.2) qui spécifie les valeurs d'ajustement des couleurs.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Obtient ou définit un objet ColorAdjustment (section 2.2.2) qui spécifie les valeurs d'ajustement des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

