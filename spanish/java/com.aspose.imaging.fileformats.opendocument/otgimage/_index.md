---
title: "OtgImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Procesa archivos de imagen de dibujo OTG de Plantilla OpenDocument con nuestra API aprovechando el formato OpenDocument XML con contenido gráfico para una manipulación fluida."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

Procesa archivos de imagen de dibujo de Plantilla OpenDocument (OTG) con nuestra API, aprovechando el formato OpenDocument XML con contenido gráfico para una manipulación fluida. Analiza documentos fácilmente, personaliza los colores de fondo y ajusta las dimensiones de la página, garantizando un control óptimo y flexibilidad para tus proyectos de gráficos vectoriales OTG.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Inicializa un nuevo objeto [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) proporcionando un contenedor de flujo y opciones de carga. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Crea un nuevo objeto de la clase [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) suministrando un contenedor de flujo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Esta propiedad brinda acceso al formato de archivo OTG, ofreciendo información crucial sobre el tipo de datos encapsulados dentro del archivo de imagen. |
| [getPages()](#getPages--) | Recupera la colección de páginas asociadas a la imagen, permitiendo a los desarrolladores de software acceder y manipular cada página individual de manera eficiente. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Inicializa un nuevo objeto [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) proporcionando un contenedor de flujo y opciones de carga. Este constructor permite a los desarrolladores cargar de manera eficiente imágenes OTG desde flujos mientras se especifican configuraciones de carga personalizadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Crea un nuevo objeto de la clase [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) suministrando un contenedor de flujo. Este constructor permite a los desarrolladores crear imágenes OTG directamente a partir de contenedores de flujo, optimizando el proceso de trabajo con datos de imágenes OTG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Esta propiedad brinda acceso al formato de archivo OTG, ofreciendo información crucial sobre el tipo de datos encapsulados dentro del archivo de imagen. Sirve como un punto de referencia fundamental para los desarrolladores de software, permitiéndoles manejar eficazmente los archivos OTG dentro de sus aplicaciones. Al utilizar esta propiedad, puedes determinar el formato específico del archivo de imagen, facilitando la integración y manipulación sin problemas de los archivos OTG en sus sistemas de software.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


Recupera la colección de páginas asociadas a la imagen, permitiendo a los desarrolladores de software acceder y manipular cada página individual de manera eficiente. Esta propiedad facilita la iteración sin problemas a través de las páginas para diversas operaciones, mejorando la funcionalidad y versatilidad de las aplicaciones de procesamiento de imágenes.

**Returns:**
com.aspose.imaging.Image[] - las páginas.
