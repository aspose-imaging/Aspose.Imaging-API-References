---
title: InterruptMonitor
second_title: Aspose.Imaging for Java API Reference
description: Represents information about interruption.
type: docs
weight: 10
url: /java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Represents information about interruption.
## Constructors

| Constructor | Description |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initializes a new instance of the `InterruptMonitor` class. |
## Methods

| Method | Description |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Gets the IInterruptMonitor instance which is unique for each thread. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Sets the IInterruptMonitor instance which is unique for each thread. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Returns `true` if interrupt monitor for current thread exists, and it was interrupted otherwise `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | Removes all thread monitors, included the ones for alive threads. |
| [isInterrupted()](#isInterrupted--) | Gets the value indicating whether operations should be interrupted. |
| [interrupt()](#interrupt--) | Sends a request to interrupt operations. |

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

            // Set a thread-local instance of the interrupt monitor.
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

                // Reset the thread-local instance of the interrupt monitor.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Print detailed information about any unexpected exception.
            System.out.println(e);
        }
    }
}

// Here is the main example using the Worker class.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Start the worker in a dedicated thread.
Thread thread = new Thread(worker);
thread.start();

try {
    // Do some meaningful work here
    Thread.sleep(2000);

    // Request to interrupt the worker thread
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Wait for interruption.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// The output may look like this:
// Interrupting the worker thread #11 at Tue Aug 06 17:57:52 YEKT 2019
// The worker thread #11 has been interrupted at Tue Aug 06 17:57:59 YEKT 2019
// Done. Press ENTER to exit.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initializes a new instance of the `InterruptMonitor` class.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Gets the IInterruptMonitor instance which is unique for each thread.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Sets the IInterruptMonitor instance which is unique for each thread.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Returns `true` if interrupt monitor for current thread exists, and it was interrupted otherwise `false`.

**Returns:**
boolean - `true` if interrupt monitor for current thread exists, and it was interrupted otherwise `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Removes all thread monitors, included the ones for alive threads.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Gets the value indicating whether operations should be interrupted.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


Sends a request to interrupt operations.


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

            // Set a thread-local instance of the interrupt monitor.
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

                // Reset the thread-local instance of the interrupt monitor.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Print detailed information about any unexpected exception.
            System.out.println(e);
        }
    }
}

// Here is the main example using the Worker class.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Start the worker in a dedicated thread.
Thread thread = new Thread(worker);
thread.start();

try {
    // Do some meaningful work here
    Thread.sleep(2000);

    // Request to interrupt the worker thread
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Wait for interruption.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// The output may look like this:
// Interrupting the worker thread #11 at Tue Aug 06 17:57:52 YEKT 2019
// The worker thread #11 has been interrupted at Tue Aug 06 17:57:59 YEKT 2019
// Done. Press ENTER to exit.
```

