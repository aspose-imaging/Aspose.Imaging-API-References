---
title: "EmfRecord"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase base para los registros EMF. Todos los registros EMF DEBEN tener una longitud que sea múltiplo de 4 bytes."
type: docs
weight: 106
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

Clase base para los registros EMF. Todos los registros EMF DEBEN tener una longitud que sea múltiplo de 4 bytes. Esto se representa en las estructuras genéricas de los tipos de registro EMF precedentes mediante la inclusión de campos AlignmentPadding donde corresponda al final de estas estructuras. El contenido de los campos AlignmentPadding DEBE ser siempre ignorado. Por brevedad, estos campos no se muestran en cada definición individual de registro EMF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | Inicializa una nueva instancia de la clase `EmfRecord`. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfRecord`. |
| [EmfRecord(int type)](#EmfRecord-int-) | Inicializa una nueva instancia de la clase `EmfRecord`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Obtiene el tipo. |
| [setType(int value)](#setType-int-) | Establece el tipo. |
| [getSize()](#getSize--) | Obtiene el tamaño del registro |
| [setSize(int value)](#setSize-int-) | Establece el tamaño del registro |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


Inicializa una nueva instancia de la clase `EmfRecord`.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfRecord`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


Inicializa una nueva instancia de la clase `EmfRecord`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | El tipo de registro. |

### getType() {#getType--}
```
public int getType()
```


Obtiene el tipo.

**Returns:**
int - El tipo.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Establece el tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tipo. |

### getSize() {#getSize--}
```
public int getSize()
```


Obtiene el tamaño del registro

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Establece el tamaño del registro

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

