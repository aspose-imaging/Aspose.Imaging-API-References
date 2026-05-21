---
title: "MetaImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase base para clases de objetos Meta"
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Clase base para clases de objetos Meta
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRecords()](#getRecords--) | Obtiene los registros. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Establece los registros. |
| [getUsedFonts()](#getUsedFonts--) | Devuelve la lista de fuentes que se usan dentro del metafichero. |
| [getMissedFonts()](#getMissedFonts--) | Devuelve la lista de fuentes que se usan dentro del metafichero pero no se encuentran. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Redimensiona el lienzo. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Obtiene los registros.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Usar Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Almacena en caché los datos para cargar todos los registros.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // La clave es un tipo de registro, el valor es el número de registros de ese tipo en la imagen WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Recopilar estadísticas
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

    // Imprimir estadísticas
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Alinear la salida con espacios
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//La salida puede verse así:
//El número total de registros: 1188
//Tipo de Registro                              Cantidad
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


Establece los registros.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Los registros. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Devuelve la lista de fuentes que se usan dentro del metafichero.

**Returns:**
java.lang.String[] - La lista de fuentes

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Para hacer que todas las fuentes sean inaccesibles
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

// El registro STDOUT puede verse así:
//        Probando el archivo: TestWmfText.wmf
//        Fuentes usadas:
//        Fuente usada: Garamond
//        Fuente usada: Arial
//        Fuente usada: Bookman Old Style
//        Fuente usada: Comic Sans MS
//        Fuente usada: Courier
//        Fuente usada: Courier New
//        Fuente usada: Impact
//        Fuente usada: Modern
//        Fuente usada: MS Sans Serif
//        Fuente usada: MS Serif
//        Fuente usada: Small Fonts
//        Fuente usada: Symbol
//        Fuente usada: Tahoma
//        Fuente usada: Times New Roman
//        Fuente usada: Verdana
//        Fuente usada: Wingdings
//        Fuentes faltantes:
//        Fuente faltante: Garamond
//        Fuente faltante: Arial
//        Fuente faltante: Bookman Old Style
//        Fuente faltante: Comic Sans MS
//        Fuente faltante: Courier
//        Fuente faltante: Courier New
//        Fuente faltante: Impact
//        Fuente faltante: Modern
//        Fuente faltante: MS Sans Serif
//        Fuente faltante: MS Serif
//        Fuente faltante: Small Fonts
//        Fuente faltante: Symbol
//        Fuente faltante: Tahoma
//        Fuente faltante: Verdana
//        Fuente faltante: Wingdings
//        Probando el archivo: TestEmfFonts.emf
//        Fuentes usadas:
//        Fuente usada: Arial
//        Fuente usada: Verdana
//        Fuente usada: Times New Roman
//        Fuente usada: Symbol
//        Fuentes faltantes:
//        Fuente faltante: Arial
//        Fuente faltante: Verdana
//        Fuente faltante: Symbol
//        Probando el archivo: TestEmfPlusFonts.emf
//        Fuentes usadas:
//        Fuente usada: MICROSOFT SANS SERIF
//        Fuentes faltantes:
//        Fuente faltante: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Devuelve la lista de fuentes que se usan dentro del metafichero pero no se encuentran.

**Returns:**
java.lang.String[] - La lista de fuentes

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Para hacer que todas las fuentes sean inaccesibles
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

// El registro STDOUT puede verse así:
//        Probando el archivo: TestWmfText.wmf
//        Fuentes usadas:
//        Fuente usada: Garamond
//        Fuente usada: Arial
//        Fuente usada: Bookman Old Style
//        Fuente usada: Comic Sans MS
//        Fuente usada: Courier
//        Fuente usada: Courier New
//        Fuente usada: Impact
//        Fuente usada: Modern
//        Fuente usada: MS Sans Serif
//        Fuente usada: MS Serif
//        Fuente usada: Small Fonts
//        Fuente usada: Symbol
//        Fuente usada: Tahoma
//        Fuente usada: Times New Roman
//        Fuente usada: Verdana
//        Fuente usada: Wingdings
//        Fuentes faltantes:
//        Fuente faltante: Garamond
//        Fuente faltante: Arial
//        Fuente faltante: Bookman Old Style
//        Fuente faltante: Comic Sans MS
//        Fuente faltante: Courier
//        Fuente faltante: Courier New
//        Fuente faltante: Impact
//        Fuente faltante: Modern
//        Fuente faltante: MS Sans Serif
//        Fuente faltante: MS Serif
//        Fuente faltante: Small Fonts
//        Fuente faltante: Symbol
//        Fuente faltante: Tahoma
//        Fuente faltante: Verdana
//        Fuente faltante: Wingdings
//        Probando el archivo: TestEmfFonts.emf
//        Fuentes usadas:
//        Fuente usada: Arial
//        Fuente usada: Verdana
//        Fuente usada: Times New Roman
//        Fuente usada: Symbol
//        Fuentes faltantes:
//        Fuente faltante: Arial
//        Fuente faltante: Verdana
//        Fuente faltante: Symbol
//        Probando el archivo: TestEmfPlusFonts.emf
//        Fuentes usadas:
//        Fuente usada: MICROSOFT SANS SERIF
//        Fuentes faltantes:
//        Fuente faltante: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Redimensiona el lienzo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El nuevo rectángulo. |


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

