---
title: "VectorRasterizationOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de rasterización vectorial."
type: docs
weight: 52
url: /es/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

Las opciones de rasterización vectorial. Tenga en cuenta que [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) ya no derivará de [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) desde la versión 24.12 de Aspose.Imaging.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Obtiene el modo de suavizado. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Establece el modo de suavizado. |
| [getBorderX()](#getBorderX--) | Obtiene o establece el borde X. |
| [setBorderX(float value)](#setBorderX-float-) | Obtiene o establece el borde X. |
| [getBorderY()](#getBorderY--) | Obtiene o establece el borde Y. |
| [setBorderY(float value)](#setBorderY-float-) | Obtiene o establece el borde Y. |
| [getCenterDrawing()](#getCenterDrawing--) | Obtiene un valor que indica si el dibujo está centrado. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Establece un valor que indica si el dibujo está centrado. |
| [getPageHeight()](#getPageHeight--) | Obtiene la altura de la página. |
| [setPageHeight(float value)](#setPageHeight-float-) | Establece la altura de la página. |
| [getPageSize()](#getPageSize--) | Obtiene el tamaño de la página. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Establece el tamaño de la página. |
| [getPageWidth()](#getPageWidth--) | Obtiene el ancho de la página. |
| [setPageWidth(float value)](#setPageWidth-float-) | Establece el ancho de la página. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene un color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Establece un color de fondo. |
| [getDrawColor()](#getDrawColor--) | Obtiene un color de primer plano. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Establece un color de primer plano. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Obtiene la sugerencia de renderizado de texto. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Establece la sugerencia de renderizado de texto. |
| [getPositioning()](#getPositioning--) | Obtiene el posicionamiento. |
| [setPositioning(int value)](#setPositioning-int-) | Establece el posicionamiento. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Obtiene el mapeo de reemplazo de texto. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Establece el mapeo de reemplazo de texto. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia esta instancia a `vectorRasterizationOptions`. |
| [deepClone()](#deepClone--) | Crea una clonación superficial del objeto. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Obtiene el modo de suavizado.

**Returns:**
int - el modo de suavizado.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Establece el modo de suavizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el modo de suavizado. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar una imagen.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Para rasterizar SVG necesitamos especificar opciones de rasterización.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Establece el color predeterminado de fondo para una imagen. El valor predeterminado es blanco.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Establece el tamaño de la página
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Se aplica antialiasing a líneas y curvas y a los bordes de áreas rellenas.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Reduce el tamaño de la imagen 10 veces, es decir, el tamaño de salida será el 10 % del tamaño original.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Guardar en un archivo PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Obtiene o establece el borde X.

**Returns:**
float - El borde X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Obtiene o establece el borde X.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El borde X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Obtiene o establece el borde Y.

**Returns:**
float - El borde Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Obtiene o establece el borde Y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El borde Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Obtiene un valor que indica si el dibujo está centrado.

**Returns:**
boolean - un valor que indica si el dibujo está centrado.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Establece un valor que indica si el dibujo está centrado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si el dibujo está centrado. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Obtiene la altura de la página.

**Returns:**
float - la altura de la página.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Establece la altura de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | la altura de la página. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Obtiene el tamaño de la página.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Establece el tamaño de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | el tamaño de la página. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // El texto se convertirá en formas.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // El tamaño de página.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Si existe un emf incrustado, renderice emf; de lo contrario, renderice wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // El texto se convertirá en formas.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // El tamaño de página.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Si existe un emf incrustado, renderice emf; de lo contrario, renderice wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Establezca el margen horizontal
    rasterizationOptions.setBorderX(50);

    // Establezca el margen vertical
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Obtiene el ancho de la página.

**Returns:**
float - el ancho de la página.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Establece el ancho de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el ancho de la página. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene un color de fondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Establece un color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un color de fondo. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // El texto se convertirá en formas.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // El tamaño de página.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Si existe un emf incrustado, renderice emf; de lo contrario, renderice wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // El texto se convertirá en formas.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // El tamaño de página.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Si existe un emf incrustado, renderice emf; de lo contrario, renderice wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Establezca el margen horizontal
    rasterizationOptions.setBorderX(50);

    // Establezca el margen vertical
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Obtiene un color de primer plano.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Establece un color de primer plano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un color de primer plano. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Obtiene la sugerencia de renderizado de texto.

Valor: La sugerencia de renderizado de texto.

**Returns:**
int - la sugerencia de renderizado de texto.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Establece la sugerencia de renderizado de texto.

Valor: La sugerencia de renderizado de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la sugerencia de renderizado de texto. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar una imagen.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Para rasterizar SVG necesitamos especificar opciones de rasterización.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Establece el color predeterminado de fondo para una imagen. El valor predeterminado es blanco.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Establece el tamaño de la página
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Se aplica antialiasing a líneas y curvas y a los bordes de áreas rellenas.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Reduce el tamaño de la imagen 10 veces, es decir, el tamaño de salida será el 10 % del tamaño original.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Guardar en un archivo PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Obtiene el posicionamiento.

Valor: El posicionamiento.

**Returns:**
int - el posicionamiento.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Establece el posicionamiento.

Valor: El posicionamiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el posicionamiento. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Obtiene el mapeo de reemplazo de texto.

Valor: El mapeo de reemplazo de texto.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - el mapeo de reemplazo de texto.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Establece el mapeo de reemplazo de texto.

Valor: El mapeo de reemplazo de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.HashMap<java.lang.String,java.lang.String> | el mapeo de reemplazo de texto. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia esta instancia a `vectorRasterizationOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Las opciones de rasterización vectorial. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


Crea una clonación superficial del objeto.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
