---
title: "EmfSetRop2"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETROP2 define un modo de operación raster binaria."
type: docs
weight: 137
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

El registro EMR\_SETROP2 define un modo de operación raster binaria.

Los modos de mezcla de operaciones raster binarias definen cómo combinar los colores de origen y destino al dibujar con la pluma actual. Los modos de mezcla son códigos de operación raster binaria, que representan todas las funciones booleanas posibles de dos variables, usando las operaciones binarias AND, OR y XOR (OR exclusivo), y la operación unaria NOT. El modo de mezcla es solo para dispositivos raster; no está disponible para dispositivos vectoriales.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetRop2`. |
| [EmfSetRop2()](#EmfSetRop2--) | Inicializa una nueva instancia de la clase `EmfSetRop2`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de operación raster y DEBE estar en la enumeración WMF Binary Raster Op ([MS-WMF] sección 2.1.1.2). |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el modo de operación raster y DEBE estar en la enumeración WMF Binary Raster Op ([MS-WMF] sección 2.1.1.2). |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetRop2`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


Inicializa una nueva instancia de la clase `EmfSetRop2`.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de operación raster y DEBE estar en la enumeración WMF Binary Raster Op ([MS-WMF] sección 2.1.1.2).

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el modo de operación raster y DEBE estar en la enumeración WMF Binary Raster Op ([MS-WMF] sección 2.1.1.2).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

