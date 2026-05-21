---
title: "EmfEof"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EOF indica el final del metafichero y especifica una paleta."
type: docs
weight: 48
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

El registro EMR\_EOF indica el final del metafile y especifica una paleta.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfEof`. |
| [EmfEof()](#EmfEof--) | Inicializa una nueva instancia de la clase `EmfEof`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Obtiene un búfer opcional que contiene datos de la paleta, que no es necesario que sea contiguo con la porción fija del registro EMR\_EOF. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Establece un búfer opcional que contiene datos de la paleta, que no es necesario que sea contiguo con la porción fija del registro EMR\_EOF. |
| [getSizeLast()](#getSizeLast--) | Obtiene un entero sin signo de 32 bits que DEBE ser igual a Size y DEBE ser el último campo del registro y, por lo tanto, del metafichero. |
| [setSizeLast(int value)](#setSizeLast-int-) | Establece un entero sin signo de 32 bits que DEBE ser igual a Size y DEBE ser el último campo del registro y, por lo tanto, del metafichero. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


Inicializa una nueva instancia de la clase `EmfEof`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El registro. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


Inicializa una nueva instancia de la clase `EmfEof`.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Obtiene un búfer opcional que contiene datos de la paleta, que no es necesario que sea contiguo con la porción fija del registro EMR\_EOF. En consecuencia, los campos en este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados. El tamaño de este campo DEBE ser múltiplo de 4 bytes.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Establece un búfer opcional que contiene datos de la paleta, que no es necesario que sea contiguo con la porción fija del registro EMR\_EOF. En consecuencia, los campos en este búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados. El tamaño de este campo DEBE ser múltiplo de 4 bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Obtiene un entero sin signo de 32 bits que DEBE ser igual a Size y DEBE ser el último campo del registro y, por lo tanto, del metafichero. Los objetos LogPaletteEntry, si existen, DEBEN preceder a este campo.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Establece un entero sin signo de 32 bits que DEBE ser igual a Size y DEBE ser el último campo del registro y, por lo tanto, del metafichero. Los objetos LogPaletteEntry, si existen, DEBEN preceder a este campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

