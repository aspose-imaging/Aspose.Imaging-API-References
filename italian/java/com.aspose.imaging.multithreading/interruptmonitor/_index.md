---
title: "InterruptMonitor"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta informazioni sull'interruzione."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Rappresenta informazioni sull'interruzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Inizializza una nuova istanza della classe `InterruptMonitor`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Ottiene l'istanza IInterruptMonitor che è unica per ogni thread. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Imposta l'istanza IInterruptMonitor che è unica per ogni thread. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Restituisce `true` se il monitor di interruzione per il thread corrente esiste ed è stato interrotto, altrimenti `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | Rimuove tutti i monitor dei thread, inclusi quelli per i thread attivi. |
| [isInterrupted()](#isInterrupted--) | Ottiene il valore che indica se le operazioni devono essere interrotte. |
| [interrupt()](#interrupt--) | Invia una richiesta per interrompere le operazioni. |

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

            // Imposta un'istanza locale al thread del monitor di interruzione.
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

                // Reimposta l'istanza locale al thread del monitor di interruzione.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Stampa informazioni dettagliate su eventuali eccezioni inattese.
            System.out.println(e);
        }
    }
}

// Ecco l'esempio principale che utilizza la classe Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Avvia il worker in un thread dedicato.
Thread thread = new Thread(worker);
thread.start();

try {
    // Esegui qui qualche lavoro significativo
    Thread.sleep(2000);

    // Richiesta di interrompere il thread del worker
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Attendi l'interruzione.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// L'output potrebbe apparire così:
// Interruzione del thread di lavoro #11 alle Tue Aug 06 17:57:52 YEKT 2019
// Il thread di lavoro #11 è stato interrotto alle Tue Aug 06 17:57:59 YEKT 2019
// Fatto. Premere ENTER per uscire.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Inizializza una nuova istanza della classe `InterruptMonitor`.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Ottiene l'istanza IInterruptMonitor che è unica per ogni thread.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Imposta l'istanza IInterruptMonitor che è unica per ogni thread.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Restituisce `true` se il monitor di interruzione per il thread corrente esiste ed è stato interrotto, altrimenti `false`.

**Returns:**
boolean - `true` se il monitor di interruzione per il thread corrente esiste, e è stato interrotto altrimenti `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Rimuove tutti i monitor dei thread, inclusi quelli per i thread attivi.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Ottiene il valore che indica se le operazioni devono essere interrotte.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


Invia una richiesta per interrompere le operazioni.


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

            // Imposta un'istanza locale al thread del monitor di interruzione.
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

                // Reimposta l'istanza locale al thread del monitor di interruzione.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Stampa informazioni dettagliate su eventuali eccezioni inattese.
            System.out.println(e);
        }
    }
}

// Ecco l'esempio principale che utilizza la classe Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Avvia il worker in un thread dedicato.
Thread thread = new Thread(worker);
thread.start();

try {
    // Esegui qui qualche lavoro significativo
    Thread.sleep(2000);

    // Richiesta di interrompere il thread del worker
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Attendi l'interruzione.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// L'output potrebbe apparire così:
// Interruzione del thread di lavoro #11 alle Tue Aug 06 17:57:52 YEKT 2019
// Il thread di lavoro #11 è stato interrotto alle Tue Aug 06 17:57:59 YEKT 2019
// Fatto. Premere ENTER per uscire.
```

