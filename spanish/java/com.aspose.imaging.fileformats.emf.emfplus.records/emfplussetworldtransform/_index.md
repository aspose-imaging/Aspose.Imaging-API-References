---
title: "EmfPlusSetWorldTransform"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetWorldTransform establece la transformación mundial según los valores de una matriz de transformación especificada."
type: docs
weight: 68
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusSetWorldTransform establece la transformación mundial según los valores de una matriz de transformación especificada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetWorldTransform`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la nueva transformación mundial actual. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la nueva transformación mundial actual. |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetWorldTransform`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la nueva transformación mundial actual.

Valor: Los datos de la matriz.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la nueva transformación mundial actual.

Valor: Los datos de la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

