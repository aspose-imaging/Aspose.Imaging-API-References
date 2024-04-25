---
title: Save
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Guarda los datos de la imagen en el flujo subyacente.
type: docs
weight: 240
url: /es/aspose.imaging/image/save/
---
## Save() {#save}

Guarda los datos de la imagen en el flujo subyacente.

```csharp
public void Save()
```

### Ejemplos

El siguiente ejemplo muestra cómo guardar una imagen BMP completa o parte de ella en un archivo o secuencia.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir a una imagen en blanco y negro
    bmpImage.BinarizeOtsu();

    // Guardar en la misma ubicación con las opciones predeterminadas.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una paleta contiene solo dos colores: Blanco y Negro en este caso.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Para todas las imágenes monocromáticas (incluidas las de blanco y negro), basta con asignar 1 bit por píxel.
    saveOptions.BitsPerPixel = 1;

    // Guardar en otra ubicación con las opciones especificadas.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Guarda solo la parte central de la imagen.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Guardar la imagen completa en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Guarda la parte central de la imagen en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La salida puede verse así:
//El tamaño de la imagen completa en bytes: 24062
//El tamaño de la parte central de la imagen en bytes: 6046
```

### Ver también

* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Guarda la imagen en la ubicación de archivo especificada.

```csharp
public override void Save(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo para guardar la imagen. |

### Ver también

* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| options | ImageOptionsBase | Las opciones. |

### Ejemplos

El siguiente ejemplo carga una imagen BMP desde un archivo y luego guarda la imagen en un archivo PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Guarda la imagen completa en un archivo PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

Este ejemplo muestra los sencillos pasos para guardar una imagen. Para demostrar esta operación, cargamos un archivo existente desde alguna ubicación del disco, realizamos la operación de rotación en la imagen y guardamos la imagen en formato PSD utilizando la ruta del archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

//Cree una instancia de clase de imagen e inicialícela con un archivo existente a través de la ruta del archivo
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Rotar la imagen 180 grados sobre el eje X
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //Guarde la imagen como PSD en la ruta del archivo con la configuración predeterminada de PsdOptions
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

El siguiente ejemplo muestra cómo guardar una imagen BMP completa o parte de ella en un archivo o secuencia.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir a una imagen en blanco y negro
    bmpImage.BinarizeOtsu();

    // Guardar en la misma ubicación con las opciones predeterminadas.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una paleta contiene solo dos colores: Blanco y Negro en este caso.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Para todas las imágenes monocromáticas (incluidas las de blanco y negro), basta con asignar 1 bit por píxel.
    saveOptions.BitsPerPixel = 1;

    // Guardar en otra ubicación con las opciones especificadas.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Guarda solo la parte central de la imagen.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Guardar la imagen completa en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Guarda la parte central de la imagen en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La salida puede verse así:
//El tamaño de la imagen completa en bytes: 24062
//El tamaño de la parte central de la imagen en bytes: 6046
```

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| options | ImageOptionsBase | Las opciones. |
| boundsRectangle | Rectangle | El rectángulo de los límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites del origen. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | opciones |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Error al guardar la imagen. |

### Ejemplos

El siguiente ejemplo carga una imagen BMP desde un archivo y luego guarda una parte rectangular de la imagen en un archivo PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Guarde la mitad superior de la imagen en un archivo PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

El siguiente ejemplo muestra cómo guardar una imagen BMP completa o parte de ella en un archivo o secuencia.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir a una imagen en blanco y negro
    bmpImage.BinarizeOtsu();

    // Guardar en la misma ubicación con las opciones predeterminadas.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una paleta contiene solo dos colores: Blanco y Negro en este caso.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Para todas las imágenes monocromáticas (incluidas las de blanco y negro), basta con asignar 1 bit por píxel.
    saveOptions.BitsPerPixel = 1;

    // Guardar en otra ubicación con las opciones especificadas.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Guarda solo la parte central de la imagen.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Guardar la imagen completa en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Guarda la parte central de la imagen en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La salida puede verse así:
//El tamaño de la imagen completa en bytes: 24062
//El tamaño de la parte central de la imagen en bytes: 6046
```

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia en la que se guardarán los datos de la imagen. |
| optionsBase | ImageOptionsBase | Las opciones de guardado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | opcionesBase |
| ArgumentException | No se puede guardar en el formato especificado porque no es compatible en este momento.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Error al exportar la imagen. |

### Ejemplos

El siguiente ejemplo carga una imagen desde un archivo, luego guarda la imagen en una secuencia de archivos PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Guarda la imagen completa en un flujo de archivos.
        image.Save(outputStream, saveOptions);
    }
}
```

Este ejemplo muestra el proceso de guardar una imagen en MemoryStream. Para demostrar esta operación, el ejemplo carga un archivo existente desde alguna ubicación del disco, realiza la operación Rotar en la imagen y guarda la imagen en formato PSD.

```csharp
[C#]

//Crear una instancia de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Cree una instancia de clase de imagen e inicialícela con un archivo existente a través de la ruta del archivo
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //Rotar la imagen 180 grados sobre el eje X
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //Guardar la imagen como PSD en MemoryStream con la configuración predeterminada de PsdOptions
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

El siguiente ejemplo muestra cómo guardar una imagen BMP completa o parte de ella en un archivo o secuencia.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir a una imagen en blanco y negro
    bmpImage.BinarizeOtsu();

    // Guardar en la misma ubicación con las opciones predeterminadas.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una paleta contiene solo dos colores: Blanco y Negro en este caso.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Para todas las imágenes monocromáticas (incluidas las de blanco y negro), basta con asignar 1 bit por píxel.
    saveOptions.BitsPerPixel = 1;

    // Guardar en otra ubicación con las opciones especificadas.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Guarda solo la parte central de la imagen.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Guardar la imagen completa en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Guarda la parte central de la imagen en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La salida puede verse así:
//El tamaño de la imagen completa en bytes: 24062
//El tamaño de la parte central de la imagen en bytes: 6046
```

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La secuencia en la que se guardarán los datos de la imagen. |
| optionsBase | ImageOptionsBase | Las opciones de guardado. |
| boundsRectangle | Rectangle | El rectángulo de los límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de la fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | opcionesBase |
| ArgumentException | No se puede guardar en el formato especificado porque no es compatible en este momento.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Error al exportar la imagen. |

### Ejemplos

El siguiente ejemplo carga una imagen desde un archivo, luego guarda una parte rectangular de la imagen en una secuencia de archivos PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Guarda la mitad superior de la imagen en un flujo de archivos.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

El siguiente ejemplo muestra cómo guardar una imagen BMP completa o parte de ella en un archivo o secuencia.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Convertir a una imagen en blanco y negro
    bmpImage.BinarizeOtsu();

    // Guardar en la misma ubicación con las opciones predeterminadas.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una paleta contiene solo dos colores: Blanco y Negro en este caso.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Para todas las imágenes monocromáticas (incluidas las de blanco y negro), basta con asignar 1 bit por píxel.
    saveOptions.BitsPerPixel = 1;

    // Guardar en otra ubicación con las opciones especificadas.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Guarda solo la parte central de la imagen.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Guardar la imagen completa en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Guarda la parte central de la imagen en un flujo de memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//La salida puede verse así:
//El tamaño de la imagen completa en bytes: 24062
//El tamaño de la parte central de la imagen en bytes: 6046
```

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* espacio de nombres [Aspose.Imaging](../../image)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
