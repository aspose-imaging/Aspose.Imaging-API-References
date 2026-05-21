---
title: "Bild"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bilden är basklassen för alla typer av bilder."
type: docs
weight: 56
url: /sv/java/com.aspose.imaging/image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.imaging.IObjectWithBounds](../../com.aspose.imaging/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler, [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler, IMetadataContainer
```

Bilden är basklassen för alla typer av bilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna `loadOptions`. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.imaging.ImageOptionsBase-int-int-) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)](#create-com.aspose.imaging.ImageOptionsBase-int-int-int---) | Skapar en [RasterImage](../../com.aspose.imaging/rasterimage)-instans från den tillhandahållna pixelarrayen. |
| [create(Image[] images)](#create-com.aspose.imaging.Image---) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(MultipageCreateOptions multipageCreateOptions)](#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-) | Skapar de angivna multipage‑skapandealternativen. |
| [create(String[] files, boolean throwExceptionOnLoadError)](#create-java.lang.String---boolean-) | Skapar multipage‑bilden som innehåller de angivna filerna. |
| [create(String[] files)](#create-java.lang.String---) | Skapar multipage‑bilden som innehåller de angivna filerna. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.imaging.Image---boolean-) | Skapar en ny bild med de angivna bilderna som sidor. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Hämtar filformatet. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.imaging.LoadOptions-) | Laddar en ny bild från den angivna filsökvägen eller URL:en. |
| [load(String filePath)](#load-java.lang.String-) | Laddar en ny bild från den angivna filsökvägen eller URL:en. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Laddar en ny bild från den angivna strömmen. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Laddar en ny bild från den angivna strömmen. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Hämtar filformatet. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Hämtar en proportionell bredd. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Hämtar en proportionell höjd. |
| [removeMetadata()](#removeMetadata--) | Tar bort metadata. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Försöker att sätta en `metadata`-instans, om detta [Image](../../com.aspose.imaging/image)-objekt stödjer och implementerar [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-typen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getBounds()](#getBounds--) | Hämtar bildens gränser. |
| [getContainer()](#getContainer--) | Hämtar `Image`-behållaren. |
| [getPalette()](#getPalette--) | Hämtar färgpaletten. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Ställer in färgpaletten. |
| [isUsePalette()](#isUsePalette--) | Hämtar ett värde som indikerar om bildpaletten används. |
| [getSize()](#getSize--) | Hämtar bildens storlek. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Hämtar avbrottsövervakaren. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-) | Ställer in avbrottsövervakaren. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [isAutoAdjustPalette()](#isAutoAdjustPalette--) | Hämtar ett värde som indikerar om paletten automatiskt justeras. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Ställer in ett värde som indikerar om paletten automatiskt justeras. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Hämtar ett värde som indikerar om bilden har bakgrundsfärg. |
| [getFileFormat()](#getFileFormat--) | Hämta enkelt filformatvärdet med den här användarvänliga egenskapen. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar eller sätter ett värde för bakgrundsfärgen. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Hämtar eller sätter ett värde som indikerar om bilden har bakgrundsfärg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Hämtar eller sätter ett värde för bakgrundsfärgen. |
| [getMetadata()](#getMetadata--) | Hämtar bildmetadata. |
| [getExifData()](#getExifData--) | Hämtar Exif-data. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Ställer in Exif-data. |
| [getXmpData()](#getXmpData--) | Hämtar Xmp-data. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Ställer in Xmp-data. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Hämtar information om progress‑händelsehanteraren. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Hämtar information om progress‑händelsehanteraren. |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.imaging.ImageOptionsBase-) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de överförda sparalternativen. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar storlek på bilden. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar alternativen baserat på de ursprungliga filinställningarna. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ändrar bredden proportionellt. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ändrar höjden proportionellt. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändrar bredden proportionellt. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändrar höjden proportionellt. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar bredden proportionellt. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar höjden proportionellt. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roterar, vänder eller roterar och vänder bilden. |
| [rotate(float angle)](#rotate-float-) | Rotera bilden kring centrum. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär den angivna rektangeln. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Beskär bilden med förskjutningar. |
| [save()](#save--) | Sparar bilddata till den underliggande strömmen. |
| [save(String filePath)](#save-java.lang.String-) | Sparar bilden till den angivna filsökvägen. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Sparar objektets data till den angivna filsökvägen i det angivna filformatet enligt sparalternativen. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Sparar objektets data till den angivna filsökvägen i det angivna filformatet enligt sparalternativen. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-) | Sparar objektets data till den angivna filsökvägen i det angivna filformatet enligt sparalternativen. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Ställer in bildpaletten. |
| [getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)](#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---) | Konverterar till aps. |

## Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.
Detta exempel skapar en ny Image‑fil på en viss diskplats som anges av egenskapen Source i BmpOptions‑instansen. Flera egenskaper för BmpOptions‑instansen sätts innan den faktiska bilden skapas. Speciellt egenskapen Source, som i detta fall refererar till den faktiska diskplatsen.
``` java
// Skapa en instans av BmpOptions och sätt dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
// Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Skapa en instans av Image och initiera den med en BmpOptions‑instans genom att anropa Create‑metoden.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Utför någon bildbehandling.

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


## Example: Determine if the palette is used by the image.

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Bestämmer om bilden kan läsas in från den angivna filsökvägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen. |

**Returns:**
boolesk - `true` om bilden kan laddas från den angivna filen; annars `false`.

**Example: This example determines whether image can be loaded from a file.**

``` java

// Använd en absolut sökväg till filen
boolean canLoad = com.aspose.imaging.Image.canLoad("c:\\temp\\sample.gif");
```

### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

**Returns:**
boolesk - `true` om bilden kan laddas från den angivna filen; annars `false`.
### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Bestämmer om bilden kan läsas in från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa från. |

**Returns:**
boolesk - `true` om bilden kan laddas från den angivna strömmen; annars `false`.

**Example: This example determines whether image can be loaded from a file stream.**

``` java
String dir = "c:\\temp\\";

boolean canLoad;

// Använd en filström.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
try {
    canLoad = com.aspose.imaging.Image.canLoad(stream);
} finally {
    stream.close();
}

// Följande data är inte en giltig bildström, så CanLoad returnerar false.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    canLoad = com.aspose.imaging.Image.canLoad(stream);
}
```

### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna `loadOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att läsa från. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

**Returns:**
boolesk - `true` om bilden kan laddas från den angivna strömmen; annars `false`.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.imaging.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Skapar en ny bild med de angivna skapandealternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Bildalternativen. |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The newly created image.

**Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.**
Detta exempel skapar en ny Image‑fil på en viss diskplats som anges av egenskapen Source i BmpOptions‑instansen. Flera egenskaper för BmpOptions‑instansen sätts innan den faktiska bilden skapas. Speciellt egenskapen Source, som i detta fall refererar till den faktiska diskplatsen.
``` java
// Skapa en instans av BmpOptions och sätt dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
// Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Skapa en instans av Image och initiera den med en BmpOptions‑instans genom att anropa Create‑metoden.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Utför någon bildbehandling.

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### create(ImageOptionsBase imageOptions, int width, int height, int[] pixels) {#create-com.aspose.imaging.ImageOptionsBase-int-int-int---}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```


Skapar en [RasterImage](../../com.aspose.imaging/rasterimage)-instans från den angivna pixelarrayen. Validerar att den specificerade bredden och höjden matchar dimensionerna på pixeldata. Denna metod kan endast användas när biblioteket är i licensierat läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Alternativen som används för att skapa [RasterImage](../../com.aspose.imaging/rasterimage). |
| width | int | Bredden på [RasterImage](../../com.aspose.imaging/rasterimage). |
| height | int | Höjden på [RasterImage](../../com.aspose.imaging/rasterimage). |
| pixlar | int[] | Arrayen med pixelvärden som används för att fylla bilden. |

**Returns:**
[Image](../../com.aspose.imaging/image) - A [RasterImage](../../com.aspose.imaging/rasterimage) populated with the provided pixel data.
### create(Image[] images) {#create-com.aspose.imaging.Image---}
```
public static Image create(Image[] images)
```


Skapar en ny bild med de angivna bilderna som sidor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Bilderna. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### create(MultipageCreateOptions multipageCreateOptions) {#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-}
```
public static Image create(MultipageCreateOptions multipageCreateOptions)
```


Skapar de angivna multipage‑skapandealternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| multipageCreateOptions | [MultipageCreateOptions](../../com.aspose.imaging.imageoptions/multipagecreateoptions) | Alternativen för att skapa flersidiga bilder. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files, boolean throwExceptionOnLoadError) {#create-java.lang.String---boolean-}
```
public static Image create(String[] files, boolean throwExceptionOnLoadError)
```


Skapar multipage‑bilden som innehåller de angivna filerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filer | java.lang.String[] | Filerna. |
| throwExceptionOnLoadError | boolean | om den är satt till `true` [throw exception on load error]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files) {#create-java.lang.String---}
```
public static Image create(String[] files)
```


Skapar multipage‑bilden som innehåller de angivna filerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filer | java.lang.String[] | Filerna. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(Image[] images, boolean disposeImages) {#create-com.aspose.imaging.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Skapar en ny bild med de angivna bilderna som sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Bilderna. |
| disposeImages | boolean | om den är satt till `true` [dispose images]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filsökvägen. |

Det fastställda filformatet betyder inte att den specificerade bilden kan laddas. Använd en av CanLoad-metodens överlagringar för att avgöra om filen kan laddas. |

**Returns:**
long - Det fastställda filformatet.

**Example: This example shows how to determine the image format without loading the entire image from a file.**

``` java
String dir = "c:\\temp\\";

// Använd en absolut sökväg till filen
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// En strängrepresentation av filformatet.
String strFormat;
if (format == com.aspose.imaging.FileFormat.Bmp) {
    strFormat = "BMP";
} else if (format == com.aspose.imaging.FileFormat.Gif) {
    strFormat = "GIF";
} else if (format == com.aspose.imaging.FileFormat.Dicom) {
    strFormat = "DICOM";
} else if (format == com.aspose.imaging.FileFormat.Djvu) {
    strFormat = "DJVU";
} else if (format == com.aspose.imaging.FileFormat.Dng) {
    strFormat = "DNG";
} else if (format == com.aspose.imaging.FileFormat.Png) {
    strFormat = "PNG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg) {
    strFormat = "JPEG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg2000) {
    strFormat = "JPEG2000";
} else if (format == com.aspose.imaging.FileFormat.Psd) {
    strFormat = "PSD";
} else if (format == com.aspose.imaging.FileFormat.Tiff) {
    strFormat = "Tiff";
} else if (format == com.aspose.imaging.FileFormat.Webp) {
    strFormat = "WEBP";
} else if (format == com.aspose.imaging.FileFormat.Cdr) {
    strFormat = "CDR";
} else if (format == com.aspose.imaging.FileFormat.Cmx) {
    strFormat = "CMX";
} else if (format == com.aspose.imaging.FileFormat.Emf) {
    strFormat = "EMF";
} else if (format == com.aspose.imaging.FileFormat.Wmf) {
    strFormat = "WMF";
} else if (format == com.aspose.imaging.FileFormat.Svg) {
    strFormat = "SVG";
} else if (format == com.aspose.imaging.FileFormat.Odg) {
    strFormat = "ODG";
} else if (format == com.aspose.imaging.FileFormat.Eps) {
    strFormat = "EPS";
} else {
    strFormat = "UNDEFINED";
}

System.out.println("The file format is " + strFormat);
```

### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna filsökvägen eller URL:en. Om `filePath` är en filsökväg öppnar metoden bara filen. Om `filePath` är en URL laddar metoden ner filen, sparar den som en temporär fil och öppnar den.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen eller URL:en att ladda bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Laddar en ny bild från den angivna filsökvägen eller URL:en. Om `filePath` är en filsökväg öppnar metoden bara filen. Om `filePath` är en URL laddar metoden ner filen, sparar den som en temporär fil och öppnar den.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen eller URL:en att ladda bilden från. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the loading of an existing Image file into an instance of com.**
Detta exempel demonstrerar hur en befintlig Image-fil laddas in i en instans av com.aspose.imaging.Image med den angivna filsökvägen.
``` java
// Skapa en Image-instans och initiera den med en befintlig bildfil från en diskplats.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Utför någon bildbehandling.
} finally {
    image.dispose();
}
```

### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att ladda bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att ladda bilden från. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att ladda bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att ladda bilden från. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the use of InputStream object to load an existing Image file**

``` java
// Skapa en instans av FileInputStream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.bmp");
try {
    // Skapa en instans av Image-klassen och ladda en befintlig fil via FileStream-objektet genom att anropa Load-metoden
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(stream);
    try {
        // Utför någon bildbehandling.
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ström | java.io.InputStream | Strömmen. |

Den bestämda filformatet betyder inte att den angivna bilden kan laddas. Använd en av overloads för CanLoad-metoden för att avgöra om strömmen kan laddas. |

**Returns:**
long - Det fastställda filformatet.

**Example: This example shows how to determine the image format without loading the entire image from a file stream.**

``` java

// Hjälparklassen som används i huvudexemplet nedan.
class Utils {
    // Hjälpmetoden för att få en strängrepresentation av filformatet.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Här är huvudexemplet
Utils utils = new Utils();

String dir = "c:\\temp\\";

// Använd en filström.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Följande data är inte en giltig bildström, så GetFileFormat returnerar FileFormat.Undefined.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Utdata kan se ut så här:
// Filformatet är BMP
// Filformatet är UNDEFINED
```

### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för att få en passande rektangel för. |
| bredd | int | Objektets bredd. |
| höjd | int | Objektets höjd. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för att få en passande rektangel för. |
| pixlar | int[] | De 32-bitars ARGB-pixlarna. |
| bredd | int | Objektets bredd. |
| höjd | int | Objektets höjd. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Hämtar en proportionell bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| newHeight | int | Den nya höjden. |

**Returns:**
int - Den proportionella bredden.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Hämtar en proportionell höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| newWidth | int | Den nya bredden. |

**Returns:**
int - Den proportionella höjden.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Tar bort metadata.

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Försöker att sätta en `metadata`-instans, om detta [Image](../../com.aspose.imaging/image)-objekt stödjer och implementerar [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-typen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Metadatan. |

**Returns:**
boolean - Sant, om [Image](../../com.aspose.imaging/image)-instansen stöder och implementerar [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-typen; annars falskt.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

**Returns:**
int - Bildens bitar per pixel-antal.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar bildens gränser.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The image bounds.
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Hämtar `Image`-behållaren.

Värde: `Image`-behållaren.

Om den här egenskapen inte är null indikerar det att bilden är inbäddad i en annan bild.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Hämtar färgpaletten. Färgpaletten används inte när pixlar representeras direkt.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |

### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Hämtar ett värde som indikerar om bildpaletten används.

Värde: `true` om paletten används i bilden; annars `false`.

**Returns:**
boolean - ett värde som indikerar om bildpaletten används.

**Example: Determine if the palette is used by the image.**

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### getSize() {#getSize--}
```
public Size getSize()
```


Hämtar bildens storlek.

**Returns:**
[Size](../../com.aspose.imaging/size) - The image size.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Ladda en DJVU-bild från en filström.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Utdata kan se ut så här:
//Det totala antalet sidor: 2
//Det aktiva sidnumret:    1
//Det första sidnumret:     1
//Det sista sidnumret:      2
//--------------------------------------------------
//Sidnummer:     1
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
//--------------------------------------------------
//Sidnummer:     2
//Sidstorlek:       { Width = 2481, Height = 3508}
//Sidens råformat: RgbIndexed1Bpp, använda kanaler: 1
```

### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Hämtar avbrottsövervakaren.

**Returns:**
[InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) - the interrupt monitor.
### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Ställer in avbrottsövervakaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) | avbrottsövervakaren. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Returns:**
int - buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar. |

### isAutoAdjustPalette() {#isAutoAdjustPalette--}
```
public boolean isAutoAdjustPalette()
```


Hämtar ett värde som indikerar om paletten automatiskt justeras.

**Returns:**
boolean - `true` om automatisk justering av palett är aktiverad; annars, `false`.
### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Ställer in ett värde som indikerar om paletten automatiskt justeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om automatisk justering av palett är aktiverad; annars, `false`. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Hämtar ett värde som indikerar om bilden har bakgrundsfärg.

**Returns:**
boolean
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämta enkelt filformatvärdet med denna användarvänliga egenskap. Idealisk för utvecklare som söker snabb åtkomst till information om filformatet.

**Returns:**
long
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar eller sätter ett värde för bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Hämtar eller sätter ett värde som indikerar om bilden har bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Hämtar eller sätter ett värde för bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Hämtar bildmetadata.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Hämtar Exif-data.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Ställer in Exif-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif‑data. |

### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


Hämtar Xmp-data.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public final void setXmpData(XmpPacketWrapper value)
```


Ställer in Xmp-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Xmp‑data. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public final ProgressEventHandler getIProgressEventHandler()
```


Hämtar information om progress‑händelsehanteraren.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Hämtar information om progress‑händelsehanteraren.

Värde: Information om progress‑händelsehanteraren.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### canSave(ImageOptionsBase options) {#canSave-com.aspose.imaging.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de överförda sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Spara‑alternativen att använda. |

**Returns:**
boolean - `true` om bilden kan sparas till det angivna filformatet som representeras av de överförda spara‑alternativen; annars, `false`.

**Example: This example shows how to determine whether image can be saved to the specified file format represented by the passed save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    saveOptions.setQuality(50);

    // Bestäm om bilden kan sparas till JPEG
    boolean canSave = image.canSave(saveOptions);
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Ändrar storlek på bilden. Standardvärdet [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |


**Example: The following example shows how to resize a metafile (WMF and EMF).**

``` java
String baseFolder = "c:\\temp\\";

String[] files = new String[]{"image3.emf", "image4.wmf"};
for (String fileName : files) {
    String inputFile = baseFolder + fileName;
    String outputFile = baseFolder + "Resize_" + fileName;
    com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) com.aspose.imaging.Image.load(inputFile);
    try {
        image.resize(image.getWidth() / 4, image.getHeight() / 4);
        image.save(outputFile);
    } finally {
        image.close();
    }
}
```


**Example: The following example shows how to resize SVG image and save it to PNG.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1431\\";
String[] fileNames = new String[] {
                "Logotype.svg",
                "sample_car.svg",
                "rg1024_green_grapes.svg",
                "MidMarkerFigure.svg",
                "embeddedFonts.svg"
        };

com.aspose.imaging.PointF[] scales = new com.aspose.imaging.PointF[] {
                new com.aspose.imaging.PointF(0.5f, 0.5f),
                new com.aspose.imaging.PointF(1f, 1f),
                new com.aspose.imaging.PointF(2f, 2f),
                new com.aspose.imaging.PointF(3.5f, 9.2f),
        };

for (String inputFile : fileNames) {
    for (com.aspose.imaging.PointF scale : scales) {
        String outputFile = String.format("%s_%2.2f_%2.2f.png", inputFile, scale.getX(), scale.getY());
        com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + inputFile);
        try {
            image.resize((int) (image.getWidth() * scale.getX()), (int) (image.getHeight() * scale.getY()));
            image.save(dir + outputFile, new com.aspose.imaging.imageoptions.PngOptions());
        }
        finally {
            image.close();
        }
    }
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |


**Example: This example loads an image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
}
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```


**Example: This example loads a WMF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
}
```


**Example: This example loads a multi-page ODG image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Spara som PNG med standardalternativ.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Maskerings‑exportalternativ
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Använd GraphCut‑klustring.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Bakgrundsfärgen kommer att vara transparent.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Minska bildstorleken för att påskynda segmenteringsprocessen
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Hämtar förgrundsmasken
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Öka maskens storlek till den ursprungliga bildens storlek
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applicera masken på den ursprungliga bilden för att få ett förgrundssegment
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image and export it to PNG format.**

``` java
// Läs in EPS-bild
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Ändra storlek på bilden med Mitchell kubisk interpolationsmetod
    image.resize(400, 400, ResizeType.Mitchell);

    // Exportera bild till PNG-format
    image.save("ExportResult.png", new PngOptions());
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |


**Example: This example loads an image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Den adaptiva algoritmen baserad på viktad och blandad rationell funktion och lanczos3-interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Det lilla rektangulära filtret
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Antalet färger i paletten.
resizeSettings.setEntriesCount(256);

// Färgkvantiseringen används inte
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Den euklidiska metoden
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner med 2 gånger med adaptiv omsampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Den adaptiva algoritmen baserad på viktad och blandad rationell funktion och lanczos3-interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Det lilla rektangulära filtret
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Antalet färger i paletten.
resizeSettings.setEntriesCount(256);

// Färgkvantiseringen används inte
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Den euklidiska metoden
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Skala ner med 2 gånger med adaptiv omsampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image using advanced settings.**

``` java
// Läs in EPS-bild
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Ställ in interpolationsläget
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Ställ in filtertypen
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Ställer in färgjämförelsesmetoden
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Ställ in färgkvantiseringmetoden
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Ändra storlek på bilden med avancerade inställningar för storleksändring
    image.resize(400, 400, resizeSettings);

    // Exportera bild till PNG-format
    image.save("ExportResult.png", new PngOptions());
}
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämtar standardalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade. Till exempel, om vi läser in en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med metoden `DataStreamSupporter.Save(string)`, kommer en PNG-bild med 8 bitar per pixel att genereras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden `Image.Save(string, ImageOptionsBase)` som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Ändrar bredden proportionellt. Standardvärdet [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\\#NearestNeighbourResample) används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Ändrar höjden proportionellt. Standardvärdet [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\\#NearestNeighbourResample) används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Detta exempel läser in en bild och ändrar dess storlek proportionellt med olika metoder för storleksändring. Endast bredden anges, höjden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
{
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Detta exempel läser in en bild och ändrar dess storlek proportionellt med olika metoder för storleksändring. Endast höjden anges, bredden beräknas automatiskt.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med bilinjär omprovning.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Maskerings‑exportalternativ
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Använd GraphCut‑klustring.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Bakgrundsfärgen kommer att vara transparent.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Minska bildstorleken för att påskynda segmenteringsprocessen
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Skapa en instans av klassen ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Hämtar förgrundsmasken
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Öka maskens storlek till den ursprungliga bildens storlek
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Applicera masken på den ursprungliga bilden för att få ett förgrundssegment
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för bildens storleksändring. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för bildens storleksändring. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Typ av rotationsvändning. |


**Example: This example demonstrates the use of Rotate operation on an image.**
Detta exempel demonstrerar användningen av Rotate‑operationen på en bild. Exemplet läser in en befintlig bildfil från en viss diskplats och utför Rotate‑operationen på bilden enligt värdet i enumen com.aspose.imaging.RotateFlipType
``` java
// Skapa en instans av bildklassen och initiera den med en befintlig bildfil via filsökväg
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Rotera bilden 180 grader kring X‑axeln
    image.rotateFlip(com.aspose.imaging.RotateFlipType.Rotate180FlipX);

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotera bilden kring centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |


**Example: The following example crops a raster image.**
Följande exempel beskär en rasterbild. Beskärningsområdet specificeras via com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Beskär bilden. Beskärningsområdet är den rektangulära centrala delen av bilden.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    image.crop(area);

    // Spara den beskurna bilden som PNG
    image.save(dir + "sample.Crop.png");
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beskär bilden med förskjutningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | int | Den vänstra förskjutningen. |
| rightShift | int | Den högra förskjutningen. |
| topShift | int | Den övre förskjutningen. |
| bottomShift | int | Den nedre förskjutningen. |


**Example: The following example crops a raster image.**
Följande exempel beskär en rasterbild. Beskärningsområdet specificeras via Left, Top, Right, Bottom-marginaler.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Beskär igen. Ställ in en marginal på 10 % av bildens storlek.
    int horizontalMargin = rasterImage.getWidth() / 10;
    int verticalMargin = rasterImage.getHeight() / 10;
    image.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Spara den beskurna bilden som PNG.
    image.save(dir + "sample.Crop.png");
}
```

### save() {#save--}
```
public final void save()
```


Sparar bilddata till den underliggande strömmen.


**Example: The following example shows how to save an entire BMP image or part of it to a file or stream.**

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Konvertera till en svart‑vit bild
    bmpImage.binarizeOtsu();

    // Spara till samma plats med standardalternativ.
    image.save();

    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // En palett innehåller endast två färger: Svart och Vit i detta fall.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.createMonochrome());

    // För alla monokroma bilder (inklusive svart‑vita) räcker det att allokera 1 bit per pixel.
    saveOptions.setBitsPerPixel(1);

    // Spara till en annan plats med de angivna alternativen.
    image.save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Spara endast den centrala delen av bilden.
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(image.getWidth() / 4, image.getHeight() / 4, image.getWidth() / 2, image.getHeight() / 2);
    image.save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Spara hela bilden till en minnesström
    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions);
        System.out.println("The size of the whole image in bytes: " + stream.size());
    } finally {
        stream.close();
    }

    // Spara den centrala delen av bilden till en minnesström
    stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions, bounds);
        System.out.println("The size of the central part of the image in bytes: " + stream.size());
    } finally {
        stream.close();
    }
} finally {
    image.close();
}

//Utdata kan se ut så här:
//Storleken på hela bilden i byte: 1662
//Storleken på den centrala delen av bilden i byte: 462
```

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Sparar bilden till den angivna filsökvägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara bilden till. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Sparar objektets data till den angivna filsökvägen i det angivna filformatet enligt sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Alternativen. |


**Example: This example shows the simple steps to Save an Image.**
Detta exempel visar de enkla stegen för att spara en bild. För att demonstrera denna operation läser vi in en befintlig fil från en viss diskplats och sparar bilden i PSD‑format.
``` java
// Läs in en befintlig fil från disk.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Spara bilden som PSD till filsökväg med standardinställningarna för PsdOptions
    image.save("C:\\temp\\output.psd", new com.aspose.imaging.imageoptions.PsdOptions());
} finally {
    image.dispose();
}
```

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Sparar objektets data till den angivna filsökvägen i det angivna filformatet enligt sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Alternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Destinationens bildgräns‑rektangel. Ställ in den tomma rektangeln för att använda källgränser. |


**Example: The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Spara den övre halvan av bilden till en PNG‑fil.
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    image.save(dir + "output.png", saveOptions, bounds);
} finally {
    image.dispose();
}
```

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Sparar objektets data till den angivna filsökvägen i det angivna filformatet enligt sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att spara bildens data till. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Alternativen. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Destinationens bildgräns‑rektangel. Ställ in den tomma rektangeln för att använda källgränser. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Sparalternativen. |


**Example: This example shows the process of saving an Image to memory buffer.**
Detta exempel visar processen för att spara en bild till minnesbuffert. För att demonstrera denna operation laddar exemplet en befintlig fil från en viss diskplats och sparar bilden i PSD-format.
``` java
java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
try {            //Create an instance of image class and initialize it with an existing image file through File path
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
    try {
        //Spara bilden till PSD-minnesström med standardinställningarna för PsdOptions.
        image.save(stream, new com.aspose.imaging.imageoptions.PsdOptions());
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Destinationens bildgräns‑rektangel. Ställ in den tomma rektangeln för att använda källgränser. |


**Example: The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    java.io.OutputStream outputStream = new java.io.FileOutputStream(dir + "sample.output.png");
    try {
        // Spara den övre halvan av bilden till en filström.
        image.save(outputStream, saveOptions, bounds);
    } finally {
        outputStream.close();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Ställer in bildpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber) {#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---}
```
public InputStream getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)
```


Konverterar till aps.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Bildalternativen. |
| clippingRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Klippningsrektangeln. |
| pageNumber | int[] | Sidnumret. |

**Returns:**
java.io.InputStream - Den serialiserade strömmen
