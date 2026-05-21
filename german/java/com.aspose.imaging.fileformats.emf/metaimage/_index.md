---
title: "MetaImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Basisklasse für Meta-Objektklassen"
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Basisklasse für Meta-Objektklassen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRecords()](#getRecords--) | Liest die Datensätze. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Setzt die Datensätze. |
| [getUsedFonts()](#getUsedFonts--) | Gibt die Liste der Schriftarten zurück, die im Metafile verwendet werden. |
| [getMissedFonts()](#getMissedFonts--) | Gibt die Liste der Schriftarten zurück, die im Metafile verwendet werden, aber nicht gefunden wurden. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ändert die Größe der Leinwand. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Liest die Datensätze.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen, einschließlich WMF, zu laden.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Daten im Cache speichern, um alle Datensätze zu laden.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Der Schlüssel ist ein Datensatztyp, der Wert ist die Anzahl der Datensätze dieses Typs im WMF‑Bild.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Statistiken sammeln
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

    // Statistiken ausgeben
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Ausgabe mit Leerzeichen ausrichten
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Datensätze: 1188
//Datensatztyp                              Anzahl
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


Setzt die Datensätze.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Die Datensätze. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Gibt die Liste der Schriftarten zurück, die im Metafile verwendet werden.

**Returns:**
java.lang.String[] - Die Schriftartenliste

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Um alle Schriftarten unzugänglich zu machen
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

// Das STDOUT-Protokoll kann folgendermaßen aussehen:
//        Testen der Datei: TestWmfText.wmf
//        Verwendete Schriftarten:
//        Verwendete Schriftart: Garamond
//        Verwendete Schriftart: Arial
//        Verwendete Schriftart: Bookman Old Style
//        Verwendete Schriftart: Comic Sans MS
//        Verwendete Schriftart: Courier
//        Verwendete Schriftart: Courier New
//        Verwendete Schriftart: Impact
//        Verwendete Schriftart: Modern
//        Verwendete Schriftart: MS Sans Serif
//        Verwendete Schriftart: MS Serif
//        Verwendete Schriftart: Small Fonts
//        Verwendete Schriftart: Symbol
//        Verwendete Schriftart: Tahoma
//        Verwendete Schriftart: Times New Roman
//        Verwendete Schriftart: Verdana
//        Verwendete Schriftart: Wingdings
//        Fehlende Schriftarten:
//        Fehlende Schriftart: Garamond
//        Fehlende Schriftart: Arial
//        Fehlende Schriftart: Bookman Old Style
//        Fehlende Schriftart: Comic Sans MS
//        Fehlende Schriftart: Courier
//        Fehlende Schriftart: Courier New
//        Fehlende Schriftart: Impact
//        Fehlende Schriftart: Modern
//        Fehlende Schriftart: MS Sans Serif
//        Fehlende Schriftart: MS Serif
//        Fehlende Schriftart: Small Fonts
//        Fehlende Schriftart: Symbol
//        Fehlende Schriftart: Tahoma
//        Fehlende Schriftart: Verdana
//        Fehlende Schriftart: Wingdings
//        Testen der Datei: TestEmfFonts.emf
//        Verwendete Schriftarten:
//        Verwendete Schriftart: Arial
//        Verwendete Schriftart: Verdana
//        Verwendete Schriftart: Times New Roman
//        Verwendete Schriftart: Symbol
//        Fehlende Schriftarten:
//        Fehlende Schriftart: Arial
//        Fehlende Schriftart: Verdana
//        Fehlende Schriftart: Symbol
//        Testen der Datei: TestEmfPlusFonts.emf
//        Verwendete Schriftarten:
//        Verwendete Schriftart: MICROSOFT SANS SERIF
//        Fehlende Schriftarten:
//        Fehlende Schriftart: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Gibt die Liste der Schriftarten zurück, die im Metafile verwendet werden, aber nicht gefunden wurden.

**Returns:**
java.lang.String[] - Die Schriftartenliste

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Um alle Schriftarten unzugänglich zu machen
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

// Das STDOUT-Protokoll kann folgendermaßen aussehen:
//        Testen der Datei: TestWmfText.wmf
//        Verwendete Schriftarten:
//        Verwendete Schriftart: Garamond
//        Verwendete Schriftart: Arial
//        Verwendete Schriftart: Bookman Old Style
//        Verwendete Schriftart: Comic Sans MS
//        Verwendete Schriftart: Courier
//        Verwendete Schriftart: Courier New
//        Verwendete Schriftart: Impact
//        Verwendete Schriftart: Modern
//        Verwendete Schriftart: MS Sans Serif
//        Verwendete Schriftart: MS Serif
//        Verwendete Schriftart: Small Fonts
//        Verwendete Schriftart: Symbol
//        Verwendete Schriftart: Tahoma
//        Verwendete Schriftart: Times New Roman
//        Verwendete Schriftart: Verdana
//        Verwendete Schriftart: Wingdings
//        Fehlende Schriftarten:
//        Fehlende Schriftart: Garamond
//        Fehlende Schriftart: Arial
//        Fehlende Schriftart: Bookman Old Style
//        Fehlende Schriftart: Comic Sans MS
//        Fehlende Schriftart: Courier
//        Fehlende Schriftart: Courier New
//        Fehlende Schriftart: Impact
//        Fehlende Schriftart: Modern
//        Fehlende Schriftart: MS Sans Serif
//        Fehlende Schriftart: MS Serif
//        Fehlende Schriftart: Small Fonts
//        Fehlende Schriftart: Symbol
//        Fehlende Schriftart: Tahoma
//        Fehlende Schriftart: Verdana
//        Fehlende Schriftart: Wingdings
//        Testen der Datei: TestEmfFonts.emf
//        Verwendete Schriftarten:
//        Verwendete Schriftart: Arial
//        Verwendete Schriftart: Verdana
//        Verwendete Schriftart: Times New Roman
//        Verwendete Schriftart: Symbol
//        Fehlende Schriftarten:
//        Fehlende Schriftart: Arial
//        Fehlende Schriftart: Verdana
//        Fehlende Schriftart: Symbol
//        Testen der Datei: TestEmfPlusFonts.emf
//        Verwendete Schriftarten:
//        Verwendete Schriftart: MICROSOFT SANS SERIF
//        Fehlende Schriftarten:
//        Fehlende Schriftart: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Ändert die Größe der Leinwand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das neue Rechteck. |


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

