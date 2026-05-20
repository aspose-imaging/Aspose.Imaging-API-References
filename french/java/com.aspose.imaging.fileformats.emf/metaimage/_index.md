---
title: "MetaImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe de base pour les classes d'objets Meta"
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Classe de base pour les classes d'objets Meta
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRecords()](#getRecords--) | Obtient les enregistrements. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Définit les enregistrements. |
| [getUsedFonts()](#getUsedFonts--) | Renvoie la liste des polices utilisées dans le métafichier. |
| [getMissedFonts()](#getMissedFonts--) | Renvoie la liste des polices utilisées dans le métafichier mais non trouvées. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Redimensionne le canevas. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Obtient les enregistrements.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Mettre en cache les données pour charger tous les enregistrements.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // La clé est un type d'enregistrement, la valeur est le nombre d'enregistrements de ce type dans l'image WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Collecter les statistiques
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

    // Imprimer les statistiques
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Aligner la sortie avec des espaces
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//La sortie peut ressembler à ceci :
//Le nombre total d'enregistrements : 1188
//Type d'enregistrement                              Nombre
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


Définit les enregistrements.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Les enregistrements. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Renvoie la liste des polices utilisées dans le métafichier.

**Returns:**
java.lang.String[] - La liste des polices

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Rendre toutes les polices inaccessibles
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

// Le journal STDOUT peut ressembler à ceci :
//        Test du fichier: TestWmfText.wmf
//        Polices utilisées:
//        Police utilisée: Garamond
//        Police utilisée: Arial
//        Police utilisée: Bookman Old Style
//        Police utilisée: Comic Sans MS
//        Police utilisée: Courier
//        Police utilisée: Courier New
//        Police utilisée: Impact
//        Police utilisée: Modern
//        Police utilisée: MS Sans Serif
//        Police utilisée: MS Serif
//        Police utilisée: Small Fonts
//        Police utilisée: Symbol
//        Police utilisée: Tahoma
//        Police utilisée: Times New Roman
//        Police utilisée: Verdana
//        Police utilisée: Wingdings
//        Polices manquantes:
//        Police manquante: Garamond
//        Police manquante: Arial
//        Police manquante: Bookman Old Style
//        Police manquante: Comic Sans MS
//        Police manquante: Courier
//        Police manquante: Courier New
//        Police manquante: Impact
//        Police manquante: Modern
//        Police manquante: MS Sans Serif
//        Police manquante: MS Serif
//        Police manquante: Small Fonts
//        Police manquante: Symbol
//        Police manquante: Tahoma
//        Police manquante: Verdana
//        Police manquante: Wingdings
//        Test du fichier: TestEmfFonts.emf
//        Polices utilisées:
//        Police utilisée: Arial
//        Police utilisée: Verdana
//        Police utilisée: Times New Roman
//        Police utilisée: Symbol
//        Polices manquantes:
//        Police manquante: Arial
//        Police manquante: Verdana
//        Police manquante: Symbol
//        Test du fichier: TestEmfPlusFonts.emf
//        Polices utilisées:
//        Police utilisée: MICROSOFT SANS SERIF
//        Polices manquantes:
//        Police manquante: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Renvoie la liste des polices utilisées dans le métafichier mais non trouvées.

**Returns:**
java.lang.String[] - La liste des polices

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Rendre toutes les polices inaccessibles
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

// Le journal STDOUT peut ressembler à ceci :
//        Test du fichier: TestWmfText.wmf
//        Polices utilisées:
//        Police utilisée: Garamond
//        Police utilisée: Arial
//        Police utilisée: Bookman Old Style
//        Police utilisée: Comic Sans MS
//        Police utilisée: Courier
//        Police utilisée: Courier New
//        Police utilisée: Impact
//        Police utilisée: Modern
//        Police utilisée: MS Sans Serif
//        Police utilisée: MS Serif
//        Police utilisée: Small Fonts
//        Police utilisée: Symbol
//        Police utilisée: Tahoma
//        Police utilisée: Times New Roman
//        Police utilisée: Verdana
//        Police utilisée: Wingdings
//        Polices manquantes:
//        Police manquante: Garamond
//        Police manquante: Arial
//        Police manquante: Bookman Old Style
//        Police manquante: Comic Sans MS
//        Police manquante: Courier
//        Police manquante: Courier New
//        Police manquante: Impact
//        Police manquante: Modern
//        Police manquante: MS Sans Serif
//        Police manquante: MS Serif
//        Police manquante: Small Fonts
//        Police manquante: Symbol
//        Police manquante: Tahoma
//        Police manquante: Verdana
//        Police manquante: Wingdings
//        Test du fichier: TestEmfFonts.emf
//        Polices utilisées:
//        Police utilisée: Arial
//        Police utilisée: Verdana
//        Police utilisée: Times New Roman
//        Police utilisée: Symbol
//        Polices manquantes:
//        Police manquante: Arial
//        Police manquante: Verdana
//        Police manquante: Symbol
//        Test du fichier: TestEmfPlusFonts.emf
//        Polices utilisées:
//        Police utilisée: MICROSOFT SANS SERIF
//        Polices manquantes:
//        Police manquante: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Redimensionne le canevas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le nouveau rectangle. |


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

