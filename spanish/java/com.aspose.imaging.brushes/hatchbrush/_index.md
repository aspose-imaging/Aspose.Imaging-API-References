---
title: "HatchBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define un pincel rectangular con un estilo de trama, un color de primer plano y un color de fondo."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Define un pincel rectangular con un estilo de trama, un color de primer plano y un color de fondo. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Obtiene el color de las líneas de trama. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Establece el color de las líneas de trama. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de los espacios entre las líneas de trama. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Establece el color de los espacios entre las líneas de trama. |
| [getHatchStyle()](#getHatchStyle--) | Obtiene el estilo de trama de este pincel. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Establece el estilo de trama de este pincel. |

## Example: This example shows the creation and usage Pen objects.
Este ejemplo muestra la creación y uso de objetos Pen. El ejemplo crea una nueva Image y dibuja Rectángulos en la superficie de Image.
``` java

// Crea una instancia de BmpOptions y establece sus diversas propiedades
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Crea una instancia de FileCreateSource y asígnala como Source para la instancia de BmpOptions
// El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Crea una instancia de Image en la ruta especificada
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Crea una instancia de Graphics e inicialízala con el objeto Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Limpia la superficie de Graphics con Color blanco.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Crea una instancia de Pen con el color Rojo y ancho 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Crea una instancia de HatchBrush y establece sus propiedades
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Crea una instancia de Pen e inicialízala con el objeto HatchBrush y ancho
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Guardar todos los cambios.
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtiene el color de las líneas de trama.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Establece el color de las líneas de trama.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | El color de las líneas de trama. |


**Example: This example shows the creation and usage Pen objects.**
Este ejemplo muestra la creación y uso de objetos Pen. El ejemplo crea una nueva Image y dibuja Rectángulos en la superficie de Image.
``` java

// Crea una instancia de BmpOptions y establece sus diversas propiedades
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Crea una instancia de FileCreateSource y asígnala como Source para la instancia de BmpOptions
// El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Crea una instancia de Image en la ruta especificada
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Crea una instancia de Graphics e inicialízala con el objeto Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Limpia la superficie de Graphics con Color blanco.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Crea una instancia de Pen con el color Rojo y ancho 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Crea una instancia de HatchBrush y establece sus propiedades
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Crea una instancia de Pen e inicialízala con el objeto HatchBrush y ancho
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Guardar todos los cambios.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene el color de los espacios entre las líneas de trama.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Establece el color de los espacios entre las líneas de trama.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | El color de los espacios entre las líneas de trama. |


**Example: This example shows the creation and usage Pen objects.**
Este ejemplo muestra la creación y uso de objetos Pen. El ejemplo crea una nueva Image y dibuja Rectángulos en la superficie de Image.
``` java

// Crea una instancia de BmpOptions y establece sus diversas propiedades
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Crea una instancia de FileCreateSource y asígnala como Source para la instancia de BmpOptions
// El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Crea una instancia de Image en la ruta especificada
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Crea una instancia de Graphics e inicialízala con el objeto Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Limpia la superficie de Graphics con Color blanco.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Crea una instancia de Pen con el color Rojo y ancho 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Crea una instancia de HatchBrush y establece sus propiedades
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Crea una instancia de Pen e inicialízala con el objeto HatchBrush y ancho
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Dibuja Rectángulos especificando el objeto Pen
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Guardar todos los cambios.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtiene el estilo de trama de este pincel.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Establece el estilo de trama de este pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

