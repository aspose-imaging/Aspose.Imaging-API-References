---
title: "EmfCommentWindowsMetaFile"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COMMENT_WINDOWS_METAFILE especifica una imagen en un metafichero WMF incrustado."
type: docs
weight: 33
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

El registro EMR\_COMMENT\_WINDOWS\_METAFILE especifica una imagen en un metafile WMF incrustado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCommentWindowsMetaFile`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) | Obtiene o establece un entero sin signo de 16 bits que especifica la versión del metafichero WMF en términos de soporte para mapas de bits independientes del dispositivo (DIB), de la enumeración WMF MetafileVersion ([MS-WMF] sección 2.1.1.19). |
| [setVersion(short value)](#setVersion-short-) | Obtiene o establece un entero sin signo de 16 bits que especifica la versión del metafichero WMF en términos de soporte para mapas de bits independientes del dispositivo (DIB), de la enumeración WMF MetafileVersion ([MS-WMF] sección 2.1.1.19). |
| [getChecksum()](#getChecksum--) | Obtiene o establece un entero sin signo de 32 bits que especifica la suma de verificación para este registro. |
| [setChecksum(int value)](#setChecksum-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la suma de verificación para este registro. |
| [getFlags()](#getFlags--) | Obtiene o establece un valor de 32 bits que DEBE ser 0x00000000 y DEBE ser ignorado. |
| [setFlags(int value)](#setFlags-int-) | Obtiene o establece un valor de 32 bits que DEBE ser 0x00000000 y DEBE ser ignorado. |
| [getWinMetafileSize()](#getWinMetafileSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del metafichero WMF en el campo WinMetafile. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del metafichero WMF en el campo WinMetafile. |
| [getWinMetafile()](#getWinMetafile--) | Obtiene o establece un búfer que contiene el metafichero WMF. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | Obtiene o establece un búfer que contiene el metafichero WMF. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCommentWindowsMetaFile`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


Obtiene o establece un entero sin signo de 16 bits que especifica la versión del metafichero WMF en términos de soporte para mapas de bits independientes del dispositivo (DIB), de la enumeración WMF MetafileVersion ([MS-WMF] sección 2.1.1.19).

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Obtiene o establece un entero sin signo de 16 bits que especifica la versión del metafichero WMF en términos de soporte para mapas de bits independientes del dispositivo (DIB), de la enumeración WMF MetafileVersion ([MS-WMF] sección 2.1.1.19).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la suma de verificación para este registro.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la suma de verificación para este registro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtiene o establece un valor de 32 bits que DEBE ser 0x00000000 y DEBE ser ignorado.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Obtiene o establece un valor de 32 bits que DEBE ser 0x00000000 y DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del metafichero WMF en el campo WinMetafile.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del metafichero WMF en el campo WinMetafile.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


Obtiene o establece un búfer que contiene el metafichero WMF.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


Obtiene o establece un búfer que contiene el metafichero WMF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

