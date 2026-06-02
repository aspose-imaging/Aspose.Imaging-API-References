---
title: "OdgImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipula el formato de archivo de imagen vectorial ODG de OpenDocument Graphic con nuestra API, ampliamente utilizada por las aplicaciones OpenOffice y LibreOffice Draw para almacenar elementos de dibujo en formato vectorial."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

Manipula el formato de archivo de imagen vectorial OpenDocument Graphic (ODG) con nuestra API, ampliamente utilizada por las aplicaciones OpenOffice y LibreOffice Draw para almacenar elementos de dibujo en formato vectorial. Analiza documentos sin problemas, accede a páginas, redimensiona y rota imágenes, garantizando un procesamiento eficiente y la personalización de archivos ODG para cumplir con tus requisitos específicos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Inicia una nueva creación del objeto de la clase [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) con la iniciación de una nueva instancia. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Diseñado para una integración sin problemas en soluciones de software, el constructor [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) inicializa una nueva instancia aprovechando un contenedor de flujo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupere fácilmente el valor del formato de archivo con esta propiedad fácil de usar. |
| [getPages()](#getPages--) | Al recuperar la colección de páginas, esta propiedad permite acceder a la totalidad de páginas asociadas a una imagen. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar una imagen.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // Convertir a OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Obtener todas las páginas
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Realiza algún procesamiento de imagen
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Inicia una nueva creación del objeto de la clase [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) con la iniciación de una nueva instancia. Aprovecha el potencial de un contenedor de flujo combinado con parámetros de opciones de carga, manteniendo un constructor versátil para cargar imágenes sin problemas. Este constructor permite un manejo eficiente de imágenes, ofreciendo configuraciones de carga personalizables para una mayor adaptabilidad y rendimiento en diversos escenarios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El flujo. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Diseñado para una integración sin problemas en soluciones de software, el constructor [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) inicializa una nueva instancia aprovechando un contenedor de flujo. Este método garantiza un manejo eficiente de los datos de imagen ODG dentro de entornos de software, optimizando la utilización de recursos y facilitando flujos de trabajo de procesamiento de imágenes simplificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupere fácilmente el valor del formato de archivo con esta propiedad fácil de usar. Ideal para desarrolladores que buscan acceso rápido a la información sobre el formato de archivo.

**Returns:**
long - un valor del formato de archivo
### getPages() {#getPages--}
```
public Image[] getPages()
```


Al recuperar la colección de páginas, esta propiedad permite acceder a la totalidad de páginas asociadas a una imagen. Al acceder a esta propiedad, los desarrolladores pueden iterar a través de páginas individuales, recuperar páginas específicas según su índice o realizar operaciones por lotes en toda la colección.

**Returns:**
com.aspose.imaging.Image[] - las páginas.
