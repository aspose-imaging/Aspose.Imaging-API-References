---
title: InterruptMonitor
second_title: Aspose.Imaging for .NET API Referansı
description: Kesinti hakkındaki bilgileri temsil eder.
type: docs
weight: 10600
url: /tr/net/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

Kesinti hakkındaki bilgileri temsil eder.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [InterruptMonitor](interruptmonitor)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted) { get; } | İşlemlerin kesintiye uğraması gerekip gerekmediğini gösteren değeri alır. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance) { get; set; } | Her iş parçacığı için benzersiz olan IInterruptMonitor örneğini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt)() | İşlemleri kesmek için bir istek gönderir. |

### Örnekler

Aşağıdaki örnek, özel bir iş parçacığında görüntü dönüştürmenin nasıl gerçekleştirileceğini ve başladıktan birkaç saniye sonra işlemin nasıl kesileceğini gösterir.

```csharp
[C#]

/// <summary>
/// Görüntü dönüştürmeyi başlatan ve kesintiye uğramasını bekleyen yardımcı sınıftır.
/// </summary>
private class Worker
{
    /// <summary>
    /// Giriş görüntüsünün yolu.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// Çıktı görüntüsünün yolu.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// Kaydetme seçenekleri.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// Kesinti izleyicisi.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// <see cref="Worker" /> sınıf.
    /// </summary>
    /// <param name="inputPath">Giriş görüntüsünün yolu.</param>
    /// <param name="outputPath">Çıktı görüntüsünün yolu.</param>
    /// <param name="saveOptions">Kaydetme seçenekleri.</param>
    /// <param name="monitor">Kesme izleyicisi.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// Bir görüntüyü bir biçimden diğerine dönüştürür. Kesintiyi yönetir.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // Kesinti izleyicisinin iş parçacığı yerel örneğini ayarlayın.
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

                // Kesinti izleyicisinin iş parçacığı yerel örneğini sıfırlayın.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // Beklenmeyen istisnalar hakkında ayrıntılı bilgi yazdırın.
            System.Console.WriteLine(e);
        }
    }
}

// İşte Worker sınıfını kullanan ana örnek.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// Çalışanı özel bir iş parçacığında başlatın.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// Burada anlamlı bir iş yapın
System.Threading.Thread.Sleep(2000);

// Çalışan iş parçacığını kesme isteği
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// Kesintiyi bekleyin.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// Çıktı şöyle görünebilir:
// 08.06.2019 15:57:53'te 14 numaralı işçi iş parçacığının kesilmesi
// 14 numaralı işçi iş parçacığı 8/6/2019 15:58:09 PM'de kesildi
// Tamamlandı. Çıkmak için ENTER'a basın.
```

### Ayrıca bakınız

* interface [IInterruptMonitor](../iinterruptmonitor)
* ad alanı [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
