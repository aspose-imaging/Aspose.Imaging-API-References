---
title: SetTransform
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Establece la transformación.
type: docs
weight: 290
url: /es/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform/
---
## MetafileRecorderGraphics2D.SetTransform method

Establece la transformación.

```csharp
public void SetTransform(Matrix transform)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| transform | Matrix | La nueva matriz de transformación. |

### Ejemplos

Este ejemplo muestra cómo cargar una imagen EMF desde un archivo y dibujar una cadena de texto sobre ella.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
        Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D.FromEmfImage(emfImage);

    // Primero, obtenga el tamaño de la imagen
    int width = emfImage.Width;
    int height = emfImage.Height;

    // Segundo, calcule una transformación para poner una cadena de texto a lo largo de la diagonal principal de la imagen -
    // desde la esquina superior izquierda hasta la esquina inferior derecha.
    float emFontSize = 96f;
    float d = (float)System.Math.Sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float)height) / width;                
    double radians = System.Math.Atan(tan);
    double degrees = (180 * radians) / System.Math.PI;

    Aspose.Imaging.Matrix transform = new Aspose.Imaging.Matrix();
    transform.Rotate((float)degrees);
    transform.Scale(scaleFactor, scaleFactor);

    // Luego, establece la transformación.
    graphics.SetTransform(transform);

    // Finalmente, coloque una marca de agua (cadena de texto de color rosa) a lo largo de la diagonal principal.
    graphics.DrawString("WATERMARK", new Aspose.Imaging.Font("Courier New", emFontSize), Aspose.Imaging.Color.LightPink, 0, 0/*, (float)degrees*/);

    // Guarde la imagen con marca de agua en otro archivo EMF.
    using (Aspose.Imaging.FileFormats.Emf.EmfImage scaledEmfImage = graphics.EndRecording())
    {
        scaledEmfImage.Save(dir + "test.scaled.emf");
    }
}
```

### Ver también

* class [Matrix](../../../aspose.imaging/matrix)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->