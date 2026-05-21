---
title: "PdfImageCompressionOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры сжатия изображений PDF."
type: docs
weight: 35
url: /ru/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Параметры сжатия изображений PDF.
## Поля

| Поле | Описание |
| --- | --- |
| [Auto](#Auto) | Автоматически выбирает наиболее подходящее сжатие для каждого изображения. |
| [None](#None) | Сохраняет необработанные байты изображения, что приводит к большему размеру PDF‑файлов. |
| [Rle](#Rle) | Сжатие Run Length. |
| [Flate](#Flate) | Сжатие Flate. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | Выбор предиктора ограничен предиктором PNG Paeth для ускорения процесса. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | Выбор предиктора более сложный и должен приводить к меньшему размеру изображений, но требует больше времени. |
| [Jpeg](#Jpeg) | Сжатие Jpeg. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Не поддерживает прозрачность. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Не поддерживает прозрачность. |
### Auto {#Auto}
```
public static final int Auto
```


Автоматически выбирает наиболее подходящее сжатие для каждого изображения.

### None {#None}
```
public static final int None
```


Сохраняет необработанные байты изображения, что приводит к большему размеру PDF‑файлов.

### Rle {#Rle}
```
public static final int Rle
```


Сжатие Run Length.

### Flate {#Flate}
```
public static final int Flate
```


Сжатие Flate.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


Выбор предиктора ограничен предиктором PNG Paeth для ускорения процесса. На практике работает удивительно хорошо. Лучше, чем [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


Выбор предиктора более сложный и должен приводить к меньшему размеру изображений, но требует больше времени. RFC 2083 утверждает, что это лучший способ. Однако на тестовых данных базовый предиктор [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) показывает отличные результаты, оставляя оптимизированный предиктор позади на 25‑40 % прироста коэффициента сжатия.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Сжатие Jpeg. Не поддерживает прозрачность.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 Не поддерживает прозрачность.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 Не поддерживает прозрачность.

