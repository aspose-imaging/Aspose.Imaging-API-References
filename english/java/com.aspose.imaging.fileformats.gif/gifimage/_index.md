---
title: GifImage
second_title: Aspose.Imaging for Java API Reference
description: The API for Graphical Interchange Format GIF image file provides developers with versatile tools for processing compressed raster images and animated GIFs.
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

The API for Graphical Interchange Format (GIF) image file provides developers with versatile tools for processing compressed raster images and animated GIFs. Offering features like XMP metadata handling, color palette settings, background and transparent color control, opacity settings, resize, crop, filter application, gamma corrections, contrast adjustment, grayscale transformation, and conversion to other formats. This API empowers seamless manipulation and enhancement of GIF images for a wide range of applications.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | Initiate a new [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) object with specified parameters for the first frame and global palette. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Crafting GIF images becomes effortless with the [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) constructor. |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | Get started effortlessly with the [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Retrieve the file format effortlessly with this property. |
| [hasTrailer()](#hasTrailer--) | Manage the presence of a trailer in your GIF files with this property. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Manage the presence of a trailer in your GIF files with this property. |
| [isPaletteSorted()](#isPaletteSorted--) | Control the sorting of the palette in your GIF images using this property. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Control the sorting of the palette in your GIF images using this property. |
| [getLoopsCount()](#getLoopsCount--) | Retrieve the loop count effortlessly with this property. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Retrieve the loop count effortlessly with this property. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Manage the palette color resolution of your GIF images with this property. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Manage the palette color resolution of your GIF images with this property. |
| [getPageCount()](#getPageCount--) | Retrieve the total number of pages contained within the image with this straightforward property. |
| [getPages()](#getPages--) | Gain access to the pages within the image through this convenient property, allowing seamless navigation and manipulation of individual pages as needed. |
| [getBlocks()](#getBlocks--) | Gain access to the GIF blocks seamlessly with this property, facilitating easy retrieval and manipulation of the image's underlying data structures. |
| [isInterlaced()](#isInterlaced--) | Determines if the image is interlaced, impacting its display during loading. |
| [getOriginalOptions()](#getOriginalOptions--) | Retrieve the original file settings-based options, crucial for maintaining fidelity and consistency in image processing and manipulation. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Incorporate a new page seamlessly into the existing image, enhancing its content and expanding its scope. |
| [getActiveFrame()](#getActiveFrame--) | Manage and manipulate frames with this property, enabling smooth navigation and modification of the active frame within the GIF image. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Manage and manipulate frames with this property, enabling smooth navigation and modification of the active frame within the GIF image. |
| [getBackgroundColor()](#getBackgroundColor--) | Manage the background color of the GIF image with this property. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Manage the background color of the GIF image with this property. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Control the background color index of the GIF image using this property. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Control the background color index of the GIF image using this property. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Manage the pixel aspect ratio of the GIF image with this property. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Manage the pixel aspect ratio of the GIF image with this property. |
| [hasTransparentColor()](#hasTransparentColor--) | Determine whether the active frame of the GIF image includes a transparent color. |
| [getTransparentColor()](#getTransparentColor--) | Retrieve the transparent color of the active frame in the GIF image. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Determine whether the active frame of the GIF image includes a transparent color. |
| [hasBackgroundColor()](#hasBackgroundColor--) | This property determines whether the GIF image contains a background color. |
| [getImageOpacity()](#getImageOpacity--) | Retrieve the opacity of the active frame within the image, offering insight into its transparency level. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes this [Image](../../com.aspose.imaging/image) instance. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes this [Image](../../com.aspose.imaging/image) instance. |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | Resizing of the image while taking into account the full frames for each page in a GIF, thus preventing potential artifacts from appearing. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Perform rotation, flipping, or both on the active frame exclusively. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Apply dithering to the current image. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crop the image using a specified rectangle area. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Enhance image quality by applying gamma correction. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Apply a specific filter to the designated area of the image, enhancing its visual quality or altering its appearance as desired. |
| [setFrameTime(int time)](#setFrameTime-int-) | Adjusts the duration of each frame in milliseconds, ensuring consistent timing throughout the image sequence. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Adjusts the brightness of the image according to the specified `brightness` parameter. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Adjusts the contrast of the image, enhancing or reducing the difference in brightness between pixels. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-correction of an image applies a nonlinear adjustment to the pixel values, enhancing or reducing brightness based on the specified coefficients for the red, green, and blue channels. |
| [grayscale()](#grayscale--) | The transformation of an image to its grayscale representation converts the color image into a grayscale version by removing color information while preserving luminance. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarization of an image with a predefined threshold converts a grayscale or color image into a binary image, where each pixel is classified as either black or white based on whether its intensity value exceeds a specified threshold. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarization of an image with Otsu thresholding is a method used to automatically determine the optimal threshold value for converting a grayscale image into a binary image. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarization of an image using Bradley's adaptive thresholding algorithm with integral image thresholding is a method for converting a grayscale image into a binary image. |
| [orderBlocks()](#orderBlocks--) | Ordering the GIF blocks according to the GIF specification ensures proper GIF layout and compliance with the standard. |
| [clearBlocks()](#clearBlocks--) | Clearing all the GIF blocks removes any existing data stored within the image. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | Inserting a new GIF block allows you to add custom data at a specific position within the image. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Adding a new GIF block allows you to include additional data within the image. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Removing a GIF block removes specific data from the image, offering the ability to clean up or modify the image structure. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Proportional resizing maintains the aspect ratio of the image while adjusting its size, ensuring that the image does not appear stretched or distorted. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | This method rotates the image around its center point. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// Create a GIF Frame block of 100x100 px.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Fill the entire block in red.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Load frames
    RasterImage[] frames = loadFrames("Animation frames");

    // Create GIF image using the first frame
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Add frames to the GIF image using the AddPage method
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Save GIF image
        image.save("Multipage.gif");
    }

    // release resources
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


Initiate a new [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) object with specified parameters for the first frame and global palette. Start managing GIF images swiftly, ensuring accurate representation with customizable settings for optimal results.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | The first frame to initialize gif image with. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The global palette to use. Note if both `firstFrame` and `globalPalette` are null then default global palette is used. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


Crafting GIF images becomes effortless with the [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) constructor. With just the firstFrame parameter, it enters a world of dynamic visual communication.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | The first frame to initialize gif image with. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Get started effortlessly with the [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) constructor. With this simple method, you can dive into creating animated GIFs with ease. Just supply the firstFrame, globalPalette, paletteColorResolution, aspectRatio, and other parameters, and you're ready to bring your visuals to life.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | The first frame to initialize gif image with. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The global palette to use. Note if both `firstFrame` and `globalPalette` are null then default global palette is used. |
| isPaletteSorted | boolean | if set to `true` the palette is sorted. Note the parameter is used when `globalPalette` is not null. |
| paletteColorResolution | byte | The palette color resolution. Note the parameter is used when `globalPalette` is not null. |
| paletteBackgroundColorIndex | byte | The palette background color index. |
| aspectRatio | byte | The aspect ratio. |
| hasTrailer | boolean | if set to `true` the gif image has trailer otherwise no trailer written at the end of the stream. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieve the file format effortlessly with this property. It's your go-to source for identifying the format of your files. Seamlessly integrated into your workflow, it provides vital information without any hassle.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Manage the presence of a trailer in your GIF files with this property. Whether you need to check if a trailer exists or set its presence, this property simplifies the process. Keep your GIF files structured and compliant with this intuitive feature.

**Returns:**
boolean - `true` if GIF has trailer; otherwise, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Manage the presence of a trailer in your GIF files with this property. Whether you need to check if a trailer exists or set its presence, this property simplifies the process. Keep your GIF files structured and compliant with this intuitive feature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if GIF has trailer; otherwise, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Control the sorting of the palette in your GIF images using this property. Whether you need to check if the palette is sorted or set the sorting behavior, this property provides a straightforward way to manage the palette organization in your GIF files.

**Returns:**
boolean - `true` if palette is sorted; otherwise, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Control the sorting of the palette in your GIF images using this property. Whether you need to check if the palette is sorted or set the sorting behavior, this property provides a straightforward way to manage the palette organization in your GIF files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if palette is sorted; otherwise, `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Retrieve the loop count effortlessly with this property. If your GIF image includes loop information, this property gives you quick access to the loop count, enabling you to seamlessly manage looping behavior in your GIF files.

**Returns:**
int - The loops count or 1 (default value)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Retrieve the loop count effortlessly with this property. If your GIF image includes loop information, this property gives you quick access to the loop count, enabling you to seamlessly manage looping behavior in your GIF files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The loops count or 1 (default value) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Manage the palette color resolution of your GIF images with this property. Adjust the number of bits used to represent colors in the palette, providing fine control over color depth and image quality.

**Returns:**
byte - The palette color resolution bits.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Manage the palette color resolution of your GIF images with this property. Adjust the number of bits used to represent colors in the palette, providing fine control over color depth and image quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The palette color resolution bits. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Retrieve the total number of pages contained within the image with this straightforward property. Ideal for quickly assessing the extent of the image content.

**Returns:**
int - the page count.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Gain access to the pages within the image through this convenient property, allowing seamless navigation and manipulation of individual pages as needed.

**Returns:**
com.aspose.imaging.Image[] - the pages.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Gain access to the GIF blocks seamlessly with this property, facilitating easy retrieval and manipulation of the image's underlying data structures.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - the GIF blocks.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Determines if the image is interlaced, impacting its display during loading. This property offers insight into the image's rendering behavior, essential for optimizing loading strategies and enhancing overall viewing experience.

**Returns:**
boolean - `true` if this image instance is interlaced; otherwise, `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Retrieve the original file settings-based options, crucial for maintaining fidelity and consistency in image processing and manipulation. This method allows seamless integration of file-specific parameters into subsequent operations, ensuring accurate rendition and adherence to the image's inherent characteristics. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorporate a new page seamlessly into the existing image, enhancing its content and expanding its scope. This method augment image collections with additional content, fostering creativity and flexibility in image management and composition.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The page to add. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Load frames
    RasterImage[] frames = loadFrames("Animation frames");

    // Create GIF image using the first frame
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Add frames to the GIF image using the AddPage method
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Save GIF image
        image.save("Multipage.gif");
    }

    // release resources
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Manage and manipulate frames with this property, enabling smooth navigation and modification of the active frame within the GIF image.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// The output looks like this:
// Active frame size: { Width = 100, Height = 100}
// Clear all the blocks
// Active frame is not set
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Manage and manipulate frames with this property, enabling smooth navigation and modification of the active frame within the GIF image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | the active frame. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Manage the background color of the GIF image with this property. You can set or retrieve the background color to ensure consistency and enhance visual appeal.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Manage the background color of the GIF image with this property. You can set or retrieve the background color to ensure consistency and enhance visual appeal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | the background color. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Control the background color index of the GIF image using this property. Set or retrieve the index to maintain consistency or achieve desired visual effects.

**Returns:**
byte - the background color index.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Control the background color index of the GIF image using this property. Set or retrieve the index to maintain consistency or achieve desired visual effects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | the background color index. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Manage the pixel aspect ratio of the GIF image with this property. Set or retrieve the aspect ratio to ensure accurate rendering and maintain visual fidelity.

**Returns:**
byte - the pixel aspect ratio.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Manage the pixel aspect ratio of the GIF image with this property. Set or retrieve the aspect ratio to ensure accurate rendering and maintain visual fidelity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | the pixel aspect ratio. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Determine whether the active frame of the GIF image includes a transparent color. This property provides a convenient way to check for transparency within the image.

**Returns:**
boolean - a value indicating whether active frame has transparent color.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Retrieve the transparent color of the active frame in the GIF image. This property allows you to access the specific color that has been designated as transparent within the currently active frame.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Determine whether the active frame of the GIF image includes a transparent color. This property provides a convenient way to check for transparency within the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether active frame has transparent color. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


This property determines whether the GIF image contains a background color. If true, it indicates that the image includes a background color.

**Returns:**
boolean - a value indicating whether image has background color.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Retrieve the opacity of the active frame within the image, offering insight into its transparency level. This property is particularly useful for understanding the degree of transparency or opaqueness of the active frame in the image.

The opacity value between 0.0 (fully transparent) and 1.0 (fully opaque).

**Returns:**
float - opacity of this image (active frame).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Resizes this [Image](../../com.aspose.imaging/image) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Resizes this [Image](../../com.aspose.imaging/image) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | The settings. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// The adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// The small rectangular filter
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// The number of colors in the palette.
resizeSettings.setEntriesCount(256);

// The color quantization is not used
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// The Euclidian method
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Scale down by 2 times using adaptive resampling.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Save to PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


Resizing of the image while taking into account the full frames for each page in a GIF, thus preventing potential artifacts from appearing. This method is essential to maintain the integrity and quality of the image, especially when dealing with animated GIFs or sequences of frames.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Perform rotation, flipping, or both on the active frame exclusively. This operation applies transformations solely to the currently active frame of the image, preserving the integrity of other frames in the sequence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotation flip type. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// The helper class used in the main example below.
class Utils {
    // The helper method to get a string representation of the file format.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// Here is the main example
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotate, flip and save to the output file.
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Apply dithering to the current image. This process enhances image quality by reducing color banding and improving color transitions, resulting in a smoother appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | The dithering method. |
| bitsCount | int | The final bits count for dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The custom palette for dithering. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Perform threshold dithering using 4-bit color palette which contains 16 colors.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Perform floyd dithering using 1-bit color palette which contains only 2 colors - black and white.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Crop the image using a specified rectangle area. This operation removes the outer portion of the image, leaving only the selected region defined by the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |


**Example: The following example crops a GIF image.**
The following example crops a GIF image. The cropping area is be specified via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Save the cropped image to PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Enhance image quality by applying gamma correction. This method adjusts the color gamma of the image to achieve optimal visual clarity. It modifies the gamma value of each pixel, resulting in improved color rendition and overall image appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | Gamma for red, green and blue channels coefficient |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Set gamma coefficient for red, green and blue channels.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Apply a specific filter to the designated area of the image, enhancing its visual quality or altering its appearance as desired. This method selectively processes pixels within the defined rectangle, allowing for targeted adjustments to be made while preserving the integrity of the surrounding image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | The options. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Apply a median filter with a rectangle size of 5 to the entire image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Apply a bilateral smoothing filter with a kernel size of 5 to the entire image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Apply a Gaussian blur filter with a radius of 5 and a sigma value of 4.0 to the entire image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Apply a Gauss-Wiener filter with a radius of 5 and a smooth value of 4.0 to the entire image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Apply a motion wiener filter with a length of 5, a smooth value of 4.0 and an angle of 90.0 degrees to the entire image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Apply a sharpen filter with a kernel size of 5 and a sigma value of 4.0 to the entire image.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Adjusts the duration of each frame in milliseconds, ensuring consistent timing throughout the image sequence. This method uniformly sets the display time for every frame, allowing for precise control over animation speed. Changing this value will reset delay for all frames.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| time | int | The time of frame duration in milliseconds. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Adjusts the brightness of the image according to the specified `brightness` parameter. This method modifies the brightness of the entire image uniformly, enhancing or reducing the overall luminance to achieve the desired effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | Brightness value. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Adjusts the contrast of the image, enhancing or reducing the difference in brightness between pixels. This method modifies the image's overall tonal range, making darker areas darker and brighter areas brighter to improve visual clarity and detail.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contrast | float | Contrast value (in range [-100; 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma-correction of an image applies a nonlinear adjustment to the pixel values, enhancing or reducing brightness based on the specified coefficients for the red, green, and blue channels. This method helps to fine-tune the color balance and luminance of the image, improving its overall appearance and visual quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | float | Gamma for red channel coefficient |
| gammaGreen | float | Gamma for green channel coefficient |
| gammaBlue | float | Gamma for blue channel coefficient |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Set individual gamma coefficients for red, green and blue channels.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


The transformation of an image to its grayscale representation converts the color image into a grayscale version by removing color information while preserving luminance. This process simplifies the image to shades of gray, making it suitable for various applications such as printing, document processing, and grayscale analysis.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
The following example transforms a colored GIF image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarization of an image with a predefined threshold converts a grayscale or color image into a binary image, where each pixel is classified as either black or white based on whether its intensity value exceeds a specified threshold.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
The following example binarizes a GIF image with the predefined threshold. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarization of an image with Otsu thresholding is a method used to automatically determine the optimal threshold value for converting a grayscale image into a binary image. The Otsu thresholding algorithm calculates the threshold that minimizes the intra-class variance of the pixel intensities in the two resulting classes (foreground and background). This technique is particularly useful when the optimal threshold value is unknown and needs to be determined adaptively based on the image's histogram.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
The following example binarizes a GIF image with Otsu thresholding. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarize the image with Otsu thresholding.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarization of an image using Bradley's adaptive thresholding algorithm with integral image thresholding is a method for converting a grayscale image into a binary image. This algorithm calculates a local threshold for each pixel based on the average intensity of the surrounding pixels within a specified window. By adaptively adjusting the threshold based on local pixel intensities, Bradley's method is effective at handling variations in lighting and contrast across the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


Ordering the GIF blocks according to the GIF specification ensures proper GIF layout and compliance with the standard. This process involves arranging the blocks in the correct sequence as defined by the specification. Additionally, it may involve removing certain [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) instances that are not necessary for the final layout. By adhering to the GIF specification, the resulting image will be correctly structured and compatible with GIF viewing applications.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Clearing all the GIF blocks removes any existing data stored within the image. This operation effectively resets the image to an empty state, removing any previously added blocks. Use this method when you need to start fresh with a clean slate for creating or modifying a GIF image.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// The output looks like this:
// Active frame size: { Width = 100, Height = 100}
// Clear all the blocks
// Active frame is not set
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


Inserting a new GIF block allows you to add custom data at a specific position within the image. This method enables you to place custom blocks at a desired location in the GIF image, providing flexibility in organizing and structuring the image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based element, at which block will be inserted. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | The GIF block to add. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


Adding a new GIF block allows you to include additional data within the image. This method enables you to append custom blocks to the GIF image, which can contain various types of information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | The GIF block to add. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Create a GIF image 100 x 100 px.
// The first block is fully black by default.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // The first circle is red
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // The second circle is black
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Gradually increase the angle of the red arc shape.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Gradually increase the angle of the black arc and wipe out the red arc.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


Removing a GIF block removes specific data from the image, offering the ability to clean up or modify the image structure. This method enables you to remove unwanted or unnecessary blocks, optimizing the GIF image for efficient storage. Use this functionality to eliminate outdated information from the image while preserving its integrity and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | The block to remove.

--------------------

Note: do not forget to Dispose the block if you will not add it to some other GifImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Proportional resizing maintains the aspect ratio of the image while adjusting its size, ensuring that the image does not appear stretched or distorted. This method resizes the image proportionally, scaling both the width and height by the same factor. The proportional resize will resize each frame according to the ratio of `newWidth`/width and `newHeight`/height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


This method rotates the image around its center point. By specifying the rotation angle, you can rotate the image clockwise or counterclockwise to achieve the desired orientation. This rotation helps adjust the image's presentation or alignment without distorting its content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotation angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color of the background. |

