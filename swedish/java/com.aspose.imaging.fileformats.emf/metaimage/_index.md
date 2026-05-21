---
title: "MetaImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Basklass för Meta-objektklasser"
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Basklass för Meta-objektklasser
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRecords()](#getRecords--) | Hämtar posterna. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Ställer in posterna. |
| [getUsedFonts()](#getUsedFonts--) | Returnerar listan med teckensnitt som används i metafilen. |
| [getMissedFonts()](#getMissedFonts--) | Returnerar listan med teckensnitt som används i metafilen men inte hittades. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ändrar storlek på canvasen. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Hämtar posterna.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att ladda alla typer av bilder, inklusive WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Cacha data för att ladda alla poster.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Nyckeln är en posttyp, värdet är antalet poster av den typen i WMF-bilden.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Samla statistik
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

    // Skriv ut statistik
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Justera utdata med mellanslag
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//Utdata kan se ut så här:
//Det totala antalet poster: 1188
//Posttyp                              Antal
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


Ställer in posterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Posterna. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Returnerar listan med teckensnitt som används i metafilen.

**Returns:**
java.lang.String[] - Teckensnittlistan

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// För att göra alla teckensnitt otillgängliga
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

// STDOUT‑loggen kan se ut så här:
//        Testar filen: TestWmfText.wmf
//        Använda teckensnitt:
//        Använt teckensnitt: Garamond
//        Använt teckensnitt: Arial
//        Använt teckensnitt: Bookman Old Style
//        Använt teckensnitt: Comic Sans MS
//        Använt teckensnitt: Courier
//        Använt teckensnitt: Courier New
//        Använt teckensnitt: Impact
//        Använt teckensnitt: Modern
//        Använt teckensnitt: MS Sans Serif
//        Använt teckensnitt: MS Serif
//        Använt teckensnitt: Small Fonts
//        Använt teckensnitt: Symbol
//        Använt teckensnitt: Tahoma
//        Använt teckensnitt: Times New Roman
//        Använt teckensnitt: Verdana
//        Använt teckensnitt: Wingdings
//        Saknade teckensnitt:
//        Saknat teckensnitt: Garamond
//        Saknat teckensnitt: Arial
//        Saknat teckensnitt: Bookman Old Style
//        Saknat teckensnitt: Comic Sans MS
//        Saknat teckensnitt: Courier
//        Saknat teckensnitt: Courier New
//        Saknat teckensnitt: Impact
//        Saknat teckensnitt: Modern
//        Saknat teckensnitt: MS Sans Serif
//        Saknat teckensnitt: MS Serif
//        Saknat teckensnitt: Small Fonts
//        Saknat teckensnitt: Symbol
//        Saknat teckensnitt: Tahoma
//        Saknat teckensnitt: Verdana
//        Saknat teckensnitt: Wingdings
//        Testar filen: TestEmfFonts.emf
//        Använda teckensnitt:
//        Använt teckensnitt: Arial
//        Använt teckensnitt: Verdana
//        Använt teckensnitt: Times New Roman
//        Använt teckensnitt: Symbol
//        Saknade teckensnitt:
//        Saknat teckensnitt: Arial
//        Saknat teckensnitt: Verdana
//        Saknat teckensnitt: Symbol
//        Testar filen: TestEmfPlusFonts.emf
//        Använda teckensnitt:
//        Använt teckensnitt: MICROSOFT SANS SERIF
//        Saknade teckensnitt:
//        Saknat teckensnitt: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Returnerar listan med teckensnitt som används i metafilen men inte hittades.

**Returns:**
java.lang.String[] - Teckensnittlistan

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// För att göra alla teckensnitt otillgängliga
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

// STDOUT‑loggen kan se ut så här:
//        Testar filen: TestWmfText.wmf
//        Använda teckensnitt:
//        Använt teckensnitt: Garamond
//        Använt teckensnitt: Arial
//        Använt teckensnitt: Bookman Old Style
//        Använt teckensnitt: Comic Sans MS
//        Använt teckensnitt: Courier
//        Använt teckensnitt: Courier New
//        Använt teckensnitt: Impact
//        Använt teckensnitt: Modern
//        Använt teckensnitt: MS Sans Serif
//        Använt teckensnitt: MS Serif
//        Använt teckensnitt: Small Fonts
//        Använt teckensnitt: Symbol
//        Använt teckensnitt: Tahoma
//        Använt teckensnitt: Times New Roman
//        Använt teckensnitt: Verdana
//        Använt teckensnitt: Wingdings
//        Saknade teckensnitt:
//        Saknat teckensnitt: Garamond
//        Saknat teckensnitt: Arial
//        Saknat teckensnitt: Bookman Old Style
//        Saknat teckensnitt: Comic Sans MS
//        Saknat teckensnitt: Courier
//        Saknat teckensnitt: Courier New
//        Saknat teckensnitt: Impact
//        Saknat teckensnitt: Modern
//        Saknat teckensnitt: MS Sans Serif
//        Saknat teckensnitt: MS Serif
//        Saknat teckensnitt: Small Fonts
//        Saknat teckensnitt: Symbol
//        Saknat teckensnitt: Tahoma
//        Saknat teckensnitt: Verdana
//        Saknat teckensnitt: Wingdings
//        Testar filen: TestEmfFonts.emf
//        Använda teckensnitt:
//        Använt teckensnitt: Arial
//        Använt teckensnitt: Verdana
//        Använt teckensnitt: Times New Roman
//        Använt teckensnitt: Symbol
//        Saknade teckensnitt:
//        Saknat teckensnitt: Arial
//        Saknat teckensnitt: Verdana
//        Saknat teckensnitt: Symbol
//        Testar filen: TestEmfPlusFonts.emf
//        Använda teckensnitt:
//        Använt teckensnitt: MICROSOFT SANS SERIF
//        Saknade teckensnitt:
//        Saknat teckensnitt: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Ändrar storlek på canvasen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den nya rektangeln. |


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

