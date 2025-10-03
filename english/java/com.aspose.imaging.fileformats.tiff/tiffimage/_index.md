---
title: TiffImage
second_title: Aspose.Imaging for Java API Reference
description: Process Tagged Image File Format TIFF raster images with our API offering comprehensive support for various resolutions and advanced editing capabilities like EXIF data manipulation and alpha channels.
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Process Tagged Image File Format (TIFF) raster images with our API, offering comprehensive support for various resolutions and advanced editing capabilities like EXIF data manipulation and alpha channels. Normalize angles for scanned images, resize, transform to grayscale, and apply filters, gamma corrections and image parameters adjustments with ease. Seamlessly handle multi-frame TIFF files, create graphics paths, add shapes, and effortlessly save images to different formats.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Initialize a new object of the [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) class, specifying the frame parameter. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Create a new instance of the [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) class, providing a list of frames as a parameter. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Retrieve the file format value associated with the image. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Indicate if components necessitate premultiplication, ensuring efficient handling of visual elements. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Indicate if components necessitate premultiplication, ensuring efficient handling of visual elements. |
| [getByteOrder()](#getByteOrder--) | Toggle the byte order for TIFF files seamlessly, ensuring precise control over data interpretation. |
| [setByteOrder(int value)](#setByteOrder-int-) | Toggle the byte order for TIFF files seamlessly, ensuring precise control over data interpretation. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Retrieve the horizontal resolution of the specified [Image](../../com.aspose.imaging/image) in pixels per inch, facilitating precise adjustment and rendering capabilities. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Modifies the horizontal resolution of the specified [Image](../../com.aspose.imaging/image) in pixels per inch, facilitating precise adjustment and rendering capabilities. |
| [getVerticalResolution()](#getVerticalResolution--) | Access the vertical resolution of the designated [Image](../../com.aspose.imaging/image) in pixels per inch, enabling precise adjustments and rendering optimizations. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Access the vertical resolution of the designated [Image](../../com.aspose.imaging/image) in pixels per inch, enabling precise adjustments and rendering optimizations. |
| [getActiveFrame()](#getActiveFrame--) | Manage the active frame seamlessly, facilitating dynamic navigation and manipulation within the designated context. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Manage the active frame seamlessly, facilitating dynamic navigation and manipulation within the designated context. |
| [getFrames()](#getFrames--) | Retrieve an array of [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) instances, enabling comprehensive access and manipulation of individual frames within the TIFF image. |
| [getPageCount()](#getPageCount--) | Retrieve the total count of pages within the specified document, facilitating efficient navigation and management of multipage content. |
| [getPages()](#getPages--) | Access the pages of the document seamlessly, enabling dynamic navigation and manipulation within the content structure. |
| [hasAlpha()](#hasAlpha--) | Determine whether the image has an alpha channel, providing crucial information for rendering and compositing operations. |
| [removeMetadata()](#removeMetadata--) | Removes this image instance metadata by setting this `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) value to `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Retrieve options derived from the original file settings, facilitating seamless preservation of key parameters such as bit-depth and other essential attributes of the original image. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Incorporate a new page into the existing image seamlessly, expanding its content and versatility. |
| [alignResolutions()](#alignResolutions--) | Implement the AlignResolutions helper method to synchronize horizontal and vertical resolutions, ensuring uniformity in image dimensions. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Establishes the resolution for the specified [RasterImage](../../com.aspose.imaging/rasterimage), enabling precise control over image rendering and display properties. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Utilize the NormalizeAngle method specifically designed for scanned text documents to rectify skewed scans, ensuring accurate alignment. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Incorporate the specified frame seamlessly into the image, expanding its content and versatility. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Add the frames from the specified image seamlessly into the current frame, consolidating their content and enhancing compositional flexibility. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Integrate the array of frames seamlessly into the image, enriching its content and versatility. |
| [insertFrame(int index, TiffFrame frameToInsert)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Insert the new frame at the specified index within the frame sequence, ensuring precise control over frame arrangement. |
| [replaceFrame(int index, TiffFrame frameToReplace)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Substitute the frame at the designated position with another frame seamlessly, facilitating dynamic frame management within the image sequence. |
| [removeFrame(int index)](#removeFrame-int-) | Effortlessly eliminate the frame identified by its index from the image sequence, streamlining frame management within your application. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Efficiently remove the specified frame from the image sequence, facilitating streamlined frame management within your application. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Conduct a proportional resize operation on the image, preserving its aspect ratio while adjusting its dimensions. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Adjust the width of the image while maintaining its aspect ratio, ensuring proportional resizing for optimal visual presentation. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Conduct a proportional adjustment of the image's height, preserving its aspect ratio for consistent visual integrity. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Perform rotation, flipping, or a combination of both operations exclusively on the active frame. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Execute dithering on the current image to enhance its visual quality and reduce color banding artifacts. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crop the image using a specified rectangular region, allowing precise selection of desired content. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Perform cropping on the image by specifying shifts in the left, right, top, and bottom directions. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Apply binarization to the image using a predefined threshold, converting it into a binary image with distinct foreground and background regions. |
| [binarizeOtsu()](#binarizeOtsu--) | Utilize Otsu thresholding to perform binarization on the image, automatically determining the optimal threshold value based on the image's histogram. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Implement binarization on the image employing Bradley's adaptive thresholding algorithm with integral image thresholding. |
| [grayscale()](#grayscale--) | Convert the image to its grayscale representation, transforming it into a single-channel image where each pixel represents intensity. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Apply gamma correction to the image, adjusting pixel intensities to achieve desired color balance. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Perform gamma correction on the image using individual coefficients for red, green, and blue channels, allowing for fine-tuned adjustments of color balance and contrast. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implement `brightness` adjustment for the image, allowing the modification of overall luminance levels. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Enhance the contrast of the [Image](../../com.aspose.imaging/image) instance, amplifying the differences between its light and dark areas. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filter the content within the specified rectangle, applying a designated image processing filter to enhance or modify the selected region. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Adjust the size of the image based on specified settings, allowing for precise control over dimensions, aspect ratio, and scaling behavior. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Create the GraphicsPath using PathResources from TIFF image
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Draw red line and save the image
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Create rectangular Figure for GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Create GraphicsPath using our Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Set PathResources using GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Save the image
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Initialize a new object of the [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) class, specifying the frame parameter. This constructor facilitates the creation of a TiffImage instance, allowing developers to specify the frame to be loaded or processed, streamlining Tiff image handling tasks within their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The tiff frame to initialize image with. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Create a new instance of the [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) class, providing a list of frames as a parameter. This constructor enables the initialization of a TiffImage object with multiple frames, facilitating efficient handling and processing of TIFF image sequences within software applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frames. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieve the file format value associated with the image. This property serves as a critical aspect of image metadata retrieval, allowing software applications to identify and interpret the format of the image data efficiently.

**Returns:**
long - a value of file format
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Indicate if components necessitate premultiplication, ensuring efficient handling of visual elements. Enhance rendering processes by toggling this property, streamlining graphic workflows for optimized performance.

**Returns:**
boolean - `true` if components must be premultiplied; otherwise, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Indicate if components necessitate premultiplication, ensuring efficient handling of visual elements. Enhance rendering processes by toggling this property, streamlining graphic workflows for optimized performance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if components must be premultiplied; otherwise, `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Save pixels for the whole image.
    image.savePixels(image.getBounds(), colors);

    // The pixels are stored in the original image in the non-premultiplied form.
    // Need to specify the corresponding option explicitly to obtain premultiplied color components.
    // The premultiplied color components are calculated by the formulas:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//The output will look like this:
//Original color: Color [A=127, R=255, G=0, B=0]
//Premultiplied color: Color [A=127, R=127, G=0, B=0]
//Original color: Color [A=127, R=0, G=255, B=0]
//Premultiplied color: Color [A=127, R=0, G=127, B=0]
//Original color: Color [A=127, R=0, G=0, B=255]
//Premultiplied color: Color [A=127, R=0, G=0, B=127]
//Original color: Color [A=127, R=255, G=255, B=0]
//Premultiplied color: Color [A=127, R=127, G=127, B=0]
//Original color: Color [A=127, R=255, G=0, B=255]
//Premultiplied color: Color [A=127, R=127, G=0, B=127]
//Original color: Color [A=127, R=0, G=255, B=255]
//Premultiplied color: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


Toggle the byte order for TIFF files seamlessly, ensuring precise control over data interpretation. Empower your applications with the flexibility to adapt to diverse file specifications, enhancing compatibility and efficiency in data processing.

**Returns:**
int - The tiff byte order.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


Toggle the byte order for TIFF files seamlessly, ensuring precise control over data interpretation. Empower your applications with the flexibility to adapt to diverse file specifications, enhancing compatibility and efficiency in data processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The tiff byte order. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Retrieve the horizontal resolution of the specified [Image](../../com.aspose.imaging/image) in pixels per inch, facilitating precise adjustment and rendering capabilities. Access essential image metadata effortlessly, empowering streamlined image processing workflows for enhanced user experiences.

**Returns:**
double - The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Get horizontal and vertical resolution of the TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 96.0
// The vertical resolution, in pixels per inch: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Modifies the horizontal resolution of the specified [Image](../../com.aspose.imaging/image) in pixels per inch, facilitating precise adjustment and rendering capabilities. Access essential image metadata effortlessly, empowering streamlined image processing workflows for enhanced user experiences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Access the vertical resolution of the designated [Image](../../com.aspose.imaging/image) in pixels per inch, enabling precise adjustments and rendering optimizations. Utilize essential image data effortlessly to streamline image processing workflows, ensuring superior quality and performance in your applications.

**Returns:**
double - The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Get horizontal and vertical resolution of the TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 96.0
// The vertical resolution, in pixels per inch: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Access the vertical resolution of the designated [Image](../../com.aspose.imaging/image) in pixels per inch, enabling precise adjustments and rendering optimizations. Utilize essential image data effortlessly to streamline image processing workflows, ensuring superior quality and performance in your applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Manage the active frame seamlessly, facilitating dynamic navigation and manipulation within the designated context. Empower your application to interact efficiently with multimedia content, enhancing user engagement and productivity.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // This is Font and Brush for drawing text on individual frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Create 5 frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Create a PNG image and draw the number of page on it.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Create a frame based on the PNG image.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Add the frame to the TIFF image.
        tiffImage.addFrame(frame);
    }

    // The image was created with a single default frame. Let's remove it.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Don't forget to dispose the frame if you won't add it to some other TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Manage the active frame seamlessly, facilitating dynamic navigation and manipulation within the designated context. Empower your application to interact efficiently with multimedia content, enhancing user engagement and productivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Active frame. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // This is Font and Brush for drawing text on individual frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Create 5 frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Create a PNG image and draw the number of page on it.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Create a frame based on the PNG image.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Add the frame to the TIFF image.
        tiffImage.addFrame(frame);
    }

    // The image was created with a single default frame. Let's remove it.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Don't forget to dispose the frame if you won't add it to some other TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


Retrieve an array of [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) instances, enabling comprehensive access and manipulation of individual frames within the TIFF image. Harness the power of this array to streamline image processing workflows, ensuring precise control and optimization of visual content.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] - the [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) array.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // This is Font and Brush for drawing text on individual frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Create 5 frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Create a PNG image and draw the number of page on it.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Create a frame based on the PNG image.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Add the frame to the TIFF image.
        tiffImage.addFrame(frame);
    }

    // The image was created with a single default frame. Let's remove it.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Don't forget to dispose the frame if you won't add it to some other TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Retrieve the total count of pages within the specified document, facilitating efficient navigation and management of multipage content. Incorporate this functionality to enhance user experience, enabling seamless access to comprehensive document structures.

**Returns:**
int - the page count.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Access the pages of the document seamlessly, enabling dynamic navigation and manipulation within the content structure. Empower your application with efficient access to individual pages, facilitating streamlined document processing and enhanced user interaction.

**Returns:**
com.aspose.imaging.Image[] - the pages.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determine whether the image has an alpha channel, providing crucial information for rendering and compositing operations. Integrate this feature to optimize visual processing workflows, ensuring accurate representation and manipulation of transparent elements.

**Returns:**
boolean - `true` if there is an alpha channel.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // If the active TIFF frame has alpha channel, then the entire TIFF image is considered to have alpha channel.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Removes this image instance metadata by setting this `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) value to `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Retrieve options derived from the original file settings, facilitating seamless preservation of key parameters such as bit-depth and other essential attributes of the original image. Utilize this method to maintain fidelity and consistency in image processing tasks, ensuring optimal results without unnecessary alterations. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorporate a new page into the existing image seamlessly, expanding its content and versatility. Utilize this method to enhance document composition and management, empowering efficient handling of multipage images within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The page to add. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Implement the AlignResolutions helper method to synchronize horizontal and vertical resolutions, ensuring uniformity in image dimensions. This functionality facilitates streamlined image processing workflows by harmonizing resolution parameters, optimizing visual quality and consistency across various platforms and devices.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Establishes the resolution for the specified [RasterImage](../../com.aspose.imaging/rasterimage), enabling precise control over image rendering and display properties. Integrate this functionality to optimize visual output and ensure compatibility with diverse output devices and platforms, enhancing the overall user experience.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | The vertical resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Get horizontal and vertical resolution of the TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 96.0
// The vertical resolution, in pixels per inch: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Utilize the NormalizeAngle method specifically designed for scanned text documents to rectify skewed scans, ensuring accurate alignment. Seamlessly integrate this functionality into your text processing workflows to enhance document readability and quality, improving overall efficiency in text recognition and analysis tasks. This method uses [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) and [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) methods.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizeProportionally | boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color of the background. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Incorporate the specified frame seamlessly into the image, expanding its content and versatility. Utilize this method to enhance image composition and management, empowering efficient handling of multi-frame images within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame to add. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // This is Font and Brush for drawing text on individual frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Create 5 frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Create a PNG image and draw the number of page on it.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Create a frame based on the PNG image.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Add the frame to the TIFF image.
        tiffImage.addFrame(frame);
    }

    // The image was created with a single default frame. Let's remove it.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Don't forget to dispose the frame if you won't add it to some other TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Add the frames from the specified image seamlessly into the current frame, consolidating their content and enhancing compositional flexibility. Integrate this method to streamline frame management and manipulation within your application, facilitating efficient handling of multi-frame images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | The source image. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Integrate the array of frames seamlessly into the image, enriching its content and versatility. Utilize this method to enhance image composition and management, enabling efficient handling of multi-frame images within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frames array to add |

### insertFrame(int index, TiffFrame frameToInsert) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frameToInsert)
```


Insert the new frame at the specified index within the frame sequence, ensuring precise control over frame arrangement. Employ this method to manage frame sequences effectively, facilitating dynamic manipulation and organization of image content within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new frame in list of frames |
| frameToInsert | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame To Insert. |

### replaceFrame(int index, TiffFrame frameToReplace) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame frameToReplace)
```


Substitute the frame at the designated position with another frame seamlessly, facilitating dynamic frame management within the image sequence. Integrate this method to enhance flexibility and precision in frame manipulation, ensuring optimal organization and presentation of image content within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero based frame position. |
| frameToReplace | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame to replace.

Note: do not forget to dispose/close the frame if you will not add it to some other TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Effortlessly eliminate the frame identified by its index from the image sequence, streamlining frame management within your application. Integrate this functionality to enhance efficiency and precision in frame manipulation, facilitating seamless organization and presentation of image content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of frame to be removed.

--------------------

Note: do not forget to Dispose the frame if you will not add it to some other TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // This is Font and Brush for drawing text on individual frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Create 5 frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Create a PNG image and draw the number of page on it.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Create a frame based on the PNG image.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Add the frame to the TIFF image.
        tiffImage.addFrame(frame);
    }

    // The image was created with a single default frame. Let's remove it.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Don't forget to dispose the frame if you won't add it to some other TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Efficiently remove the specified frame from the image sequence, facilitating streamlined frame management within your application. Integrate this functionality to enhance precision and flexibility in frame manipulation, ensuring seamless organization and presentation of image content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | The frame to remove.

--------------------

Note: do not forget to Dispose the frame if you will not add it to some other TiffImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Conduct a proportional resize operation on the image, preserving its aspect ratio while adjusting its dimensions. Employ this method to dynamically scale images within your application, ensuring consistent visual representation of content integrity. The proportional resize will resize each frame according to the ratio of `newWidth`/width and `newHeight`/height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Adjust the width of the image while maintaining its aspect ratio, ensuring proportional resizing for optimal visual presentation. Utilize this method to dynamically scale images within your application, facilitating consistent and aesthetically pleasing rendering across various display contexts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| resizeType | int | Type of the resize. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
This example loads a TIFF image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Conduct a proportional adjustment of the image's height, preserving its aspect ratio for consistent visual integrity. Employ this method to dynamically resize images within your application, ensuring optimal display across diverse platforms and devices without compromising content quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | int | The new height. |
| resizeType | int | Type of the resize. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
This example loads a TIFF image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Perform rotation, flipping, or a combination of both operations exclusively on the active frame. This method allows precise manipulation of individual frames within the image sequence, enhancing flexibility in image editing and composition within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotation and flipping type. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// This is a helper class.
class Utils {
    // Gets a string representation of the rotate flip type.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Here is the main example
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotate, flip and save to the output file.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Execute dithering on the current image to enhance its visual quality and reduce color banding artifacts. Integrate this method into your image processing workflow to ensure smoother transitions between colors, resulting in improved overall image appearance and clarity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | The dithering method. |
| bitsCount | int | The final bits count for dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The custom palette for dithering. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Perform threshold dithering using 4-bit color palette which contains 16 colors.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Perform floyd dithering using 1-bit color palette which contains only 2 colors - black and white.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Crop the image using a specified rectangular region, allowing precise selection of desired content. Integrate this method into your image processing workflow to efficiently remove unwanted areas and focus on essential details, enhancing the overall clarity and composition of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |


**Example: The following example crops a TIFF image.**
The following example crops a TIFF image. The cropping area is be specified via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Save the cropped image to PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Perform cropping on the image by specifying shifts in the left, right, top, and bottom directions. This method enables precise selection of the desired portion of the image, facilitating efficient removal of unwanted areas and focusing on essential content. Integrate this functionality into your image processing pipeline to enhance clarity and composition as needed within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | int | The left shift. |
| rightShift | int | The right shift. |
| topShift | int | The top shift. |
| bottomShift | int | The bottom shift. |


**Example: The following example crops a TIFF image.**
The following example crops a TIFF image. The cropping area is specified via Left, Top, Right, Bottom margins.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Crop again. Set a margin of 10% of the image size.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Save the cropped image to PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Apply binarization to the image using a predefined threshold, converting it into a binary image with distinct foreground and background regions. Incorporate this method into your image processing workflow to facilitate segmentation and feature extraction tasks, enhancing the accuracy and efficiency of image analysis within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
The following example binarizes a TIFF image with the predefined threshold. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Utilize Otsu thresholding to perform binarization on the image, automatically determining the optimal threshold value based on the image's histogram. Integrate this method into your image processing workflow to achieve effective segmentation and feature extraction, enhancing the accuracy and reliability of image analysis tasks within your application.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
The following example binarizes a TIFF image with Otsu thresholding. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarize the image with Otsu thresholding.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Implement binarization on the image employing Bradley's adaptive thresholding algorithm with integral image thresholding. This approach dynamically computes local thresholds based on the image's neighborhood, enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | int | The size of s x s window of pixels centered around this pixel |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarize the image with a brightness difference of 5. The brightness is a difference between a pixel and the average of an 10 x 10 window of pixels centered around this pixel.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Convert the image to its grayscale representation, transforming it into a single-channel image where each pixel represents intensity. Integrate this method into your image processing pipeline to simplify analysis and enhance compatibility with grayscale-based algorithms, facilitating various computer vision and image analysis tasks within your application.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
The following example transforms a colored TIFF image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Apply gamma correction to the image, adjusting pixel intensities to achieve desired color balance. Incorporate this method into your image processing workflow to enhance visual quality and improve the accuracy of subsequent analysis or display tasks within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | Gamma for red, green and blue channels coefficient |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Set gamma coefficient for red, green and blue channels.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Perform gamma correction on the image using individual coefficients for red, green, and blue channels, allowing for fine-tuned adjustments of color balance and contrast. Integrate this method into your image processing pipeline to achieve precise control over color rendering and enhance visual fidelity within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | float | Gamma for red channel coefficient |
| gammaGreen | float | Gamma for green channel coefficient |
| gammaBlue | float | Gamma for blue channel coefficient |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Set individual gamma coefficients for red, green and blue channels.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implement `brightness` adjustment for the image, allowing the modification of overall luminance levels. Incorporate this method into your image processing workflow to enhance visibility and improve the visual quality of images within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | Brightness value. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Enhance the contrast of the [Image](../../com.aspose.imaging/image) instance, amplifying the differences between its light and dark areas. Integrate this functionality to improve the visual clarity and overall quality of the image within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contrast | float | Contrast value (in range [-100; 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filter the content within the specified rectangle, applying a designated image processing filter to enhance or modify the selected region. Integrate this method into your image manipulation workflow to achieve targeted enhancements or transformations within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | The options. |


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Apply a median filter with a rectangle size of 5 to the entire image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Apply a bilateral smoothing filter with a kernel size of 5 to the entire image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Apply a Gaussian blur filter with a radius of 5 and a sigma value of 4.0 to the entire image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Apply a Gauss-Wiener filter with a radius of 5 and a smooth value of 4.0 to the entire image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Apply a motion wiener filter with a length of 5, a smooth value of 4.0 and an angle of 90.0 degrees to the entire image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Apply a sharpen filter with a kernel size of 5 and a sigma value of 4.0 to the entire image.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Adjust the size of the image based on specified settings, allowing for precise control over dimensions, aspect ratio, and scaling behavior. Integrate this method into your image processing workflow to achieve customized resizing operations tailored to the specific requirements of your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | The resize settings. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

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

// The euclidian method
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Scale down by 2 times using adaptive resampling.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Save to PNG
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

