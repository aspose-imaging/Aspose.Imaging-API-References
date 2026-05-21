---
title: "XmpBasicPackage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el espacio de nombres básico XMP."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Representa el espacio de nombres básico XMP.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Inicializa una nueva instancia de la clase `XmpBasicPackage`. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase `XmpBasicPackage`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Valor rechazado de la calificación. |
| [RATING_MIN](#RATING-MIN) | Valor mínimo de la calificación. |
| [RATING_MAX](#RATING-MAX) | Valor máximo de la calificación. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Establece la etiqueta. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Añade una propiedad de cadena. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Agrega la fecha de creación del recurso. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Agrega la fecha de creación del recurso. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Establece la herramienta creadora. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Establece el identificador. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Agrega la fecha de última modificación de los metadatos. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Agrega la fecha de última modificación de los metadatos. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Agrega la fecha de última modificación del recurso. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Agrega la fecha de última modificación del recurso. |
| [setRating(int choice)](#setRating-int-) | Establece la calificación. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Inicializa una nueva instancia de la clase `XmpBasicPackage`.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Inicializa una nueva instancia de la clase `XmpBasicPackage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | java.lang.String | El prefijo. |
| namespaceUri | java.lang.String | El URI del espacio de nombres. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Valor rechazado de la calificación.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Valor mínimo de la calificación.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Valor máximo de la calificación.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Establece la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etiqueta | java.lang.String | La etiqueta. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Añade una propiedad de cadena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | java.lang.String | El valor de cadena. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Agrega la fecha de creación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createdDate | java.util.Date | Fecha de creación. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Agrega la fecha de creación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createdDate | java.lang.String | Fecha de creación. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Establece la herramienta creadora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| creatorTool | java.lang.String | Nombre de la herramienta. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Establece el identificador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| identificador | java.lang.String[] | El identificador. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Agrega la fecha de última modificación de los metadatos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| metadataDate | java.util.Date | Fecha de metadatos. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Agrega la fecha de última modificación de los metadatos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| metadataDate | java.lang.String | Fecha de metadatos. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Agrega la fecha de última modificación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modifiedDate | java.util.Date | Fecha de última modificación. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Agrega la fecha de última modificación del recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modifiedDate | java.lang.String | Fecha de última modificación. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Establece la calificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opción | int | De -1 a 5 |

