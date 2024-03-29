---
title: AddPage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Agrega página a la imagen.
type: docs
weight: 120
url: /es/net/aspose.imaging.fileformats.dicom/dicomimage/addpage/
---
## AddPage(RasterImage) {#addpage_1}

Agrega página a la imagen.

```csharp
public void AddPage(RasterImage page)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| page | RasterImage | La página para agregar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *page* es nulo. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [DicomImage](../../dicomimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* asamblea [Aspose.Imaging](../../../)

---

## AddPage() {#addpage}

Agrega una nueva página al final de la lista de páginas.

```csharp
public DicomPage AddPage()
```

### Valor_devuelto

El recién creado[`DicomPage`](../../dicompage).

### Ejemplos

Cree una imagen Dicom de varias páginas.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // Dibujar algo usando gráficos vectoriales
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Guarda los píxeles de la imagen dibujada. Ahora están en la primera página de la imagen de Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // Agrega algunas páginas después, haciéndolas más oscuras
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // Agregue algunas páginas al frente de la página principal, haciéndolas más brillantes
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // Guardar la imagen de varias páginas creada en el archivo de salida
    image.Save("MultiPage.dcm");
}
```

### Ver también

* class [DicomPage](../../dicompage)
* class [DicomImage](../../dicomimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
