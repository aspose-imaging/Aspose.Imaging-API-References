---
title: DrawPie
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Dibuja una forma circular definida por una elipse especificada por unRectangleFaspose.imaging/rectanglef estructura y dos líneas radiales.
type: docs
weight: 280
url: /es/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Dibuja una forma circular definida por una elipse especificada por un[`RectangleF`](../../rectanglef) estructura y dos líneas radiales.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y el estilo de la forma circular. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) estructura que representa el rectángulo delimitador que define la elipse de la que procede la forma circular. |
| startAngle | Single | Ángulo medido en grados en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la forma circular. |
| sweepAngle | Single | Ángulo medido en grados en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la forma circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Dibuja una forma circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y el estilo de la forma circular. |
| x | Single | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la forma circular. |
| y | Single | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la forma circular. |
| width | Single | Ancho del rectángulo delimitador que define la elipse de la que procede la forma circular. |
| height | Single | Altura del rectángulo delimitador que define la elipse de la que procede la forma circular. |
| startAngle | Single | Ángulo medido en grados en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la forma circular. |
| sweepAngle | Single | Ángulo medido en grados en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la forma circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Dibuja una forma circular definida por una elipse especificada por un[`Rectangle`](../../rectangle) estructura y dos líneas radiales.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y el estilo de la forma circular. |
| rect | Rectangle | [`Rectangle`](../../rectangle) estructura que representa el rectángulo delimitador que define la elipse de la que procede la forma circular. |
| startAngle | Single | Ángulo medido en grados en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la forma circular. |
| sweepAngle | Single | Ángulo medido en grados en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la forma circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ejemplos

Este ejemplo usa la clase Graphics para crear formas primitivas en la superficie de la imagen. Para demostrar la operación, el ejemplo crea una nueva imagen en formato PNG y dibuja formas primitivas en la superficie de la imagen utilizando los métodos de dibujo expuestos por la clase Graphics.

```csharp
[C#]

//Crea una instancia de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Cree una instancia de PngOptions y configure sus diversas propiedades
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Establecer la fuente para PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crear una instancia de Imagen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Crear e inicializar una instancia de la clase Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Borrar superficie gráfica
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // Dibuje un Arco especificando el objeto Pluma que tiene color Negro, 
        //un rectángulo que rodea el arco, el ángulo de inicio y el ángulo de barrido
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Dibuje un Bézier especificando el objeto Pen que tiene color azul y puntos de coordenadas.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Dibuje una curva especificando el objeto Pen que tiene color verde y una matriz de puntos
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Dibuja una Elipse usando el objeto Pluma y un Rectángulo circundante
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Dibuja una línea 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Dibujar un segmento circular
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Dibuje un polígono especificando el objeto Pen que tiene color rojo y una matriz de puntos
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Dibujar un Rectángulo
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Crear un objeto SolidBrush y establecer sus diversas propiedades
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Dibuje una cadena usando el objeto SolidBrush y la fuente, en un punto específico
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // guarda todos los cambios.
        image.Save();
    }
}
```

### Ver también

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Dibuja una forma circular definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y el estilo de la forma circular. |
| x | Int32 | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la forma circular. |
| y | Int32 | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la que proviene la forma circular. |
| width | Int32 | Ancho del rectángulo delimitador que define la elipse de la que procede la forma circular. |
| height | Int32 | Altura del rectángulo delimitador que define la elipse de la que procede la forma circular. |
| startAngle | Int32 | Ángulo medido en grados en el sentido de las agujas del reloj desde el eje x hasta el primer lado de la forma circular. |
| sweepAngle | Int32 | Ángulo medido en grados en el sentido de las agujas del reloj desde el*startAngle* parámetro al segundo lado de la forma circular. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
