---
title: "Capa"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la capa de texto de Photoshop."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Representa la capa de texto de Photoshop.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase `Layer`. |
| [Layer()](#Layer--) | Inicializa una nueva instancia de la clase `Layer`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Obtiene o establece el nombre de la capa de texto. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre de la capa de texto. |
| [getText()](#getText--) | Obtiene o establece el contenido de texto de la capa. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el contenido de texto de la capa. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Devuelve el valor contenido en cadena en formato XMP. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `System.Object` especificado es igual a esta instancia. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


Inicializa una nueva instancia de la clase `Layer`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerName | java.lang.String | Nombre de la capa. |
| layerText | java.lang.String | El texto de la capa. |

### Layer() {#Layer--}
```
public Layer()
```


Inicializa una nueva instancia de la clase `Layer`.

### getName() {#getName--}
```
public String getName()
```


Obtiene o establece el nombre de la capa de texto.

Valor: El nombre de la capa de texto.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Obtiene o establece el nombre de la capa de texto.

Valor: El nombre de la capa de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


Obtiene o establece el contenido de texto de la capa.

Valor: El contenido de texto de la capa.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Obtiene o establece el contenido de texto de la capa.

Valor: El contenido de texto de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Devuelve el valor contenido en cadena en formato XMP.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `System.Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `System.Object` especificado es igual a esta instancia; de lo contrario, `false`.
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | Un objeto para comparar con este objeto. |

**Returns:**
boolean - verdadero si el objeto actual es igual al parámetro `other`; de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
