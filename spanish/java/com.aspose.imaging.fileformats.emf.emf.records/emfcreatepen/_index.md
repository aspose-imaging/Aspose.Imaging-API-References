---
title: "EmfCreatePen"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CREATEPEN define un lápiz lógico para operaciones gráficas."
type: docs
weight: 41
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

El registro EMR\_CREATEPEN define una pluma lógica para operaciones gráficas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCreatePen`. |
| [EmfCreatePen()](#EmfCreatePen--) | Inicializa una nueva instancia de la clase `EmfCreatePen`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhPen()](#getIhPen--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto lápiz lógico en la Tabla de Objetos EMF (sección 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto lápiz lógico en la Tabla de Objetos EMF (sección 3.1.1.1). |
| [getLogPen()](#getLogPen--) | Obtiene o establece un objeto LogPen (sección 2.2.19) que especifica el estilo, el ancho y el color del lápiz lógico. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Obtiene o establece un objeto LogPen (sección 2.2.19) que especifica el estilo, el ancho y el color del lápiz lógico. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCreatePen`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


Inicializa una nueva instancia de la clase `EmfCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto lápiz lógico en la Tabla de Objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto lápiz lógico en la Tabla de Objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Obtiene o establece un objeto LogPen (sección 2.2.19) que especifica el estilo, el ancho y el color del lápiz lógico.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Obtiene o establece un objeto LogPen (sección 2.2.19) que especifica el estilo, el ancho y el color del lápiz lógico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

