---
title: FillPie
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Rellena el interior de una sección circular definida por una elipse especificada por unRectangleFaspose.imaging/rectanglef estructura y dos líneas radiales.
type: docs
weight: 370
url: /es/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Rellena el interior de una sección circular definida por una elipse especificada por un[`RectangleF`](../../rectanglef) estructura y dos líneas radiales.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) que determina las características del relleno. |
| rect | Rectangle | [`Rectangle`](../../rectangle)estructura que representa el rectángulo delimitador que define la elipse de la que procede la sección circular. |
| startAngle | Single | Ángulo en grados medido en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la sección circular. |
| sweepAngle | Single | Ángulo en grados medido en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la sección circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. |

### Ejemplos

El siguiente ejemplo muestra cómo componer una imagen GIF animada a partir de bloques GIF individuales.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen GIF de 100 x 100 px.
// El primer bloque es completamente negro por defecto.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // El primer circulo es rojo
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // El segundo circulo es negro
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Aumenta gradualmente el ángulo de la forma del arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Aumenta gradualmente el ángulo del arco negro y borra el arco rojo.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Ver también

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Rellena el interior de una sección circular definida por una elipse especificada por un[`RectangleF`](../../rectanglef) estructura y dos líneas radiales.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) que determina las características del relleno. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)estructura que representa el rectángulo delimitador que define la elipse de la que procede la sección circular. |
| startAngle | Single | Ángulo en grados medido en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la sección circular. |
| sweepAngle | Single | Ángulo en grados medido en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la sección circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. |

### Ver también

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Rellena el interior de una sección circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) que determina las características del relleno. |
| x | Single | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la sección circular. |
| y | Single | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la sección circular. |
| width | Single | Ancho del rectángulo delimitador que define la elipse de la que procede la sección circular. |
| height | Single | Altura del rectángulo delimitador que define la elipse de la que procede la sección circular. |
| startAngle | Single | Ángulo en grados medido en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la sección circular. |
| sweepAngle | Single | Ángulo en grados medido en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la sección circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. |

### Ver también

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Rellena el interior de una sección circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) que determina las características del relleno. |
| x | Int32 | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la sección circular. |
| y | Int32 | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la sección circular. |
| width | Int32 | Ancho del rectángulo delimitador que define la elipse de la que procede la sección circular. |
| height | Int32 | Altura del rectángulo delimitador que define la elipse de la que procede la sección circular. |
| startAngle | Int32 | Ángulo en grados medido en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la sección circular. |
| sweepAngle | Int32 | Ángulo en grados medido en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la sección circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. |

### Ver también

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
