---
title: Save
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Salva i dati dellimmagine nel flusso sottostante.
type: docs
weight: 240
url: /it/net/aspose.imaging/image/save/
---
## Save() {#save}

Salva i dati dell'immagine nel flusso sottostante.

```csharp
public void Save()
```

### Esempi

L'esempio seguente mostra come salvare un'intera immagine BMP o parte di essa in un file o flusso.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Converti in un'immagine in bianco e nero
    bmpImage.BinarizeOtsu();

    // Salva nella stessa posizione con le opzioni predefinite.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una tavolozza contiene solo due colori: in questo caso bianco e nero.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Per tutte le immagini monocromatiche (comprese quelle in bianco e nero) è sufficiente allocare 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Salva in un'altra posizione con le opzioni specificate.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Salva solo la parte centrale dell'immagine.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Salva l'intera immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Salva la parte centrale dell'immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//L'output potrebbe essere simile a questo:
//La dimensione dell'intera immagine in byte: 24062
//La dimensione della parte centrale dell'immagine in byte: 6046
```

### Guarda anche

* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Salva l'immagine nella posizione del file specificata.

```csharp
public override void Save(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file in cui salvare l'immagine. |

### Guarda anche

* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| options | ImageOptionsBase | Le opzioni. |

### Esempi

L'esempio seguente carica un'immagine BMP da un file, quindi salva l'immagine in un file PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Salva l'intera immagine in un file PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

Questo esempio mostra i semplici passaggi per salvare un'immagine. Per dimostrare questa operazione, carichiamo un file esistente da una posizione del disco, eseguiamo l'operazione di rotazione sull'immagine e salviamo l'immagine in formato PSD usando il percorso del file

```csharp
[C#]

string dir = "c:\\temp\\";

//Crea un'istanza della classe image e inizializzala con un file esistente tramite il percorso del file
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Ruota l'immagine di 180 gradi sull'asse X
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //Salva l'immagine come PSD nel percorso del file con le impostazioni predefinite di PsdOptions
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

L'esempio seguente mostra come salvare un'intera immagine BMP o parte di essa in un file o flusso.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Converti in un'immagine in bianco e nero
    bmpImage.BinarizeOtsu();

    // Salva nella stessa posizione con le opzioni predefinite.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una tavolozza contiene solo due colori: in questo caso bianco e nero.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Per tutte le immagini monocromatiche (comprese quelle in bianco e nero) è sufficiente allocare 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Salva in un'altra posizione con le opzioni specificate.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Salva solo la parte centrale dell'immagine.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Salva l'intera immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Salva la parte centrale dell'immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//L'output potrebbe essere simile a questo:
//La dimensione dell'intera immagine in byte: 24062
//La dimensione della parte centrale dell'immagine in byte: 6046
```

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| options | ImageOptionsBase | Le opzioni. |
| boundsRectangle | Rectangle | L'immagine di destinazione delimita il rettangolo. Imposta il rettangolo vuoto per utilizzare i limiti sorgente. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | opzioni |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Salvataggio dell'immagine non riuscito. |

### Esempi

L'esempio seguente carica un'immagine BMP da un file, quindi salva una parte rettangolare dell'immagine in un file PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Salva la metà superiore dell'immagine in un file PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

L'esempio seguente mostra come salvare un'intera immagine BMP o parte di essa in un file o flusso.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Converti in un'immagine in bianco e nero
    bmpImage.BinarizeOtsu();

    // Salva nella stessa posizione con le opzioni predefinite.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una tavolozza contiene solo due colori: in questo caso bianco e nero.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Per tutte le immagini monocromatiche (comprese quelle in bianco e nero) è sufficiente allocare 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Salva in un'altra posizione con le opzioni specificate.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Salva solo la parte centrale dell'immagine.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Salva l'intera immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Salva la parte centrale dell'immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//L'output potrebbe essere simile a questo:
//La dimensione dell'intera immagine in byte: 24062
//La dimensione della parte centrale dell'immagine in byte: 6046
```

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | ImageOptionsBase | Le opzioni di salvataggio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | opzioniBase |
| ArgumentException | Impossibile salvare nel formato specificato poiché al momento non è supportato.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Esportazione dell'immagine non riuscita. |

### Esempi

L'esempio seguente carica un'immagine da un file, quindi salva l'immagine in un flusso di file PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Salva l'intera immagine in un flusso di file.
        image.Save(outputStream, saveOptions);
    }
}
```

Questo esempio mostra il processo di salvataggio di un'immagine in MemoryStream. Per dimostrare questa operazione, l'esempio carica un file esistente da una posizione su disco, esegue l'operazione Ruota sull'immagine e Salva l'immagine in formato PSD

```csharp
[C#]

//Crea un'istanza di MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea un'istanza della classe image e inizializzala con un file esistente tramite il percorso del file
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //Ruota l'immagine di 180 gradi sull'asse X
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //Salva l'immagine come PSD su MemoryStream con le impostazioni predefinite di PsdOptions
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

L'esempio seguente mostra come salvare un'intera immagine BMP o parte di essa in un file o flusso.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Converti in un'immagine in bianco e nero
    bmpImage.BinarizeOtsu();

    // Salva nella stessa posizione con le opzioni predefinite.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una tavolozza contiene solo due colori: in questo caso bianco e nero.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Per tutte le immagini monocromatiche (comprese quelle in bianco e nero) è sufficiente allocare 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Salva in un'altra posizione con le opzioni specificate.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Salva solo la parte centrale dell'immagine.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Salva l'intera immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Salva la parte centrale dell'immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//L'output potrebbe essere simile a questo:
//La dimensione dell'intera immagine in byte: 24062
//La dimensione della parte centrale dell'immagine in byte: 6046
```

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso in cui salvare i dati dell'immagine. |
| optionsBase | ImageOptionsBase | Le opzioni di salvataggio. |
| boundsRectangle | Rectangle | L'immagine di destinazione delimita il rettangolo. Imposta il rettangolo vuoto per utilizzare i limiti di origine. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | opzioniBase |
| ArgumentException | Impossibile salvare nel formato specificato poiché al momento non è supportato.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Esportazione dell'immagine non riuscita. |

### Esempi

L'esempio seguente carica un'immagine da un file, quindi salva una parte rettangolare dell'immagine in un flusso di file PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Salva la metà superiore dell'immagine in un flusso di file.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

L'esempio seguente mostra come salvare un'intera immagine BMP o parte di essa in un file o flusso.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Converti in un'immagine in bianco e nero
    bmpImage.BinarizeOtsu();

    // Salva nella stessa posizione con le opzioni predefinite.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Una tavolozza contiene solo due colori: in questo caso bianco e nero.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Per tutte le immagini monocromatiche (comprese quelle in bianco e nero) è sufficiente allocare 1 bit per pixel.
    saveOptions.BitsPerPixel = 1;

    // Salva in un'altra posizione con le opzioni specificate.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Salva solo la parte centrale dell'immagine.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Salva l'intera immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Salva la parte centrale dell'immagine in un flusso di memoria
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//L'output potrebbe essere simile a questo:
//La dimensione dell'intera immagine in byte: 24062
//La dimensione della parte centrale dell'immagine in byte: 6046
```

### Guarda anche

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
