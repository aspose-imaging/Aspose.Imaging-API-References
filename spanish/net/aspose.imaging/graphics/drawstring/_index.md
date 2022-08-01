---
title: DrawString
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Dibuja la cadena de texto especificada en la ubicación especificada con elBrushaspose.imaging/brush yFontaspose.imaging/font objetos.
type: docs
weight: 320
url: /es/net/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush) y[`Font`](../../font) objetos.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush) que determina el color y la textura del texto dibujado. |
| x | Single | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | Single | La coordenada y de la esquina superior izquierda del texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush) y[`Font`](../../font) objetos.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush) que determina el color y la textura del texto dibujado. |
| point | PointF | [`PointF`](../../pointf) estructura que especifica la esquina superior izquierda del texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush) y[`Font`](../../font) objetos usando los atributos de formato del especificado[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush) que determina el color y la textura del texto dibujado. |
| x | Single | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | Single | La coordenada y de la esquina superior izquierda del texto dibujado. |
| format | StringFormat | [`StringFormat`](../../stringformat) que especifica los atributos de formato, como el espaciado entre líneas y la alineación, que se aplican al texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush) y[`Font`](../../font) objetos usando los atributos de formato del especificado[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush) que determina el color y la textura del texto dibujado. |
| point | PointF | [`PointF`](../../pointf) estructura que especifica la esquina superior izquierda del texto dibujado. |
| format | StringFormat | [`StringFormat`](../../stringformat) que especifica los atributos de formato, como el espaciado entre líneas y la alineación, que se aplican al texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Dibuja la cadena de texto especificada en el rectángulo especificado con el[`Brush`](../../brush) y[`Font`](../../font) objetos.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush) que determina el color y la textura del texto dibujado. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) estructura que especifica la ubicación del texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Dibuja la cadena de texto especificada en el rectángulo especificado con el[`Brush`](../../brush) y[`Font`](../../font) objetos usando los atributos de formato del especificado[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush) que determina el color y la textura del texto dibujado. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) estructura que especifica la ubicación del texto dibujado. |
| format | StringFormat | [`StringFormat`](../../stringformat) que especifica los atributos de formato, como el espaciado entre líneas y la alineación, que se aplican al texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. -o- *brush* es nulo. |

### Ver también

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* espacio de nombres [Aspose.Imaging](../../graphics)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
