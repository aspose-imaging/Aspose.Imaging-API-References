---
title: "Önbellek"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Önbellek ayarlarını içerir."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Önbellek ayarlarını içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Yeniden tahsisatın tam olup olmayacağını gösteren bir değer alır. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Yeniden tahsisatın tam olup olmayacağını gösteren bir değer ayarlar. |
| [getCacheFolder()](#getCacheFolder--) | Önbellek klasörünü alır. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Önbellek klasörünü ayarlar. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Bellekte ayrılan bayt sayısını alır. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Diskte ayrılan bayt sayısını alır. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Bellekteki önbellek için kullanılabilir maksimum belleği alır. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Bellekteki önbellek için kullanılabilir maksimum belleği ayarlar. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Önbellek için kullanılabilir maksimum disk alanını alır. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Önbellek için kullanılabilir maksimum disk alanını ayarlar. |
| [getCacheType()](#getCacheType--) | Kullanılan önbellek şemasını alır veya ayarlar. |
| [setCacheType(int value)](#setCacheType-int-) | Kullanılan önbellek şemasını ayarlar. |
| [setDefaults()](#setDefaults--) | `Cache` ayarlarını varsayılanlara ayarlar. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// Varsayılan olarak önbellek klasörü, kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Otomatik mod esnek ve etkilidir
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Herhangi bir zamanda bellekte veya diskte şu anda tahsis edilen bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbellek
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
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

    // Yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt tahsis edilecektir.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz durumda önbellek değerleri 0'dan farklı olacaktır.
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


Yeniden tahsisin kesin olup olmadığını gösteren bir değer alır. Yeniden tahsis kesin değilse performans daha yüksek olmalıdır.

**Returns:**
boolean - `true` if reallocation is exact; otherwise, `false`.

Kesin yeniden tahsis, yalnızca belirtilen üst sınıra kadar ek bellek tahsisi yapar. Yeniden tahsis sırasında bellek için üst sınır verildiğinde, önbellekteki veri mümkünse diske kopyalanır. Disk belleği için üst sınır verildiğinde ise uygun istisna fırlatılır. Bu seçenek kapatıldığında, mümkün olduğunda ek kopyalama yapılmayacağı için performans daha yüksek olmalıdır; ancak bu, bellek veya disk için belirtilen üst sınırların aşılmasına da yol açabilir.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Yeniden tahsisin kesin olup olmadığını gösteren bir değer ayarlar. Yeniden tahsis kesin değilse performans daha yüksek olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | `true` eğer yeniden tahsis kesin ise; aksi takdirde `false`. |

Kesin yeniden tahsis, yalnızca belirtilen üst sınıra kadar ek bellek tahsisi yapar. Yeniden tahsis sırasında bellek için üst sınır verildiğinde, önbellekteki veri mümkünse diske kopyalanır. Disk belleği için üst sınır verildiğinde ise uygun istisna fırlatılır. Bu seçenek kapatıldığında, mümkün olduğunda ek kopyalama yapılmayacağı için performans daha yüksek olmalıdır; ancak bu, bellek veya disk için belirtilen üst sınırların aşılmasına da yol açabilir. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Varsayılan olarak önbellek klasörü, kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Otomatik mod esnek ve etkilidir
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Herhangi bir zamanda bellekte veya diskte şu anda tahsis edilen bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbellek
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
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

    // Yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt tahsis edilecektir.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz durumda önbellek değerleri 0'dan farklı olacaktır.
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


Önbellek klasörünü alır.

**Returns:**
java.lang.String - Önbellek klasörü.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Önbellek klasörünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Önbellek klasörü. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Bellekte ayrılan bayt sayısını alır.

**Returns:**
long - Bellekte tahsis edilen bayt sayısı.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Varsayılan olarak önbellek klasörü, kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Otomatik mod esnek ve etkilidir
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Herhangi bir zamanda bellekte veya diskte şu anda tahsis edilen bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbellek
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
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

    // Yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt tahsis edilecektir.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz durumda önbellek değerleri 0'dan farklı olacaktır.
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


Diskte ayrılan bayt sayısını alır.

**Returns:**
long - Diskte tahsis edilen bayt sayısı.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Varsayılan olarak önbellek klasörü, kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Otomatik mod esnek ve etkilidir
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Herhangi bir zamanda bellekte veya diskte şu anda tahsis edilen bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbellek
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
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

    // Yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt tahsis edilecektir.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz durumda önbellek değerleri 0'dan farklı olacaktır.
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


Bellekte önbellek için kullanılabilir en fazla belleği alır. Belirtilen değer megabayt sayısıdır.

**Returns:**
int - Önbellek için en fazla bellek.

0 değeri, tüm kullanılabilir belleği tüketir ve üst sınır olmadığı anlamına gelir.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Bellekte önbellek için kullanılabilir en fazla belleği ayarlar. Belirtilen değer megabayt sayısıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Önbellek için en fazla bellek. |

0 değeri, tüm kullanılabilir belleği tüketir ve üst sınır olmadığı anlamına gelir. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Varsayılan olarak önbellek klasörü, kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Otomatik mod esnek ve etkilidir
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Herhangi bir zamanda bellekte veya diskte şu anda tahsis edilen bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbellek
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
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

    // Yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt tahsis edilecektir.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz durumda önbellek değerleri 0'dan farklı olacaktır.
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


Önbellek için kullanılabilir en fazla disk alanını alır. Belirtilen değer megabayt sayısıdır.

**Returns:**
int - Önbellek için kullanılabilir en fazla disk alanı.

0 değeri, tüm kullanılabilir belleği tüketir ve üst sınır olmadığı anlamına gelir.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Önbellek için kullanılabilir en fazla disk alanını ayarlar. Belirtilen değer megabayt sayısıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Önbellek için kullanılabilir en fazla disk alanı. |

0 değeri, tüm kullanılabilir belleği tüketir ve üst sınır olmadığı anlamına gelir. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Varsayılan olarak önbellek klasörü, kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Otomatik mod esnek ve etkilidir
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Herhangi bir zamanda bellekte veya diskte şu anda tahsis edilen bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbellek
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
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

    // Yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt tahsis edilecektir.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz durumda önbellek değerleri 0'dan farklı olacaktır.
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


Kullanılan önbellek şemasını alır veya ayarlar.

**Returns:**
int - Kullanılan önbellek şeması.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Kullanılan önbellek şemasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Kullanılan önbellek şeması. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Varsayılan olarak önbellek klasörü, kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Otomatik mod esnek ve etkilidir
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Herhangi bir zamanda bellekte veya diskte şu anda tahsis edilen bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbellek
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
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

    // Yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt tahsis edilecektir.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Tahsis özellikleri, tüm Aspose.Imaging nesnelerinin doğru bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz durumda önbellek değerleri 0'dan farklı olacaktır.
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


`Cache` ayarlarını varsayılanlara ayarlar.

