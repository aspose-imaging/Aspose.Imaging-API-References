---
title: "InterruptMonitor"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示中断信息。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.multithreading/interruptmonitor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.multithreading.IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

表示中断信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | 初始化 `InterruptMonitor` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | 获取每个线程唯一的 IInterruptMonitor 实例。 |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-) | 设置每个线程唯一的 IInterruptMonitor 实例。 |
| [isThreadInterrupted()](#isThreadInterrupted--) | 如果当前线程的中断监视器存在且已被中断，则返回 `true`，否则返回 `false`。 |
| [removeAllMonitors()](#removeAllMonitors--) | 移除所有线程监视器，包括活跃线程的监视器。 |
| [isInterrupted()](#isInterrupted--) | 获取指示是否应中断操作的值。 |
| [interrupt()](#interrupt--) | 发送中断操作的请求。 |

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

            // 设置中断监视器的线程本地实例。
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

                // 重置中断监视器的线程本地实例。
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // 打印任何意外异常的详细信息。
            System.out.println(e);
        }
    }
}

// 以下是使用 Worker 类的主要示例。
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// 在专用线程中启动 worker。
Thread thread = new Thread(worker);
thread.start();

try {
    // 在此执行一些有意义的工作
    Thread.sleep(2000);

    // 请求中断 worker 线程
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // 等待中断。
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// 输出可能如下所示：
// 中断工作线程 #11 于 Tue Aug 06 17:57:52 YEKT 2019
// 工作线程 #11 已于 Tue Aug 06 17:57:59 YEKT 2019 被中断
// 完成。按 ENTER 退出。
```

### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


初始化 `InterruptMonitor` 类的新实例。

### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


获取每个线程唯一的 IInterruptMonitor 实例。

**Returns:**
[IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor)
### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.imaging.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


设置每个线程唯一的 IInterruptMonitor 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.imaging.multithreading/iinterruptmonitor) |  |

### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


如果当前线程的中断监视器存在且已被中断，则返回 `true`，否则返回 `false`。

**Returns:**
布尔型 - `true` 表示当前线程的中断监视器存在且已被中断，否则为 `false`。
### removeAllMonitors() {#removeAllMonitors--}
```
public static void removeAllMonitors()
```


移除所有线程监视器，包括活跃线程的监视器。

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


获取指示是否应中断操作的值。

**Returns:**
boolean
### interrupt() {#interrupt--}
```
public void interrupt()
```


发送中断操作的请求。


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

            // 设置中断监视器的线程本地实例。
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

                // 重置中断监视器的线程本地实例。
                com.aspose.imaging.multithreading.InterruptMonitor.setThreadLocalInstance(null);
            }
        } catch (java.lang.Exception e) {
            // 打印任何意外异常的详细信息。
            System.out.println(e);
        }
    }
}

// 以下是使用 Worker 类的主要示例。
String baseDir = "c:\\temp\\";

com.aspose.imaging.multithreading.InterruptMonitor monitor = new com.aspose.imaging.multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new com.aspose.imaging.imageoptions.BmpOptions(), monitor);

// 在专用线程中启动 worker。
Thread thread = new Thread(worker);
thread.start();

try {
    // 在此执行一些有意义的工作
    Thread.sleep(2000);

    // 请求中断 worker 线程
    monitor.interrupt();
    System.out.printf("Interrupting the worker thread #%s at %s", thread.getId(), new java.util.Date());

    // 等待中断。
    thread.join();
} catch (InterruptedException e) {
    System.out.println(e);
}

System.out.println("Done. Press ENTER to exit.");
System.in.read();

// 输出可能如下所示：
// 中断工作线程 #11 于 Tue Aug 06 17:57:52 YEKT 2019
// 工作线程 #11 已于 Tue Aug 06 17:57:59 YEKT 2019 被中断
// 完成。按 ENTER 退出。
```

