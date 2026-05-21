---
title: "EmfImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para el soporte del formato de imagen vectorial Enhanced Metafile Format EMF es una herramienta integral para procesar imágenes gráficas de manera independiente del dispositivo mientras se preservan sus propiedades originales."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

La API para el soporte del formato de imagen vectorial Enhanced Metafile Format (EMF) es una herramienta integral para procesar imágenes gráficas de manera independiente del dispositivo mientras se preservan sus propiedades originales. Desarrollada para mantener proporciones, dimensiones, colores y otros atributos gráficos, incluye soporte para el formato EMF Plus y funcionalidades para recortar regiones, cambiar el tamaño del lienzo y de las imágenes, rotar, voltear, establecer paletas de imágenes, exportar e importar al contexto de dispositivo APS, comprimir y convertir EMF a otros formatos, garantizando una manipulación versátil e integración fluida de imágenes EMF en diversas aplicaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfImage()](#EmfImage--) | Comience a trabajar con imágenes EMF inicializando una nueva instancia de la clase [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Cree una nueva instancia de la clase [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) especificando los parámetros de ancho y alto. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeader()](#getHeader--) | Recupere el registro de encabezado del metarchivo EMF con esta propiedad. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Modifique el registro de encabezado del metarchivo EMF con esta propiedad. |
| [isCached()](#isCached--) | Acceda a un valor que indica si los datos del objeto están actualmente en caché, eliminando la necesidad de lecturas de datos adicionales. |
| [getRecords()](#getRecords--) | Recupere o modifique los registros asociados al objeto. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Modifique los registros asociados al objeto. |
| [getFileFormat()](#getFileFormat--) | Acceda al valor del formato de archivo asociado al objeto. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupere el recuento de bits por píxel específico de imágenes raster, ya que este parámetro no se aplica a imágenes vectoriales. |
| [getWidthF()](#getWidthF--) | Acceda al ancho de la imagen, proporcionando información esencial para una renderización y procesamiento precisos. |
| [getHeightF()](#getHeightF--) | Recupere la altura de la imagen, facilitando ajustes precisos de renderizado y diseño. |
| [cacheData()](#cacheData--) | Cachee datos de manera eficiente y evite cargas redundantes desde el `DataStreamSupporter.DataStreamContainer` ([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) con este método. |
| [getUsedFonts()](#getUsedFonts--) | Recupere la lista de fuentes utilizadas dentro del metarchivo con este método. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Redimensione el lienzo con facilidad usando esta función. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones originales de la imagen. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Establece la paleta de la imagen. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


Comience a trabajar con imágenes EMF inicializando una nueva instancia de la clase [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). Ideal para incorporar rápidamente imágenes EMF en sus proyectos con facilidad y eficiencia.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Cree una nueva instancia de la clase [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) especificando los parámetros de ancho y alto. Este constructor simplifica el proceso de inicializar imágenes EMF con dimensiones específicas, mejorando la eficiencia de su flujo de trabajo de desarrollo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho. |
| height | int | La altura. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Recupere el registro de encabezado del metarchivo EMF con esta propiedad. Ideal para gestionar datos de metarchivo de manera eficiente dentro de su aplicación. Mejore su flujo de trabajo con un acceso simplificado a la información del encabezado del metarchivo.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Modifique el registro de encabezado del metarchivo EMF con esta propiedad. Ideal para gestionar datos de metarchivo de manera eficiente dentro de su aplicación. Mejore su flujo de trabajo con un acceso simplificado a la información del encabezado del metarchivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Acceda a un valor que indica si los datos del objeto están actualmente en caché, eliminando la necesidad de lecturas de datos adicionales. Mejore la eficiencia determinando rápidamente si los datos en caché están disponibles para acceso inmediato. Optimice su flujo de trabajo con procesos de recuperación de datos simplificados.

**Returns:**
boolean - `true` si los datos del objeto están en caché; de lo contrario, `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Recuperar o modificar los registros asociados al objeto. Acceder y gestionar eficientemente la colección de registros para una manipulación y procesamiento de datos mejorados. Optimiza tu flujo de trabajo interactuando sin problemas con los registros del objeto.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Modificar los registros asociados al objeto. Acceder y gestionar eficientemente la colección de registros para una manipulación y procesamiento de datos mejorados. Optimiza tu flujo de trabajo interactuando sin problemas con los registros del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Los registros. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Acceder al valor del formato de archivo asociado al objeto. Determinar fácilmente el formato del archivo asociado al objeto para un procesamiento simplificado y verificaciones de compatibilidad. Simplifica tu flujo de trabajo recuperando la información del formato de archivo con facilidad.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recuperar el recuento de bits por píxel específico de imágenes raster, ya que este parámetro no se aplica a imágenes vectoriales. Determinar rápidamente la profundidad de píxeles de las imágenes raster para un análisis y manipulación precisos, garantizando un manejo exacto de los datos de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Acceder al ancho de la imagen, proporcionando información esencial para una renderización y procesamiento precisos. Recuperar rápidamente el ancho de la imagen para garantizar la compatibilidad y una disposición adecuada en diversas aplicaciones y plataformas.

**Returns:**
float - El ancho de la imagen en píxeles.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Recuperar la altura de la imagen, facilitando ajustes precisos de renderizado y disposición. Acceder a la propiedad de altura garantiza la compatibilidad y una integración fluida en diferentes plataformas y aplicaciones.

**Returns:**
float - La altura de la imagen en píxeles.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachear datos de manera eficiente y evitar cargas redundantes desde el `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) con este método. Mejora el rendimiento y simplifica el acceso a los datos en tu aplicación, optimizando la utilización de recursos para una mayor capacidad de respuesta.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Almacena en caché los datos para cargar todos los registros.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // La clave es un tipo de registro, el valor es el número de registros de ese tipo en la imagen WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Recopilar estadísticas
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
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
    emfImage.dispose();
}

//La salida puede verse así:
//El número total de registros: 1188
//Tipo de Registro                              Cantidad
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Recupera la lista de fuentes utilizadas dentro del metafile con este método. Obtén información sobre el uso de fuentes, facilitando una gestión eficiente y la optimización de los recursos tipográficos para una renderización y fidelidad de visualización mejoradas.

**Returns:**
java.lang.String[] - La lista de fuentes
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Redimensiona el lienzo con facilidad usando esta función. Perfecto para ajustar las dimensiones generales de la imagen sin alterar su contenido. Mejora la presentación y prepara las imágenes para varios tamaños de pantalla sin esfuerzo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El nuevo rectángulo. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones originales de la imagen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Establece la paleta de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

