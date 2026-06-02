---
title: "Cache"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "包含缓存设置。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

包含缓存设置。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | 获取一个值，指示重新分配是否应精确。 |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | 设置一个值，指示重新分配是否应精确。 |
| [getCacheFolder()](#getCacheFolder--) | 获取缓存文件夹。 |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | 设置缓存文件夹。 |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | 获取已分配的内存字节计数。 |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | 获取已分配的磁盘字节计数。 |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | 获取缓存在内存中的最大可用内存。 |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | 设置缓存在内存中的最大可用内存。 |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | 获取缓存的最大可用磁盘空间。 |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | 设置缓存的最大可用磁盘空间。 |
| [getCacheType()](#getCacheType--) | 获取或设置使用的缓存方案。 |
| [setCacheType(int value)](#setCacheType-int-) | 设置使用的缓存方案。 |
| [setDefaults()](#setDefaults--) | 将 `Cache` 设置为默认值。 |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// 默认情况下，缓存文件夹设置为用户本地的临时目录。
// 您还可以指定除默认之外的其他缓存文件夹，如下所示：
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// 自动模式灵活且高效
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// 默认值为 0，这意味着没有上限
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来缓存
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// 按如下方式进行图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
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


获取一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。

**Returns:**
boolean - 如果重新分配是精确的则为 `true`；否则为 `false`。

精确的重新分配仅会在指定的上限范围内进行额外内存的重新分配。若在重新分配期间为内存传递上限，缓存数据将在可能的情况下复制到磁盘。若为磁盘内存传递上限，则会抛出相应的异常。如果关闭此选项，由于不会进行额外的复制，性能应更高，但这也可能导致超出为内存或磁盘指定的上限。
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | boolean | `true` 表示重新分配是精确的；否则为 `false`。 |

精确的重新分配仅会在指定的上限范围内进行额外内存的重新分配。若在重新分配期间为内存传递上限，缓存数据将在可能的情况下复制到磁盘。若为磁盘内存传递上限，则会抛出相应的异常。如果关闭此选项，由于不会进行额外的复制，性能应更高，但这也可能导致超出为内存或磁盘指定的上限。 |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// 默认情况下，缓存文件夹设置为用户本地的临时目录。
// 您还可以指定除默认之外的其他缓存文件夹，如下所示：
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// 自动模式灵活且高效
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// 默认值为 0，这意味着没有上限
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来缓存
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// 按如下方式进行图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
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


获取缓存文件夹。

**Returns:**
java.lang.String - 缓存文件夹。
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


设置缓存文件夹。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 缓存文件夹。 |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


获取已分配的内存字节计数。

**Returns:**
long - 已分配的内存字节数。

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// 默认情况下，缓存文件夹设置为用户本地的临时目录。
// 您还可以指定除默认之外的其他缓存文件夹，如下所示：
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// 自动模式灵活且高效
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// 默认值为 0，这意味着没有上限
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来缓存
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// 按如下方式进行图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
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


获取已分配的磁盘字节计数。

**Returns:**
long - 已分配的磁盘字节数。

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// 默认情况下，缓存文件夹设置为用户本地的临时目录。
// 您还可以指定除默认之外的其他缓存文件夹，如下所示：
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// 自动模式灵活且高效
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// 默认值为 0，这意味着没有上限
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来缓存
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// 按如下方式进行图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
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


获取用于内存缓存的最大可用内存。指定的值为兆字节数。

**Returns:**
int - 缓存的最大内存。

值为 0 将占用所有可用内存，表示没有上限。
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


设置用于内存缓存的最大可用内存。指定的值为兆字节数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 缓存的最大内存。 |

值为 0 将占用所有可用内存，表示没有上限。 |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// 默认情况下，缓存文件夹设置为用户本地的临时目录。
// 您还可以指定除默认之外的其他缓存文件夹，如下所示：
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// 自动模式灵活且高效
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// 默认值为 0，这意味着没有上限
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来缓存
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// 按如下方式进行图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
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


获取缓存的最大可用磁盘空间。指定的值是兆字节计数。

**Returns:**
int - 缓存的最大可用磁盘空间。

值为 0 将占用所有可用内存，表示没有上限。
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


设置缓存的最大可用磁盘空间。指定的值是兆字节计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 缓存的最大可用磁盘空间。 |

值为 0 将占用所有可用内存，表示没有上限。 |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// 默认情况下，缓存文件夹设置为用户本地的临时目录。
// 您还可以指定除默认之外的其他缓存文件夹，如下所示：
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// 自动模式灵活且高效
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// 默认值为 0，这意味着没有上限
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来缓存
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// 按如下方式进行图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
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


获取或设置使用的缓存方案。

**Returns:**
int - 使用的缓存方案。
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


设置使用的缓存方案。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 使用的缓存方案。 |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// 默认情况下，缓存文件夹设置为用户本地的临时目录。
// 您还可以指定除默认之外的其他缓存文件夹，如下所示：
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// 自动模式灵活且高效
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// 默认值为 0，这意味着没有上限
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来缓存
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// 按如下方式进行图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
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


将 `Cache` 设置为默认值。

