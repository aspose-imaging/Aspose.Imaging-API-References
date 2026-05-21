---
title: "InterruptMonitor"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente des informations sur l'interruption."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Représente des informations sur l'interruption.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Initialise une nouvelle instance de la classe `InterruptMonitor`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Obtient l'instance IInterruptMonitor qui est unique pour chaque thread. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Définit l'instance IInterruptMonitor qui est unique pour chaque thread. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Renvoie `true` si le moniteur d'interruption du thread actuel existe et a été interrompu, sinon `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | Supprime tous les moniteurs de thread, y compris ceux des threads actifs. |
| [isInterrupted()](#isInterrupted--) | Obtient la valeur indiquant si les opérations doivent être interrompues. |
| [interrupt()](#interrupt--) | Envoie une requête pour interrompre les opérations. |

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

            // Définit une instance locale au thread du moniteur d'interruption.
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

                // Réinitialise l'instance locale au thread du moniteur d'interruption.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Affiche des informations détaillées sur toute exception inattendue.
            System.out.println(e);
        }
    }
}

// Voici l'exemple principal utilisant la classe Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Démarre le worker dans un thread dédié.
Thread thread = new Thread(worker);
thread.start();

try {
    // Effectuez un travail significatif ici.
    Thread.sleep(2000);

    // Demande d'interrompre le thread du worker.
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Attendez l'interruption.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// La sortie peut ressembler à ceci :
// Interruption du thread de travail #11 à Tue Aug 06 17:57:52 YEKT 2019
// Le thread de travail #11 a été interrompu à Tue Aug 06 17:57:59 YEKT 2019
// Terminé. Appuyez sur ENTRÉE pour quitter.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Initialise une nouvelle instance de la classe `InterruptMonitor`.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Obtient l'instance IInterruptMonitor qui est unique pour chaque thread.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Définit l'instance IInterruptMonitor qui est unique pour chaque thread.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Renvoie `true` si le moniteur d'interruption du thread actuel existe et a été interrompu, sinon `false`.

**Returns:**
booléen - `true` si le moniteur d'interruption pour le thread actuel existe et a été interrompu, sinon `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Supprime tous les moniteurs de thread, y compris ceux des threads actifs.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Obtient la valeur indiquant si les opérations doivent être interrompues.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


Envoie une requête pour interrompre les opérations.


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

            // Définit une instance locale au thread du moniteur d'interruption.
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

                // Réinitialise l'instance locale au thread du moniteur d'interruption.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Affiche des informations détaillées sur toute exception inattendue.
            System.out.println(e);
        }
    }
}

// Voici l'exemple principal utilisant la classe Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Démarre le worker dans un thread dédié.
Thread thread = new Thread(worker);
thread.start();

try {
    // Effectuez un travail significatif ici.
    Thread.sleep(2000);

    // Demande d'interrompre le thread du worker.
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Attendez l'interruption.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// La sortie peut ressembler à ceci :
// Interruption du thread de travail #11 à Tue Aug 06 17:57:52 YEKT 2019
// Le thread de travail #11 a été interrompu à Tue Aug 06 17:57:59 YEKT 2019
// Terminé. Appuyez sur ENTRÉE pour quitter.
```

