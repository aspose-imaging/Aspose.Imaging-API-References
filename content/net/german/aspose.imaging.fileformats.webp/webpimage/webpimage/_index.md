---
title: WebPImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonWebPImageaspose.imaging.fileformats.webp/webpimage class aus stream.
type: docs
weight: 10
url: /de/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) class aus stream.

```csharp
public WebPImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Das Stream-WebP-Bild. |

### Beispiele

Dieses Beispiel zeigt, wie ein WebP-Bild aus einem Dateistream geladen und in PNG gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein WebP-Bild aus einem Dateistream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // Als PNG speichern
    // Beachten Sie, dass nur der aktive Frame in PNG gespeichert wird, da PNG kein mehrseitiges Format ist.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) Klasse aus stream.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Das Stream-WebP-Bild. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) Klasse aus Datei.

```csharp
public WebPImage(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zur Datei WebP Image |

### Beispiele

Dieses Beispiel zeigt, wie ein WebP-Bild aus einer Datei geladen und im PNG-Format gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein WebP-Bild aus einer Datei.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Als PNG speichern
    // Beachten Sie, dass nur der aktive Frame in PNG gespeichert wird, da PNG kein mehrseitiges Format ist.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) Klasse aus Datei.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zur Datei WebP Image |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) Klasse von rasterImage.

```csharp
public WebPImage(RasterImage rasterImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Rasterbild. |

### Beispiele

Dieses Beispiel zeigt, wie Sie ein WebP-Bild aus einem anderen Rasterbild erstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein PNG-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Das gesamte Bild rot füllen.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Erstellen Sie ein WebP-Bild basierend auf dem PNG-Bild.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Speichern in einer WebP-Datei mit Standardoptionen
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) Klasse von rasterImage.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Rasterbild. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) Klasse mit leerem Bild.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite |
| height | Int32 | Die Bildhöhe. |
| options | WebPOptions | Die Optionen. |

### Beispiele

Dieses Beispiel zeigt, wie Sie ein WebP-Image mit den angegebenen Optionen von Grund auf neu erstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// Erstellen Sie ein WebP-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Das gesamte Bild rot füllen.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // In einer WebP-Datei speichern
    webPImage.Save(dir + "output.webp");
}
```

Dieses Beispiel zeigt, wie Sie mit den angegebenen Optionen ein animiertes WebP-Bild mit mehreren Frames erstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Der Standardframe plus 36 + 36 zusätzliche Frames.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Erstellen Sie ein WebP-Bild mit 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Der erste Kreis ist rot
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Der zweite Kreis ist schwarz
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Erhöhen Sie allmählich den Winkel der roten Bogenform.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Erhöhen Sie allmählich den Winkel des schwarzen Bogens und löschen Sie den roten Bogen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // In einer WebP-Datei speichern
    webPImage.Save(dir + "output.webp");
}
```

### Siehe auch

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Initialisiert eine neue Instanz von[`WebPImage`](../../webpimage) Klasse mit leerem Bild.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite |
| height | Int32 | Die Bildhöhe. |
| options | WebPOptions | Die Optionen. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
