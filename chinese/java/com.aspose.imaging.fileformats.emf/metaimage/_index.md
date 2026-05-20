---
title: "MetaImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Meta 对象类的基类"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Meta 对象类的基类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRecords()](#getRecords--) | 获取记录。 |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | 设置记录。 |
| [getUsedFonts()](#getUsedFonts--) | 返回在元文件中使用的字体列表。 |
| [getMissedFonts()](#getMissedFonts--) | 返回在元文件中使用但未找到的字体列表。 |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | 调整画布大小。 |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


获取记录。

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // 缓存数据以加载所有记录。
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // 键是记录类型，值是该类型在 WMF 图像中的记录数量。
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // 收集统计信息
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

    // 打印统计信息
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // 使用空格对齐输出
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//输出可能如下所示：
//记录总数：1188
//记录类型                              数量
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


设置记录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | 记录。 |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


返回在元文件中使用的字体列表。

**Returns:**
java.lang.String[] - 字体列表

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// 使所有字体不可访问
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

// STDOUT 日志可能如下所示：
//        正在测试文件：TestWmfText.wmf
//        使用的字体：
//        使用的字体：Garamond
//        使用的字体：Arial
//        使用的字体：Bookman Old Style
//        使用的字体：Comic Sans MS
//        使用的字体：Courier
//        使用的字体：Courier New
//        使用的字体：Impact
//        使用的字体：Modern
//        使用的字体：MS Sans Serif
//        使用的字体：MS Serif
//        使用的字体：Small Fonts
//        使用的字体：Symbol
//        使用的字体：Tahoma
//        使用的字体：Times New Roman
//        使用的字体：Verdana
//        使用的字体：Wingdings
//        缺少的字体：
//        缺少的字体：Garamond
//        缺少的字体：Arial
//        缺少的字体：Bookman Old Style
//        缺少的字体：Comic Sans MS
//        缺少的字体：Courier
//        缺少的字体：Courier New
//        缺少的字体：Impact
//        缺少的字体：Modern
//        缺少的字体：MS Sans Serif
//        缺少的字体：MS Serif
//        缺少的字体：Small Fonts
//        缺少的字体：Symbol
//        缺少的字体：Tahoma
//        缺少的字体：Verdana
//        缺少的字体：Wingdings
//        正在测试文件：TestEmfFonts.emf
//        使用的字体：
//        使用的字体：Arial
//        使用的字体：Verdana
//        使用的字体：Times New Roman
//        使用的字体：Symbol
//        缺少的字体：
//        缺少的字体：Arial
//        缺少的字体：Verdana
//        缺少的字体：Symbol
//        正在测试文件：TestEmfPlusFonts.emf
//        使用的字体：
//        使用的字体：MICROSOFT SANS SERIF
//        缺少的字体：
//        缺少的字体：MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


返回在元文件中使用但未找到的字体列表。

**Returns:**
java.lang.String[] - 字体列表

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// 使所有字体不可访问
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

// STDOUT 日志可能如下所示：
//        正在测试文件：TestWmfText.wmf
//        使用的字体：
//        使用的字体：Garamond
//        使用的字体：Arial
//        使用的字体：Bookman Old Style
//        使用的字体：Comic Sans MS
//        使用的字体：Courier
//        使用的字体：Courier New
//        使用的字体：Impact
//        使用的字体：Modern
//        使用的字体：MS Sans Serif
//        使用的字体：MS Serif
//        使用的字体：Small Fonts
//        使用的字体：Symbol
//        使用的字体：Tahoma
//        使用的字体：Times New Roman
//        使用的字体：Verdana
//        使用的字体：Wingdings
//        缺少的字体：
//        缺少的字体：Garamond
//        缺少的字体：Arial
//        缺少的字体：Bookman Old Style
//        缺少的字体：Comic Sans MS
//        缺少的字体：Courier
//        缺少的字体：Courier New
//        缺少的字体：Impact
//        缺少的字体：Modern
//        缺少的字体：MS Sans Serif
//        缺少的字体：MS Serif
//        缺少的字体：Small Fonts
//        缺少的字体：Symbol
//        缺少的字体：Tahoma
//        缺少的字体：Verdana
//        缺少的字体：Wingdings
//        正在测试文件：TestEmfFonts.emf
//        使用的字体：
//        使用的字体：Arial
//        使用的字体：Verdana
//        使用的字体：Times New Roman
//        使用的字体：Symbol
//        缺少的字体：
//        缺少的字体：Arial
//        缺少的字体：Verdana
//        缺少的字体：Symbol
//        正在测试文件：TestEmfPlusFonts.emf
//        使用的字体：
//        使用的字体：MICROSOFT SANS SERIF
//        缺少的字体：
//        缺少的字体：MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


调整画布大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 新的矩形。 |


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

