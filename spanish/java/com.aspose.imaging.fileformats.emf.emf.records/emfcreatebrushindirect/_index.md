---
title: "EmfCreateBrushIndirect"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CREATEBRUSHINDIRECT define un pincel lógico para operaciones gráficas."
type: docs
weight: 35
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

El registro EMR\_CREATEBRUSHINDIRECT define un pincel lógico para operaciones gráficas.

El objeto pincel lógico definido por este registro puede ser seleccionado en el contexto de dispositivo de reproducción mediante un registro EMR\\_SELECTOBJECT (sección 2.3.8.5), que especifica el pincel lógico a usar en operaciones gráficas posteriores.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | Inicializa una nueva instancia de la clase `EmfCreateBrushIndirect`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | Obtiene o establece un objeto LogBrushEx (sección 2.2.12) que especifica el estilo, color y patrón del pincel lógico. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Obtiene o establece un objeto LogBrushEx (sección 2.2.12) que especifica el estilo, color y patrón del pincel lógico. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCreateBrushIndirect`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


Inicializa una nueva instancia de la clase `EmfCreateBrushIndirect`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel lógico en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto pincel lógico en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Obtiene o establece un objeto LogBrushEx (sección 2.2.12) que especifica el estilo, color y patrón del pincel lógico. El campo BrushStyle en este objeto DEBE ser BS\_SOLID, BS\_HATCHED o BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Obtiene o establece un objeto LogBrushEx (sección 2.2.12) que especifica el estilo, color y patrón del pincel lógico. El campo BrushStyle en este objeto DEBE ser BS\_SOLID, BS\_HATCHED o BS\_NULL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

