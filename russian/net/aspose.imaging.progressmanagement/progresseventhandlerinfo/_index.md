---
title: ProgressEventHandlerInfo
second_title: Справочник по Aspose.Imaging for .NET API
description: Этот класс представляет информацию о ходе выполнения операций загрузки/сохранения/экспорта изображения  которую можно использовать во внешнем приложении для демонстрации хода преобразования конечному пользователю
type: docs
weight: 10780
url: /ru/net/aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Этот класс представляет информацию о ходе выполнения операций загрузки/сохранения/экспорта изображения, , которую можно использовать во внешнем приложении для демонстрации хода преобразования конечному пользователю

```csharp
public class ProgressEventHandlerInfo
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Description](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/description) { get; } | Получает описание события |
| [EventType](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/eventtype) { get; } | Получает тип события. |
| [MaxValue](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/maxvalue) { get; } | Получает верхний предел значения прогресса. |
| [Value](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/value) { get; } | Получает текущее значение прогресса. |

### Примеры

В следующем примере показано, как распечатать информацию о событиях выполнения операций загрузки/экспорта.

```csharp
[C#]

public void Test3460()
{
    string dir = "c:\\aspose.imaging\\net\\issues\\3460";
    string fileName = System.IO.Path.Combine(dir, "big.png");

    // Пример использования отдельных обработчиков событий выполнения операции для операций загрузки/экспорта
    using (var image = Aspose.Imaging.Image.Load(fileName, new Aspose.Imaging.LoadOptions { ProgressEventHandler = ProgressCallback }))
    {
        image.Save(fileName + ".psd",
                   new Aspose.Imaging.ImageOptions.PsdOptions() { ProgressEventHandler = ExportProgressCallback });
    }
}

private void ProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("{0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

private void ExportProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("Export event {0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

// Журнал STDOUT может выглядеть так:
//Инициализация: 1/4
// Предварительная обработка: 2/4
//Обработка: 3/4
// Завершение: 4/4
//Инициализация экспорта события: 1/4
// Экспорт события PreProcessing: 2/4
//Обработка событий экспорта: 3/4
//Экспорт события RelativeProgress: 1/1
//Относительный прогресс: 1/1
//Экспорт события Завершение: 4/4
```

### Смотрите также

* пространство имен [Aspose.Imaging.ProgressManagement](../../aspose.imaging.progressmanagement)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
