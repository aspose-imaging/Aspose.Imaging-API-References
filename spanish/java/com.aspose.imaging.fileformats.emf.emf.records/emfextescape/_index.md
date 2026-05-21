---
title: "EmfExtEscape"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_EXTESCAPE pasa información arbitraria a un controlador de impresora."
type: docs
weight: 53
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfextescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfExtEscape extends EmfEscapeRecordType
```

El registro EMR\_EXTESCAPE pasa información arbitraria a un controlador de impresora. La intención es que la información no resulte en la realización de dibujos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfExtEscape(EmfRecord source)](#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfExtEscape`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCjIn()](#getCjIn--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora. |
| [setCjIn(int value)](#setCjIn-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora. |
| [getData()](#getData--) | Obtiene o establece los datos a pasar al controlador de impresora. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece los datos a pasar al controlador de impresora. |
### EmfExtEscape(EmfRecord source) {#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtEscape(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfExtEscape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtiene o establece los datos a pasar al controlador de impresora. DEBE haber cjIn bytes disponibles.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtiene o establece los datos a pasar al controlador de impresora. DEBE haber cjIn bytes disponibles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

