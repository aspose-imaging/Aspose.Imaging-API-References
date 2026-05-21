---
title: "EmfCreateColorSpaceW"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_CREATECOLORSPACEW crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres Unicode."
type: docs
weight: 37
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

El registro EMR\_CREATECOLORSPACEW crea un objeto de espacio de color lógico a partir de un perfil de color con un nombre compuesto por caracteres Unicode.

El objeto de espacio de color lógico definido por este registro puede ser seleccionado en el contexto del dispositivo de reproducción mediante un registro EMR\_SETCOLORSPACE (sección 2.3.8.7), que define el espacio de color lógico que se utilizará en operaciones gráficas posteriores.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCreateColorSpaceW`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de espacio de color lógico en la tabla de objetos EMF (sección 3.1.1.1). |
| [getLcs()](#getLcs--) | Obtiene o establece un objeto WMF LogColorSpaceW ([MS-WMF] sección 2.2.2.12) que puede especificar el nombre de un perfil de color en caracteres Unicode UTF16-LE. |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | Obtiene o establece un objeto WMF LogColorSpaceW ([MS-WMF] sección 2.2.2.12) que puede especificar el nombre de un perfil de color en caracteres Unicode UTF16-LE. |
| [getDwFlags()](#getDwFlags--) | Obtiene o establece un entero sin signo de 32 bits que proporciona información sobre los datos en este registro. |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que proporciona información sobre los datos en este registro. |
| [getCbData()](#getCbData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. |
| [setCbData(int value)](#setCbData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. |
| [getData()](#getData--) | Obtiene o establece una matriz opcional de bytes que especifica los datos del perfil de color. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece una matriz opcional de bytes que especifica los datos del perfil de color. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCreateColorSpaceW`.

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
public WmfLogColorSpaceW getLcs()
```


Obtiene o establece un objeto WMF LogColorSpaceW ([MS-WMF] sección 2.2.2.12) que puede especificar el nombre de un perfil de color en caracteres Unicode UTF16-LE.

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


Obtiene o establece un objeto WMF LogColorSpaceW ([MS-WMF] sección 2.2.2.12) que puede especificar el nombre de un perfil de color en caracteres Unicode UTF16-LE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtiene o establece un entero sin signo de 32 bits que proporciona información sobre los datos en este registro.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que proporciona información sobre los datos en este registro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtiene o establece una matriz opcional de bytes que especifica los datos del perfil de color.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtiene o establece una matriz opcional de bytes que especifica los datos del perfil de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

