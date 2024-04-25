---
title: Pen
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delPenaspose.imaging/pen clase con el color especificado.
type: docs
weight: 10
url: /es/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

Inicializa una nueva instancia del[`Pen`](../../pen) clase con el color especificado.

```csharp
public Pen(Color color)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| color | Color | A[`Color`](../color) estructura que indica el color de este[`Pen`](../../pen). |

### Ver también

* struct [Color](../../color)
* class [Pen](../../pen)
* espacio de nombres [Aspose.Imaging](../../pen)
* asamblea [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

Inicializa una nueva instancia del[`Pen`](../../pen) clase con el especificado[`Color`](../color) y[`Width`](../width) propiedades.

```csharp
public Pen(Color color, float width)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| color | Color | A[`Color`](../color) estructura que indica el color de este[`Pen`](../../pen). |
| width | Single | Un valor que indica el ancho de este[`Pen`](../../pen). |

### Ejemplos

Este ejemplo muestra la creación y el uso de objetos Pen. El ejemplo crea una nueva imagen y dibuja rectángulos en la superficie de la imagen.

```csharp
[C#]

//Cree una instancia de BmpOptions y configure sus diversas propiedades
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Cree una instancia de FileCreateSource y asígnela como Fuente para la instancia de BmpOptions
//El segundo parámetro booleano determina si el archivo a crear es temporal o no
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Crear una instancia de Imagen en la ruta especificada
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Crea una instancia de Graphics e inicialízala con el objeto Image
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // Limpiar la superficie de gráficos con color blanco
    graphics.Clear(Aspose.Imaging.Color.White);

    //Crear una instancia de Pen con color Rojo y ancho 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Crear una instancia de HatchBrush y establecer sus propiedades
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Crear una instancia de Pen
    //inicializarlo con objeto HatchBrush y ancho
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // guarda todos los cambios.
    image.Save();
}
```

### Ver también

* struct [Color](../../color)
* class [Pen](../../pen)
* espacio de nombres [Aspose.Imaging](../../pen)
* asamblea [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

Inicializa una nueva instancia del[`Pen`](../../pen) clase con el especificado[`Brush`](../brush) .

```csharp
public Pen(Brush brush)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| brush | Brush | A[`Brush`](../brush) que determina las propiedades de relleno de este[`Pen`](../../pen). |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. |

### Ver también

* class [Brush](../../brush)
* class [Pen](../../pen)
* espacio de nombres [Aspose.Imaging](../../pen)
* asamblea [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

Inicializa una nueva instancia del[`Pen`](../../pen) clase con el especificado[`Brush`](../brush) y[`Width`](../width) .

```csharp
public Pen(Brush brush, float width)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| brush | Brush | A[`Brush`](../brush) que determina las características de este[`Pen`](../../pen). |
| width | Single | El ancho de la nueva[`Pen`](../../pen). |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. |

### Ver también

* class [Brush](../../brush)
* class [Pen](../../pen)
* espacio de nombres [Aspose.Imaging](../../pen)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
