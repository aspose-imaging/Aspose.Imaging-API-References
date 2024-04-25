---
title: InterruptMonitor
second_title: Aspose.Imaging für .NET-API-Referenz
description: Stellt Informationen zur Unterbrechung dar.
type: docs
weight: 10600
url: /de/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

Stellt Informationen zur Unterbrechung dar.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [InterruptMonitor](interruptmonitor)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted) { get; } | Ruft den Wert ab, der angibt, ob Operationen unterbrochen werden sollen. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance) { get; set; } | Ruft die IInterruptMonitor-Instanz ab oder legt sie fest, die für jeden Thread eindeutig ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt)() | Sendet eine Anfrage zur Unterbrechung des Betriebs. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie die Bildkonvertierung in einem dedizierten Thread durchführen und den Vorgang einige Sekunden nach dem Start unterbrechen.

```csharp
[C#]

/// <summary>
/// Dies ist eine Hilfsklasse, die die Bildkonvertierung initiiert und auf ihre Unterbrechung wartet.
/// </summary>
private class Worker
{
    /// <summary>
    /// Der Pfad zum Eingabebild.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// Der Pfad zum Ausgabebild.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// Die Speicheroptionen.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// Der Interrupt-Monitor.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// Initialisiert eine neue Instanz des <see cref="Worker" /> Klasse.
    /// </summary>
    /// <param name="inputPath">Der Pfad zum Eingabebild.</param>
    /// <param name="outputPath">Der Pfad zum Ausgabebild.</param>
    /// <param name="saveOptions">Die Speicheroptionen.</param>
    /// <param name="monitor">Der Interrupt-Monitor.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// Konvertiert ein Bild von einem Format in ein anderes. Behandelt Unterbrechungen.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // Thread-lokale Instanz des Interrupt-Monitors setzen.
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

                // Thread-lokale Instanz des Interrupt-Monitors zurücksetzen.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // Detaillierte Informationen über jede unerwartete Ausnahme ausgeben.
            System.Console.WriteLine(e);
        }
    }
}

// Hier ist das Hauptbeispiel mit der Worker-Klasse.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// Worker in einem dedizierten Thread starten.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// Erledige hier eine sinnvolle Arbeit
System.Threading.Thread.Sleep(2000);

// Anforderung zum Unterbrechen des Worker-Threads
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// Auf Unterbrechung warten.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// Die Ausgabe könnte so aussehen:
// Unterbrechen des Worker-Threads Nr. 14 am 06.08.2019 15:57:53
// Der Worker-Thread #14 wurde am 6.8.2019 15:58:09 unterbrochen
// Fertig. Drücken Sie zum Beenden ENTER.
```

### Siehe auch

* interface [IInterruptMonitor](../iinterruptmonitor)
* namensraum [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
