---
title: "WmfFillRegion"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_FILLREGION rellena una región usando un pincel especificado."
type: docs
weight: 37
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

El registro META\_FILLREGION rellena una región usando un pincel especificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | Inicializa una nueva instancia de la clase `WmfFillRegion`. |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | Inicializa una nueva instancia de la clase `WmfFillRegion`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | Obtiene o establece el índice de la región. |
| [setRegionIndex(int value)](#setRegionIndex-int-) | Obtiene o establece el índice de la región. |
| [getBrushIndex()](#getBrushIndex--) | Obtiene o establece el índice del pincel. |
| [setBrushIndex(int value)](#setBrushIndex-int-) | Obtiene o establece el índice del pincel. |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


Inicializa una nueva instancia de la clase `WmfFillRegion`.

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


Inicializa una nueva instancia de la clase `WmfFillRegion`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | La región. |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | El pincel. |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


Obtiene o establece el índice de la región.

Valor: Índice en la tabla de objetos WMF para obtener la región que se debe rellenar.

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


Obtiene o establece el índice de la región.

Valor: Índice en la tabla de objetos WMF para obtener la región que se debe rellenar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


Obtiene o establece el índice del pincel.

Valor: Índice en la tabla de objetos WMF para obtener el pincel que se usará para rellenar la región.

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


Obtiene o establece el índice del pincel.

Valor: Índice en la tabla de objetos WMF para obtener el pincel que se usará para rellenar la región.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

