---
title: "EmfCreateColorSpace"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CREATECOLORSPACE crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre que consiste en caracteres ASCII."
type: docs
weight: 36
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

El registro EMR\_CREATECOLORSPACE crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres ASCII.

El objeto de espacio de color lógico definido por este registro puede ser seleccionado en el contexto del dispositivo de reproducción mediante un registro EMR\_SETCOLORSPACE (sección 2.3.8.7), que define el espacio de color lógico que se utilizará en operaciones gráficas posteriores.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCreateColorSpace`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [getLcs()](#getLcs--) | Obtiene o establece un objeto WMF LogColorSpace ([MS-WMF] sección 2.2.2.11), que puede especificar el nombre de un perfil de color en caracteres ASCII. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | Obtiene o establece un objeto WMF LogColorSpace ([MS-WMF] sección 2.2.2.11), que puede especificar el nombre de un perfil de color en caracteres ASCII. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCreateColorSpace`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpace getLcs()
```


Obtiene o establece un objeto WMF LogColorSpace ([MS-WMF] sección 2.2.2.11), que puede especificar el nombre de un perfil de color en caracteres ASCII.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


Obtiene o establece un objeto WMF LogColorSpace ([MS-WMF] sección 2.2.2.11), que puede especificar el nombre de un perfil de color en caracteres ASCII.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

