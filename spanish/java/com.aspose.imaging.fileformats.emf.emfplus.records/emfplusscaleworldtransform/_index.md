---
title: "EmfPlusScaleWorldTransform"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusScaleWorldTransform realiza un escalado en la transformación del espacio mundial actual."
type: docs
weight: 52
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusScaleWorldTransform realiza un escalado en la transformación del espacio mundial actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusScaleWorldTransform`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtiene un valor que indica si [post multiplied matrix]. |
| [getSx()](#getSx--) | Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala horizontal. |
| [setSx(float value)](#setSx-float-) | Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala horizontal. |
| [getSy()](#getSy--) | Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala vertical. |
| [setSy(float value)](#setSy-float-) | Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala vertical. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusScaleWorldTransform`.

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
### getSx() {#getSx--}
```
public float getSx()
```


Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala horizontal. El escalado se realiza construyendo una nueva matriz de transformación a partir de los valores de los campos Sx y Sy, como se muestra en la tabla siguiente. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figura 3: Matriz de Transformación de Escala

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala horizontal. El escalado se realiza construyendo una nueva matriz de transformación a partir de los valores de los campos Sx y Sy, como se muestra en la tabla siguiente. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Figura 3: Matriz de Transformación de Escala

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala vertical.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que define el factor de escala vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

