---
title: InterruptMonitor
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente des informations sur linterruption.
type: docs
weight: 10600
url: /fr/net/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

Représente des informations sur l'interruption.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [InterruptMonitor](interruptmonitor)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted) { get; } | Obtient la valeur indiquant si les opérations doivent être interrompues. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance) { get; set; } | Obtient ou définit l'instance IInterruptMonitor qui est unique pour chaque thread. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt)() | Envoie une requête pour interrompre les opérations. |

### Exemples

L'exemple suivant montre comment effectuer la conversion d'image dans un thread dédié et interrompre le processus quelques secondes après le démarrage.

```csharp
[C#]

/// <summary>
/// Il s'agit de la classe d'assistance qui lance la conversion d'image et attend son interruption.
/// </summary>
private class Worker
{
    /// <summary>
    /// Le chemin vers l'image d'entrée.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// Le chemin vers l'image de sortie.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// Les options de sauvegarde.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// Le moniteur d'interruption.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// Initialise une nouvelle instance de <see cref="Worker" /> classer.
    /// </summary>
    /// <param name="inputPath">Le chemin vers l'image d'entrée.</param>
    /// <param name="outputPath">Le chemin vers l'image de sortie.</param>
    /// <param name="saveOptions">Les options d'enregistrement.</param>
    /// <param name="monitor">Le moniteur d'interruption.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// Convertit une image d'un format à un autre. Gère les interruptions.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // Définit une instance locale de thread du moniteur d'interruption.
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

                // Réinitialise l'instance thread-local du moniteur d'interruption.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // Affiche des informations détaillées sur toute exception inattendue.
            System.Console.WriteLine(e);
        }
    }
}

// Voici l'exemple principal utilisant la classe Worker.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// Démarre le worker dans un thread dédié.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// Faites un travail significatif ici
System.Threading.Thread.Sleep(2000);

// Demande d'interruption du thread de travail
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// Attendre l'interruption.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// La sortie peut ressembler à ceci :
// Interruption du thread de travail #14 au 06/08/2019 15:57:53
// Le thread de travail #14 a été interrompu le 06/08/2019 15:58:09
// Fait. Appuyez sur ENTRÉE pour quitter.
```

### Voir également

* interface [IInterruptMonitor](../iinterruptmonitor)
* espace de noms [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
