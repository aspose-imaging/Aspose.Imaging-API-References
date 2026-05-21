---
title: "FileCreateSource"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una fuente de archivo para creación."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Representa una fuente de archivo para creación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Inicializa una nueva instancia de la clase `FileCreateSource`. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Inicializa una nueva instancia de la clase `FileCreateSource`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFilePath()](#getFilePath--) | Obtiene la ruta del archivo para crear. |
| [isTemporal()](#isTemporal--) | Obtiene un valor que indica si el archivo será temporal. |
| [getStreamContainer()](#getStreamContainer--) | Obtiene el contenedor de flujo. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Este ejemplo demuestra el uso de las clases Font y SolidBrush para dibujar cadenas en la superficie de Image. El ejemplo crea una nueva Image y dibuja formas usando Figures y GraphicsPath
``` java
//Crea una instancia de BmpOptions y establece sus diversas propiedades.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Crea una instancia de FileCreateSource y asígnala como Source para la instancia de BmpOptions
//El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Crea una instancia de Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crea e inicializa una instancia de la clase Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Limpia la superficie de Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crea una instancia de Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Crea una instancia de SolidBrush con color rojo
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Dibuja una cadena
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // guarda todos los cambios
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Inicializa una nueva instancia de la clase `FileCreateSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo para crear. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Inicializa una nueva instancia de la clase `FileCreateSource`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo para crear. |
| isTemporal | boolean | Si se establece en `true`, el archivo creado será temporal. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Obtiene la ruta del archivo para crear.

Valor: La ruta del archivo para crear.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Obtiene un valor que indica si el archivo será temporal.

Valor: `true` si el archivo será temporal; de lo contrario, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Obtiene el contenedor de flujo.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Usar con precaución. Necesitará disponer del contenedor de flujo después de la recuperación.
