---
title: PremultiplyComponents
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece un valor que indica si los componentes se deben premultiplicar.
type: docs
weight: 110
url: /es/net/aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/
---
## TiffImage.PremultiplyComponents property

Obtiene o establece un valor que indica si los componentes se deben premultiplicar.

```csharp
public override bool PremultiplyComponents { get; set; }
```

### El valor de la propiedad

`verdadero` si los componentes deben premultiplicarse; de lo contrario,`falso` .

### Ejemplos

El siguiente ejemplo crea una nueva imagen TIFF, guarda los píxeles semitransparentes especificados, luego carga esos píxeles y obtiene los colores finales en la forma premultiplicada.

```csharp
[C#]

int imageWidth = 3;
int imageHeight = 2;

Aspose.Imaging.Color[] colors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 0, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 255, 255, 0),
    Aspose.Imaging.Color.FromArgb(127, 255, 0, 255),
    Aspose.Imaging.Color.FromArgb(127, 0, 255, 255),
};

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Create(createOptions, imageWidth, imageHeight))
{
    // Guardar píxeles para toda la imagen.
    image.SavePixels(image.Bounds, colors);

    // Los píxeles se almacenan en la imagen original en forma no premultiplicada.
    // Es necesario especificar la opción correspondiente explícitamente para obtener componentes de color premultiplicados.
    // Los componentes de color premultiplicados se calculan mediante las fórmulas:
    // rojo = rojo_original * alfa / 255;
    // verde = original_verde * alfa / 255;
    // azul = azul_original * alfa / 255;
    image.PremultiplyComponents = true;
    Aspose.Imaging.Color[] premultipliedColors = image.LoadPixels(image.Bounds);

    for (int i = 0; i < colors.Length; i++)
    {
        System.Console.WriteLine("Original color: {0}", colors[i].ToString());
        System.Console.WriteLine("Premultiplied color: {0}", premultipliedColors[i].ToString());
    }
}

//La salida se verá así:
//Color original: Color [A=127, R=255, G=0, B=0]
//Color premultiplicado: Color [A=127, R=127, G=0, B=0]
//Color original: Color [A=127, R=0, G=255, B=0]
//Color premultiplicado: Color [A=127, R=0, G=127, B=0]
//Color original: Color [A=127, R=0, G=0, B=255]
//Color premultiplicado: Color [A=127, R=0, G=0, B=127]
//Color original: Color [A=127, R=255, G=255, B=0]
//Color premultiplicado: Color [A=127, R=127, G=127, B=0]
//Color original: Color [A=127, R=255, G=0, B=255]
//Color premultiplicado: Color [A=127, R=127, G=0, B=127]
//Color original: Color [A=127, R=0, G=255, B=255]
//Color premultiplicado: Color [A=127, R=0, G=127, B=127]
```

### Ver también

* class [TiffImage](../../tiffimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
