---
title: DrawCurve
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Dibuja una spline cardinal a través de una matriz específica dePointFaspose.imaging/pointf estructuras Este método utiliza una tensión predeterminada de 0.5.
type: docs
weight: 200
url: /es/net/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf) estructuras Este método utiliza una tensión predeterminada de 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf) estructuras que definen la spline. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf) estructuras usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf) estructuras que representan los puntos que definen la curva. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf) estructuras El dibujo comienza desplazado desde el principio de la matriz. Este método utiliza una tensión predeterminada de 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf) estructuras que definen la spline. |
| offset | Int32 | Desplazamiento desde el primer elemento en la matriz de la*points* parámetro al punto inicial de la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial para incluir en la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf)estructuras usando una tensión específica. El dibujo comienza desplazado desde el principio de la matriz.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf) estructuras que definen la spline. |
| offset | Int32 | Desplazamiento desde el primer elemento en la matriz de la*points* parámetro al punto inicial de la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial para incluir en la curva. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Dibuja una spline cardinal a través de una matriz específica de[`Point`](../../point) estructuras.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Gama de[`Point`](../../point) estructuras que definen la spline. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

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
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Dibuja una spline cardinal a través de una matriz específica de[`Point`](../../point) estructuras usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Gama de[`Point`](../../point) estructuras que definen la spline. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Dibuja una spline cardinal a través de una matriz específica de[`Point`](../../point) estructuras usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Gama de[`Point`](../../point) estructuras que definen la spline. |
| offset | Int32 | Desplazamiento desde el primer elemento en la matriz de la*points* parámetro al punto inicial de la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial para incluir en la curva. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
