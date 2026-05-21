---
title: "EmfCreateBrushIndirect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_CREATEBRUSHINDIRECT définit un pinceau logique pour les opérations graphiques."
type: docs
weight: 35
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_CREATEBRUSHINDIRECT définit un pinceau logique pour les opérations graphiques.

L'objet pinceau logique défini par cet enregistrement peut être sélectionné dans le contexte de périphérique de lecture par un enregistrement EMR\_SELECTOBJECT (section 2.3.8.5), qui spécifie le pinceau logique à utiliser dans les opérations graphiques ultérieures.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | Initialise une nouvelle instance de la classe `EmfCreateBrushIndirect`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau logique dans la table d'objets EMF (section 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau logique dans la table d'objets EMF (section 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | Obtient ou définit un objet LogBrushEx (section 2.2.12) qui spécifie le style, la couleur et le motif du pinceau logique. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Obtient ou définit un objet LogBrushEx (section 2.2.12) qui spécifie le style, la couleur et le motif du pinceau logique. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCreateBrushIndirect`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


Initialise une nouvelle instance de la classe `EmfCreateBrushIndirect`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Obtient ou définit un objet LogBrushEx (section 2.2.12) qui spécifie le style, la couleur et le motif du pinceau logique. Le champ BrushStyle de cet objet DOIT être BS\_SOLID, BS\_HATCHED ou BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Obtient ou définit un objet LogBrushEx (section 2.2.12) qui spécifie le style, la couleur et le motif du pinceau logique. Le champ BrushStyle de cet objet DOIT être BS\_SOLID, BS\_HATCHED ou BS\_NULL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

