---
title: "MetaImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый класс для классов Meta-объектов"
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.emf/metaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public abstract class MetaImage extends VectorImage
```

Базовый класс для классов Meta-объектов
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MetaImage()](#MetaImage--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRecords()](#getRecords--) | Получает записи. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Устанавливает записи. |
| [getUsedFonts()](#getUsedFonts--) | Возвращает список шрифтов, используемых внутри метафайла. |
| [getMissedFonts()](#getMissedFonts--) | Возвращает список шрифтов, используемых внутри метафайла, но не найденных. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Изменяет размер холста. |
### MetaImage() {#MetaImage--}
```
public MetaImage()
```


### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Получает записи.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.

**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Кэшировать данные для загрузки всех записей.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Ключ — тип записи, значение — количество записей данного типа в WMF‑изображении.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Собрать статистику
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

    // Вывести статистику
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Выровнять вывод пробелами
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//Вывод может выглядеть так:
//Общее количество записей: 1188
//Тип записи                              Количество
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


Устанавливает записи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Записи. |

### getUsedFonts() {#getUsedFonts--}
```
public abstract String[] getUsedFonts()
```


Возвращает список шрифтов, используемых внутри метафайла.

**Returns:**
java.lang.String[] - Список шрифтов

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Сделать все шрифты недоступными
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

// Журнал STDOUT может выглядеть так:
//        Тестирование файла: TestWmfText.wmf
//        Используемые шрифты:
//        Используемый шрифт: Garamond
//        Используемый шрифт: Arial
//        Используемый шрифт: Bookman Old Style
//        Используемый шрифт: Comic Sans MS
//        Используемый шрифт: Courier
//        Используемый шрифт: Courier New
//        Используемый шрифт: Impact
//        Используемый шрифт: Modern
//        Используемый шрифт: MS Sans Serif
//        Используемый шрифт: MS Serif
//        Используемый шрифт: Small Fonts
//        Используемый шрифт: Symbol
//        Используемый шрифт: Tahoma
//        Используемый шрифт: Times New Roman
//        Используемый шрифт: Verdana
//        Используемый шрифт: Wingdings
//        Пропущенные шрифты:
//        Пропущенный шрифт: Garamond
//        Пропущенный шрифт: Arial
//        Пропущенный шрифт: Bookman Old Style
//        Пропущенный шрифт: Comic Sans MS
//        Пропущенный шрифт: Courier
//        Пропущенный шрифт: Courier New
//        Пропущенный шрифт: Impact
//        Пропущенный шрифт: Modern
//        Пропущенный шрифт: MS Sans Serif
//        Пропущенный шрифт: MS Serif
//        Пропущенный шрифт: Small Fonts
//        Пропущенный шрифт: Symbol
//        Пропущенный шрифт: Tahoma
//        Пропущенный шрифт: Verdana
//        Пропущенный шрифт: Wingdings
//        Тестирование файла: TestEmfFonts.emf
//        Используемые шрифты:
//        Используемый шрифт: Arial
//        Используемый шрифт: Verdana
//        Используемый шрифт: Times New Roman
//        Используемый шрифт: Symbol
//        Пропущенные шрифты:
//        Пропущенный шрифт: Arial
//        Пропущенный шрифт: Verdana
//        Пропущенный шрифт: Symbol
//        Тестирование файла: TestEmfPlusFonts.emf
//        Используемые шрифты:
//        Используемый шрифт: MICROSOFT SANS SERIF
//        Пропущенные шрифты:
//        Пропущенный шрифт: MICROSOFT SANS SERIF
```

### getMissedFonts() {#getMissedFonts--}
```
public final String[] getMissedFonts()
```


Возвращает список шрифтов, используемых внутри метафайла, но не найденных.

**Returns:**
java.lang.String[] - Список шрифтов

**Example: The following example shows how to print information about used and missed fonts in WMF/EMF images.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1429\\";
String[] files = {
        "TestWmfText.wmf",
        "TestEmfFonts.emf",
        "TestEmfPlusFonts.emf"
};

// Сделать все шрифты недоступными
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

// Журнал STDOUT может выглядеть так:
//        Тестирование файла: TestWmfText.wmf
//        Используемые шрифты:
//        Используемый шрифт: Garamond
//        Используемый шрифт: Arial
//        Используемый шрифт: Bookman Old Style
//        Используемый шрифт: Comic Sans MS
//        Используемый шрифт: Courier
//        Используемый шрифт: Courier New
//        Используемый шрифт: Impact
//        Используемый шрифт: Modern
//        Используемый шрифт: MS Sans Serif
//        Используемый шрифт: MS Serif
//        Используемый шрифт: Small Fonts
//        Используемый шрифт: Symbol
//        Используемый шрифт: Tahoma
//        Используемый шрифт: Times New Roman
//        Используемый шрифт: Verdana
//        Используемый шрифт: Wingdings
//        Пропущенные шрифты:
//        Пропущенный шрифт: Garamond
//        Пропущенный шрифт: Arial
//        Пропущенный шрифт: Bookman Old Style
//        Пропущенный шрифт: Comic Sans MS
//        Пропущенный шрифт: Courier
//        Пропущенный шрифт: Courier New
//        Пропущенный шрифт: Impact
//        Пропущенный шрифт: Modern
//        Пропущенный шрифт: MS Sans Serif
//        Пропущенный шрифт: MS Serif
//        Пропущенный шрифт: Small Fonts
//        Пропущенный шрифт: Symbol
//        Пропущенный шрифт: Tahoma
//        Пропущенный шрифт: Verdana
//        Пропущенный шрифт: Wingdings
//        Тестирование файла: TestEmfFonts.emf
//        Используемые шрифты:
//        Используемый шрифт: Arial
//        Используемый шрифт: Verdana
//        Используемый шрифт: Times New Roman
//        Используемый шрифт: Symbol
//        Пропущенные шрифты:
//        Пропущенный шрифт: Arial
//        Пропущенный шрифт: Verdana
//        Пропущенный шрифт: Symbol
//        Тестирование файла: TestEmfPlusFonts.emf
//        Используемые шрифты:
//        Используемый шрифт: MICROSOFT SANS SERIF
//        Пропущенные шрифты:
//        Пропущенный шрифт: MICROSOFT SANS SERIF
```

### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public abstract void resizeCanvas(Rectangle newRectangle)
```


Изменяет размер холста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Новый прямоугольник. |


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

