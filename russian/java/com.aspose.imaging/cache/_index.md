---
title: "Кеш"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Содержит настройки кэша."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Содержит настройки кэша.
## Методы

| Метод | Описание |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Возвращает значение, указывающее, должно ли перераспределение быть точным или нет. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Устанавливает значение, указывающее, должно ли перераспределение быть точным или нет. |
| [getCacheFolder()](#getCacheFolder--) | Возвращает папку кеша. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Устанавливает папку кеша. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Возвращает количество выделенных байтов в памяти. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Возвращает количество выделенных байтов на диске. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Возвращает максимальный доступный объём памяти для кеша в памяти. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Устанавливает максимальный доступный объём памяти для кеша в памяти. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Возвращает максимальное доступное дисковое пространство для кеша. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Устанавливает максимальное доступное дисковое пространство для кеша. |
| [getCacheType()](#getCacheType--) | Возвращает или устанавливает используемую схему кеша. |
| [setCacheType(int value)](#setCacheType-int-) | Устанавливает используемую схему кеша. |
| [setDefaults()](#setDefaults--) | Устанавливает настройки `Cache` по умолчанию. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// По умолчанию папка кеша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кеша, отличную от значения по умолчанию, как показано ниже:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Автоматический режим гибок и эффективен
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Значение по умолчанию равно 0, что означает отсутствие верхнего предела
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// В любой момент вы можете проверить, сколько байт в данный момент выделено для памяти или диска
// кешировать, проверяя следующие свойства
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Выполните обработку изображения, как показано ниже
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // После выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены.
// Если вы забыли вызвать dispose у какого-либо объекта, значения кеша будут отличаться от 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


Возвращает значение, указывающее, должна ли переалокация быть точной. Если переалокация неточная, производительность должна быть выше.

**Returns:**
boolean - `true`, если переалокация точна; иначе `false`.

Точная переалокация будет выполнять переалокацию дополнительной памяти только до указанного верхнего предела. При указании верхнего предела для памяти во время переалокации кэшированные данные будут скопированы на диск, если это возможно. При указании верхнего предела для дисковой памяти во время переалокации будет выброшено соответствующее исключение. Производительность должна быть выше, если эта опция отключена, так как не будет выполняться дополнительное копирование, если это возможно, однако это также может привести к превышению указанных верхних пределов для памяти или диска.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Устанавливает значение, указывающее, должна ли переалокация быть точной. Если переалокация неточная, производительность должна быть выше.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | `true`, если переалокация точна; иначе `false`. |

Точная переалокация будет выполнять переалокацию дополнительной памяти только до указанного верхнего предела. При указании верхнего предела для памяти во время переалокации кэшированные данные будут скопированы на диск, если это возможно. При указании верхнего предела для дисковой памяти во время переалокации будет выброшено соответствующее исключение. Производительность должна быть выше, если эта опция отключена, так как не будет выполняться дополнительное копирование, если это возможно, однако это также может привести к превышению указанных верхних пределов для памяти или диска. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// По умолчанию папка кеша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кеша, отличную от значения по умолчанию, как показано ниже:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Автоматический режим гибок и эффективен
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Значение по умолчанию равно 0, что означает отсутствие верхнего предела
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// В любой момент вы можете проверить, сколько байт в данный момент выделено для памяти или диска
// кешировать, проверяя следующие свойства
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Выполните обработку изображения, как показано ниже
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // После выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены.
// Если вы забыли вызвать dispose у какого-либо объекта, значения кеша будут отличаться от 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Возвращает папку кеша.

**Returns:**
java.lang.String - Папка кеша.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Устанавливает папку кеша.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Папка кеша. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Возвращает количество выделенных байтов в памяти.

**Returns:**
long - Количество выделенных байт в памяти.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// По умолчанию папка кеша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кеша, отличную от значения по умолчанию, как показано ниже:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Автоматический режим гибок и эффективен
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Значение по умолчанию равно 0, что означает отсутствие верхнего предела
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// В любой момент вы можете проверить, сколько байт в данный момент выделено для памяти или диска
// кешировать, проверяя следующие свойства
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Выполните обработку изображения, как показано ниже
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // После выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены.
// Если вы забыли вызвать dispose у какого-либо объекта, значения кеша будут отличаться от 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Возвращает количество выделенных байтов на диске.

**Returns:**
long - Количество выделенных байт на диске.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// По умолчанию папка кеша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кеша, отличную от значения по умолчанию, как показано ниже:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Автоматический режим гибок и эффективен
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Значение по умолчанию равно 0, что означает отсутствие верхнего предела
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// В любой момент вы можете проверить, сколько байт в данный момент выделено для памяти или диска
// кешировать, проверяя следующие свойства
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Выполните обработку изображения, как показано ниже
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // После выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены.
// Если вы забыли вызвать dispose у какого-либо объекта, значения кеша будут отличаться от 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Возвращает максимальный доступный объём памяти для кеша в памяти. Указанное значение — количество мегабайт.

**Returns:**
int - Максимальная память для кеша.

Значение 0 будет использовать всю доступную память и служит отсутствием верхнего предела.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Устанавливает максимальный доступный объём памяти для кеша в памяти. Указанное значение — количество мегабайт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Максимальная память для кеша. |

Значение 0 будет использовать всю доступную память и служит отсутствием верхнего предела. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// По умолчанию папка кеша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кеша, отличную от значения по умолчанию, как показано ниже:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Автоматический режим гибок и эффективен
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Значение по умолчанию равно 0, что означает отсутствие верхнего предела
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// В любой момент вы можете проверить, сколько байт в данный момент выделено для памяти или диска
// кешировать, проверяя следующие свойства
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Выполните обработку изображения, как показано ниже
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // После выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены.
// Если вы забыли вызвать dispose у какого-либо объекта, значения кеша будут отличаться от 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Получает максимальное доступное дисковое пространство для кэша. Указанное значение — количество мегабайт.

**Returns:**
int - Максимальное доступное дисковое пространство для кэша.

Значение 0 будет использовать всю доступную память и служит отсутствием верхнего предела.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Устанавливает максимальное доступное дисковое пространство для кэша. Указанное значение — количество мегабайт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Максимальное доступное дисковое пространство для кэша. |

Значение 0 будет использовать всю доступную память и служит отсутствием верхнего предела. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// По умолчанию папка кеша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кеша, отличную от значения по умолчанию, как показано ниже:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Автоматический режим гибок и эффективен
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Значение по умолчанию равно 0, что означает отсутствие верхнего предела
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// В любой момент вы можете проверить, сколько байт в данный момент выделено для памяти или диска
// кешировать, проверяя следующие свойства
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Выполните обработку изображения, как показано ниже
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // После выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены.
// Если вы забыли вызвать dispose у какого-либо объекта, значения кеша будут отличаться от 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Возвращает или устанавливает используемую схему кеша.

**Returns:**
int - Используемая схема кэша.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Устанавливает используемую схему кеша.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Используемая схема кэша. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// По умолчанию папка кеша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кеша, отличную от значения по умолчанию, как показано ниже:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Автоматический режим гибок и эффективен
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Значение по умолчанию равно 0, что означает отсутствие верхнего предела
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// В любой момент вы можете проверить, сколько байт в данный момент выделено для памяти или диска
// кешировать, проверяя следующие свойства
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Выполните обработку изображения, как показано ниже
com.aspose.imaging.imageoptions.GifOptions options = new com.aspose.imaging.imageoptions.GifOptions();
options.setPalette(new com.aspose.imaging.ColorPalette(
        new com.aspose.imaging.Color[]
                {
                        com.aspose.imaging.Color.getRed(),
                        com.aspose.imaging.Color.getBlue(),
                        com.aspose.imaging.Color.getBlack(),
                        com.aspose.imaging.Color.getWhite()
                }));
options.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(options, 100, 100);
try {
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[10000];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getWhite();
    }

    System.out.println("Set the white color for 10000 pixels.");
    image.savePixels(image.getBounds(), pixels);

    // После выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.Imaging правильно освобождены.
// Если вы забыли вызвать dispose у какого-либо объекта, значения кеша будут отличаться от 0.
l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");
```

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Устанавливает настройки `Cache` по умолчанию.

