---
title: "InterruptMonitor"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Kesinti hakkında bilgi temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Kesinti hakkında bilgi temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | `InterruptMonitor` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini ayarlar. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Mevcut iş parçacığı için kesinti izleyicisi varsa `true` döndürür, aksi takdirde `false` döndürür. |
| [removeAllMonitors()](#removeAllMonitors--) | Canlı iş parçacıkları dahil olmak üzere tüm iş parçacığı izleyicilerini kaldırır. |
| [isInterrupted()](#isInterrupted--) | İşlemlerin kesilmesi gerekip gerekmediğini gösteren değeri alır. |
| [interrupt()](#interrupt--) | İşlemleri kesmek için bir istek gönderir. |

## Example: The following example shows how to interrupt the long process of image conversion.

``` java
/**
 * <p>This is helper class which initiates image conversion and waits for its interruption.</p>
 */
class Worker implements Runnable {
    /**
     * The path to the input image.
     */
    private final String inputPath;

    /**
     * The path to the output image.
     */
    private final String outputPath;

    /**
     * The save options.
     */
    private final com.aspose.imaging.ImageOptionsBase saveOptions;

    /**
     * The interrupt monitor.
     */
    private final com.aspose.imaging.multithreading.InterruptMonitor monitor;

    /**
     * <p>Initializes a new instance of the {#link #Worker} class.</p>
     *
     * @param inputPath   The path to the input image.
     * @param outputPath  The path to the output image.
     * @param saveOptions The save options.
     * @param monitor     The interrupt monitor.
     */
    public Worker(String inputPath, String outputPath, com.aspose.imaging.ImageOptionsBase saveOptions, com.aspose.imaging.multithreading.InterruptMonitor monitor) {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /**
     * <p>Converts an image from one format to another. Handles interruption.</p>
     */
    public void run() {
        try {
            com.aspose.imaging.Image image = com.aspose.imaging.Image.load(this.inputPath);

            // Kesinti izleyicisinin iş parçacığı yerel bir örneğini ayarlar.
            com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(this.monitor);

            try {
                image.save(this.outputPath, this.saveOptions);
            } catch (com.aspose.imaging.coreexceptions.OperationInterruptedException e) {
                System.out.printf(
                        "The worker thread #%s has been interrupted at %s\r\n",
                        java.lang.Thread.currentThread().getId(),
                        new java.util.Date());
            } finally {
                image.dispose();

                // Kesinti izleyicisinin iş parçacığı yerel örneğini sıfırlar.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Beklenmeyen bir istisna hakkında ayrıntılı bilgi yazdırır.
            System.out.println(e);
        }
    }
}

// Worker sınıfını kullanan ana örnek burada.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Worker'ı ayrı bir iş parçacığında başlat.
Thread thread = new Thread(worker);
thread.start();

try {
    // Burada anlamlı bir iş yap.
    Thread.sleep(2000);

    // Worker iş parçacığını kesmek için istek gönder.
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Kesilme için bekle.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Çıktı şöyle görünebilir:
// İşçi iş parçacığı #11, Tue Aug 06 17:57:52 YEKT 2019 tarihinde kesiliyor
// İşçi iş parçacığı #11, Tue Aug 06 17:57:59 YEKT 2019 tarihinde kesildi.
// Tamam. Çıkmak için ENTER tuşuna basın.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


`InterruptMonitor` sınıfının yeni bir örneğini başlatır.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Mevcut iş parçacığı için kesinti izleyicisi varsa `true` döndürür, aksi takdirde `false` döndürür.

**Returns:**
boolean - `true` eğer mevcut iş parçacığı için kesinti izleyicisi varsa ve kesintiye uğradıysa, aksi takdirde `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Canlı iş parçacıkları dahil olmak üzere tüm iş parçacığı izleyicilerini kaldırır.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


İşlemlerin kesilmesi gerekip gerekmediğini gösteren değeri alır.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


İşlemleri kesmek için bir istek gönderir.


**Example: The following example shows how to interrupt the long process of image conversion.**

``` java
/**
 * <p>This is helper class which initiates image conversion and waits for its interruption.</p>
 */
class Worker implements Runnable {
    /**
     * The path to the input image.
     */
    private final String inputPath;

    /**
     * The path to the output image.
     */
    private final String outputPath;

    /**
     * The save options.
     */
    private final com.aspose.imaging.ImageOptionsBase saveOptions;

    /**
     * The interrupt monitor.
     */
    private final com.aspose.imaging.multithreading.InterruptMonitor monitor;

    /**
     * <p>Initializes a new instance of the {#link #Worker} class.</p>
     *
     * @param inputPath   The path to the input image.
     * @param outputPath  The path to the output image.
     * @param saveOptions The save options.
     * @param monitor     The interrupt monitor.
     */
    public Worker(String inputPath, String outputPath, com.aspose.imaging.ImageOptionsBase saveOptions, com.aspose.imaging.multithreading.InterruptMonitor monitor) {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /**
     * <p>Converts an image from one format to another. Handles interruption.</p>
     */
    public void run() {
        try {
            com.aspose.imaging.Image image = com.aspose.imaging.Image.load(this.inputPath);

            // Kesinti izleyicisinin iş parçacığı yerel bir örneğini ayarlar.
            com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(this.monitor);

            try {
                image.save(this.outputPath, this.saveOptions);
            } catch (com.aspose.imaging.coreexceptions.OperationInterruptedException e) {
                System.out.printf(
                        "The worker thread #%s has been interrupted at %s\r\n",
                        java.lang.Thread.currentThread().getId(),
                        new java.util.Date());
            } finally {
                image.dispose();

                // Kesinti izleyicisinin iş parçacığı yerel örneğini sıfırlar.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Beklenmeyen bir istisna hakkında ayrıntılı bilgi yazdırır.
            System.out.println(e);
        }
    }
}

// Worker sınıfını kullanan ana örnek burada.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Worker'ı ayrı bir iş parçacığında başlat.
Thread thread = new Thread(worker);
thread.start();

try {
    // Burada anlamlı bir iş yap.
    Thread.sleep(2000);

    // Worker iş parçacığını kesmek için istek gönder.
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Kesilme için bekle.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Çıktı şöyle görünebilir:
// İşçi iş parçacığı #11, Tue Aug 06 17:57:52 YEKT 2019 tarihinde kesiliyor
// İşçi iş parçacığı #11, Tue Aug 06 17:57:59 YEKT 2019 tarihinde kesildi.
// Tamam. Çıkmak için ENTER tuşuna basın.
```

