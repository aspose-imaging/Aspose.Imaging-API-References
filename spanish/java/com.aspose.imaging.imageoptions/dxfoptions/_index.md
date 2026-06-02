---
title: "DxfOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para la creación de imágenes vectoriales DXF (Drawing Interchange Format) ofrece soluciones personalizadas para generar archivos de dibujo AutoCAD con precisión y flexibilidad."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

La API para la creación de imágenes vectoriales Drawing Interchange Format (DXF) ofrece soluciones personalizadas para generar archivos de dibujo AutoCAD con precisión y flexibilidad. Diseñada específicamente para trabajar con líneas de texto y curvas Bézier, los desarrolladores pueden manipular eficientemente estos elementos, contar puntos Bézier y convertir curvas en polilíneas para una exportación sin problemas, garantizando compatibilidad y fidelidad en imágenes vectoriales DXF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Constructor de Coping |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | Cuántos puntos generar al convertir curvas Bezier a polilíneas, mínimo 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | Cuántos puntos generar al convertir curvas Bezier a polilíneas, mínimo 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | Funciona cuando \#textAsLines está configurado a `true`. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | Funciona cuando \#textAsLines está configurado a `true`. |
| [getTextAsLines()](#getTextAsLines--) | Si el texto debe exportarse como contornos compuestos de polilíneas (por defecto) o como entidades de TEXTO editables de Autocad. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Si el texto debe exportarse como contornos compuestos de polilíneas (por defecto) o como entidades de TEXTO editables de Autocad. |

## Example: This example demonstrates export to Dxf format

``` java

//Crear una instancia de Image e inicializarla con un archivo de imagen existente desde la ubicación en disco.
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Constructor de Coping

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | Las opciones de origen para coping |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


Cuántos puntos generar al convertir curvas Bezier a polilíneas, mínimo 4. Usado cuando (/) y (/) están ambos /// configurados a `true`

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


Cuántos puntos generar al convertir curvas Bezier a polilíneas, mínimo 4. Usado cuando (/) y (/) están ambos /// configurados a `true`

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


Funciona cuando \#textAsLines está configurado a `true`. Si se deben convertir las curvas Bezier en contornos de texto a polilíneas multipunto.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


Funciona cuando \#textAsLines está configurado a `true`. Si se deben convertir las curvas Bezier en contornos de texto a polilíneas multipunto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Si el texto debe exportarse como contornos compuestos de polilíneas (por defecto) o como entidades de TEXTO editables de Autocad. Si esta opción está establecida

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Si el texto debe exportarse como contornos compuestos de polilíneas (por defecto) o como entidades de TEXTO editables de Autocad. Si esta opción está establecida

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

