---
title: ExactReallocateOnly
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta el rendimiento debería ser mayor.
type: docs
weight: 50
url: /es/net/aspose.imaging/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Obtiene o establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### El valor de la propiedad

`verdadero` si la reasignación es exacta; de lo contrario,`falso` .

### Observaciones

La reasignación exacta llevará a cabo la reasignación de memoria adicional solo hasta el límite superior especificado. Al superar el límite superior de la memoria en memoria durante la reasignación, los datos almacenados en caché se copiarán en el disco si es posible. Al superar el límite superior de la memoria de disco durante la reasignación, se lanza la excepción adecuada. El rendimiento debería ser mayor si esta opción está desactivada, ya que no se realizará ninguna copia adicional si es posible, sin embargo, esto también puede llevar a superar los límites superiores especificados para la memoria o el disco.

### Ejemplos

Este ejemplo demuestra el uso de Aspose.Imaging.Cache

```csharp
[C#]

// De forma predeterminada, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puede especificar otra carpeta de caché que no sea la predeterminada, como la siguiente:
// Cache.CacheFolder = @"D:\\MyTemp";

// El modo automático es flexible y eficiente
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

// El valor predeterminado es 0, lo que significa que no hay límite superior
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar en gran medida el rendimiento
Aspose.Imaging.Cache.ExactReallocateOnly = false;

// En cualquier momento puede verificar cuántos bytes están asignados actualmente para la memoria o el disco 
// caché examinando las siguientes propiedades
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

// Haz un poco de procesamiento de imágenes como se muestra a continuación
Aspose.Imaging.ImageOptions.GifOptions options = new Aspose.Imaging.ImageOptions.GifOptions();
options.Palette = new ColorPalette(new Aspose.Imaging.Color[] { Aspose.Imaging.Color.Red, Aspose.Imaging.Color.Blue, Aspose.Imaging.Color.Black, Aspose.Imaging.Color.White });
options.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(options, 100, 100))
{
    Aspose.Imaging.Color[] pixels = new Aspose.Imaging.Color[10000];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Aspose.Imaging.Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // después de ejecutar el código anterior, se asignarán 40000 bytes en memoria.
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

// Las propiedades de asignación se pueden usar para verificar si todos los objetos Aspose.Imaging se eliminaron correctamente.
// En caso de que haya olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.            
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### Ver también

* class [Cache](../../cache)
* espacio de nombres [Aspose.Imaging](../../cache)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
