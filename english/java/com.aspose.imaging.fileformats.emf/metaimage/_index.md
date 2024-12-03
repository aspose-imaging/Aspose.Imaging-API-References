---
title: MetaImage
second_title: Aspose.Imaging for Java API Reference
description: Base class for Meta object classes
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Base class for Meta object classes
## Constructors

| Constructor | Description |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRecords()](#getRecords--) | Gets the records. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Sets the records. |
| [getUsedFonts()](#getUsedFonts--) | Returns the list of font which used inside metafile. |
| [getMissedFonts()](#getMissedFonts--) | Returns the list of fonts which used inside metafile but not found. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Resizes the canvas. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Gets the records.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Cache data to load all records.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // The key is a record type, the value is number of records of that type in the WMF image.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Gather statistics
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Print statistics
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Align output with spaces
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//The output may look like this:
//The total number of records: 1188
//Record Type                              Count
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Sets the records.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | The records. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Returns the list of font which used inside metafile.

**Returns:**
java.lang.String[] - The font list

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// To make all fonts inaccessible
String[] fontDirectories = com.aspose.imaging.FontSettings.getFontsFolders();
com.aspose.imaging.FontSettings.setFontsFolder("empty");
try {
    for (String file : files) {
        System.out.println("Testing the file: " + file);
        final com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) Image.load(dir + file);
        try {
            System.out.println("Used fonts:");
            String[] used = image.getUsedFonts();
            for (String it : used) {
                System.out.println("Used font: " + it);
            }

            System.out.println("Missed fonts:");
            String[] missed = image.getMissedFonts();
            for (String it : missed) {
                System.out.println("Missed font: " + it);
            }
        } finally {
            image.close();
        }
    }
} finally {
    com.aspose.imaging.FontSettings.setFontsFolders(fontDirectories, true);
}

// The STDOUT log may look like this:
//        Testing the file: TestWmfText.wmf
//        Used fonts:
//        Used font: Garamond
//        Used font: Arial
//        Used font: Bookman Old Style
//        Used font: Comic Sans MS
//        Used font: Courier
//        Used font: Courier New
//        Used font: Impact
//        Used font: Modern
//        Used font: MS Sans Serif
//        Used font: MS Serif
//        Used font: Small Fonts
//        Used font: Symbol
//        Used font: Tahoma
//        Used font: Times New Roman
//        Used font: Verdana
//        Used font: Wingdings
//        Missed fonts:
//        Missed font: Garamond
//        Missed font: Arial
//        Missed font: Bookman Old Style
//        Missed font: Comic Sans MS
//        Missed font: Courier
//        Missed font: Courier New
//        Missed font: Impact
//        Missed font: Modern
//        Missed font: MS Sans Serif
//        Missed font: MS Serif
//        Missed font: Small Fonts
//        Missed font: Symbol
//        Missed font: Tahoma
//        Missed font: Verdana
//        Missed font: Wingdings
//        Testing the file: TestEmfFonts.emf
//        Used fonts:
//        Used font: Arial
//        Used font: Verdana
//        Used font: Times New Roman
//        Used font: Symbol
//        Missed fonts:
//        Missed font: Arial
//        Missed font: Verdana
//        Missed font: Symbol
//        Testing the file: TestEmfPlusFonts.emf
//        Used fonts:
//        Used font: MICROSOFT SANS SERIF
//        Missed fonts:
//        Missed font: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Returns the list of fonts which used inside metafile but not found.

**Returns:**
java.lang.String[] - The font list

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// To make all fonts inaccessible
String[] fontDirectories = com.aspose.imaging.FontSettings.getFontsFolders();
com.aspose.imaging.FontSettings.setFontsFolder("empty");
try {
    for (String file : files) {
        System.out.println("Testing the file: " + file);
        final com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) Image.load(dir + file);
        try {
            System.out.println("Used fonts:");
            String[] used = image.getUsedFonts();
            for (String it : used) {
                System.out.println("Used font: " + it);
            }

            System.out.println("Missed fonts:");
            String[] missed = image.getMissedFonts();
            for (String it : missed) {
                System.out.println("Missed font: " + it);
            }
        } finally {
            image.close();
        }
    }
} finally {
    com.aspose.imaging.FontSettings.setFontsFolders(fontDirectories, true);
}

// The STDOUT log may look like this:
//        Testing the file: TestWmfText.wmf
//        Used fonts:
//        Used font: Garamond
//        Used font: Arial
//        Used font: Bookman Old Style
//        Used font: Comic Sans MS
//        Used font: Courier
//        Used font: Courier New
//        Used font: Impact
//        Used font: Modern
//        Used font: MS Sans Serif
//        Used font: MS Serif
//        Used font: Small Fonts
//        Used font: Symbol
//        Used font: Tahoma
//        Used font: Times New Roman
//        Used font: Verdana
//        Used font: Wingdings
//        Missed fonts:
//        Missed font: Garamond
//        Missed font: Arial
//        Missed font: Bookman Old Style
//        Missed font: Comic Sans MS
//        Missed font: Courier
//        Missed font: Courier New
//        Missed font: Impact
//        Missed font: Modern
//        Missed font: MS Sans Serif
//        Missed font: MS Serif
//        Missed font: Small Fonts
//        Missed font: Symbol
//        Missed font: Tahoma
//        Missed font: Verdana
//        Missed font: Wingdings
//        Testing the file: TestEmfFonts.emf
//        Used fonts:
//        Used font: Arial
//        Used font: Verdana
//        Used font: Times New Roman
//        Used font: Symbol
//        Missed fonts:
//        Missed font: Arial
//        Missed font: Verdana
//        Missed font: Symbol
//        Testing the file: TestEmfPlusFonts.emf
//        Used fonts:
//        Used font: MICROSOFT SANS SERIF
//        Missed fonts:
//        Missed font: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Resizes the canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The new rectangle. |


**Example: The following example shows how to add a border with the specified margins around a metafile (WMF and EMF).**

``` java
String baseFolder = "c:\\temp\\";
int borderLeft = 50;
int borderTop = 50;
int borderRight = 50;
int borderBottom = 50;

String[] files = new String[]{"image1.emf", "image2.wmf"};
for (String fileName : files) {
    String inputFile = baseFolder + fileName;
    String outputFile = baseFolder + "Border_" + fileName;
    com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) com.aspose.imaging.Image.load(inputFile);
    try {
        image.resizeCanvas(new com.aspose.imaging.Rectangle(-borderLeft, -borderTop, image.getWidth() + borderLeft + borderRight, image.getHeight() + borderTop + borderBottom));
        image.save(outputFile);
    } finally {
        image.close();
    }
}
```

