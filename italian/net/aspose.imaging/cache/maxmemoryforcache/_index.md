---
title: MaxMemoryForCache
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte.
type: docs
weight: 70
url: /it/net/aspose.imaging/cache/maxmemoryforcache/
---
## Cache.MaxMemoryForCache property

Ottiene o imposta la memoria massima disponibile per la cache in memoria. Il valore specificato è il conteggio dei megabyte.

```csharp
public static int MaxMemoryForCache { get; set; }
```

### Valore della proprietà

La memoria massima per la cache.

### Osservazioni

Il valore 0 consumerà tutta la memoria disponibile e non fungerà da limite superiore.

### Esempi

Questo esempio illustra l'uso di Aspose.Imaging.Cache

```csharp
[C#]

// Per impostazione predefinita, la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// Puoi anche specificare un'altra cartella cache rispetto a quella predefinita come la seguente:
// Cache.CacheFolder = @"D:\\MyTemp";

// La modalità automatica è flessibile ed efficiente
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

// Il valore predefinito è 0, il che significa che non esiste un limite superiore
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Non è consigliabile modificare la seguente proprietà in quanto potrebbe influire notevolmente sulle prestazioni
Aspose.Imaging.Cache.ExactReallocateOnly = false;

// In qualsiasi momento puoi controllare quanti byte sono attualmente allocati per la memoria o il disco 
// memorizza nella cache esaminando le seguenti proprietà
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

// Esegui un po' di elaborazione delle immagini come di seguito
Aspose.Imaging.ImageOptions.GifOptions options = new Aspose.Imaging.ImageOptions.GifOptions();
options.Palette = new ColorPalette(new Aspose.Imaging.Color[] { Aspose.Imaging.Color.Red, Aspose.Imaging.Color.Blue, Aspose.Imaging.Color.Black, Aspose.Imaging.Color.White });
options.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(options, 100, 100))
{
    Aspose.Imaging.Color[] pixels = new Aspose.Imaging.Color[10000];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Aspose.Imaging.Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

// Le proprietà di allocazione possono essere utilizzate per verificare se tutti gli oggetti Aspose.Imaging sono stati eliminati correttamente.
// Nel caso in cui ti sei dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.            
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### Guarda anche

* class [Cache](../../cache)
* spazio dei nomi [Aspose.Imaging](../../cache)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->