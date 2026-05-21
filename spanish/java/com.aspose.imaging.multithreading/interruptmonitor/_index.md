---
title: "InterruptMonitor"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa información sobre la interrupción."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Representa información sobre la interrupción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Inicializa una nueva instancia de la clase `InterruptMonitor`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Obtiene la instancia IInterruptMonitor que es única para cada hilo. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Establece la instancia IInterruptMonitor que es única para cada hilo. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Devuelve `true` si el monitor de interrupción para el hilo actual existe y fue interrumpido; de lo contrario, `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | Elimina todos los monitores de hilos, incluidos los de los hilos activos. |
| [isInterrupted()](#isInterrupted--) | Obtiene el valor que indica si las operaciones deben ser interrumpidas. |
| [interrupt()](#interrupt--) | Envía una solicitud para interrumpir operaciones. |

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

            // Establece una instancia local al hilo del monitor de interrupción.
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

                // Restablece la instancia local al hilo del monitor de interrupción.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Imprime información detallada sobre cualquier excepción inesperada.
            System.out.println(e);
        }
    }
}

// Aquí está el ejemplo principal que usa la clase Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Inicia el trabajador en un hilo dedicado.
Thread thread = new Thread(worker);
thread.start();

try {
    // Realiza algún trabajo significativo aquí
    Thread.sleep(2000);

    // Solicitar interrumpir el hilo del trabajador
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Esperar a la interrupción.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// La salida puede verse así:
// Interrumpiendo el hilo de trabajo #11 a las Tue Aug 06 17:57:52 YEKT 2019
// El hilo de trabajo #11 ha sido interrumpido a las Tue Aug 06 17:57:59 YEKT 2019
// Hecho. Presione ENTER para salir.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Inicializa una nueva instancia de la clase `InterruptMonitor`.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Obtiene la instancia IInterruptMonitor que es única para cada hilo.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Establece la instancia IInterruptMonitor que es única para cada hilo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Devuelve `true` si el monitor de interrupción para el hilo actual existe y fue interrumpido; de lo contrario, `false`.

**Returns:**
boolean - `true` si el monitor de interrupción para el hilo actual existe y fue interrumpido, de lo contrario `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Elimina todos los monitores de hilos, incluidos los de los hilos activos.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Obtiene el valor que indica si las operaciones deben ser interrumpidas.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


Envía una solicitud para interrumpir operaciones.


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

            // Establece una instancia local al hilo del monitor de interrupción.
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

                // Restablece la instancia local al hilo del monitor de interrupción.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Imprime información detallada sobre cualquier excepción inesperada.
            System.out.println(e);
        }
    }
}

// Aquí está el ejemplo principal que usa la clase Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Inicia el trabajador en un hilo dedicado.
Thread thread = new Thread(worker);
thread.start();

try {
    // Realiza algún trabajo significativo aquí
    Thread.sleep(2000);

    // Solicitar interrumpir el hilo del trabajador
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Esperar a la interrupción.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// La salida puede verse así:
// Interrumpiendo el hilo de trabajo #11 a las Tue Aug 06 17:57:52 YEKT 2019
// El hilo de trabajo #11 ha sido interrumpido a las Tue Aug 06 17:57:59 YEKT 2019
// Hecho. Presione ENTER para salir.
```

