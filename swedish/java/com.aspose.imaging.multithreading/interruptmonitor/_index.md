---
title: "InterruptMonitor"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar information om avbrott."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Representerar information om avbrott.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initierar en ny instans av klassen `InterruptMonitor`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Hämtar IInterruptMonitor-instansen som är unik för varje tråd. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Ställer in IInterruptMonitor-instansen som är unik för varje tråd. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Returnerar `true` om avbrottsmonitor för den aktuella tråden finns, annars `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | Tar bort alla trådadmonitorer, inklusive de för aktiva trådar. |
| [isInterrupted()](#isInterrupted--) | Hämtar värdet som indikerar om operationer ska avbrytas. |
| [interrupt()](#interrupt--) | Skickar en begäran om att avbryta operationer. |

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

            // Ställ in en trådlokal instans av avbrottsmonitoren.
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

                // Återställ den trådlokala instansen av avbrottsmonitoren.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Skriv ut detaljerad information om något oväntat undantag.
            System.out.println(e);
        }
    }
}

// Här är huvudexemplet som använder klassen Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Starta arbetaren i en dedikerad tråd.
Thread thread = new Thread(worker);
thread.start();

try {
    // Utför något meningsfullt arbete här
    Thread.sleep(2000);

    // Begär att avbryta arbetstråden
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Vänta på avbrott.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Utdata kan se ut så här:
// Avbryter arbetstråden #11 kl. Tue Aug 06 17:57:52 YEKT 2019
// Arbetstråden #11 har avbrutits den Tue Aug 06 17:57:59 YEKT 2019
// Klart. Tryck på ENTER för att avsluta.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initierar en ny instans av klassen `InterruptMonitor`.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Hämtar IInterruptMonitor-instansen som är unik för varje tråd.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Ställer in IInterruptMonitor-instansen som är unik för varje tråd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Returnerar `true` om avbrottsmonitor för den aktuella tråden finns, annars `false`.

**Returns:**
boolean - `true` om avbrottsmonitor för aktuell tråd finns, och den avbröts annars `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Tar bort alla trådadmonitorer, inklusive de för aktiva trådar.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Hämtar värdet som indikerar om operationer ska avbrytas.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


Skickar en begäran om att avbryta operationer.


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

            // Ställ in en trådlokal instans av avbrottsmonitoren.
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

                // Återställ den trådlokala instansen av avbrottsmonitoren.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Skriv ut detaljerad information om något oväntat undantag.
            System.out.println(e);
        }
    }
}

// Här är huvudexemplet som använder klassen Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Starta arbetaren i en dedikerad tråd.
Thread thread = new Thread(worker);
thread.start();

try {
    // Utför något meningsfullt arbete här
    Thread.sleep(2000);

    // Begär att avbryta arbetstråden
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Vänta på avbrott.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Utdata kan se ut så här:
// Avbryter arbetstråden #11 kl. Tue Aug 06 17:57:52 YEKT 2019
// Arbetstråden #11 har avbrutits den Tue Aug 06 17:57:59 YEKT 2019
// Klart. Tryck på ENTER för att avsluta.
```

