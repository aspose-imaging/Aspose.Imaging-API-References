---
title: InterruptMonitor
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa información sobre la interrupción.
type: docs
weight: 10600
url: /es/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

Representa información sobre la interrupción.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [InterruptMonitor](interruptmonitor)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted) { get; } | Obtiene el valor que indica si se debe interrumpir la operación. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance) { get; set; } | Obtiene o establece la instancia de IInterruptMonitor que es única para cada subproceso. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt)() | Envía petición de interrupción de operaciones. |

### Ejemplos

El siguiente ejemplo muestra cómo realizar la conversión de imágenes en un hilo dedicado e interrumpir el proceso unos segundos después de comenzar.

```csharp
[C#]

/// <summary>
/// Esta es una clase auxiliar que inicia la conversión de imágenes y espera su interrupción.
/// </summary>
private class Worker
{
    /// <summary>
    /// La ruta a la imagen de entrada.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// La ruta a la imagen de salida.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// Las opciones de guardado.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// El monitor de interrupciones.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// Inicializa una nueva instancia de <ver cref="Worker" /> clase.
    /// </summary>
    /// <param name="inputPath">La ruta a la imagen de entrada.</param>
    /// <param name="outputPath">La ruta a la imagen de salida.</param>
    /// <param name="saveOptions">Las opciones de guardado.</param>
    /// <param name="monitor">El monitor de interrupción.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// Convierte una imagen de un formato a otro. Maneja la interrupción.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // Establecer una instancia local de subproceso del monitor de interrupción.
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

                // Restablecer la instancia local de subproceso del monitor de interrupción.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // Imprime información detallada sobre cualquier excepción inesperada.
            System.Console.WriteLine(e);
        }
    }
}

// Aquí está el ejemplo principal usando la clase Worker.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// Inicie el trabajador en un subproceso dedicado.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// Haz un trabajo significativo aquí
System.Threading.Thread.Sleep(2000);

// Solicitud para interrumpir el subproceso de trabajo
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// Espere la interrupción.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// La salida puede verse así:
// Interrumpiendo el subproceso de trabajo #14 el 6/8/2019 3:57:53 p. m.
// El subproceso de trabajo n.° 14 se interrumpió el 6/8/2019 3:58:09 p. m.
// Hecho. Pulse ENTRAR para salir.
```

### Ver también

* interface [IInterruptMonitor](../iinterruptmonitor)
* espacio de nombres [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
