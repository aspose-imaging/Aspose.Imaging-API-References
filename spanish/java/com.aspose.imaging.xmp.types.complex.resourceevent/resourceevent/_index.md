---
title: "ResourceEvent"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contiene dimensiones para un objeto dibujado."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.xmp.types.complex.resourceevent/resourceevent/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Contiene dimensiones para un objeto dibujado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Inicializa una nueva instancia de la clase `ResourceEvent`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAction()](#getAction--) | Obtiene la acción. |
| [setAction(String value)](#setAction-java.lang.String-) | Establece la acción. |
| [getChanged()](#getChanged--) | Obtiene la lista delimitada por punto y coma de las partes del recurso que se cambiaron desde el historial de eventos anterior. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Establece la lista delimitada por punto y coma de las partes del recurso que se cambiaron desde el historial de eventos anterior. |
| [getInstanceId()](#getInstanceId--) | Obtiene el valor de xmpMM:InstanceId. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Obtiene o establece el valor de xmpMM:InstanceId. |
| [getParameters()](#getParameters--) | Obtiene o establece la descripción adicional de la acción. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Obtiene o establece la descripción adicional de la acción. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Obtiene o establece el nombre del agente de software. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Obtiene o establece el nombre del agente de software. |
| [getActionDate()](#getActionDate--) | Obtiene o establece la fecha de la acción. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Obtiene o establece la fecha de la acción. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtiene el valor de cadena contenido en formato XMP. |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Inicializa una nueva instancia de la clase `ResourceEvent`.

### getAction() {#getAction--}
```
public String getAction()
```


Obtiene la acción.

Los valores definidos son: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Los nuevos valores deben ser verbos en tiempo pasado.

**Returns:**
java.lang.String - La acción.
### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Establece la acción.

Los valores definidos son: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Los nuevos valores deben ser verbos en tiempo pasado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La acción. |

### getChanged() {#getChanged--}
```
public String getChanged()
```


Obtiene la lista delimitada por punto y coma de las partes del recurso que se cambiaron desde el historial de eventos anterior.

**Returns:**
java.lang.String - La lista delimitada por punto y coma de las partes del recurso que se cambiaron desde el historial de eventos anterior.
### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Establece la lista delimitada por punto y coma de las partes del recurso que se cambiaron desde el historial de eventos anterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La lista delimitada por punto y coma de las partes del recurso que se cambiaron desde el historial de eventos anterior. |

### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Obtiene el valor de xmpMM:InstanceId.

**Returns:**
java.util.UUID - El valor de xmpMM:InstanceId.
### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Obtiene o establece el valor de xmpMM:InstanceId.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID | El valor de xmpMM:InstanceId. |

### getParameters() {#getParameters--}
```
public String getParameters()
```


Obtiene o establece la descripción adicional de la acción.

Valor: La descripción adicional de la acción.

**Returns:**
java.lang.String
### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Obtiene o establece la descripción adicional de la acción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La descripción adicional de la acción. |

### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Obtiene o establece el nombre del agente de software.

**Returns:**
java.lang.String - El nombre del agente de software.
### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Obtiene o establece el nombre del agente de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El nombre del agente de software. |

### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Obtiene o establece la fecha de la acción.

**Returns:**
java.util.Date - La fecha de la acción.
### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Obtiene o establece la fecha de la acción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date | La fecha de la acción. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtiene el valor de cadena contenido en formato XMP.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
