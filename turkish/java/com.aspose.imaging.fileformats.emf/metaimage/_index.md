---
title: "MetaImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Meta nesne sınıfları için temel sınıf"
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Meta nesne sınıfları için temel sınıf
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRecords()](#getRecords--) | Kayıtları alır. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Kayıtları ayarlar. |
| [getUsedFonts()](#getUsedFonts--) | Metafile içinde kullanılan fontların listesini döndürür. |
| [getMissedFonts()](#getMissedFonts--) | Metafile içinde kullanılan ancak bulunamayan fontların listesini döndürür. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Tuvali yeniden boyutlandırır. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Kayıtları alır.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, WMF dahil tüm görüntü türlerini yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Tüm kayıtları yüklemek için verileri önbelleğe alın.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Anahtar bir kayıt türüdür, değer ise WMF görüntüsündeki o türdeki kayıt sayısını gösterir.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // İstatistikleri topla
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

    // İstatistikleri yazdır
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Çıktıyı boşluklarla hizala
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//Çıktı şöyle görünebilir:
//Toplam kayıt sayısı: 1188
//Kayıt Türü                              Sayı
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


Kayıtları ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Kayıtlar. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Metafile içinde kullanılan fontların listesini döndürür.

**Returns:**
java.lang.String[] - Yazı tipi listesi

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Tüm yazı tiplerini erişilemez hale getirmek için
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

// STDOUT günlüğü şu şekilde görünebilir:
//        Dosyayı test ediyor: TestWmfText.wmf
//        Kullanılan yazı tipleri:
//        Kullanılan yazı tipi: Garamond
//        Kullanılan yazı tipi: Arial
//        Kullanılan yazı tipi: Bookman Old Style
//        Kullanılan yazı tipi: Comic Sans MS
//        Kullanılan yazı tipi: Courier
//        Kullanılan yazı tipi: Courier New
//        Kullanılan yazı tipi: Impact
//        Kullanılan yazı tipi: Modern
//        Kullanılan yazı tipi: MS Sans Serif
//        Kullanılan yazı tipi: MS Serif
//        Kullanılan yazı tipi: Small Fonts
//        Kullanılan yazı tipi: Symbol
//        Kullanılan yazı tipi: Tahoma
//        Kullanılan yazı tipi: Times New Roman
//        Kullanılan yazı tipi: Verdana
//        Kullanılan yazı tipi: Wingdings
//        Eksik yazı tipleri:
//        Eksik yazı tipi: Garamond
//        Eksik yazı tipi: Arial
//        Eksik yazı tipi: Bookman Old Style
//        Eksik yazı tipi: Comic Sans MS
//        Eksik yazı tipi: Courier
//        Eksik yazı tipi: Courier New
//        Eksik yazı tipi: Impact
//        Eksik yazı tipi: Modern
//        Eksik yazı tipi: MS Sans Serif
//        Eksik yazı tipi: MS Serif
//        Eksik yazı tipi: Small Fonts
//        Eksik yazı tipi: Symbol
//        Eksik yazı tipi: Tahoma
//        Eksik yazı tipi: Verdana
//        Eksik yazı tipi: Wingdings
//        Dosyayı test ediyor: TestEmfFonts.emf
//        Kullanılan yazı tipleri:
//        Kullanılan yazı tipi: Arial
//        Kullanılan yazı tipi: Verdana
//        Kullanılan yazı tipi: Times New Roman
//        Kullanılan yazı tipi: Symbol
//        Eksik yazı tipleri:
//        Eksik yazı tipi: Arial
//        Eksik yazı tipi: Verdana
//        Eksik yazı tipi: Symbol
//        Dosyayı test ediyor: TestEmfPlusFonts.emf
//        Kullanılan yazı tipleri:
//        Kullanılan yazı tipi: MICROSOFT SANS SERIF
//        Eksik yazı tipleri:
//        Eksik yazı tipi: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Metafile içinde kullanılan ancak bulunamayan fontların listesini döndürür.

**Returns:**
java.lang.String[] - Yazı tipi listesi

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Tüm yazı tiplerini erişilemez hale getirmek için
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

// STDOUT günlüğü şu şekilde görünebilir:
//        Dosyayı test ediyor: TestWmfText.wmf
//        Kullanılan yazı tipleri:
//        Kullanılan yazı tipi: Garamond
//        Kullanılan yazı tipi: Arial
//        Kullanılan yazı tipi: Bookman Old Style
//        Kullanılan yazı tipi: Comic Sans MS
//        Kullanılan yazı tipi: Courier
//        Kullanılan yazı tipi: Courier New
//        Kullanılan yazı tipi: Impact
//        Kullanılan yazı tipi: Modern
//        Kullanılan yazı tipi: MS Sans Serif
//        Kullanılan yazı tipi: MS Serif
//        Kullanılan yazı tipi: Small Fonts
//        Kullanılan yazı tipi: Symbol
//        Kullanılan yazı tipi: Tahoma
//        Kullanılan yazı tipi: Times New Roman
//        Kullanılan yazı tipi: Verdana
//        Kullanılan yazı tipi: Wingdings
//        Eksik yazı tipleri:
//        Eksik yazı tipi: Garamond
//        Eksik yazı tipi: Arial
//        Eksik yazı tipi: Bookman Old Style
//        Eksik yazı tipi: Comic Sans MS
//        Eksik yazı tipi: Courier
//        Eksik yazı tipi: Courier New
//        Eksik yazı tipi: Impact
//        Eksik yazı tipi: Modern
//        Eksik yazı tipi: MS Sans Serif
//        Eksik yazı tipi: MS Serif
//        Eksik yazı tipi: Small Fonts
//        Eksik yazı tipi: Symbol
//        Eksik yazı tipi: Tahoma
//        Eksik yazı tipi: Verdana
//        Eksik yazı tipi: Wingdings
//        Dosyayı test ediyor: TestEmfFonts.emf
//        Kullanılan yazı tipleri:
//        Kullanılan yazı tipi: Arial
//        Kullanılan yazı tipi: Verdana
//        Kullanılan yazı tipi: Times New Roman
//        Kullanılan yazı tipi: Symbol
//        Eksik yazı tipleri:
//        Eksik yazı tipi: Arial
//        Eksik yazı tipi: Verdana
//        Eksik yazı tipi: Symbol
//        Dosyayı test ediyor: TestEmfPlusFonts.emf
//        Kullanılan yazı tipleri:
//        Kullanılan yazı tipi: MICROSOFT SANS SERIF
//        Eksik yazı tipleri:
//        Eksik yazı tipi: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Tuvali yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Yeni dikdörtgen. |


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

