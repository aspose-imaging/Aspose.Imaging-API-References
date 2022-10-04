---
title: FileCreateSource
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avFileCreateSourceaspose.imaging.sources/filecreatesource class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Initierar en ny instans av[`FileCreateSource`](../../filecreatesource) class.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att skapa. |

### Exempel

Det här exemplet skapar en ny bildfil på någon diskplats som specificeras av Source-egenskapen för BmpOptions-instansen. Om den andra parametern inte skickas till FileCreateSources konstruktor, har filen som ska skapas som standard egenskapen IsTemporal satt till True. Med IsTemporal satt till True, kommer ingen fil att sparas på disken i slutet av körningen.

```csharp
[C#]

//Skapar en instans av BmpOptions och ställer in dess olika egenskaper
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
//Om den andra parametern inte skickas, har filen som standard IsTemporal satt till True
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Skapar en instans av bild 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //gör lite bildbehandling
}
```

### Se även

* class [FileCreateSource](../../filecreatesource)
* namnutrymme [Aspose.Imaging.Sources](../../filecreatesource)
* hopsättning [Aspose.Imaging](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initierar en ny instans av[`FileCreateSource`](../../filecreatesource) class.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att skapa. |
| isTemporal | Boolean | Om inställt på`Sann`den skapade filen kommer att vara tidsmässig. |

### Exempel

Det här exemplet skapar en ny bildfil på någon diskplats som specificeras av Source-egenskapen för BmpOptions-instansen. Flera egenskaper för BmpOptions-instansen ställs in innan den faktiska bilden skapas. Speciellt egenskapen Source, som refererar till den faktiska diskplatsen i det här fallet.

```csharp
[C#]

//Skapa en instans av BmpOptions och ställ in dess olika egenskaper
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Skapa en instans av bild och initiera den med instans av BmpOptions genom att anropa metoden Skapa
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //gör lite bildbehandling

    // spara alla ändringar
    image.Save();
}
```

### Se även

* class [FileCreateSource](../../filecreatesource)
* namnutrymme [Aspose.Imaging.Sources](../../filecreatesource)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->