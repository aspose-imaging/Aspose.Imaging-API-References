---
title: "EmfPolyDraw"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_POLYDRAW especifica un conjunto de segmentos de línea y curvas de Bézier."
type: docs
weight: 89
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

El registro EMR\_POLYDRAW especifica un conjunto de segmentos de línea y curvas de Bézier.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPolyDraw`. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Inicializa una nueva instancia de la clase [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Obtiene una matriz de longitud Count de valores byte que especifica cómo se utiliza cada punto en la matriz Gets or sets aPoints. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Establece una matriz de longitud Count de valores byte que especifica cómo se utiliza cada punto en la matriz Gets or sets aPoints. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPolyDraw`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Inicializa una nueva instancia de la clase [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw).

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Obtiene una matriz de longitud Count de valores byte que especifica cómo se utiliza cada punto en la matriz Gets or sets aPoints. Este valor DEBE estar en la enumeración Point (sección 2.1.26).

**Returns:**
byte[] - una matriz de longitud Count de valores byte que especifica cómo se utiliza cada punto en la matriz Gets or sets aPoints.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Establece una matriz de longitud Count de valores byte que especifica cómo se utiliza cada punto en la matriz Gets or sets aPoints. Este valor DEBE estar en la enumeración Point (sección 2.1.26).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] | una matriz de longitud Count de valores byte que especifica cómo se utiliza cada punto en la matriz Gets or sets aPoints. |

