---
title: "EmfPlusComment"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusComment especifica datos privados arbitrarios."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

El registro EmfPlusComment especifica datos privados arbitrarios.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusComment`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Obtiene o establece una matriz de bytes de longitud DataSize de datos privados. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Obtiene o establece una matriz de bytes de longitud DataSize de datos privados. |
| [getFlags()](#getFlags--) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
| [setFlags(short value)](#setFlags-short-) | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusComment`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Obtiene o establece una matriz de bytes de longitud DataSize de datos privados. bytes de datos específicos del registro que siguen.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Obtiene o establece una matriz de bytes de longitud DataSize de datos privados. bytes de datos específicos del registro que siguen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Obtiene o establece un entero sin signo de 16 bits que no se utiliza. Este campo DEBERÍA establecerse en cero y DEBE ser ignorado al recibirlo.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Obtiene o establece un entero sin signo de 16 bits que no se utiliza. Este campo DEBERÍA establecerse en cero y DEBE ser ignorado al recibirlo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

