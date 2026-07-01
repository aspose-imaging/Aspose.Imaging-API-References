---
title: "MetaImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفئة الأساسية لفئات كائنات Meta"
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

الفئة الأساسية لفئات كائنات Meta
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRecords()](#getRecords--) | يحصل على السجلات. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | يضبط السجلات. |
| [getUsedFonts()](#getUsedFonts--) | يعيد قائمة الخطوط المستخدمة داخل metafile. |
| [getMissedFonts()](#getMissedFonts--) | يعيد قائمة الخطوط المستخدمة داخل metafile ولكن لم يتم العثور عليها. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | يعيد تحجيم اللوحة. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


يحصل على السجلات.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // تخزين البيانات مؤقتًا لتحميل جميع السجلات.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // المفتاح هو نوع السجل، والقيمة هي عدد السجلات من ذلك النوع في صورة WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // جمع الإحصائيات
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

    // طباعة الإحصائيات
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // محاذاة الإخراج باستخدام المسافات
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//قد يبدو الإخراج هكذا:
//إجمالي عدد السجلات: 1188
//نوع السجل                              العدد
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


يضبط السجلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | السجلات. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


يعيد قائمة الخطوط المستخدمة داخل metafile.

**Returns:**
java.lang.String[] - قائمة الخطوط

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// لجعل جميع الخطوط غير قابلة للوصول
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

// قد يبدو سجل STDOUT هكذا:
//        اختبار الملف: TestWmfText.wmf
//        الخطوط المستخدمة:
//        الخط المستخدم: Garamond
//        الخط المستخدم: Arial
//        الخط المستخدم: Bookman Old Style
//        الخط المستخدم: Comic Sans MS
//        الخط المستخدم: Courier
//        الخط المستخدم: Courier New
//        الخط المستخدم: Impact
//        الخط المستخدم: Modern
//        الخط المستخدم: MS Sans Serif
//        الخط المستخدم: MS Serif
//        الخط المستخدم: Small Fonts
//        الخط المستخدم: Symbol
//        الخط المستخدم: Tahoma
//        الخط المستخدم: Times New Roman
//        الخط المستخدم: Verdana
//        الخط المستخدم: Wingdings
//        الخطوط المفقودة:
//        الخط المفقود: Garamond
//        الخط المفقود: Arial
//        الخط المفقود: Bookman Old Style
//        الخط المفقود: Comic Sans MS
//        الخط المفقود: Courier
//        الخط المفقود: Courier New
//        الخط المفقود: Impact
//        الخط المفقود: Modern
//        الخط المفقود: MS Sans Serif
//        الخط المفقود: MS Serif
//        الخط المفقود: Small Fonts
//        الخط المفقود: Symbol
//        الخط المفقود: Tahoma
//        الخط المفقود: Verdana
//        الخط المفقود: Wingdings
//        اختبار الملف: TestEmfFonts.emf
//        الخطوط المستخدمة:
//        الخط المستخدم: Arial
//        الخط المستخدم: Verdana
//        الخط المستخدم: Times New Roman
//        الخط المستخدم: Symbol
//        الخطوط المفقودة:
//        الخط المفقود: Arial
//        الخط المفقود: Verdana
//        الخط المفقود: Symbol
//        اختبار الملف: TestEmfPlusFonts.emf
//        الخطوط المستخدمة:
//        الخط المستخدم: MICROSOFT SANS SERIF
//        الخطوط المفقودة:
//        الخط المفقود: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


يعيد قائمة الخطوط المستخدمة داخل metafile ولكن لم يتم العثور عليها.

**Returns:**
java.lang.String[] - قائمة الخطوط

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// لجعل جميع الخطوط غير قابلة للوصول
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

// قد يبدو سجل STDOUT هكذا:
//        اختبار الملف: TestWmfText.wmf
//        الخطوط المستخدمة:
//        الخط المستخدم: Garamond
//        الخط المستخدم: Arial
//        الخط المستخدم: Bookman Old Style
//        الخط المستخدم: Comic Sans MS
//        الخط المستخدم: Courier
//        الخط المستخدم: Courier New
//        الخط المستخدم: Impact
//        الخط المستخدم: Modern
//        الخط المستخدم: MS Sans Serif
//        الخط المستخدم: MS Serif
//        الخط المستخدم: Small Fonts
//        الخط المستخدم: Symbol
//        الخط المستخدم: Tahoma
//        الخط المستخدم: Times New Roman
//        الخط المستخدم: Verdana
//        الخط المستخدم: Wingdings
//        الخطوط المفقودة:
//        الخط المفقود: Garamond
//        الخط المفقود: Arial
//        الخط المفقود: Bookman Old Style
//        الخط المفقود: Comic Sans MS
//        الخط المفقود: Courier
//        الخط المفقود: Courier New
//        الخط المفقود: Impact
//        الخط المفقود: Modern
//        الخط المفقود: MS Sans Serif
//        الخط المفقود: MS Serif
//        الخط المفقود: Small Fonts
//        الخط المفقود: Symbol
//        الخط المفقود: Tahoma
//        الخط المفقود: Verdana
//        الخط المفقود: Wingdings
//        اختبار الملف: TestEmfFonts.emf
//        الخطوط المستخدمة:
//        الخط المستخدم: Arial
//        الخط المستخدم: Verdana
//        الخط المستخدم: Times New Roman
//        الخط المستخدم: Symbol
//        الخطوط المفقودة:
//        الخط المفقود: Arial
//        الخط المفقود: Verdana
//        الخط المفقود: Symbol
//        اختبار الملف: TestEmfPlusFonts.emf
//        الخطوط المستخدمة:
//        الخط المستخدم: MICROSOFT SANS SERIF
//        الخطوط المفقودة:
//        الخط المفقود: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


يعيد تحجيم اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الجديد. |


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

