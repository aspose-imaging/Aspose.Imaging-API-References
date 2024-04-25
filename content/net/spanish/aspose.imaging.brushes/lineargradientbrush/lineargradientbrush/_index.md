---
title: LinearGradientBrush
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delLinearGradientBrushaspose.imaging.brushes/lineargradientbrush clase con parámetros por defecto. El color inicial es negro el color final es blanco el ángulo es de 45 grados y el rectángulo está ubicado en 00 con tamaño 11.
type: docs
weight: 10
url: /es/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

Inicializa una nueva instancia del[`LinearGradientBrush`](../../lineargradientbrush) clase con parámetros por defecto. El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1).

```csharp
public LinearGradientBrush()
```

### Ver también

* class [LinearGradientBrush](../../lineargradientbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../lineargradientbrush)
* asamblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Inicializa una nueva instancia del[`LinearGradientBrush`](../../lineargradientbrush) clase con los puntos y colores especificados.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| point1 | Point | A[`Point`](../../../aspose.imaging/point) estructura que representa el punto de partida del gradiente lineal. |
| point2 | Point | A[`Point`](../../../aspose.imaging/point) estructura que representa el punto final del gradiente lineal. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color inicial del degradado lineal. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color final del degradado lineal. |

### Ejemplos

El siguiente ejemplo muestra cómo crear una copia en escala de grises de un marco existente y agregarlo a una imagen TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Crear una fuente de archivo permanente, no temporal.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // El degradado lineal desde la esquina superior izquierda hasta la esquina inferior derecha de la imagen.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Rellena el cuadro activo con un pincel de degradado lineal.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Opciones de escala de grises
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Crea una copia en escala de grises del marco activo.
    // Los datos de píxeles se conservan pero se convierten al formato deseado.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Agregue el marco recién creado a la imagen TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Ver también

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../lineargradientbrush)
* asamblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Inicializa una nueva instancia del[`LinearGradientBrush`](../../lineargradientbrush) clase con los puntos y colores especificados.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| point1 | PointF | A[`PointF`](../../../aspose.imaging/pointf) estructura que representa el punto de partida del gradiente lineal. |
| point2 | PointF | A[`PointF`](../../../aspose.imaging/pointf) estructura que representa el punto final del gradiente lineal. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color inicial del degradado lineal. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color final del degradado lineal. |

### Ver también

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../lineargradientbrush)
* asamblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Inicializa una nueva instancia del[`LinearGradientBrush`](../../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef) estructura que especifica los límites del gradiente lineal. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color inicial del degradado. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color final del degradado. |
| angle | Single | El ángulo, medido en grados en el sentido de las agujas del reloj desde el eje x, de la línea de orientación del degradado. |

### Ver también

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../lineargradientbrush)
* asamblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Inicializa una nueva instancia del[`LinearGradientBrush`](../../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef) estructura que especifica los límites del gradiente lineal. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color inicial del degradado. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color final del degradado. |
| angle | Single | El ángulo, medido en grados en el sentido de las agujas del reloj desde el eje x, de la línea de orientación del degradado. |

### Ver también

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../lineargradientbrush)
* asamblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Inicializa una nueva instancia del[`LinearGradientBrush`](../../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef) estructura que especifica los límites del gradiente lineal. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color inicial del degradado. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color final del degradado. |
| angle | Single | El ángulo, medido en grados en el sentido de las agujas del reloj desde el eje x, de la línea de orientación del degradado. |
| isAngleScalable | Boolean | si se establece en`verdadero` el ángulo se cambia durante las transformaciones con esto[`LinearGradientBrush`](../../lineargradientbrush). |

### Ver también

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../lineargradientbrush)
* asamblea [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Inicializa una nueva instancia del[`LinearGradientBrush`](../../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef) estructura que especifica los límites del gradiente lineal. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color inicial del degradado. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) estructura que representa el color final del degradado. |
| angle | Single | El ángulo, medido en grados en el sentido de las agujas del reloj desde el eje x, de la línea de orientación del degradado. |
| isAngleScalable | Boolean | si se establece en`verdadero` el ángulo se cambia durante las transformaciones con esto[`LinearGradientBrush`](../../lineargradientbrush). |

### Ver también

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../lineargradientbrush)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
