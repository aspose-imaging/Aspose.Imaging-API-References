---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusMultiplyWorldTransform multiplica la transformación del espacio mundial actual por una matriz de transformación especificada."
type: docs
weight: 41
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusMultiplyWorldTransform multiplica la transformación del espacio mundial actual por una matriz de transformación especificada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusMultiplyWorldTransform`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtiene un valor que indica si [post multiplied matrix]. |
| [getMatrixData()](#getMatrixData--) | Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la matriz de multiplicación. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la matriz de multiplicación. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusMultiplyWorldTransform`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Obtiene un valor que indica si [matriz post multiplicada]. Si está establecida, la matriz de transformación debe ser post-multiplicada. Si no está establecida, debe ser pre-multiplicada.

Valor: `true` si [post multiplied matrix]; de lo contrario, `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la matriz de multiplicación.

Valor: Los datos de la matriz.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Obtiene o establece un objeto EmfPlusTransformMatrix (sección 2.2.2.47) que define la matriz de multiplicación.

Valor: Los datos de la matriz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

