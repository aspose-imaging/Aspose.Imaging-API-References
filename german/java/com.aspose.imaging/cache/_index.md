---
title: "Cache"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Enthält Cache-Einstellungen."
type: docs
weight: 15
url: /de/java/com.aspose.imaging/cache/
---
**Inheritance:**
java.lang.Object
```
public final class Cache
```

Enthält Cache-Einstellungen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Liest einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Setzt einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. |
| [getCacheFolder()](#getCacheFolder--) | Liest den Cache-Ordner. |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Setzt den Cache-Ordner. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Liest die Anzahl der im Speicher zugewiesenen Bytes. |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Liest die Anzahl der auf der Festplatte zugewiesenen Bytes. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Liest den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Setzt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Liest den maximal verfügbaren Festplattenspeicher für den Cache. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Setzt den maximal verfügbaren Festplattenspeicher für den Cache. |
| [getCacheType()](#getCacheType--) | Liest oder setzt das verwendete Cache-Schema. |
| [setCacheType(int value)](#setCacheType-int-) | Setzt das verwendete Cache-Schema. |
| [setDefaults()](#setDefaults--) | Setzt die `Cache`-Einstellungen auf die Standardwerte. |

## Example: This example demonstrates how to use com.aspose.imaging.Cache

``` java
// Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache-Ordner als den Standard angeben, wie im Folgenden:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Der Automodus ist flexibel und effizient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt.
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann.
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind.
// Cache durch Untersuchung der folgenden Eigenschaften.
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Führen Sie die nachstehende Bildverarbeitung durch.
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

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle **Aspose.Imaging**‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
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


Gibt einen Wert zurück, der angibt, ob die Neu­allokation exakt sein soll oder nicht. Ist die Neu­allokation nicht exakt, sollte die Leistung höher sein.

**Returns:**
boolean – `true`, wenn die Neu­allokation exakt ist; andernfalls `false`.

Die exakte Neu­allokation führt die Neu­allokation zusätzlichen Speichers nur bis zur angegebenen Obergrenze durch. Wird bei der Neu­allokation die Obergrenze für den In‑Memory‑Speicher übergeben, werden die zwischengespeicherten Daten nach Möglichkeit auf die Festplatte kopiert. Wird die Obergrenze für den Festplattenspeicher übergeben, wird die entsprechende Ausnahme ausgelöst. Die Leistung sollte höher sein, wenn diese Option deaktiviert ist, da keine zusätzlichen Kopiervorgänge durchgeführt werden, sofern möglich; dies kann jedoch dazu führen, dass die angegebenen Obergrenzen für Speicher oder Festplatte überschritten werden.
### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Setzt einen Wert, der angibt, ob die Neu­allokation exakt sein soll oder nicht. Ist die Neu­allokation nicht exakt, sollte die Leistung höher sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | `true`, wenn die Neu­allokation exakt ist; andernfalls `false`. |

Die exakte Neu­allokation führt die Neu­allokation zusätzlichen Speichers nur bis zur angegebenen Obergrenze durch. Wird bei der Neu­allokation die Obergrenze für den In‑Memory‑Speicher übergeben, werden die zwischengespeicherten Daten nach Möglichkeit auf die Festplatte kopiert. Wird die Obergrenze für den Festplattenspeicher übergeben, wird die entsprechende Ausnahme ausgelöst. Die Leistung sollte höher sein, wenn diese Option deaktiviert ist, da keine zusätzlichen Kopiervorgänge durchgeführt werden, sofern möglich; dies kann jedoch dazu führen, dass die angegebenen Obergrenzen für Speicher oder Festplatte überschritten werden. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache-Ordner als den Standard angeben, wie im Folgenden:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Der Automodus ist flexibel und effizient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt.
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann.
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind.
// Cache durch Untersuchung der folgenden Eigenschaften.
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Führen Sie die nachstehende Bildverarbeitung durch.
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

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle **Aspose.Imaging**‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
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


Liest den Cache-Ordner.

**Returns:**
java.lang.String – Der Cache‑Ordner.
### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Setzt den Cache-Ordner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Der Cache‑Ordner. |

### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Liest die Anzahl der im Speicher zugewiesenen Bytes.

**Returns:**
long – Die zugewiesene In‑Memory‑Byte‑Anzahl.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache-Ordner als den Standard angeben, wie im Folgenden:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Der Automodus ist flexibel und effizient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt.
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann.
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind.
// Cache durch Untersuchung der folgenden Eigenschaften.
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Führen Sie die nachstehende Bildverarbeitung durch.
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

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle **Aspose.Imaging**‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
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


Liest die Anzahl der auf der Festplatte zugewiesenen Bytes.

**Returns:**
long – Die zugewiesene Festplatten‑Byte‑Anzahl.

**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache-Ordner als den Standard angeben, wie im Folgenden:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Der Automodus ist flexibel und effizient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt.
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann.
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind.
// Cache durch Untersuchung der folgenden Eigenschaften.
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Führen Sie die nachstehende Bildverarbeitung durch.
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

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle **Aspose.Imaging**‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
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


Gibt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher zurück. Der angegebene Wert ist die Megabyte‑Anzahl.

**Returns:**
int – Der maximale Speicher für den Cache.

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als keine Obergrenze.
### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Setzt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. Der angegebene Wert ist die Megabyte‑Anzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der maximale Speicher für den Cache. |

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als keine Obergrenze. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache-Ordner als den Standard angeben, wie im Folgenden:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Der Automodus ist flexibel und effizient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt.
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann.
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind.
// Cache durch Untersuchung der folgenden Eigenschaften.
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Führen Sie die nachstehende Bildverarbeitung durch.
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

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle **Aspose.Imaging**‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
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


Liefert den maximal verfügbaren Festplattenspeicher für den Cache. Der angegebene Wert ist die Megabyte-Anzahl.

**Returns:**
int - Der maximal verfügbare Festplattenspeicher für den Cache.

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als keine Obergrenze.
### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Legt den maximal verfügbaren Festplattenspeicher für den Cache fest. Der angegebene Wert ist die Megabyte-Anzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der maximal verfügbare Festplattenspeicher für den Cache. |

Ein Wert von 0 verbraucht den gesamten verfügbaren Speicher und dient als keine Obergrenze. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache-Ordner als den Standard angeben, wie im Folgenden:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Der Automodus ist flexibel und effizient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt.
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann.
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind.
// Cache durch Untersuchung der folgenden Eigenschaften.
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Führen Sie die nachstehende Bildverarbeitung durch.
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

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle **Aspose.Imaging**‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
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


Liest oder setzt das verwendete Cache-Schema.

**Returns:**
int - Das verwendete Cache-Schema.
### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Setzt das verwendete Cache-Schema.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das verwendete Cache-Schema. |


**Example: This example demonstrates how to use com.aspose.imaging.Cache**

``` java
// Standardmäßig ist der Cache-Ordner auf das lokale Temp-Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache-Ordner als den Standard angeben, wie im Folgenden:
// com.aspose.imaging.Cache.setCacheFolder("C:\\Temp");

// Der Automodus ist flexibel und effizient
com.aspose.imaging.Cache.setCacheType(com.aspose.imaging.CacheType.Auto);

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt.
com.aspose.imaging.Cache.setMaxDiskSpaceForCache(1073741824); // 1 gigabyte
com.aspose.imaging.Cache.setMaxMemoryForCache(1073741824); // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann.
com.aspose.imaging.Cache.setExactReallocateOnly(false);

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind.
// Cache durch Untersuchung der folgenden Eigenschaften.
long l1 = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
long l2 = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();

System.out.println("Initial values.");
System.out.println("Allocated disk space, in bytes: " + l1);
System.out.println("Allocated memory, in bytes: " + l2);
System.out.println("--------------------------------------");

// Führen Sie die nachstehende Bildverarbeitung durch.
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

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = com.aspose.imaging.Cache.getAllocatedDiskBytesCount();
    long memoryBytes = com.aspose.imaging.Cache.getAllocatedMemoryBytesCount();
    System.out.println("Allocated disk space, in bytes: " + diskBytes);
    System.out.println("Allocated memory, in bytes: " + memoryBytes);
    System.out.println("--------------------------------------");
} finally {
    System.out.println("Dispose image.");
    image.dispose();
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle **Aspose.Imaging**‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
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


Setzt die `Cache`-Einstellungen auf die Standardwerte.

