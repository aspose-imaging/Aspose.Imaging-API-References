---
title: "EmfSetBrushOrgEx"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_SETBRUSHORGEX especifica el origen del pincel actual."
type: docs
weight: 121
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBrushOrgEx extends EmfStateRecordType
```

El registro EMR\_SETBRUSHORGEX especifica el origen del pincel actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfSetBrushOrgEx(EmfRecord source)](#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfSetBrushOrgEx`. |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx--) | Inicializa una nueva instancia de la clase `EmfSetBrushOrgEx`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOrigin()](#getOrigin--) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que especifica el origen horizontal y vertical del pincel en unidades de dispositivo. |
| [setOrigin(Point value)](#setOrigin-com.aspose.imaging.Point-) | Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que especifica el origen horizontal y vertical del pincel en unidades de dispositivo. |
### EmfSetBrushOrgEx(EmfRecord source) {#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBrushOrgEx(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfSetBrushOrgEx`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfSetBrushOrgEx() {#EmfSetBrushOrgEx--}
```
public EmfSetBrushOrgEx()
```


Inicializa una nueva instancia de la clase `EmfSetBrushOrgEx`.

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que especifica el origen horizontal y vertical del pincel en unidades de dispositivo.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOrigin(Point value) {#setOrigin-com.aspose.imaging.Point-}
```
public void setOrigin(Point value)
```


Obtiene o establece un objeto WMF PointL de 64 bits, especificado en la sección 2.2.2.15 de [MS-WMF], que especifica el origen horizontal y vertical del pincel en unidades de dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

