---
title: GraphicsPath
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delGraphicsPathaspose.imaging/graphicspath clase.
type: docs
weight: 10
url: /es/net/aspose.imaging/graphicspath/graphicspath/
---
## GraphicsPath() {#constructor}

Inicializa una nueva instancia del[`GraphicsPath`](../../graphicspath) clase.

```csharp
public GraphicsPath()
```

### Ejemplos

Estos ejemplos hacen uso de las clases GraphicsPath y Graphics para crear y manipular figuras en una superficie de imagen. El ejemplo crea una nueva imagen (de tipo Tiff), limpia la superficie y dibuja rutas con la ayuda de la clase GraphicsPath. Al final, se llama al método DrawPath expuesto por la clase Graphics para representar las rutas en la superficie.

```csharp
[C#]

//Crear una instancia de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Crear una instancia de TiffOptions y establecer sus diversas propiedades
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Establecer el origen de la instancia de ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crear una instancia de Imagen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Crear e inicializar una instancia de la clase Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Borrar superficie gráfica
        graphics.Clear(Color.Wheat);

        //Crear una instancia de la clase GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Crear una instancia de la clase Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Agregar formas al objeto Figura
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Agregar objeto Figura a GraphicsPath
        graphicspath.AddFigure(figure);

        //Dibujar ruta con objeto Pluma de color Negro
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // guarda todos los cambios.
        image.Save();
    }
}
```

### Ver también

* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[]) {#constructor_1}

Inicializa una nueva instancia del[`GraphicsPath`](../../graphicspath) clase.

```csharp
public GraphicsPath(Figure[] figures)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| figures | Figure[] | Las cifras desde las que inicializar. |

### Ver también

* class [Figure](../../figure)
* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[], FillMode) {#constructor_2}

Inicializa una nueva instancia del[`GraphicsPath`](../../graphicspath) clase.

```csharp
public GraphicsPath(Figure[] figures, FillMode fillMode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| figures | Figure[] | Las cifras desde las que inicializar. |
| fillMode | FillMode | El modo de relleno. |

### Ver también

* class [Figure](../../figure)
* enum [FillMode](../../fillmode)
* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

---

## GraphicsPath(FillMode) {#constructor_3}

Inicializa una nueva instancia del[`GraphicsPath`](../../graphicspath) clase.

```csharp
public GraphicsPath(FillMode fillMode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fillMode | FillMode | El modo de relleno. |

### Ver también

* enum [FillMode](../../fillmode)
* class [GraphicsPath](../../graphicspath)
* espacio de nombres [Aspose.Imaging](../../graphicspath)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
