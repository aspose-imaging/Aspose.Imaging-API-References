---
title: "InterruptMonitor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل معلومات حول الانقطاع."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

يمثل معلومات حول الانقطاع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | ينشئ مثيلًا جديدًا من الفئة `InterruptMonitor`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | يحصل على مثيل IInterruptMonitor الذي يكون فريدًا لكل مسار. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | يضبط مثيل IInterruptMonitor الذي يكون فريدًا لكل مسار. |
| [isThreadInterrupted()](#isThreadInterrupted--) | يرجع `true` إذا كان مراقب المقاطعة للمسار الحالي موجودًا وتم مقاطعته، وإلا يرجع `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | يزيل جميع مراقبي المسارات، بما في ذلك تلك الخاصة بالمسارات الحية. |
| [isInterrupted()](#isInterrupted--) | يحصل على القيمة التي تشير إلى ما إذا كان يجب مقاطعة العمليات. |
| [interrupt()](#interrupt--) | يرسل طلبًا لمقاطعة العمليات. |

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

            // تعيين نسخة محلية للموضوع من مراقب المقاطعة.
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

                // إعادة تعيين النسخة المحلية للموضوع من مراقب المقاطعة.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // طباعة معلومات مفصلة حول أي استثناء غير متوقع.
            System.out.println(e);
        }
    }
}

// إليك المثال الرئيسي باستخدام الفئة Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// ابدأ العامل في خيط مخصص.
Thread thread = new Thread(worker);
thread.start();

try {
    // قم ببعض العمل المفيد هنا
    Thread.sleep(2000);

    // طلب مقاطعة خيط العامل
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // انتظر المقاطعة.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// قد يبدو الإخراج هكذا:
// جاري مقاطعة خيط العامل #11 في Tue Aug 06 17:57:52 YEKT 2019
// تم مقاطعة خيط العامل #11 في Tue Aug 06 17:57:59 YEKT 2019
// تم. اضغط ENTER للخروج.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


ينشئ مثيلًا جديدًا من الفئة `InterruptMonitor`.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


يحصل على مثيل IInterruptMonitor الذي يكون فريدًا لكل مسار.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


يضبط مثيل IInterruptMonitor الذي يكون فريدًا لكل مسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


يرجع `true` إذا كان مراقب المقاطعة للمسار الحالي موجودًا وتم مقاطعته، وإلا يرجع `false`.

**Returns:**
منطقي - `true` إذا كان مراقب المقاطعة للموضوع الحالي موجودًا، وتم مقاطعته؛ وإلا `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


يزيل جميع مراقبي المسارات، بما في ذلك تلك الخاصة بالمسارات الحية.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


يحصل على القيمة التي تشير إلى ما إذا كان يجب مقاطعة العمليات.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


يرسل طلبًا لمقاطعة العمليات.


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

            // تعيين نسخة محلية للموضوع من مراقب المقاطعة.
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

                // إعادة تعيين النسخة المحلية للموضوع من مراقب المقاطعة.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // طباعة معلومات مفصلة حول أي استثناء غير متوقع.
            System.out.println(e);
        }
    }
}

// إليك المثال الرئيسي باستخدام الفئة Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// ابدأ العامل في خيط مخصص.
Thread thread = new Thread(worker);
thread.start();

try {
    // قم ببعض العمل المفيد هنا
    Thread.sleep(2000);

    // طلب مقاطعة خيط العامل
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // انتظر المقاطعة.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// قد يبدو الإخراج هكذا:
// جاري مقاطعة خيط العامل #11 في Tue Aug 06 17:57:52 YEKT 2019
// تم مقاطعة خيط العامل #11 في Tue Aug 06 17:57:59 YEKT 2019
// تم. اضغط ENTER للخروج.
```

