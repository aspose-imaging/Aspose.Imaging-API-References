---
title: "EmfFillPath"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_FILLPATH cierra cualquier figura abierta en la ruta actual y rellena el interior de la ruta utilizando el pincel actual y el modo de relleno de polígonos."
type: docs
weight: 58
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emffillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillPath extends EmfDrawingRecordType
```

El registro EMR\_FILLPATH cierra cualquier figura abierta en la ruta actual y rellena el interior de la ruta usando el pincel actual y el modo de relleno de polígonos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfFillPath(EmfRecord source)](#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfFillPath`. |
| [EmfFillPath()](#EmfFillPath--) | Inicializa una nueva instancia de la clase `EmfFillPath`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador, en unidades del dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador, en unidades del dispositivo. |
### EmfFillPath(EmfRecord source) {#EmfFillPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillPath(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfFillPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfFillPath() {#EmfFillPath--}
```
public EmfFillPath()
```


Inicializa una nueva instancia de la clase `EmfFillPath`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador, en unidades del dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL de 128 bits, especificado en la sección 2.2.2.19 de [MS-WMF], que define el rectángulo delimitador, en unidades del dispositivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

