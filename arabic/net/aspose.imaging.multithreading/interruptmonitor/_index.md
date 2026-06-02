---
title: "فئة InterruptMonitor"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.Multithreading.InterruptMonitor. تمثل معلومات حول المقاطعة"
type: docs
weight: 11170
url: /ar/net/aspose.imaging.multithreading/interruptmonitor/
---
## InterruptMonitor class

يمثل معلومات حول الانقطاع.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [IsInterrupted](../../aspose.imaging.multithreading/interruptmonitor/isinterrupted/) { get; } | يحصل على القيمة التي تشير إلى ما إذا كان يجب مقاطعة العمليات. |
| static [ThreadLocalInstance](../../aspose.imaging.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | يحصل أو يعيّن نسخة IInterruptMonitor التي تكون فريدة لكل خيط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Interrupt](../../aspose.imaging.multithreading/interruptmonitor/interrupt/)() | يرسل طلبًا لمقاطعة العمليات. |

## أمثلة

المثال التالي يوضح كيفية إجراء تحويل الصورة في خيط مخصص ومقاطعة العملية بعد بضع ثوانٍ من بدءها.

```csharp
[C#]

/// <summary>
/// هذه فئة مساعدة تقوم ببدء تحويل الصورة وتنتظر مقاطعتها.
/// </summary>
private class Worker
{
    /// <summary>
    /// المسار إلى صورة الإدخال.
    /// </summary>
    private readonly string inputPath;

    /// <summary>
    /// المسار إلى صورة الإخراج.
    /// </summary>
    private readonly string outputPath;

    /// <summary>
    /// خيارات الحفظ.
    /// </summary>
    private readonly Aspose.Imaging.ImageOptionsBase saveOptions;

    /// <summary>
    /// مراقب المقاطعة.
    /// </summary>
    private readonly Aspose.Imaging.Multithreading.InterruptMonitor monitor;

    /// <summary>
    /// يهيئ نسخة جديدة من الفئة <see cref="Worker" />.
    /// </summary>
    /// <param name="inputPath">المسار إلى صورة الإدخال.</param>
    /// <param name="outputPath">المسار إلى صورة الإخراج.</param>
    /// <param name="saveOptions">خيارات الحفظ.</param>
    /// <param name="monitor">مراقب المقاطعة.</param>
    public Worker(string inputPath, string outputPath, Aspose.Imaging.ImageOptionsBase saveOptions, Aspose.Imaging.Multithreading.InterruptMonitor monitor)
    {
        this.inputPath = inputPath;
        this.outputPath = outputPath;
        this.saveOptions = saveOptions;
        this.monitor = monitor;
    }

    /// <summary>
    /// يحول صورة من تنسيق إلى آخر. يتعامل مع الانقطاع.
    /// </summary>
    public void ThreadProc()
    {
        try
        {
            Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(this.inputPath);
            
            // تعيين كائن محلي للموضوع لمراقب الانقطاع.
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

                // إعادة تعيين الكائن المحلي للموضوع لمراقب الانقطاع.
                Aspose.Imaging.Multithreading.InterruptMonitor.ThreadLocalInstance = null;
            }
        }
        catch (System.Exception e)
        {
            // طباعة معلومات مفصلة حول أي استثناء غير متوقع.
            System.Console.WriteLine(e);
        }
    }
}

// إليك المثال الرئيسي باستخدام الفئة Worker.
string baseDir = "c:\\temp\\";

Aspose.Imaging.Multithreading.InterruptMonitor monitor = new Aspose.Imaging.Multithreading.InterruptMonitor();
Worker worker = new Worker(baseDir + "big.png", baseDir + "big.bmp", new Aspose.Imaging.ImageOptions.BmpOptions(), monitor);

// ابدأ العامل في خيط مخصص.
System.Threading.Thread thread = new System.Threading.Thread(new System.Threading.ThreadStart(worker.ThreadProc));
thread.Start();

// قم ببعض العمل المفيد هنا
System.Threading.Thread.Sleep(2000);

// طلب لإيقاف خيط العامل
monitor.Interrupt();
System.Console.WriteLine("Interrupting the worker thread #{0} at {1}", thread.ManagedThreadId, System.DateTime.Now);

// انتظر الانقطاع.
thread.Join();

System.Console.WriteLine("Done. Press ENTER to exit.");
System.Console.ReadLine();

// قد يبدو الإخراج هكذا:
// جاري إيقاف خيط العامل #14 في 8/6/2019 3:57:53 م
// تم إيقاف خيط العامل #14 في 8/6/2019 3:58:09 م
// تم. اضغط ENTER للخروج.
```

### انظر أيضًا

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Imaging.Multithreading](../../aspose.imaging.multithreading/)
* assembly [Aspose.Imaging](../../)


