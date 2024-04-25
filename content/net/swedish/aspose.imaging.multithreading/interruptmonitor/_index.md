---
title: InterruptMonitor
second_title: Aspose.Imaging för .NET API-referens
description: Representerar information om avbrott.
type: docs
weight: 10600
url: /sv/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

Representerar information om avbrott.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [InterruptMonitor](interruptmonitor)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted) { get; } | Hämtar värdet som anger om operationer ska avbrytas. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance) { get; set; } | Hämtar eller ställer in IInterruptMonitor-instansen som är unik för varje tråd. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt)() | Skickar en begäran om att avbryta operationer. |

### Exempel

Följande exempel visar hur du utför bildkonverteringen i en dedikerad tråd och avbryter processen på några sekunder efter start.

```csharp
[C#]

/// <summary>
/// Detta är en hjälpklass som initierar bildkonvertering och väntar på att den avbryts.
/// </summary>
private class Worker
{
    /// <summary>
    /// Sökvägen till inmatningsbilden.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// Sökvägen till utdatabilden.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// Spara alternativen.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// Avbrottsmonitorn.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// Initierar en ny instans av <see cref="Worker" /> klass.
    /// </summary>
    /// <param name="inputPath">Sökvägen till indatabilden.</param>
    /// <param name="outputPath">Sökvägen till utdatabilden.</param>
    /// <param name="saveOptions">Sparaalternativen.</param>
    /// <param name="monitor">Avbrottsmonitorn.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// Konverterar en bild från ett format till ett annat. Hanterar avbrott.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // Ställ in en trådlokal instans av avbrottsmonitorn.
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

                // Återställ den trådlokala instansen av avbrottsövervakningen.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // Skriv ut detaljerad information om eventuella oväntade undantag.
            System.Console.WriteLine(e);
        }
    }
}

// Här är huvudexemplet med klassen Worker.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// Starta arbetaren i en dedikerad tråd.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// Gör något meningsfullt arbete här
System.Threading.Thread.Sleep(2000);

// Begäran om att avbryta arbetartråden
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// Vänta på avbrott.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// Utdata kan se ut så här:
// Avbryter arbetartråden #14 den 8/6/2019 15:57:53
// Arbetartråden #14 har avbrutits den 8/6/2019 15:58:09
// Gjort. Tryck på ENTER för att avsluta.
```

### Se även

* interface [IInterruptMonitor](../iinterruptmonitor)
* namnutrymme [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
