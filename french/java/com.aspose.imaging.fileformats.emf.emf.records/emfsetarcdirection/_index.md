---
title: "EmfSetArcDirection"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETARCDIRECTION spécifie la direction de dessin à utiliser pour la sortie des arcs et des rectangles."
type: docs
weight: 118
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

L'enregistrement EMR\_SETARCDIRECTION spécifie la direction de dessin à utiliser pour la sortie d'arcs et de rectangles.

L'enregistrement EMR\_SETARCDIRECTION affecte la direction dans laquelle les enregistrements suivants sont dessinés : - EMR\_ARC (section 2.3.5.2) - EMR\_ARCTO (section 2.3.5.3) - EMR\_CHORD (section 2.3.5.4) - EMR\_ELLIPSE (section 2.3.5.5) - EMR\_PIE (section 2.3.5.15) - EMR\_RECTANGLE (section 2.3.5.34) - EMR\_ROUNDRECT (section 2.3.5.35)
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetArcDirection`. |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | Initialise une nouvelle instance de la classe `EmfSetArcDirection`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la direction de l'arc. |
| [setArcDirection(int value)](#setArcDirection-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la direction de l'arc. |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetArcDirection`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


Initialise une nouvelle instance de la classe `EmfSetArcDirection`.

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la direction de l'arc. La valeur DOIT appartenir à l'énumération ArcDirection (section 2.1.2). La direction par défaut est dans le sens inverse des aiguilles d'une montre.

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la direction de l'arc. La valeur DOIT appartenir à l'énumération ArcDirection (section 2.1.2). La direction par défaut est dans le sens inverse des aiguilles d'une montre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

