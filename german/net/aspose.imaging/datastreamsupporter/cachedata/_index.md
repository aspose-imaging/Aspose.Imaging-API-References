---
title: CacheData
second_title: Aspose.Imaging für .NET-API-Referenz
description: Zwischenspeichert die Daten und stellt sicher dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wirdDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 30
url: /de/net/aspose.imaging/datastreamsupporter/cachedata/
---
## DataStreamSupporter.CacheData method

Zwischenspeichert die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wird[`DataStreamContainer`](../datastreamcontainer) .

```csharp
public abstract void CacheData()
```

### Beispiele

Das folgende Beispiel zeigt, wie sich das Zwischenspeichern von Bildern auf die Leistung auswirkt. Im Allgemeinen erfolgt das Lesen von zwischengespeicherten Daten schneller als das Lesen von nicht zwischengespeicherten Daten.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein Bild aus einer PNG-Datei.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Alle Pixeldaten zwischenspeichern, sodass kein zusätzliches Laden von Daten aus dem zugrunde liegenden Datenstrom durchgeführt wird
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Das Lesen aller Pixel ist ziemlich schnell.
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Laden Sie ein Bild aus einer PNG-Datei
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Das Lesen aller Pixel ist nicht so schnell wie beim Caching
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Die Ausgabe könnte so aussehen:
// Das Lesen aller gecachten Pixel hat 1500 ms gedauert.
// Das Lesen aller Pixel ohne vorheriges Caching dauerte 150000 ms.
```

### Siehe auch

* class [DataStreamSupporter](../../datastreamsupporter)
* namensraum [Aspose.Imaging](../../datastreamsupporter)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
