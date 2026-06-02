---
title: "EmfRasterizationOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de rasterización Emf."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

Las opciones de rasterización Emf.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Obtiene o establece el modo de renderizado. |
| [setRenderMode(int value)](#setRenderMode-int-) | Obtiene o establece el modo de renderizado. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia esto a `vectorRasterizationOptions`. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Obtiene o establece el modo de renderizado.

**Returns:**
int - El modo de renderizado.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Obtiene o establece el modo de renderizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de renderizado. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia esto a `vectorRasterizationOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

