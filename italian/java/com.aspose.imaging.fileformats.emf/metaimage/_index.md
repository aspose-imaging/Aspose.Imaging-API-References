---
title: "MetaImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe base per le classi di oggetti Meta"
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Classe base per le classi di oggetti Meta
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRecords()](#getRecords--) | Ottiene i record. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Imposta i record. |
| [getUsedFonts()](#getUsedFonts--) | Restituisce l'elenco dei font utilizzati all'interno del metafile. |
| [getMissedFonts()](#getMissedFonts--) | Restituisce l'elenco dei font utilizzati all'interno del metafile ma non trovati. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ridimensiona la tela. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Ottiene i record.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Utilizzare Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Memorizza nella cache i dati per caricare tutti i record.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // La chiave è un tipo di record, il valore è il numero di record di quel tipo nell'immagine WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Raccogli statistiche
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

    // Stampa statistiche
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Allinea l'output con spazi
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//L'output potrebbe apparire così:
//Il numero totale di record: 1188
//Tipo di Record                              Conteggio
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


Imposta i record.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | I record. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Restituisce l'elenco dei font utilizzati all'interno del metafile.

**Returns:**
java.lang.String[] - L'elenco dei caratteri

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Per rendere tutti i caratteri inaccessibili
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

// Il registro STDOUT può apparire così:
//        Test del file: TestWmfText.wmf
//        Caratteri usati:
//        Carattere usato: Garamond
//        Carattere usato: Arial
//        Carattere usato: Bookman Old Style
//        Carattere usato: Comic Sans MS
//        Carattere usato: Courier
//        Carattere usato: Courier New
//        Carattere usato: Impact
//        Carattere usato: Modern
//        Carattere usato: MS Sans Serif
//        Carattere usato: MS Serif
//        Carattere usato: Small Fonts
//        Carattere usato: Symbol
//        Carattere usato: Tahoma
//        Carattere usato: Times New Roman
//        Carattere usato: Verdana
//        Carattere usato: Wingdings
//        Font mancanti:
//        Font mancante: Garamond
//        Font mancante: Arial
//        Font mancante: Bookman Old Style
//        Font mancante: Comic Sans MS
//        Font mancante: Courier
//        Font mancante: Courier New
//        Font mancante: Impact
//        Font mancante: Modern
//        Font mancante: MS Sans Serif
//        Font mancante: MS Serif
//        Font mancante: Small Fonts
//        Font mancante: Symbol
//        Font mancante: Tahoma
//        Font mancante: Verdana
//        Font mancante: Wingdings
//        Test del file: TestEmfFonts.emf
//        Caratteri usati:
//        Carattere usato: Arial
//        Carattere usato: Verdana
//        Carattere usato: Times New Roman
//        Carattere usato: Symbol
//        Font mancanti:
//        Font mancante: Arial
//        Font mancante: Verdana
//        Font mancante: Symbol
//        Test del file: TestEmfPlusFonts.emf
//        Caratteri usati:
//        Carattere usato: MICROSOFT SANS SERIF
//        Font mancanti:
//        Font mancante: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Restituisce l'elenco dei font utilizzati all'interno del metafile ma non trovati.

**Returns:**
java.lang.String[] - L'elenco dei caratteri

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Per rendere tutti i caratteri inaccessibili
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

// Il registro STDOUT può apparire così:
//        Test del file: TestWmfText.wmf
//        Caratteri usati:
//        Carattere usato: Garamond
//        Carattere usato: Arial
//        Carattere usato: Bookman Old Style
//        Carattere usato: Comic Sans MS
//        Carattere usato: Courier
//        Carattere usato: Courier New
//        Carattere usato: Impact
//        Carattere usato: Modern
//        Carattere usato: MS Sans Serif
//        Carattere usato: MS Serif
//        Carattere usato: Small Fonts
//        Carattere usato: Symbol
//        Carattere usato: Tahoma
//        Carattere usato: Times New Roman
//        Carattere usato: Verdana
//        Carattere usato: Wingdings
//        Font mancanti:
//        Font mancante: Garamond
//        Font mancante: Arial
//        Font mancante: Bookman Old Style
//        Font mancante: Comic Sans MS
//        Font mancante: Courier
//        Font mancante: Courier New
//        Font mancante: Impact
//        Font mancante: Modern
//        Font mancante: MS Sans Serif
//        Font mancante: MS Serif
//        Font mancante: Small Fonts
//        Font mancante: Symbol
//        Font mancante: Tahoma
//        Font mancante: Verdana
//        Font mancante: Wingdings
//        Test del file: TestEmfFonts.emf
//        Caratteri usati:
//        Carattere usato: Arial
//        Carattere usato: Verdana
//        Carattere usato: Times New Roman
//        Carattere usato: Symbol
//        Font mancanti:
//        Font mancante: Arial
//        Font mancante: Verdana
//        Font mancante: Symbol
//        Test del file: TestEmfPlusFonts.emf
//        Caratteri usati:
//        Carattere usato: MICROSOFT SANS SERIF
//        Font mancanti:
//        Font mancante: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Ridimensiona la tela.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il nuovo rettangolo. |


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

