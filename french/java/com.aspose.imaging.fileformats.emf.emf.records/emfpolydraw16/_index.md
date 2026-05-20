---
title: "EmfPolyDraw16"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_POLYDRAW16 spécifie un ensemble de segments de ligne et de courbes de Bézier."
type: docs
weight: 90
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

L'enregistrement EMR\_POLYDRAW16 spécifie un ensemble de segments de ligne et de courbes de Bézier.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPolyDraw16`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Obtient ou définit un tableau de longueur Count d'octets qui spécifie les types de points. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Définit un tableau d'octets de longueur Count qui spécifie les types de points. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPolyDraw16`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Obtient ou définit un tableau d'octets de longueur Count qui spécifie les types de points. Cette valeur DOIT être dans l'énumération Point (section 2.1.26).

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Définit un tableau d'octets de longueur Count qui spécifie les types de points. Cette valeur DOIT être dans l'énumération Point (section 2.1.26).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] | un tableau d'octets de longueur Count qui spécifie les types de points. |

