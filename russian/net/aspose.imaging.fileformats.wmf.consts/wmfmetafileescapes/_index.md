---
title: WmfMetafileEscapes
second_title: Справочник по Aspose.Imaging for .NET API
description: Перечисление MetafileEscapes определяет функциональные возможности драйвера принтера которые могут быть недоступны непосредственно через записи WMF определенные в перечислении RecordType раздел 2.1.1.1.
type: docs
weight: 8230
url: /ru/net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

Перечисление MetafileEscapes определяет функциональные возможности драйвера принтера, которые могут быть недоступны непосредственно через записи WMF, определенные в перечислении RecordType (раздел 2.1.1.1).

```csharp
public enum WmfMetafileEscapes
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Newframe | `1` | Уведомляет драйвер принтера о том, что приложение завершило запись на страницу. |
| Abortdoc | `2` | Останавливает обработку текущего документа. |
| Nextband | `3` | Уведомляет драйвер принтера о том, что приложение завершило запись в группу. |
| Setcolortable | `4` | Устанавливает значения таблицы цветов. |
| Getcolortable | `5` | Получает значения таблицы цветов. |
| Flushout | `6` | Вызывает сброс всего ожидающего вывода на устройство вывода. |
| Draftmode | `7` | Указывает, что драйвер принтера ДОЛЖЕН печатать только текст, а не графику. |
| Queryescsupport | `8` | Запрашивает драйвер принтера, чтобы определить, поддерживается ли конкретная функция escape на устройстве вывода, которым он управляет. |
| Setabortproc | `9` | Устанавливает определяемую приложением функцию, которая позволяет отменить задание на печать во время печати. |
| Startdoc | `10` | Уведомляет драйвер принтера о запуске нового задания на печать. |
| Enddoc | `11` | Уведомляет драйвер принтера о завершении текущего задания на печать. |
| Getphyspagesize | `12` | Получает физический размер страницы, выбранный в данный момент на устройстве вывода. |
| Getprintingoffset | `13` | Извлекает смещение от верхнего левого угла физической страницы , где начинается фактическая печать или рисование. |
| Getscalingfactor | `14` | Извлекает коэффициенты масштабирования для оси x и оси y принтера. |
| MetaEscapeEnhancedMetafile | `15` | Используется для встраивания расширенного формата метафайла (EMF) метафайла в метафайл WMF. |
| Setpenwidth | `16` | Устанавливает ширину пера в пикселях. |
| Setcopycount | `17` | Устанавливает количество копий. |
| Setpapersource | `18` | Устанавливает источник, такой как конкретный лоток для бумаги или лоток на принтере, для форм вывода. |
| Passthrough | `19` | Эта запись проходит через произвольные данные. |
| Gettechnology | `20` | Получает информацию о графической технологии, которая поддерживается устройством . |
| Setlinecap | `21` | Определяет режим рисования линий для использования при выводе на устройство. |
| Setlinejoin | `22` | Указывает режим соединения строк для использования при выводе на устройство. |
| Setmiterlimit | `23` | Устанавливает предел длины соединений митры для использования при выводе на устройство. |
| Bandinfo | `24` | Получает или задает настройки, касающиеся группирования на устройстве, например, количество полос. |
| Drawpatternrect | `25` | Рисует прямоугольник с заданным шаблоном. |
| Getvectorpensize | `26` | Извлекает размер физического пера, определенный в данный момент на устройстве. |
| Getvectorbrushsize | `27` | Получает физический размер кисти, определенный в данный момент на устройстве. |
| Enableduplex | `28` | Включает или отключает двустороннюю (дуплексную) печать на устройстве. |
| Getsetpaperbins | `29` | Извлекает или указывает источник форм вывода на устройстве. |
| Getsetprintorient | `30` | Получает или указывает ориентацию бумаги на устройстве. |
| Enumpaperbins | `31` | Извлекает информацию об источниках различных форм на устройстве вывода . |
| Setdibscaling | `32` | Задает масштабирование аппаратно-независимых растровых изображений (DIB). |
| Epsprinting | `33` | Указывает начало и конец инкапсулированного раздела PostScript (EPS). |
| Enumpapermetrics | `34` | Запрашивает у драйвера принтера размеры бумаги и другие данные форм. |
| Getsetpapermetrics | `35` | Извлекает или указывает размеры бумаги и другие данные формы на устройстве вывода . |
| PostscriptData | `37` | Отправляет произвольные данные PostScript на устройство вывода. |
| PostscriptIgnore | `38` | Уведомляет устройство вывода о необходимости игнорировать данные PostScript. |
| Getdeviceunits | `42` | Получает единицы устройства, настроенные в настоящее время на устройстве вывода. |
| Getextendedtextmetrics | `256` | Получает расширенные текстовые метрики, настроенные в настоящее время на выходном устройстве. |
| Getpairkerntable | `258` | Получает таблицу керна шрифта, определенную в данный момент на устройстве вывода. |
| Exttextout | `512` | Рисует текст, используя текущий выбранный шрифт, цвет фона и цвет текста. |
| Getfacename | `513` | Получает имя начертания шрифта, настроенное в данный момент на устройстве. |
| Downloadface | `514` | Устанавливает имя шрифта на устройстве. |
| MetafileDriver | `2049` | Запрашивает драйвер принтера о поддержке метафайлов на выходном устройстве. |
| Querydibsupport | `3073` | Запрашивает у драйвера принтера поддержку DIB на устройстве вывода. |
| BeginPath | `4096` | Открывает путь. |
| ClipToPath | `4097` | Определяет область отсечения, ограниченную контуром. Ввод ДОЛЖЕН быть 16-битным количеством, которое определяет действие, которое нужно предпринять. |
| EndPath | `4098` | Завершает путь. |
| OpenChannel | `4110` | То же, что и STARTDOC, указанный с документом NULL, и выводит имя файла, данные в необработанном режиме и нулевой тип. |
| Downloadheader | `4111` | Указывает драйверу принтера загружать наборы процедур PostScript. |
| CloseChannel | `4112` | То же, что и ENDDOC. См. OPEN_CHANNEL. |
| PostscriptPassthrough | `4115` | Отправляет произвольные данные непосредственно в драйвер принтера, который, как ожидается, будет обрабатывать эти данные только в режиме PostScript.PostscriptIdentify. |
| EncapsulatedPostscript | `4116` | Отправляет произвольные данные непосредственно в драйвер принтера. |
| PostscriptIdentify | `4117` | Устанавливает драйвер принтера в режим PostScript или GDI. |
| PostscriptInjection | `4118` | Вставляет блок необработанных данных в поток PostScript. Ввод ДОЛЖЕН быть 32-битной величиной, определяющей количество байтов для вставки, 16-битной величиной , определяющей точку вставки, и 16-битной величиной, определяющей страницу число, за которым следует байты для ввода. |
| Checkjpegformat | `4119` | Проверяет, поддерживает ли принтер изображение в формате JPEG. |
| Checkpngformat | `4120` | Проверяет, поддерживает ли принтер изображение в формате PNG. |
| GetPsFeaturesetting | `4121` | Получает информацию об указанной настройке функции для драйвера принтера PostScript . |
| MxdcEscape | `4122` | Позволяет приложениям записывать документы в файл или на принтер в формате XML Paper Specification (XPS). |
| Spclpassthrough2 | `4568` | Позволяет приложениям включать частные процедуры и другие произвольные данные в документы. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->