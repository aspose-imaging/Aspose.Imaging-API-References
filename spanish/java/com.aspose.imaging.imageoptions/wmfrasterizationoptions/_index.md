---
title: "WmfRasterizationOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de rasterización Wmf."
type: docs
weight: 55
url: /es/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Las opciones de rasterización Wmf.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Inicializa una nueva instancia de la clase `WmfRasterizationOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Obtiene o establece el modo de renderizado WMF. |
| [setRenderMode(int value)](#setRenderMode-int-) | Obtiene o establece el modo de renderizado WMF. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copia esto a `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Inicializa una nueva instancia de la clase `WmfRasterizationOptions`.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Obtiene o establece el modo de renderizado WMF.

Valor: El modo de renderizado WMF.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Obtiene o establece el modo de renderizado WMF.

Valor: El modo de renderizado WMF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia esto a `vectorRasterizationOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

