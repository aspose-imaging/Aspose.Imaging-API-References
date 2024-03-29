---
title: InterruptMonitor
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет информацию о прерывании.
type: docs
weight: 10600
url: /ru/net/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

Представляет информацию о прерывании.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [InterruptMonitor](interruptmonitor)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted) { get; } | Получает значение, указывающее, следует ли прерывать операции. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance) { get; set; } | Получает или задает экземпляр IInterruptMonitor, уникальный для каждого потока. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt)() | Отправляет запрос на прерывание операций. |

### Примеры

В следующем примере показано, как выполнить преобразование изображения в выделенном потоке и прервать процесс через несколько секунд после запуска.

```csharp
[C#]

/// <summary>
/// Это вспомогательный класс, который инициирует преобразование изображения и ожидает его прерывания.
/// </summary>
private class Worker
{
    /// <summary>
    /// Путь к входному изображению.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// Путь к выходному изображению.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// Параметры сохранения.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// Монитор прерываний.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// Инициализирует новый экземпляр класса <see cref="Worker" /> учебный класс.
    /// </summary>
    /// <param name="inputPath">Путь к входному изображению.</param>
    /// <param name="outputPath">Путь к выходному изображению.</param>
    /// <param name="saveOptions">Параметры сохранения.</param>
    /// <param name="monitor">Монитор прерываний.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// Преобразует изображение из одного формата в другой. Справляется с прерыванием.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // Установить локальный экземпляр монитора прерываний.
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

                // Сброс экземпляра локального потока монитора прерываний.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // Вывести подробную информацию о любом неожиданном исключении.
            System.Console.WriteLine(e);
        }
    }
}

// Вот основной пример использования класса Worker.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// Запуск рабочего в выделенном потоке.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// Делаем здесь какую-нибудь осмысленную работу
System.Threading.Thread.Sleep(2000);

// Запрос на прерывание рабочего потока
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// Ждем прерывания.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// Вывод может выглядеть так:
// Прерывание рабочего потока № 14 от 06.08.2019 15:57:53
// Рабочий поток №14 был прерван 06.08.2019 15:58:09
// Сделанный. Нажмите ENTER для выхода.
```

### Смотрите также

* interface [IInterruptMonitor](../iinterruptmonitor)
* пространство имен [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
