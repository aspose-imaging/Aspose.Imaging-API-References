---
title: "WmfMetafileEscapes"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление MetafileEscapes определяет функциональность драйвера принтера, которая может быть недоступна напрямую через записи WMF, определённые в разделе 2.1.1.1 перечисления RecordType."
type: docs
weight: 24
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

Перечисление MetafileEscapes определяет функции драйвера принтера, которые могут быть недоступны напрямую через записи WMF, определённые в перечислении RecordType (раздел 2.1.1.1).
## Поля

| Поле | Описание |
| --- | --- |
| [Newframe](#Newframe) | Уведомляет драйвер принтера о том, что приложение закончило запись на страницу. |
| [Abortdoc](#Abortdoc) | Останавливает обработку текущего документа. |
| [Nextband](#Nextband) | Уведомляет драйвер принтера о том, что приложение закончило запись в полосу. |
| [Setcolortable](#Setcolortable) | Устанавливает значения таблицы цветов. |
| [Getcolortable](#Getcolortable) | Получает значения таблицы цветов. |
| [Flushout](#Flushout) | Вызывает сброс всего отложенного вывода на устройство вывода. |
| [Draftmode](#Draftmode) | Указывает, что драйвер принтера ДОЛЖЕН печатать только текст и без графики. |
| [Queryescsupport](#Queryescsupport) | Запрашивает у драйвера принтера, поддерживается ли конкретная функция escape на управляемом им устройстве вывода. |
| [Setabortproc](#Setabortproc) | Устанавливает определяемую приложением функцию, позволяющую отменить задание печати во время печати. |
| [Startdoc](#Startdoc) | Уведомляет драйвер принтера о начале нового задания печати. |
| [Enddoc](#Enddoc) | Уведомляет драйвер принтера о завершении текущего задания печати. |
| [Getphyspagesize](#Getphyspagesize) | Получает текущий физический размер страницы, выбранный на устройстве вывода. |
| [Getprintingoffset](#Getprintingoffset) | Получает смещение от верхнего левого угла физической страницы, где начинается фактическая печать или рисование. |
| [Getscalingfactor](#Getscalingfactor) | Получает коэффициенты масштабирования по оси X и оси Y принтера. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Используется для встраивания метафайла формата Enhanced Metafile (EMF) в метафайл WMF. |
| [Setpenwidth](#Setpenwidth) | Устанавливает ширину пера в пикселях. |
| [Setcopycount](#Setcopycount) | Устанавливает количество копий. |
| [Setpapersource](#Setpapersource) | Устанавливает источник, например конкретный лоток или контейнер для бумаги на принтере, для форм вывода. |
| [Passthrough](#Passthrough) | Эта запись передаёт произвольные данные. |
| [Gettechnology](#Gettechnology) | Получает информацию о графической технологии, поддерживаемой на устройстве. |
| [Setlinecap](#Setlinecap) | Указывает режим рисования линий, используемый при выводе на устройство. |
| [Setlinejoin](#Setlinejoin) | Указывает режим соединения линий, используемый при выводе на устройство. |
| [Setmiterlimit](#Setmiterlimit) | Устанавливает предел длины срезов (miter joins) для использования при выводе на устройство. |
| [Bandinfo](#Bandinfo) | Получает или задает параметры, связанные с полосовой разметкой на устройстве, такие как количество полос. |
| [Drawpatternrect](#Drawpatternrect) | Рисует прямоугольник с определённым узором. |
| [Getvectorpensize](#Getvectorpensize) | Получает физический размер пера, текущий на устройстве. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Получает физический размер кисти, текущий на устройстве. |
| [Enableduplex](#Enableduplex) | Включает или отключает двустороннюю (дуплекс) печать на устройстве. |
| [Getsetpaperbins](#Getsetpaperbins) | Получает или задает источник форм вывода на устройстве. |
| [Getsetprintorient](#Getsetprintorient) | Получает или задает ориентацию бумаги на устройстве. |
| [Enumpaperbins](#Enumpaperbins) | Получает информацию о источниках различных форм на устройстве вывода. |
| [Setdibscaling](#Setdibscaling) | Задаёт масштабирование независимых от устройства битовых карт (DIB). |
| [Epsprinting](#Epsprinting) | Указывает начало и конец секции инкапсулированного PostScript (EPS). |
| [Enumpapermetrics](#Enumpapermetrics) | Запрашивает у драйвера принтера размеры бумаги и другие данные форм. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Получает или задает размеры бумаги и другие данные форм на устройстве вывода. |
| [PostscriptData](#PostscriptData) | Отправляет произвольные данные PostScript на устройство вывода. |
| [PostscriptIgnore](#PostscriptIgnore) | Уведомляет устройство вывода игнорировать данные PostScript. |
| [Getdeviceunits](#Getdeviceunits) | Получает единицы измерения устройства, текущие на устройстве вывода. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Получает расширенные метрики текста, текущие на устройстве вывода. |
| [Getpairkerntable](#Getpairkerntable) | Получает таблицу кернинга шрифта, текущую на устройстве вывода. |
| [Exttextout](#Exttextout) | Рисует текст, используя текущий выбранный шрифт, цвет фона и цвет текста. |
| [Getfacename](#Getfacename) | Получает название гарнитуры шрифта, текущей на устройстве. |
| [Downloadface](#Downloadface) | Устанавливает название гарнитуры шрифта на устройстве. |
| [MetafileDriver](#MetafileDriver) | Запрашивает у драйвера принтера поддержку метафайлов на устройстве вывода. |
| [Querydibsupport](#Querydibsupport) | Запрашивает у драйвера принтера поддержку DIB на устройстве вывода. |
| [BeginPath](#BeginPath) | Открывает путь. |
| [ClipToPath](#ClipToPath) | Определяет область отсечения, ограниченную путём. |
| [EndPath](#EndPath) | Завершает путь. |
| [OpenChannel](#OpenChannel) | То же, что STARTDOC, указанный с NULL документом и именем выходного файла, данные в необработанном режиме и типом ноль. |
| [Downloadheader](#Downloadheader) | Инструктирует драйвер принтера загрузить наборы процедур PostScript. |
| [CloseChannel](#CloseChannel) | То же, что ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Отправляет произвольные данные напрямую драйверу принтера, который ожидает обрабатывать эти данные только в режиме PostScript. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Отправляет произвольные данные напрямую драйверу принтера. |
| [PostscriptIdentify](#PostscriptIdentify) | Устанавливает драйвер принтера в режим PostScript или GDI. |
| [PostscriptInjection](#PostscriptInjection) | Вставляет блок необработанных данных в поток PostScript. |
| [Checkjpegformat](#Checkjpegformat) | Проверяет, поддерживает ли принтер изображение JPEG. |
| [Checkpngformat](#Checkpngformat) | Проверяет, поддерживает ли принтер изображение PNG. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | Получает информацию о заданной настройке функции для драйвера принтера PostScript. |
| [MxdcEscape](#MxdcEscape) | Позволяет приложениям записывать документы в файл или на принтер в формате XML Paper Specification (XPS). |
| [Spclpassthrough2](#Spclpassthrough2) | Позволяет приложениям включать частные процедуры и другие произвольные данные в документы. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Уведомляет драйвер принтера о том, что приложение закончило запись на страницу.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Останавливает обработку текущего документа.

### Nextband {#Nextband}
```
public static final int Nextband
```


Уведомляет драйвер принтера о том, что приложение закончило запись в полосу.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Устанавливает значения таблицы цветов.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Получает значения таблицы цветов.

### Flushout {#Flushout}
```
public static final int Flushout
```


Вызывает сброс всего отложенного вывода на устройство вывода.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Указывает, что драйвер принтера ДОЛЖЕН печатать только текст и без графики.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Запрашивает у драйвера принтера, поддерживается ли конкретная функция escape на управляемом им устройстве вывода.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Устанавливает определяемую приложением функцию, позволяющую отменить задание печати во время печати.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Уведомляет драйвер принтера о начале нового задания печати.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Уведомляет драйвер принтера о завершении текущего задания печати.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Получает текущий физический размер страницы, выбранный на устройстве вывода.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Получает смещение от верхнего левого угла физической страницы, где начинается фактическая печать или рисование.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Получает коэффициенты масштабирования по оси X и оси Y принтера.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Используется для встраивания метафайла формата Enhanced Metafile (EMF) в метафайл WMF.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Устанавливает ширину пера в пикселях.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Устанавливает количество копий.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Устанавливает источник, например конкретный лоток или контейнер для бумаги на принтере, для форм вывода.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


Эта запись передаёт произвольные данные.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Получает информацию о графической технологии, поддерживаемой на устройстве.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Указывает режим рисования линий, используемый при выводе на устройство.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Указывает режим соединения линий, используемый при выводе на устройство.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Устанавливает предел длины срезов (miter joins) для использования при выводе на устройство.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Получает или задает параметры, связанные с полосовой разметкой на устройстве, такие как количество полос.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Рисует прямоугольник с определённым узором.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Получает физический размер пера, текущий на устройстве.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Получает физический размер кисти, текущий на устройстве.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Включает или отключает двустороннюю (дуплекс) печать на устройстве.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Получает или задает источник форм вывода на устройстве.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Получает или задает ориентацию бумаги на устройстве.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Получает информацию о источниках различных форм на устройстве вывода.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Задаёт масштабирование независимых от устройства битовых карт (DIB).

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Указывает начало и конец секции инкапсулированного PostScript (EPS).

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Запрашивает у драйвера принтера размеры бумаги и другие данные форм.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Получает или задает размеры бумаги и другие данные форм на устройстве вывода.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


Отправляет произвольные данные PostScript на устройство вывода.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Уведомляет устройство вывода игнорировать данные PostScript.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Получает единицы измерения устройства, текущие на устройстве вывода.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Получает расширенные метрики текста, текущие на устройстве вывода.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Получает таблицу кернинга шрифта, текущую на устройстве вывода.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Рисует текст, используя текущий выбранный шрифт, цвет фона и цвет текста.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Получает название гарнитуры шрифта, текущей на устройстве.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Устанавливает название гарнитуры шрифта на устройстве.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Запрашивает у драйвера принтера поддержку метафайлов на устройстве вывода.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Запрашивает у драйвера принтера поддержку DIB на устройстве вывода.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Открывает путь.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Определяет область обрезки, ограниченную путем. Входные данные ДОЛЖНЫ быть 16-битным значением, определяющим действие.

### EndPath {#EndPath}
```
public static final int EndPath
```


Завершает путь.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


То же, что STARTDOC, указанный с NULL документом и именем выходного файла, данные в необработанном режиме и типом ноль.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Инструктирует драйвер принтера загрузить наборы процедур PostScript.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


То же, что ENDDOC. См. OPEN\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Отправляет произвольные данные напрямую драйверу принтера, который ожидает обрабатывать эти данные только в режиме PostScript. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Отправляет произвольные данные напрямую драйверу принтера.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Устанавливает драйвер принтера в режим PostScript или GDI.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Вставляет блок необработанных данных в поток PostScript. Входные данные ДОЛЖНЫ быть 32-битным значением, указывающим количество байтов для внедрения, 16-битным значением, указывающим точку внедрения, и 16-битным значением, указывающим номер страницы, за которыми следуют байты для внедрения.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Проверяет, поддерживает ли принтер изображение JPEG.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Проверяет, поддерживает ли принтер изображение PNG.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


Получает информацию о заданной настройке функции для драйвера принтера PostScript.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Позволяет приложениям записывать документы в файл или на принтер в формате XML Paper Specification (XPS).

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Позволяет приложениям включать частные процедуры и другие произвольные данные в документы.

