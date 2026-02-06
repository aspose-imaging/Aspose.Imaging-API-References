---
title: Class InterruptMonitor
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Multithreading.InterruptMonitor class. Represents information about interruption
type: docs
weight: 11160
url: /net/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

Represents information about interruption.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructors

| Name | Description |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted/) { get; } | Gets the value indicating whether operations should be interrupted. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Gets or sets the IInterruptMonitor instance which is unique for each thread. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt/)() | Sends a request to interrupt operations. |

## Examples

The following example shows how to perform the image conversion in a dedicated thread and interrupt the process in a few seconds after starting.

```csharp
[C#]

/// <summary>
/// This is helper class which initiates image conversion and waits for its interruption.
/// </summary>
private class Worker
{
    /// <summary>
    /// The path to the input image.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// The path to the output image.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// The save options.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// The interrupt monitor.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// Initializes a new instance of the <see cref="Worker" /> class.
    /// </summary>
    /// <param name="inputPath">The path to the input image.</param>
    /// <param name="outputPath">The path to the output image.</param>
    /// <param name="saveOptions">The save options.</param>
    /// <param name="monitor">The interrupt monitor.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// Converts an image from one format to another. Handles interruption.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // Set a thread-local instance of the interrupt monitor.
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

                // Reset the thread-local instance of the interrupt monitor.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // Print detailed information about any unexpected exception.
            System.Console.WriteLine(e);
        }
    }
}

// Here is the main example using the Worker class.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// Start the worker in a dedicated thread.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// Do some meaningful work here
System.Threading.Thread.Sleep(2000);

// Request to interrupt the worker thread
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// Wait for interruption.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// The output may look like this:
// Interrupting the worker thread #14 at 8/6/2019 3:57:53 PM
// The worker thread #14 has been interrupted at 8/6/2019 3:58:09 PM
// Done. Press ENTER to exit.
```

### See Also

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading/)
* assembly [Aspose.Imaging](../../)


