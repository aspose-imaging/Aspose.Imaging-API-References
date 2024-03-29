---
title: BufferSizeHint
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos.
type: docs
weight: 10
url: /es/net/aspose.imaging/imageoptionsbase/buffersizehint/
---
## ImageOptionsBase.BufferSizeHint property

Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos.

```csharp
public int BufferSizeHint { get; set; }
```

### El valor de la propiedad

La sugerencia del tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

### Ejemplos

El siguiente ejemplo muestra cómo establecer un límite de memoria al crear una nueva imagen JPEG. El límite de memoria es el tamaño máximo permitido (en megabytes) para todos los búferes internos.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// Establecer un límite de memoria de 50 megabytes para la imagen de destino creada
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.JpegOptions
{
    CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive,
    BufferSizeHint = 50,
    Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "createdFile.jpg", false),
};
    
using (var image = Aspose.Imaging.Image.Create(createOptions, 1000, 1000))
{
    image.Save(); // guardar en la misma ubicación
}
```

El siguiente ejemplo muestra cómo establecer un límite de memoria al crear una imagen PNG y dibujar gráficos complejos en ella. El límite de memoria es el tamaño máximo permitido (en megabytes) para todos los búferes internos.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3383\\";

const int ImageSize = 2000;
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_simple.png", false);
createOptions.BufferSizeHint = 30; // El límite de memoria es de 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    // Puede usar cualquier operación gráfica aquí, todas se realizarán dentro del límite de memoria establecido
    // Por ejemplo:
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);
    graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 3f), 0, 0, image.Width, image.Height);

    image.Save();
}

// También se admite una gran cantidad de operaciones gráficas:
const int OperationAreaSize = 10;
createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_complex.png", false);
createOptions.BufferSizeHint = 30; // El límite de memoria es de 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.BeginUpdate();
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);

    int x, y;
    int numberOfOperations = 0;
    for (int column = 0; column * OperationAreaSize < ImageSize; column++)
    {
        for (int row = 0; row * OperationAreaSize < ImageSize; row++)
        {
            x = column * OperationAreaSize;
            y = row * OperationAreaSize;

            bool reversed = (column + row) % 2 != 0;
            if (reversed)
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x + OperationAreaSize - 2,
                    y,
                    x,
                    y + OperationAreaSize);
            }
            else
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x,
                    y,
                    x + OperationAreaSize - 2,
                    y + OperationAreaSize);
            }

            numberOfOperations++;
        }
    }

    // Aquí se aplicarán alrededor de 40k operaciones, mientras no ocupen demasiada memoria 
    // ya que ya están descargados en el archivo externo, y se cargarán desde allí uno a la vez
    graphics.EndUpdate();

    image.Save();
}
```

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase)
* espacio de nombres [Aspose.Imaging](../../imageoptionsbase)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
