---
title: "OdImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El documento abierto"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

El documento abierto
## Métodos

| Método | Descripción |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Recupera la página predeterminada asociada a la imagen, proporcionando acceso esencial a la página principal dentro de la colección de imágenes. |
| [isCached()](#isCached--) | Obtiene un valor booleano que indica si los datos del objeto están actualmente en caché, eliminando así la necesidad de leer los datos. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupera el recuento de bits por píxel de la imagen. |
| [getPageCount()](#getPageCount--) | Obtiene el recuento total de páginas dentro de la imagen. |
| [getOdMetadata()](#getOdMetadata--) | Obtiene los metadatos específicos de los archivos OpenDocument. |
| [getRecords()](#getRecords--) | Obtiene los registros OpenDocument almacenados dentro de la imagen. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Obtiene la página predeterminada asociada a la imagen, proporcionando acceso esencial a la página principal dentro de la colección de imágenes. Esta propiedad simplifica la navegación y manipulación de los datos de la imagen, mejorando la eficiencia de los flujos de trabajo de desarrollo de software.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor booleano que indica si los datos del objeto están actualmente en caché, eliminando así la necesidad de leer los datos. Esta propiedad sirve como indicador de optimización, mejorando el rendimiento al minimizar operaciones redundantes de acceso a datos.

**Returns:**
boolean - un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene el recuento de bits por píxel de la imagen. Esta propiedad brinda información sobre el nivel de detalle y la profundidad de color representada en la imagen, ayudando en diversas tareas de procesamiento y optimización de imágenes.

**Returns:**
int - el recuento de bits por píxel de la imagen.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Obtiene el recuento total de páginas dentro de la imagen. Esta propiedad es esencial para aplicaciones que gestionan imágenes multipágina, permitiéndoles determinar con precisión el número de páginas disponibles para procesamiento o visualización.

**Returns:**
int - el recuento de páginas.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


Obtiene metadatos específicos de los archivos OpenDocument. Esta propiedad permite el acceso a información esencial incrustada en los archivos OD, facilitando diversas operaciones como la extracción, modificación o análisis de metadatos.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Obtiene los registros OpenDocument almacenados dentro de la imagen. Esta propiedad otorga acceso a elementos de datos estructurados específicos incrustados en archivos OpenDocument, facilitando la recuperación o manipulación de información relevante para un procesamiento o análisis posterior.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - los registros.
