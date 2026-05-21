---
title: "EmfPlusTranslateWorldTransform"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusTranslateWorldTransform realiza una traslación en la transformación del espacio mundial actual."
type: docs
weight: 72
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusTranslateWorldTransform realiza una traslación en la transformación del espacio mundial actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusTranslateWorldTransform`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtiene un valor que indica si [post multiplied matrix]. |
| [getDx()](#getDx--) | Obtiene o establece un valor de punto flotante de 32 bits que define la distancia horizontal. |
| [setDx(float value)](#setDx-float-) | Obtiene o establece un valor de punto flotante de 32 bits que define la distancia horizontal. |
| [getDy()](#getDy--) | Obtiene o establece un valor de punto flotante de 32 bits que define el valor de la distancia vertical. |
| [setDy(float value)](#setDy-float-) | Obtiene o establece un valor de punto flotante de 32 bits que define el valor de la distancia vertical. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusTranslateWorldTransform`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Obtiene un valor que indica si [post multiplied matrix]. Si está establecido, la matriz de transformación debe ser post-multiplicada. Si está despejado, debe ser pre-multiplicada.

Valor: `true` si [post multiplied matrix]; de lo contrario, `false`.

**Returns:**
boolean
### getDx() {#getDx--}
```
public float getDx()
```


Obtiene o establece un valor de punto flotante de 32 bits que define la distancia horizontal. La traducción se realiza construyendo una nueva matriz de transformación mundial a partir de los campos dx y dy.

Valor: El dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que define la distancia horizontal. La traducción se realiza construyendo una nueva matriz de transformación mundial a partir de los campos dx y dy.

Valor: El dx.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Obtiene o establece un valor de punto flotante de 32 bits que define el valor de la distancia vertical.

Valor: El dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que define el valor de la distancia vertical.

Valor: El dy.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

