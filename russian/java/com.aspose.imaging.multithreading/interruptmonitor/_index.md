---
title: "InterruptMonitor"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет информацию о прерывании."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

Представляет информацию о прерывании.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | Инициализирует новый экземпляр класса `InterruptMonitor`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | Получает экземпляр IInterruptMonitor, уникальный для каждого потока. |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | Устанавливает экземпляр IInterruptMonitor, уникальный для каждого потока. |
| [isThreadInterrupted()](#isThreadInterrupted--) | Возвращает `true`, если монитор прерываний для текущего потока существует и был прерван, иначе `false`. |
| [removeAllMonitors()](#removeAllMonitors--) | Удаляет все мониторы потоков, включая те, которые принадлежат живым потокам. |
| [isInterrupted()](#isInterrupted--) | Получает значение, указывающее, следует ли прерывать операции. |
| [interrupt()](#interrupt--) | Отправляет запрос на прерывание операций. |

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

            // Устанавливает потоково-локальный экземпляр монитора прерываний.
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

                // Сбрасывает потоково-локальный экземпляр монитора прерываний.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Выводит подробную информацию о любой неожиданной ошибке.
            System.out.println(e);
        }
    }
}

// Вот основной пример с использованием класса Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Запустите worker в отдельном потоке.
Thread thread = new Thread(worker);
thread.start();

try {
    // Выполните здесь некоторую полезную работу.
    Thread.sleep(2000);

    // Запрос на прерывание потока worker.
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Ожидайте прерывания.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Вывод может выглядеть так:
// Прерывание рабочего потока #11 в Tue Aug 06 17:57:52 YEKT 2019
// Рабочий поток #11 был прерван в Tue Aug 06 17:57:59 YEKT 2019
// Готово. Нажмите ENTER, чтобы выйти.
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


Инициализирует новый экземпляр класса `InterruptMonitor`.

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


Получает экземпляр IInterruptMonitor, уникальный для каждого потока.

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


Устанавливает экземпляр IInterruptMonitor, уникальный для каждого потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


Возвращает `true`, если монитор прерываний для текущего потока существует и был прерван, иначе `false`.

**Returns:**
boolean - `true`, если монитор прерываний для текущего потока существует и он был прерван, иначе `false`.
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


Удаляет все мониторы потоков, включая те, которые принадлежат живым потокам.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


Получает значение, указывающее, следует ли прерывать операции.

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


Отправляет запрос на прерывание операций.


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

            // Устанавливает потоково-локальный экземпляр монитора прерываний.
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

                // Сбрасывает потоково-локальный экземпляр монитора прерываний.
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // Выводит подробную информацию о любой неожиданной ошибке.
            System.out.println(e);
        }
    }
}

// Вот основной пример с использованием класса Worker.
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// Запустите worker в отдельном потоке.
Thread thread = new Thread(worker);
thread.start();

try {
    // Выполните здесь некоторую полезную работу.
    Thread.sleep(2000);

    // Запрос на прерывание потока worker.
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // Ожидайте прерывания.
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// Вывод может выглядеть так:
// Прерывание рабочего потока #11 в Tue Aug 06 17:57:52 YEKT 2019
// Рабочий поток #11 был прерван в Tue Aug 06 17:57:59 YEKT 2019
// Готово. Нажмите ENTER, чтобы выйти.
```

