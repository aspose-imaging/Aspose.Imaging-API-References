---
title: "WmfImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule imágenes Microsoft Windows Metafile WMF con nuestra API, manejando sin problemas tanto datos vectoriales como de mapa de bits almacenados en registros de longitud variable."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Manipule imágenes Microsoft Windows Metafile (WMF) con nuestra API, manejando sin problemas tanto datos vectoriales como de mapa de bits almacenados en registros de longitud variable. Redimensione, rote y voltee imágenes con facilidad mientras establece paletas de colores personalizadas. Convierta archivos WMF a formatos WMZ comprimidos o guárdelos en formatos de imagen raster para un uso versátil en distintas plataformas y aplicaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfImage()](#WmfImage--) | Cree una nueva instancia de la clase [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), inicializándola para una mayor manipulación y procesamiento de datos de imágenes Windows Metafile (WMF). |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Instancie una nueva instancia de la clase [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) con parámetros de ancho y alto personalizables, facilitando la creación de imágenes WMF en blanco adaptadas a dimensiones específicas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isCached()](#isCached--) | Obtenga un valor booleano que indica si los datos del objeto están actualmente en caché, eliminando la necesidad de operaciones adicionales de lectura de datos. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtenga el recuento de bits por píxel de la imagen, indicando el nivel de profundidad de color o granularidad. |
| [getWidthF()](#getWidthF--) | Acceda al ancho de la imagen, indicando el número de píxeles a lo largo de su eje horizontal. |
| [getHeightF()](#getHeightF--) | Acceda a la altura de la imagen, representando el número de píxeles a lo largo de su eje vertical. |
| [getInch()](#getInch--) | Acceda o modifique la propiedad inch, que representa una unidad de medida típicamente usada para especificar dimensiones físicas en contextos de impresión o visualización. |
| [setInch(int value)](#setInch-int-) | Acceda o modifique la propiedad inch, que representa una unidad de medida típicamente usada para especificar dimensiones físicas en contextos de impresión o visualización. |
| [getFileFormat()](#getFileFormat--) | Acceda al valor del formato de archivo asociado a la imagen, proporcionando información sobre el formato en el que la imagen está almacenada. |
| [getFrameBounds()](#getFrameBounds--) | Acceda a los límites del marco, indicando su posición y dimensiones dentro de la imagen. |
| [cacheData()](#cacheData--) | Cachee los datos de manera eficiente, eliminando la necesidad de cargar adicionalmente desde el `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Aplique una paleta especificada a la imagen, permitiendo la personalización de la representación de colores. |
| [getUsedFonts()](#getUsedFonts--) | Obtenga la lista de fuentes usadas dentro del metafile, proporcionando información sobre los recursos tipográficos utilizados en la imagen. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Redimensione el lienzo de la imagen, ajustando sus dimensiones mientras conserva el contenido de la imagen. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Incorpore el objeto de registro especificado en la imagen, enriqueciendo su contenido con datos o metadatos adicionales. |
| [getPostScript()](#getPostScript--) | Acceda a los datos PostScript asociados a la imagen, proporcionando información detallada sobre su estructura o contenido. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones originales de la imagen. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

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


## Example: The following example shows how to convert a compressed images (*.
El siguiente ejemplo muestra cómo convertir imágenes comprimidas (*.emz,*.wmz, *.svgz) a formato raster.
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Crea una nueva instancia de la clase [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), inicializándola para la manipulación y el procesamiento posteriores de datos de imágenes Windows Metafile (WMF). Este constructor proporciona un objeto fundamental para trabajar con imágenes WMF, permitiendo una integración fluida de las capacidades de manejo de imágenes WMF en la funcionalidad de tu aplicación.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Instancia una nueva instancia de la clase [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) con parámetros de ancho y alto personalizables, facilitando la creación de imágenes WMF en blanco adaptadas a dimensiones específicas. Utiliza este constructor para generar dinámicamente imágenes WMF con dimensiones precisas, permitiendo una creación y manipulación flexible de imágenes dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho. |
| height | int | La altura. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtén un valor booleano que indica si los datos del objeto están actualmente en caché, eliminando la necesidad de operaciones adicionales de lectura de datos. Utiliza esta propiedad para optimizar el rendimiento determinando si los datos del objeto están disponibles de inmediato sin necesidad de costosos procesos de recuperación de datos dentro de tu aplicación.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtén el recuento de bits por píxel de la imagen, indicando el nivel de profundidad o granularidad de color. Utiliza esta propiedad para determinar la representación y precisión de color de la imagen, facilitando verificaciones de compatibilidad y procesamiento relacionado con el color dentro de tu aplicación.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Accede al ancho de la imagen, indicando el número de píxeles a lo largo de su eje horizontal. Utiliza esta propiedad para determinar las dimensiones espaciales y la relación de aspecto de la imagen, permitiendo ajustes precisos de diseño y renderizado dentro de tu aplicación.

**Returns:**
float - El ancho de la imagen en píxeles.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Accede a la altura de la imagen, que representa el número de píxeles a lo largo de su eje vertical. Utiliza esta propiedad para determinar las dimensiones espaciales y la relación de aspecto de la imagen, permitiendo ajustes precisos de diseño y renderizado dentro de tu aplicación.

**Returns:**
float - La altura de la imagen en píxeles.
### getInch() {#getInch--}
```
public int getInch()
```


Accede o modifica la propiedad inch, que representa una unidad de medida típicamente usada para especificar dimensiones físicas en contextos de impresión o pantalla. Utiliza esta propiedad para establecer o recuperar valores en pulgadas asociados a la imagen, facilitando una representación precisa de las dimensiones físicas dentro de tu aplicación.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Accede o modifica la propiedad inch, que representa una unidad de medida típicamente usada para especificar dimensiones físicas en contextos de impresión o pantalla. Utiliza esta propiedad para establecer o recuperar valores en pulgadas asociados a la imagen, facilitando una representación precisa de las dimensiones físicas dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accede al valor del formato de archivo asociado a la imagen, proporcionando información sobre el formato en el que se almacena la imagen. Utiliza esta propiedad para determinar el formato de archivo de la imagen, facilitando verificaciones de compatibilidad y procesamiento específico del formato dentro de tu aplicación.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Accede a los límites del marco, indicando su posición y dimensiones dentro de la imagen. Utiliza esta propiedad para obtener información detallada sobre la ubicación espacial del marco, permitiendo una manipulación y renderizado precisos dentro de tu aplicación.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacena en caché los datos de manera eficiente, eliminando la necesidad de cargar adicionalmente desde el subyacente `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Utiliza este método para optimizar el rendimiento y minimizar el uso de recursos dentro de tu aplicación almacenando y accediendo a la caché local de datos.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Almacena en caché los datos para cargar todos los registros.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // La clave es un tipo de registro, el valor es el número de registros de ese tipo en la imagen WMF.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // Recopilar estadísticas
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Imprimir estadísticas
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Alinear la salida con espacios
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    wmfImage.dispose();
}

//La salida puede verse así:
//El número total de registros: 613
//Tipo de Registro                              Cantidad
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Aplicar una paleta especificada a la imagen, permitiendo la personalización de la representación de colores. Utilice este método para mejorar la renderización visual y lograr efectos de color específicos dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Recuperar la lista de fuentes utilizadas dentro del metarchivo, proporcionando información sobre los recursos tipográficos empleados en la imagen. Utilice este método para analizar el uso de fuentes y garantizar la disponibilidad de fuentes para la renderización o procesamiento adicional dentro de su aplicación.

**Returns:**
java.lang.String[] - La lista de fuentes
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Cambiar el tamaño del lienzo de la imagen, ajustando sus dimensiones mientras se conserva el contenido de la imagen. Utilice este método para modificar el tamaño del lienzo sin alterar el contenido, facilitando ajustes de diseño y cambios de composición dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El nuevo rectángulo. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Incorporar el objeto de registro especificado en la imagen, enriqueciendo su contenido con datos o metadatos adicionales. Utilice este método para integrar sin problemas los objetos de registro en la imagen, facilitando el almacenamiento y la organización integral de datos dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | El registro. |

**Returns:**
int - Número de registro.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Acceder a los datos PostScript asociados con la imagen, proporcionando información detallada sobre su estructura o contenido. Utilice este método para recuperar los datos PostScript para un análisis o procesamiento adicional dentro de su aplicación, habilitando funcionalidades avanzadas relacionadas con la renderización o manipulación de PostScript.

**Returns:**
java.lang.String - El post script
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones originales de la imagen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
