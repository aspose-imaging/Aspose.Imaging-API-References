---
title: "LoadOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет параметры загрузки."
type: docs
weight: 70
url: /ru/java/com.aspose.imaging/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.progressmanagement.IProgressEventHandler
```
public class LoadOptions implements IProgressEventHandler
```

Представляет параметры загрузки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Получает режим восстановления данных. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Устанавливает режим восстановления данных. |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Получает фоновый `Color` изображения `Image`. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.imaging.Color-) | Устанавливает фоновый `Color` изображения `Image`. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Получает значение, указывающее, следует ли применять преобразование ICC‑профиля. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Устанавливает значение, указывающее, следует ли применять преобразование ICC‑профиля. |
| [addCustomFontSource(CustomFontSource source, Object[] args)](#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-) | Добавляет пользовательский источник шрифтов для предоставления шрифтов, специфичных для изображения. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [getConcurrentImageProcessing()](#getConcurrentImageProcessing--) | Получает значение, указывающее, включена ли [concurrent image processing]. |
| [setConcurrentImageProcessing(boolean value)](#setConcurrentImageProcessing-boolean-) | Устанавливает значение, указывающее, включена ли [concurrent image processing]. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Получает обработчик события прогресса. |
| [setIProgressEventHandler(ProgressEventHandler value)](#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Устанавливает обработчик события прогресса. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Получает режим восстановления данных.

**Returns:**
int - Режим восстановления данных.
### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Устанавливает режим восстановления данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Режим восстановления данных. |

### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Получает фоновый `Color` изображения `Image`.

**Returns:**
[Color](../../com.aspose.imaging/color) - The background color.

Обычно фоновый цвет устанавливается, когда значение пикселя невозможно восстановить из‑за повреждения данных.
### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.imaging.Color-}
```
public void setDataBackgroundColor(Color value)
```


Устанавливает фоновый `Color` изображения `Image`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.imaging/color) | Фоновый цвет. |

Обычно фоновый цвет устанавливается, когда значение пикселя невозможно восстановить из‑за повреждения данных. |

### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Получает значение, указывающее, следует ли применять преобразование ICC‑профиля.

**Returns:**
boolean
### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Устанавливает значение, указывающее, следует ли применять преобразование ICC‑профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### addCustomFontSource(CustomFontSource source, Object[] args) {#addCustomFontSource-com.aspose.imaging.CustomFontSource-java.lang.Object...-}
```
public final void addCustomFontSource(CustomFontSource source, Object[] args)
```


Добавляет пользовательский источник шрифтов для предоставления шрифтов, специфичных для изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [CustomFontSource](../../com.aspose.imaging/customfontsource) | Функция поставщика пользовательского источника шрифтов. |
| args | java.lang.Object[] | Аргументы. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: Подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int — подсказка размера буфера, определяющая максимальный допустимый размер для всех внутренних буферов.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: Подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | подсказка размера буфера, определяющая максимальный допустимый размер для всех внутренних буферов. |


**Example: The following example shows how to set a memory limit when loading a JPEG image.**
В следующем примере показано, как установить ограничение памяти при загрузке JPEG‑изображения. Ограничение памяти — это максимальный допустимый размер (в мегабайтах) всех внутренних буферов.
``` java
String workDir = "c:\\temp\\";
// Установка ограничения памяти в 50 мегабайт для целевого загруженного изображения
com.aspose.imaging.LoadOptions loadOptions = new com.aspose.imaging.LoadOptions();
loadOptions.setBufferSizeHint(50);
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(workDir + "inputFile.jpg", loadOptions);
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Baseline);
    jpegOptions.setQuality(100);
    image.save(workDir + "outputFile_Baseline.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);
    image.save(workDir + "outputFile_Progressive.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Lossless);
    jpegOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);
    jpegOptions.setBitsPerChannel((byte) 4);
    image.save(workDir + "outputFile_Lossless.jpg", jpegOptions);

    jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    jpegOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.JpegLs);
    jpegOptions.setJpegLsInterleaveMode(com.aspose.imaging.fileformats.jpeg.JpegLsInterleaveMode.None);
    jpegOptions.setJpegLsAllowedLossyError(3);
    jpegOptions.setJpegLsPreset(null);
    image.save(workDir + "outputFile_JpegLs.jpg", jpegOptions);
} finally {
    image.close();
}
```

### getConcurrentImageProcessing() {#getConcurrentImageProcessing--}
```
public final boolean getConcurrentImageProcessing()
```


Получает значение, указывающее, включена ли [concurrent image processing].

Значение: `true`, если [concurrent image processing]; в противном случае — `false`.

**Returns:**
boolean - значение, указывающее, включена ли [concurrent image processing].
### setConcurrentImageProcessing(boolean value) {#setConcurrentImageProcessing-boolean-}
```
public final void setConcurrentImageProcessing(boolean value)
```


Устанавливает значение, указывающее, включена ли [concurrent image processing].

Значение: `true`, если [concurrent image processing]; в противном случае — `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, включена ли [concurrent image processing]. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public ProgressEventHandler getIProgressEventHandler()
```


Получает обработчик события прогресса.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setIProgressEventHandler(ProgressEventHandler value) {#setIProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setIProgressEventHandler(ProgressEventHandler value)
```


Устанавливает обработчик события прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | обработчик события прогресса. |

