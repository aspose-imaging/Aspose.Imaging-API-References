---
title: "EmfPlusRotateWorldTransform"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusRotateWorldTransform realiza una rotación en la transformación del espacio mundial actual."
type: docs
weight: 50
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusRotateWorldTransform realiza una rotación en la transformación del espacio mundial actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusRotateWorldTransform`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Obtiene un valor que indica si [post multiplied matrix]. |
| [getAngle()](#getAngle--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ángulo de rotación en grados. |
| [setAngle(float value)](#setAngle-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ángulo de rotación en grados. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusRotateWorldTransform`.

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el ángulo de rotación en grados. La operación se realiza construyendo una nueva matriz de transformación a partir del siguiente diagrama: ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Figura 2: Matriz de Transformación de Rotación La transformación del espacio mundial actual se multiplica por esta matriz, y el resultado se convierte en la nueva transformación del espacio mundial actual. El campo Flags determina el orden de la multiplicación.

Valor: El ángulo.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el ángulo de rotación en grados. La operación se realiza construyendo una nueva matriz de transformación a partir del siguiente diagrama: ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Figura 2: Matriz de Transformación de Rotación La transformación del espacio mundial actual se multiplica por esta matriz, y el resultado se convierte en la nueva transformación del espacio mundial actual. El campo Flags determina el orden de la multiplicación.

Valor: El ángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

