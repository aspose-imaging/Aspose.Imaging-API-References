---
title: "EmfPolyDraw"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_POLYDRAW spécifie un ensemble de segments de ligne et de courbes de Bézier."
type: docs
weight: 89
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

L'enregistrement EMR\_POLYDRAW spécifie un ensemble de segments de ligne et de courbes de Bézier.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPolyDraw`. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Initialise une nouvelle instance de la classe [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Obtient un tableau de longueur Count de valeurs d'octet qui spécifie comment chaque point du tableau aPoints (obtenu ou défini) est utilisé. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Définit un tableau de longueur Count de valeurs d'octet qui spécifie comment chaque point du tableau aPoints (obtenu ou défini) est utilisé. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPolyDraw`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Initialise une nouvelle instance de la classe [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw).

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Obtient un tableau de longueur Count de valeurs d'octet qui spécifie comment chaque point du tableau aPoints (obtenu ou défini) est utilisé. Cette valeur DOIT appartenir à l'énumération Point (section 2.1.26).

**Returns:**
byte[] - un tableau de longueur Count de valeurs d'octet qui spécifie comment chaque point du tableau aPoints (obtenu ou défini) est utilisé.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Définit un tableau de longueur Count de valeurs d'octet qui spécifie comment chaque point du tableau aPoints (obtenu ou défini) est utilisé. Cette valeur DOIT appartenir à l'énumération Point (section 2.1.26).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] | un tableau de longueur Count de valeurs d'octet qui spécifie comment chaque point du tableau aPoints (obtenu ou défini) est utilisé. |

