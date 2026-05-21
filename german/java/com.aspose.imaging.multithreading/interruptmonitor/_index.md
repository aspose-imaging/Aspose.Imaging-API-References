---
title: "InterruptMonitor"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt Informationen über Unterbrechungen dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Stellt Informationen über Unterbrechungen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initialisiert eine neue Instanz der Klasse `InterruptMonitor`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Gibt die IInterruptMonitor-Instanz zurück, die für jeden Thread eindeutig ist. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Gibt `true` zurück, wenn ein Interrupt-Monitor für den aktuellen Thread existiert und unterbrochen wurde, andernfalls `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | Entfernt alle Thread-Monitore, einschließlich derjenigen für aktive Threads. |
| [isInterrupted()](#isInterrupted--) | Gibt den Wert zurück, der angibt, ob Vorgänge unterbrochen werden sollen. |
| [interrupt()](#interrupt--) | Sendet eine Anfrage, um Vorgänge zu unterbrechen. |

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

            // Setzt eine threadlokale Instanz des Interrupt-Monitors.
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

                // Setzt die threadlokale Instanz des Interrupt-Monitors zurück.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Gibt detaillierte Informationen über jede unerwartete Ausnahme aus.
            System.out.println(e);
        }
    }
}

// Hier ist das Hauptbeispiel, das die Worker-Klasse verwendet.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Startet den Worker in einem eigenen Thread.
Thread thread = new Thread(worker);
thread.start();

try {
    // Führe hier einige sinnvolle Arbeiten aus
    Thread.sleep(2000);

    // Anfrage, den Worker-Thread zu unterbrechen
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Warte auf Unterbrechung.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Die Ausgabe könnte so aussehen:
// Unterbreche den Arbeitsthread #11 um Tue Aug 06 17:57:52 YEKT 2019
// Der Arbeitsthread #11 wurde um Tue Aug 06 17:57:59 YEKT 2019 unterbrochen
// Fertig. Drücken Sie ENTER, um zu beenden.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initialisiert eine neue Instanz der Klasse `InterruptMonitor`.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Gibt die IInterruptMonitor-Instanz zurück, die für jeden Thread eindeutig ist.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Setzt die IInterruptMonitor-Instanz, die für jeden Thread eindeutig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Gibt `true` zurück, wenn ein Interrupt-Monitor für den aktuellen Thread existiert und unterbrochen wurde, andernfalls `false`.

**Returns:**
boolescher Wert - `true`, wenn ein Interrupt‑Monitor für den aktuellen Thread existiert und er unterbrochen wurde, sonst `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Entfernt alle Thread-Monitore, einschließlich derjenigen für aktive Threads.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Gibt den Wert zurück, der angibt, ob Vorgänge unterbrochen werden sollen.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


Sendet eine Anfrage, um Vorgänge zu unterbrechen.


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

            // Setzt eine threadlokale Instanz des Interrupt-Monitors.
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

                // Setzt die threadlokale Instanz des Interrupt-Monitors zurück.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Gibt detaillierte Informationen über jede unerwartete Ausnahme aus.
            System.out.println(e);
        }
    }
}

// Hier ist das Hauptbeispiel, das die Worker-Klasse verwendet.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Startet den Worker in einem eigenen Thread.
Thread thread = new Thread(worker);
thread.start();

try {
    // Führe hier einige sinnvolle Arbeiten aus
    Thread.sleep(2000);

    // Anfrage, den Worker-Thread zu unterbrechen
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Warte auf Unterbrechung.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Die Ausgabe könnte so aussehen:
// Unterbreche den Arbeitsthread #11 um Tue Aug 06 17:57:52 YEKT 2019
// Der Arbeitsthread #11 wurde um Tue Aug 06 17:57:59 YEKT 2019 unterbrochen
// Fertig. Drücken Sie ENTER, um zu beenden.
```

