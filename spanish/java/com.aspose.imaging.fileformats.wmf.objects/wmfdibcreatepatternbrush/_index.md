---
title: "WmfDibCreatePatternBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_DIBCREATEPATTERNBRUSH crea una sección de Brush Object 2.2.1.1 con un patrón especificado por una sección de DeviceIndependentBitmap DIB Object 2.2.2.9."
type: docs
weight: 29
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfDibCreatePatternBrush extends WmfGraphicObject
```

El registro META\_DIBCREATEPATTERNBRUSH crea un objeto Brush (sección 2.2.1.1) con un patrón especificado por un objeto DeviceIndependentBitmap (DIB) (sección 2.2.2.9).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfDibCreatePatternBrush()](#WmfDibCreatePatternBrush--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStyle()](#getStyle--) | Obtiene o establece el estilo. |
| [setStyle(int value)](#setStyle-int-) | Obtiene o establece el estilo. |
| [getColorUsage()](#getColorUsage--) | Obtiene o establece el uso del color. |
| [setColorUsage(int value)](#setColorUsage-int-) | Obtiene o establece el uso del color. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtiene o establece el mapa de bits de origen. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtiene o establece el mapa de bits de origen. |
### WmfDibCreatePatternBrush() {#WmfDibCreatePatternBrush--}
```
public WmfDibCreatePatternBrush()
```


### getStyle() {#getStyle--}
```
public int getStyle()
```


Obtiene o establece el estilo.

Valor: Los valores legales para este campo se definen de la siguiente manera: si el valor no es BS\_PATTERN, se DEBE asumir BS\_DIBPATTERNPT. Estos valores se especifican en la enumeración BrushStyle (sección 2.1.1.4).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Obtiene o establece el estilo.

Valor: Los valores legales para este campo se definen de la siguiente manera: si el valor no es BS\_PATTERN, se DEBE asumir BS\_DIBPATTERNPT. Estos valores se especifican en la enumeración BrushStyle (sección 2.1.1.4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Obtiene o establece el uso del color.

Valor: El campo Colors de un DIB Object contiene valores RGB explícitos, o índices en una paleta.

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Obtiene o establece el uso del color.

Valor: El campo Colors de un DIB Object contiene valores RGB explícitos, o índices en una paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtiene o establece el mapa de bits de origen.

Valor: Datos de DIB Object de bits variables que definen el patrón a usar en el brush.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtiene o establece el mapa de bits de origen.

Valor: Datos de DIB Object de bits variables que definen el patrón a usar en el brush.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

