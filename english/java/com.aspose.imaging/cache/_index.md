---
title: Cache
second_title: Aspose.Imaging for Java API Reference
description: Contains cache settings.
type: docs
weight: 15
url: /java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contains cache settings.
## Methods

| Method | Description |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Gets a value indicating whether reallocation should be exact or not. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Sets a value indicating whether reallocation should be exact or not. |
| [getCacheFolder()](#getCacheFolder--) | Gets the cache folder. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Sets the cache folder. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Gets the allocated in-memory bytes count. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Gets the allocated disk bytes count. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Gets the maximum available memory for cache in memory. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Sets the maximum available memory for cache in memory. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Gets the maximum available disk space for cache. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Sets the maximum available disk space for cache. |
| [getCacheType()](#getCacheType--) | Gets or sets the cache scheme used. |
| [setCacheType(int value)](#setCacheType-int-) | Sets the cache scheme used. |
| [setDefaults()](#setDefaults--) | Sets the `Cache` settings to defaults. |

## Example
This example demonstrates how to use com.aspose.imaging.Cache
``` java
// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Auto mode is flexible and efficient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Default value is 0, which means there is no upper limit
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// At any time you may check how many bytes currently allocated for memory or disk
// cache by examining the following properties
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Do some image processing as below
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

    // After executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.
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


Gets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher.

**Returns:**
boolean - `true` if reallocation is exact; otherwise, `false`.

The exact reallocation will perform reallocation of additional memory only up to the upper limit specified. When passing upper limit for in-memory during reallocation the cached data will be copied to disk if possible. When passing upper limit for disk memory during reallocation the appropriate exception is thrown. The performance should be higher if this option is turned off as no additional copying will be performed if possible, however this may also lead to pass upper limits specified for memory or disk.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if reallocation is exact; otherwise, `false`.

The exact reallocation will perform reallocation of additional memory only up to the upper limit specified. When passing upper limit for in-memory during reallocation the cached data will be copied to disk if possible. When passing upper limit for disk memory during reallocation the appropriate exception is thrown. The performance should be higher if this option is turned off as no additional copying will be performed if possible, however this may also lead to pass upper limits specified for memory or disk. |


**Example:**
This example demonstrates how to use com.aspose.imaging.Cache
``` java
// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Auto mode is flexible and efficient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Default value is 0, which means there is no upper limit
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// At any time you may check how many bytes currently allocated for memory or disk
// cache by examining the following properties
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Do some image processing as below
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

    // After executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.
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


Gets the cache folder.

**Returns:**
java.lang.String - The cache folder.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Sets the cache folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The cache folder. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Gets the allocated in-memory bytes count.

**Returns:**
long - The allocated in-memory bytes count.

**Example:**
This example demonstrates how to use com.aspose.imaging.Cache
``` java
// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Auto mode is flexible and efficient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Default value is 0, which means there is no upper limit
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// At any time you may check how many bytes currently allocated for memory or disk
// cache by examining the following properties
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Do some image processing as below
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

    // After executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.
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


Gets the allocated disk bytes count.

**Returns:**
long - The allocated disk bytes count.

**Example:**
This example demonstrates how to use com.aspose.imaging.Cache
``` java
// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Auto mode is flexible and efficient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Default value is 0, which means there is no upper limit
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// At any time you may check how many bytes currently allocated for memory or disk
// cache by examining the following properties
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Do some image processing as below
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

    // After executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.
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


Gets the maximum available memory for cache in memory. The value specified is megabytes count.

**Returns:**
int - The maximum memory for cache.

Value of 0 will consume all available memory and serves as no upper limit.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Sets the maximum available memory for cache in memory. The value specified is megabytes count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum memory for cache.

Value of 0 will consume all available memory and serves as no upper limit. |


**Example:**
This example demonstrates how to use com.aspose.imaging.Cache
``` java
// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Auto mode is flexible and efficient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Default value is 0, which means there is no upper limit
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// At any time you may check how many bytes currently allocated for memory or disk
// cache by examining the following properties
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Do some image processing as below
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

    // After executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.
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


Gets the maximum available disk space for cache. The value specified is megabytes count.

**Returns:**
int - The maximum available disk space for cache.

Value of 0 will consume all available memory and serves as no upper limit.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Sets the maximum available disk space for cache. The value specified is megabytes count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum available disk space for cache.

Value of 0 will consume all available memory and serves as no upper limit. |


**Example:**
This example demonstrates how to use com.aspose.imaging.Cache
``` java
// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Auto mode is flexible and efficient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Default value is 0, which means there is no upper limit
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// At any time you may check how many bytes currently allocated for memory or disk
// cache by examining the following properties
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Do some image processing as below
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

    // After executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.
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


Gets or sets the cache scheme used.

**Returns:**
int - The cache scheme used.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Sets the cache scheme used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The cache scheme used. |


**Example:**
This example demonstrates how to use com.aspose.imaging.Cache
``` java
// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Auto mode is flexible and efficient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Default value is 0, which means there is no upper limit
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// At any time you may check how many bytes currently allocated for memory or disk
// cache by examining the following properties
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Do some image processing as below
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

    // After executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// The allocation properties may be used to check whether all Aspose.Imaging objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.
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


Sets the `Cache` settings to defaults.

