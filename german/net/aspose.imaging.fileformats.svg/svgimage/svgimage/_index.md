---
title: SvgImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonSvgImageaspose.imaging.fileformats.svg/svgimage Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.fileformats.svg/svgimage/svgimage/
---
## SvgImage(string) {#constructor_3}

Initialisiert eine neue Instanz von[`SvgImage`](../../svgimage) Klasse.

```csharp
public SvgImage(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Pfad ist null. |

### Siehe auch

* class [SvgImage](../../svgimage)
* namensraum [Aspose.Imaging.FileFormats.Svg](../../svgimage)
* Montage [Aspose.Imaging](../../../)

---

## SvgImage(Stream) {#constructor_2}

Initialisiert eine neue Instanz von[`SvgImage`](../../svgimage) Klasse.

```csharp
public SvgImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Strom ist null. |

### Beispiele

Dieses Beispiel zeigt, wie ein SVG-Bild aus einem Dateistream geladen und in PNG gerastert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein SVG-Bild aus einem Dateistream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // Um SVG zu rastern, müssen wir Rasterisierungsoptionen angeben.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### Siehe auch

* class [SvgImage](../../svgimage)
* namensraum [Aspose.Imaging.FileFormats.Svg](../../svgimage)
* Montage [Aspose.Imaging](../../../)

---

## SvgImage(int, int) {#constructor_1}

Initialisiert eine neue Instanz von[`SvgImage`](../../svgimage) Klasse.

```csharp
public SvgImage(int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite. |
| height | Int32 | Die Bildhöhe. |

### Siehe auch

* class [SvgImage](../../svgimage)
* namensraum [Aspose.Imaging.FileFormats.Svg](../../svgimage)
* Montage [Aspose.Imaging](../../../)

---

## SvgImage(SvgOptions, int, int) {#constructor}

Initialisiert eine neue Instanz von[`SvgImage`](../../svgimage) Klasse.

```csharp
public SvgImage(SvgOptions svgOptions, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgOptions | SvgOptions | Die SVG-Optionen. |
| width | Int32 | Bild breite. |
| height | Int32 | Bildhöhe. |

### Siehe auch

* class [SvgOptions](../../../aspose.imaging.imageoptions/svgoptions)
* class [SvgImage](../../svgimage)
* namensraum [Aspose.Imaging.FileFormats.Svg](../../svgimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
