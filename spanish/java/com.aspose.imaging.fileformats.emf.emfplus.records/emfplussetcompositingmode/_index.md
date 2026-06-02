---
title: "EmfPlusSetCompositingMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetCompositingMode especifica cómo se combinan los colores de origen con los colores de fondo."
type: docs
weight: 58
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

El registro EmfPlusSetCompositingMode especifica cómo se combinan los colores de origen con los colores de fondo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetCompositingMode`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | Obtiene o establece el valor del modo de composición, de la enumeración CompositingMode (sección 2.1.1.5). |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Obtiene o establece el valor del modo de composición, de la enumeración CompositingMode (sección 2.1.1.5). |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetCompositingMode`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Obtiene o establece el valor del modo de composición, de la enumeración CompositingMode (sección 2.1.1.5). La composición puede expresarse como el estado de la mezcla alfa, que puede estar activada o desactivada.

Valor: El modo de composición.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Obtiene o establece el valor del modo de composición, de la enumeración CompositingMode (sección 2.1.1.5). La composición puede expresarse como el estado de la mezcla alfa, que puede estar activada o desactivada.

Valor: El modo de composición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

