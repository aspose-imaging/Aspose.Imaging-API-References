---
title: "Clase XmpDate"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Inicializa una nueva instancia de la clase [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Inicializa una nueva instancia de la clase [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [estático] | string | r | La cadena de formato ISO 8601 (ida y vuelta). |
| formato | string | r | Obtiene la cadena de formato para el valor actual. |
| valor | System.DateTime | r/w | Obtiene o establece el valor de fecha. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |
| [get_xmp_representation()](#get_xmp_representation__2) | Devuelve el valor contenido en cadena en formato XMP. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Inicializa una nueva instancia de la clase [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| date_string | string | La representación en cadena de la fecha. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Inicializa una nueva instancia de la clase [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fecha_hora | System.DateTime | Un valor de fecha y hora que se representa usando un subconjunto del formato ISO RFC 8601. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Object | Una clonación por miembros. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Devuelve el valor contenido en cadena en formato XMP.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve una cadena que contiene la representación xmp. |


