---
title: "EmfPolyDraw16"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_POLYDRAW16 especifica un conjunto de segmentos de línea y curvas de Bézier."
type: docs
weight: 90
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

El registro EMR\_POLYDRAW16 especifica un conjunto de segmentos de línea y curvas de Bézier.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfPolyDraw16`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Obtiene o establece una matriz de longitud Count de bytes que especifica los tipos de punto. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Establece una matriz de bytes de longitud Count que especifica los tipos de punto. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfPolyDraw16`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Obtiene o establece una matriz de bytes de longitud Count que especifica los tipos de punto. Este valor DEBE estar en la enumeración Point (sección 2.1.26).

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Establece una matriz de bytes de longitud Count que especifica los tipos de punto. Este valor DEBE estar en la enumeración Point (sección 2.1.26).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] | una matriz de bytes de longitud Count que especifica los tipos de punto. |

