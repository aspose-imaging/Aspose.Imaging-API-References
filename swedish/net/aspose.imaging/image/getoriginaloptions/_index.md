---
title: GetOriginalOptions
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av Saveaspose.imaging/datastreamsupporter/save metod kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel använd den här metoden för att få motsvarande sparalternativ och skicka dem tillSaveaspose.imaging/image/save metod som den andra parametern.
type: docs
weight: 190
url: /sv/net/aspose.imaging/image/getoriginaloptions/
---
## Image.GetOriginalOptions method

Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../../datastreamsupporter/save) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](../save) metod som den andra parametern.

```csharp
public virtual ImageOptionsBase GetOriginalOptions()
```

### Returvärde

Alternativen baserade på de ursprungliga filinställningarna.

### Se även

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->