---
title: "EmfEscapeRecordType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los tipos de registro de escape ejecutan funciones del controlador de impresora."
type: docs
weight: 49
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfEscapeRecordType extends EmfRecord
```

Los tipos de registro de escape ejecutan funciones del controlador de impresora.
## Métodos

| Método | Descripción |
| --- | --- |
| [getIEscape()](#getIEscape--) | Obtiene o establece un entero sin signo de 32 bits que especifica la secuencia de escape del controlador de impresora a ejecutar. |
| [setIEscape(int value)](#setIEscape-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica la secuencia de escape del controlador de impresora a ejecutar. |
### getIEscape() {#getIEscape--}
```
public int getIEscape()
```


Obtiene o establece un entero sin signo de 32 bits que especifica la secuencia de escape del controlador de impresora a ejecutar. Esto DEBE ser uno de los valores de la enumeración WMF MetafileEscapes ([MSWMF] sección 2.1.1.17).

**Returns:**
int
### setIEscape(int value) {#setIEscape-int-}
```
public void setIEscape(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica la secuencia de escape del controlador de impresora a ejecutar. Esto DEBE ser uno de los valores de la enumeración WMF MetafileEscapes ([MSWMF] sección 2.1.1.17).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

