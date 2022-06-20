---
title: Interrupt
second_title: Aspose.Imaging for .NET API 参考
description: 发送中断操作请求
type: docs
weight: 30
url: /zh/net/aspose.imaging.multithreading/interruptmonitor/interrupt/
---
## InterruptMonitor.Interrupt method

发送中断操作请求。

```csharp
public virtual void Interrupt()
```

### 例子

以下示例展示了如何在专用线程中执行图像转换并在启动后几秒钟内中断进程。

```csharp
[C#]

/// <summary>
    /// 这是启动图像转换并等待其中断的辅助类。
/// </summary>
private class Worker
{
    /// <summary>
        /// 输入图像的路径.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
        /// 输出图像的路径.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
        /// 保存选项.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
        /// 中断监视器.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
        /// 初始化 <see cref="Worker" /> 的新实例类.
    /// </summary>
    /// <param name="inputPath">输入图像的路径。</param>
        /// <param name="outputPath">输出图像的路径。</param>
        /// <param name="saveOptions">保存选项。</param>
        /// <param name="monitor">中断监视器。</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
        /// 将图像从一种格式转换为另一种格式。处理中断。
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
                // 设置中断监视器的线程本地实例。
            Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = this.monitor;

            try
            {
                image.Save(this.outputPath, this.saveOptions);
            }
            catch (Aspose.Imaging.CoreExceptions.OperationInterruptedException e)
            {
                System.Console.WriteLine(
                    "The worker thread #{0} has been interrupted at {1}",
                    System.Threading.Thread.CurrentThread.ManagedThreadId,
                    System.DateTime.Now);
            }
            finally
            {
                image.Dispose();

                    // 重置中断监视器的线程本地实例。
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
                // 打印有关任何意外异常的详细信息。
            System.Console.WriteLine(e);
        }
    }
}

    // 这是使用 Worker 类的主要示例。
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

    // 在专用线程中启动工作线程。
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

    // 在这里做一些有意义的工作
System.Threading.Thread.Sleep(2000);

    // 请求中断工作线程
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

    // 等待中断。
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// 输出可能如下所示：
    // 在 8/6/2019 3:57:53 PM
 中断工作线程 #14
    // 工作线程 #14 已在 8/6/2019 3:58:09 PM
 中断
// 完毕。按 ENTER 退出。
```

### 也可以看看

* class [InterruptMonitor](../../interruptmonitor)
* 命名空间 [Aspose.Imaging.Multithreading](../../interruptmonitor)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->