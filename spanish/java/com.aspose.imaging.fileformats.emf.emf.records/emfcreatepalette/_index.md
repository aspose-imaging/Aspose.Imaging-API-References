---
title: "EmfCreatePalette"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CREATEPALETTE define una paleta lógica para operaciones gráficas."
type: docs
weight: 40
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

El registro EMR\_CREATEPALETTE define una paleta lógica para operaciones gráficas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCreatePalette`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta lógica en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta lógica en la tabla de objetos EMF (sección 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | Obtiene o establece un objeto LogPalette (sección 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Obtiene o establece un objeto LogPalette (sección 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCreatePalette`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta lógica en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de paleta lógica en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Obtiene o establece un objeto LogPalette (sección 2.2.17). El campo Version de este objeto DEBE establecerse en 0x0300. Si el valor NumberOfEntries de este objeto es cero, el procesamiento de este registro DEBE fallar.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Obtiene o establece un objeto LogPalette (sección 2.2.17). El campo Version de este objeto DEBE establecerse en 0x0300. Si el valor NumberOfEntries de este objeto es cero, el procesamiento de este registro DEBE fallar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

