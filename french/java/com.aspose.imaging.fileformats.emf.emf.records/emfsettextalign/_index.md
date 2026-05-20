---
title: "EmfSetTextAlign"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETTEXTALIGN spécifie l'alignement du texte."
type: docs
weight: 139
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

L'enregistrement EMR\_SETTEXTALIGN spécifie l'alignement du texte.

Les enregistrements EMR\_SMALLTEXTOUT, EMR\_EXTTEXTOUTA et EMR\_EXTTEXTOUTW utilisent des valeurs d'alignement du texte pour positionner une chaîne de texte sur le support de sortie. Ces valeurs spécifient la relation entre un point de référence et un rectangle qui encadre le texte. Le point de référence est soit la position actuelle, soit un point transmis à un enregistrement de sortie de texte. Le rectangle qui encadre le texte est formé par les cellules de caractères de la chaîne de texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetTextAlign`. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Initialise une nouvelle instance de la classe `EmfSetTextAlign`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'alignement du texte en utilisant un masque de drapeaux d'alignement du texte. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'alignement du texte en utilisant un masque de drapeaux d'alignement du texte. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetTextAlign`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Initialise une nouvelle instance de la classe `EmfSetTextAlign`.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'alignement du texte en utilisant un masque de drapeaux d'alignement du texte. Il s'agit soit de `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.3) pour le texte avec une ligne de base horizontale, soit de `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.4) pour le texte avec une ligne de base verticale. Une seule valeur peut être choisie parmi celles qui affectent l'alignement horizontal et vertical.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'alignement du texte en utilisant un masque de drapeaux d'alignement du texte. Il s'agit soit de `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.3) pour le texte avec une ligne de base horizontale, soit de `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] section 2.1.2.4) pour le texte avec une ligne de base verticale. Une seule valeur peut être choisie parmi celles qui affectent l'alignement horizontal et vertical.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

