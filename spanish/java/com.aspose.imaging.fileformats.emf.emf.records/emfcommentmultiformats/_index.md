---
title: "EmfCommentMultiFormats"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COMMENT_MULTIFORMATS especifica una imagen en varios formatos gráficos."
type: docs
weight: 30
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

El registro EMR\_COMMENT\_MULTIFORMATS especifica una imagen en varios formatos gráficos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCommentMultiFormats`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida, en coordenadas lógicas. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida, en coordenadas lógicas. |
| [getAFormats()](#getAFormats--) | Obtiene o establece una matriz de longitud CountFormats de formatos gráficos, especificados por objetos EmrFormat (sección 2.2.4), en orden de preferencia. |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Obtiene o establece una matriz de longitud CountFormats de formatos gráficos, especificados por objetos EmrFormat (sección 2.2.4), en orden de preferencia. |
| [getFormatData()](#getFormatData--) | Obtiene o establece una matriz de bytes de longitud variable con los datos de imagen para todos los formatos gráficos contenidos en este registro. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Obtiene o establece una matriz de bytes de longitud variable con los datos de imagen para todos los formatos gráficos contenidos en este registro. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCommentMultiFormats`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida, en coordenadas lógicas.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida, en coordenadas lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Obtiene o establece una matriz de longitud CountFormats de formatos gráficos, especificados por objetos EmrFormat (sección 2.2.4), en orden de preferencia.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Obtiene o establece una matriz de longitud CountFormats de formatos gráficos, especificados por objetos EmrFormat (sección 2.2.4), en orden de preferencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Obtiene o establece una matriz de bytes de longitud variable con los datos de imagen para todos los formatos gráficos contenidos en este registro. El tamaño de los datos de cada imagen lo proporciona el campo DataSize en el objeto EmrFormat correspondiente. Por lo tanto, el tamaño total de este campo es la suma de los valores DataSize en todos los objetos EmrFormat. El formato gráfico de los datos de cada imagen se especifica mediante el campo Signature en el objeto EmrFormat correspondiente.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Obtiene o establece una matriz de bytes de longitud variable con los datos de imagen para todos los formatos gráficos contenidos en este registro. El tamaño de los datos de cada imagen lo proporciona el campo DataSize en el objeto EmrFormat correspondiente. Por lo tanto, el tamaño total de este campo es la suma de los valores DataSize en todos los objetos EmrFormat. El formato gráfico de los datos de cada imagen se especifica mediante el campo Signature en el objeto EmrFormat correspondiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[][] |  |

