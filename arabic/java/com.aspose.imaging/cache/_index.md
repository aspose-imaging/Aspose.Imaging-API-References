---
title: "Cache"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على إعدادات الذاكرة المؤقتة."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

يحتوي على إعدادات الذاكرة المؤقتة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | يحصل على قيمة تشير إلى ما إذا كان يجب أن يكون إعادة التخصيص دقيقة أم لا. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب أن يكون إعادة التخصيص دقيقة أم لا. |
| [getCacheFolder()](#getCacheFolder--) | يحصل على مجلد التخزين المؤقت. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | يضبط مجلد التخزين المؤقت. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | يحصل على عدد البايتات المخصصة في الذاكرة. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | يحصل على عدد البايتات المخصصة على القرص. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | يحصل على الحد الأقصى للذاكرة المتاحة للتخزين المؤقت في الذاكرة. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | يضبط الحد الأقصى للذاكرة المتاحة للتخزين المؤقت في الذاكرة. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | يحصل على الحد الأقصى للمساحة المتاحة على القرص للتخزين المؤقت. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | يضبط الحد الأقصى للمساحة المتاحة على القرص للتخزين المؤقت. |
| [getCacheType()](#getCacheType--) | يحصل أو يضبط مخطط التخزين المؤقت المستخدم. |
| [setCacheType(int value)](#setCacheType-int-) | يضبط مخطط التخزين المؤقت المستخدم. |
| [setDefaults()](#setDefaults--) | يضبط إعدادات `Cache` إلى القيم الافتراضية. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// بشكل افتراضي يتم تعيين مجلد التخزين المؤقت إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد تخزين مؤقت آخر غير الافتراضي كما يلي:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// الوضع التلقائي مرن وفعال
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// قم ببعض معالجة الصور كما يلي
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

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على بعض الكائنات، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
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


يحصل على قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة، يجب أن يكون الأداء أعلى.

**Returns:**
منطقي - `true` إذا كانت إعادة التخصيص دقيقة؛ وإلا `false`.

ستقوم إعادة التخصيص الدقيقة بإعادة تخصيص الذاكرة الإضافية فقط حتى الحد الأعلى المحدد. عند تمرير الحد الأعلى للذاكرة الداخلية أثناء إعادة التخصيص، سيتم نسخ البيانات المؤقتة إلى القرص إذا أمكن. عند تمرير الحد الأعلى لذاكرة القرص أثناء إعادة التخصيص، يتم طرح الاستثناء المناسب. يجب أن يكون الأداء أعلى إذا تم إيقاف هذا الخيار لأنه لن يتم إجراء نسخ إضافي إذا كان ذلك ممكنًا، ومع ذلك قد يؤدي ذلك أيضًا إلى تجاوز الحدود العليا المحددة للذاكرة أو القرص.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة، يجب أن يكون الأداء أعلى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | `true` إذا كانت إعادة التخصيص دقيقة؛ وإلا `false`. |

ستقوم إعادة التخصيص الدقيقة بإعادة تخصيص الذاكرة الإضافية فقط حتى الحد الأعلى المحدد. عند تمرير الحد الأعلى للذاكرة الداخلية أثناء إعادة التخصيص، سيتم نسخ البيانات المؤقتة إلى القرص إذا أمكن. عند تمرير الحد الأعلى لذاكرة القرص أثناء إعادة التخصيص، يتم طرح الاستثناء المناسب. يجب أن يكون الأداء أعلى إذا تم إيقاف هذا الخيار لأنه لن يتم إجراء نسخ إضافي إذا كان ذلك ممكنًا، ومع ذلك قد يؤدي ذلك أيضًا إلى تجاوز الحدود العليا المحددة للذاكرة أو القرص. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// بشكل افتراضي يتم تعيين مجلد التخزين المؤقت إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد تخزين مؤقت آخر غير الافتراضي كما يلي:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// الوضع التلقائي مرن وفعال
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// قم ببعض معالجة الصور كما يلي
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

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على بعض الكائنات، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
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


يحصل على مجلد التخزين المؤقت.

**Returns:**
java.lang.String - مجلد الذاكرة المؤقتة.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


يضبط مجلد التخزين المؤقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | مجلد الذاكرة المؤقتة. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


يحصل على عدد البايتات المخصصة في الذاكرة.

**Returns:**
long - عدد البايتات المخصصة في الذاكرة.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// بشكل افتراضي يتم تعيين مجلد التخزين المؤقت إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد تخزين مؤقت آخر غير الافتراضي كما يلي:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// الوضع التلقائي مرن وفعال
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// قم ببعض معالجة الصور كما يلي
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

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على بعض الكائنات، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
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


يحصل على عدد البايتات المخصصة على القرص.

**Returns:**
long - عدد البايتات المخصصة على القرص.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// بشكل افتراضي يتم تعيين مجلد التخزين المؤقت إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد تخزين مؤقت آخر غير الافتراضي كما يلي:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// الوضع التلقائي مرن وفعال
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// قم ببعض معالجة الصور كما يلي
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

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على بعض الكائنات، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
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


يحصل على الحد الأقصى للذاكرة المتاحة للذاكرة المؤقتة في الذاكرة. القيمة المحددة هي عدد الميجابايت.

**Returns:**
int - الحد الأقصى للذاكرة للذاكرة المؤقتة.

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


يضبط الحد الأقصى للذاكرة المتاحة للذاكرة المؤقتة في الذاكرة. القيمة المحددة هي عدد الميجابايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | الحد الأقصى للذاكرة للذاكرة المؤقتة. |

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// بشكل افتراضي يتم تعيين مجلد التخزين المؤقت إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد تخزين مؤقت آخر غير الافتراضي كما يلي:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// الوضع التلقائي مرن وفعال
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// قم ببعض معالجة الصور كما يلي
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

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على بعض الكائنات، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
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


يحصل على الحد الأقصى المتاح لمساحة القرص المؤقت. القيمة المحددة هي عدد الميجابايت.

**Returns:**
int - الحد الأقصى المتاح لمساحة القرص المؤقت.

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


يضبط الحد الأقصى المتاح لمساحة القرص المؤقت. القيمة المحددة هي عدد الميجابايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | الحد الأقصى المتاح لمساحة القرص المؤقت. |

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// بشكل افتراضي يتم تعيين مجلد التخزين المؤقت إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد تخزين مؤقت آخر غير الافتراضي كما يلي:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// الوضع التلقائي مرن وفعال
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// قم ببعض معالجة الصور كما يلي
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

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على بعض الكائنات، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
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


يحصل أو يضبط مخطط التخزين المؤقت المستخدم.

**Returns:**
int - مخطط التخزين المؤقت المستخدم.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


يضبط مخطط التخزين المؤقت المستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | مخطط التخزين المؤقت المستخدم. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// بشكل افتراضي يتم تعيين مجلد التخزين المؤقت إلى دليل المؤقت المحلي للمستخدم.
// يمكنك أيضًا تحديد مجلد تخزين مؤقت آخر غير الافتراضي كما يلي:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// الوضع التلقائي مرن وفعال
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// القيمة الافتراضية هي 0، مما يعني عدم وجود حد أعلى
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// لا يُنصح بتغيير الخاصية التالية لأنها قد تؤثر بشكل كبير على الأداء
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// في أي وقت يمكنك التحقق من عدد البايتات المخصصة حاليًا للذاكرة أو القرص
// الذاكرة المؤقتة بفحص الخصائص التالية
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// قم ببعض معالجة الصور كما يلي
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

    // بعد تنفيذ الشيفرة أعلاه سيتم تخصيص 40000 بايت في الذاكرة.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// يمكن استخدام خصائص التخصيص للتحقق مما إذا كانت جميع كائنات Aspose.Imaging قد تم تحريرها بشكل صحيح.
// في حال نسيت استدعاء dispose على بعض الكائنات، ستكون قيم الذاكرة المؤقتة مختلفة عن 0.
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


يضبط إعدادات `Cache` إلى القيم الافتراضية.

