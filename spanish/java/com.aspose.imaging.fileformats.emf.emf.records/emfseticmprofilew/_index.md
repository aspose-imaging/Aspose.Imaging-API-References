---
title: "EmfSetIcmProfileW"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETICMPROFILEW especifica un perfil de color en un archivo cuyo nombre está compuesto por caracteres Unicode para la salida gráfica."
type: docs
weight: 127
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

El registro EMR\_SETICMPROFILEW especifica un perfil de color en un archivo cuyo nombre está compuesto por caracteres Unicode, para la salida gráfica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetIcmProfileW`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Obtiene o establece un entero sin signo de 32 bits que contiene los indicadores del perfil de color. |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que contiene los indicadores del perfil de color. |
| [getCbName()](#getCbName--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado. |
| [setCbName(int value)](#setCbName-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado. |
| [getCbData()](#getCbData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos del perfil de color, si está adjunto. |
| [setCbData(int value)](#setCbData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos del perfil de color, si está adjunto. |
| [getData()](#getData--) | Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado. |
| [getName()](#getName--) | Obtiene el nombre |
| [getRawData()](#getRawData--) | Obtiene los datos sin procesar |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetIcmProfileW`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtiene o establece un entero sin signo de 32 bits que contiene los indicadores del perfil de color.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que contiene los indicadores del perfil de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos del perfil de color, si está adjunto.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos del perfil de color, si está adjunto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Obtiene los datos sin procesar

**Returns:**
byte[]
