---
title: "Cache"
second_title: "Aspose.Imaging för Java API-referens"
description: "Innehåller cacheinställningar."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Innehåller cacheinställningar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Hämtar ett värde som indikerar om omallokering ska vara exakt eller inte. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Ställer in ett värde som indikerar om omallokering ska vara exakt eller inte. |
| [getCacheFolder()](#getCacheFolder--) | Hämtar cachemappen. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Ställer in cachemappen. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Hämtar antalet allokerade byte i minnet. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Hämtar antalet allokerade byte på disken. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Hämtar det maximala tillgängliga minnet för cache i minnet. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Ställer in det maximala tillgängliga minnet för cache i minnet. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Hämtar det maximala tillgängliga diskutrymmet för cache. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Ställer in det maximala tillgängliga diskutrymmet för cache. |
| [getCacheType()](#getCacheType--) | Hämtar eller ställer in det använda cache‑schemat. |
| [setCacheType(int value)](#setCacheType-int-) | Ställer in det använda cache‑schemat. |
| [setDefaults()](#setDefaults--) | Ställer in `Cache`-inställningarna till standardvärden. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// Som standard är cachemappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cachemapp än standard, som följande:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Automatiskt läge är flexibelt och effektivt
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom den kan påverka prestandan avsevärt
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cacha genom att undersöka följande egenskaper
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Utför någon bildbehandling enligt nedan
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

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.
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


Hämtar ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokeringen inte är exakt bör prestandan vara högre.

**Returns:**
boolean - `true` om omallokeringen är exakt; annars `false`.

Den exakta omallokeringen kommer endast att omallokera ytterligare minne upp till den angivna övre gränsen. När en övre gräns för minnet anges under omallokeringen kommer cachade data att kopieras till disk om möjligt. När en övre gräns för diskminnet anges under omallokeringen kastas ett lämpligt undantag. Prestandan bör vara högre om detta alternativ är avstängt eftersom ingen ytterligare kopiering kommer att utföras om möjligt, men detta kan också leda till att de angivna övre gränserna för minne eller disk överskrids.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Ställer in ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokeringen inte är exakt bör prestandan vara högre.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | `true` om omallokeringen är exakt; annars `false`. |

Den exakta omallokeringen kommer endast att omallokera ytterligare minne upp till den angivna övre gränsen. När en övre gräns för minnet anges under omallokeringen kommer cachade data att kopieras till disk om möjligt. När en övre gräns för diskminnet anges under omallokeringen kastas ett lämpligt undantag. Prestandan bör vara högre om detta alternativ är avstängt eftersom ingen ytterligare kopiering kommer att utföras om möjligt, men detta kan också leda till att de angivna övre gränserna för minne eller disk överskrids. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Som standard är cachemappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cachemapp än standard, som följande:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Automatiskt läge är flexibelt och effektivt
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom den kan påverka prestandan avsevärt
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cacha genom att undersöka följande egenskaper
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Utför någon bildbehandling enligt nedan
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

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.
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


Hämtar cachemappen.

**Returns:**
java.lang.String - Cachemappen.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Ställer in cachemappen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Cachemappen. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Hämtar antalet allokerade byte i minnet.

**Returns:**
long - Antalet allokerade byte i minnet.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Som standard är cachemappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cachemapp än standard, som följande:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Automatiskt läge är flexibelt och effektivt
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom den kan påverka prestandan avsevärt
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cacha genom att undersöka följande egenskaper
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Utför någon bildbehandling enligt nedan
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

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.
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


Hämtar antalet allokerade byte på disken.

**Returns:**
long - Antalet allokerade byte på disk.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Som standard är cachemappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cachemapp än standard, som följande:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Automatiskt läge är flexibelt och effektivt
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom den kan påverka prestandan avsevärt
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cacha genom att undersöka följande egenskaper
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Utför någon bildbehandling enligt nedan
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

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.
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


Hämtar det maximala tillgängliga minnet för cache i minnet. Det angivna värdet är antalet megabyte.

**Returns:**
int - Det maximala minnet för cache.

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Ställer in det maximala tillgängliga minnet för cache i minnet. Det angivna värdet är antalet megabyte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Det maximala minnet för cache. |

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Som standard är cachemappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cachemapp än standard, som följande:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Automatiskt läge är flexibelt och effektivt
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom den kan påverka prestandan avsevärt
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cacha genom att undersöka följande egenskaper
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Utför någon bildbehandling enligt nedan
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

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.
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


Hämtar det maximala tillgängliga diskutrymmet för cache. Det angivna värdet är antalet megabyte.

**Returns:**
int - Det maximala tillgängliga diskutrymmet för cache.

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Ställer in det maximala tillgängliga diskutrymmet för cache. Det angivna värdet är antalet megabyte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Det maximala tillgängliga diskutrymmet för cache. |

Värdet 0 kommer att använda allt tillgängligt minne och fungerar som ingen övre gräns. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Som standard är cachemappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cachemapp än standard, som följande:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Automatiskt läge är flexibelt och effektivt
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom den kan påverka prestandan avsevärt
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cacha genom att undersöka följande egenskaper
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Utför någon bildbehandling enligt nedan
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

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.
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


Hämtar eller ställer in det använda cache‑schemat.

**Returns:**
int - Det cache-schema som används.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Ställer in det använda cache‑schemat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Det cache-schema som används. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Som standard är cachemappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cachemapp än standard, som följande:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Automatiskt läge är flexibelt och effektivt
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom den kan påverka prestandan avsevärt
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cacha genom att undersöka följande egenskaper
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Utför någon bildbehandling enligt nedan
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

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.Imaging-objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.
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


Ställer in `Cache`-inställningarna till standardvärden.

