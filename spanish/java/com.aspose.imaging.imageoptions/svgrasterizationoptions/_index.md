---
title: "SvgRasterizationOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de rasterización de SVG."
type: docs
weight: 46
url: /es/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

Las opciones de rasterización de SVG.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | Inicializa una nueva instancia de la clase `SvgRasterizationOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getScaleX()](#getScaleX--) | Obtiene o establece la escala x. |
| [setScaleX(float value)](#setScaleX-float-) | Obtiene o establece la escala x. |
| [getScaleY()](#getScaleY--) | Obtiene o establece la escala y. |
| [setScaleY(float value)](#setScaleY-float-) | Obtiene o establece la escala y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia esta instancia a `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


Inicializa una nueva instancia de la clase `SvgRasterizationOptions`.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Obtiene o establece la escala x.

**Returns:**
float - La escala x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Obtiene o establece la escala x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La escala x. |


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

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Obtiene o establece la escala y.

**Returns:**
float - La escala y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Obtiene o establece la escala y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | La escala y. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia esta instancia a `vectorRasterizationOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Las opciones de rasterización vectorial. |

