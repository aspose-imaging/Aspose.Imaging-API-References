---
title: "WmfEscapeEnhancedMetafile"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro Escape Enhanced Meta file."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

El registro Escape Enhanced Meta file.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtiene o establece el identificador del comentario. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtiene o establece el identificador del comentario. |
| [getCommentType()](#getCommentType--) | Obtiene o establece el tipo del comentario. |
| [setCommentType(int value)](#setCommentType-int-) | Obtiene o establece el tipo del comentario. |
| [getVersion()](#getVersion--) | Obtiene o establece la versión. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece la versión. |
| [getChecksum()](#getChecksum--) | Obtiene o establece la suma de verificación. |
| [setChecksum(int value)](#setChecksum-int-) | Obtiene o establece la suma de verificación. |
| [getFlags()](#getFlags--) | Obtiene o establece las banderas. |
| [setFlags(int value)](#setFlags-int-) | Obtiene o establece las banderas. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Obtiene o establece el recuento de registros de comentario. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Obtiene o establece el recuento de registros de comentario. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Obtiene o establece el tamaño del registro actual. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Obtiene o establece el tamaño del registro actual. |
| [getRemainingBytes()](#getRemainingBytes--) | Obtiene o establece los bytes restantes. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Obtiene o establece los bytes restantes. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Obtiene o establece el tamaño de los datos del metarchivo mejorado. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Obtiene o establece el tamaño de los datos del metarchivo mejorado. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Obtiene o establece los datos del metarchivo mejorado. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Obtiene o establece los datos del metarchivo mejorado. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtiene o establece el identificador del comentario.

Valor: Un entero sin signo de 32 bits que define este registro como un registro de comentario WMF. Este valor DEBE ser 0x43464D57.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtiene o establece el identificador del comentario.

Valor: Un entero sin signo de 32 bits que define este registro como un registro de comentario WMF. Este valor DEBE ser 0x43464D57.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Obtiene o establece el tipo del comentario.

Valor: Un entero sin signo de 32 bits que identifica el tipo de comentario en este registro. Este valor DEBE ser 0x00000001.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Obtiene o establece el tipo del comentario.

Valor: Un entero sin signo de 32 bits que identifica el tipo de comentario en este registro. Este valor DEBE ser 0x00000001.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece la versión.

Valor: Un entero sin signo de 32 bits que especifica la interoperabilidad del metafichero EMF. Esto DEBERÍA ser 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece la versión.

Valor: Un entero sin signo de 32 bits que especifica la interoperabilidad del metafichero EMF. Esto DEBERÍA ser 0x00010000.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Obtiene o establece la suma de verificación.

Valor: Un entero sin signo de 16 bits utilizado para validar la corrección del flujo EMF incrustado. Este valor DEBE ser el complemento a uno del resultado de aplicar una operación XOR a todas las WORDs en el flujo EMF.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Obtiene o establece la suma de verificación.

Valor: Un entero sin signo de 16 bits utilizado para validar la corrección del flujo EMF incrustado. Este valor DEBE ser el complemento a uno del resultado de aplicar una operación XOR a todas las WORDs en el flujo EMF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtiene o establece las banderas.

Valor: Este entero sin signo de 32 bits no se usa y DEBE establecerse en cero.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Obtiene o establece las banderas.

Valor: Este entero sin signo de 32 bits no se usa y DEBE establecerse en cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Obtiene o establece el recuento de registros de comentario.

Valor: Un entero sin signo de 32 bits que especifica el número total de registros consecutivos META\_ESCAPE\_ENHANCED\_METAFILE que contienen el metafichero EMF incrustado.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Obtiene o establece el recuento de registros de comentario.

Valor: Un entero sin signo de 32 bits que especifica el número total de registros consecutivos META\_ESCAPE\_ENHANCED\_METAFILE que contienen el metafichero EMF incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Obtiene o establece el tamaño del registro actual.

Valor: Un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo EnhancedMetafileData. Este valor DEBE ser menor o igual a 8,192.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Obtiene o establece el tamaño del registro actual.

Valor: Un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo EnhancedMetafileData. Este valor DEBE ser menor o igual a 8,192.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Obtiene o establece los bytes restantes.

Valor: Un entero sin signo de 32 bits que especifica el número de bytes en el flujo EMF que quedan por procesar después de este registro. Esos bytes EMF adicionales DEBEN seguir en los campos EnhancedMetafileData de los registros de escape META\_ESCAPE\_ENHANDED\_METAFILE subsiguientes.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Obtiene o establece los bytes restantes.

Valor: Un entero sin signo de 32 bits que especifica el número de bytes en el flujo EMF que quedan por procesar después de este registro. Esos bytes EMF adicionales DEBEN seguir en los campos EnhancedMetafileData de los registros de escape META\_ESCAPE\_ENHANDED\_METAFILE subsiguientes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Obtiene o establece el tamaño de los datos del metarchivo mejorado.

Valor: Un entero sin signo de 32 bits que especifica el tamaño total del flujo EMF incrustado en esta secuencia de registros META\_ESCAPE\_ENHANCED\_METAFILE.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Obtiene o establece el tamaño de los datos del metarchivo mejorado.

Valor: Un entero sin signo de 32 bits que especifica el tamaño total del flujo EMF incrustado en esta secuencia de registros META\_ESCAPE\_ENHANCED\_METAFILE.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Obtiene o establece los datos del metarchivo mejorado.

Valor: Un segmento de un archivo EMF. Los bytes en registros consecutivos META\_ESCAPE\_ENHANCED\_METAFILE DEBEN concatenarse para representar el archivo EMF completo incrustado.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Obtiene o establece los datos del metarchivo mejorado.

Valor: Un segmento de un archivo EMF. Los bytes en registros consecutivos META\_ESCAPE\_ENHANCED\_METAFILE DEBEN concatenarse para representar el archivo EMF completo incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

