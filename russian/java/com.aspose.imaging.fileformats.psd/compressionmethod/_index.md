---
title: "CompressionMethod"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет метод сжатия, используемый для данных изображения."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Определяет метод сжатия, используемый для данных изображения.
## Поля

| Поле | Описание |
| --- | --- |
| [Raw](#Raw) | Без сжатия. |
| [RLE](#RLE) | RLE-сжатые данные изображения начинаются с подсчётов байтов для всех строк сканирования (строки \* каналы), при этом каждый счёт хранится как двухбайтовое значение. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP без предсказания. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP с предсказанием. |
### Raw {#Raw}
```
public static final short Raw
```


Без сжатия. Данные изображения хранятся как необработанные байты в планарном порядке RGBA. Это означает, что сначала записываются все данные R, затем все данные G, затем B и, наконец, все данные A.

### RLE {#RLE}
```
public static final short RLE
```


RLE-сжатые данные изображения начинаются с подсчётов байтов для всех строк сканирования (строки \* каналы), при этом каждый счёт хранится как двухбайтовое значение. Затем следуют RLE-сжатые данные, при этом каждая строка сканирования сжимается отдельно. Сжатие RLE использует тот же алгоритм, что и процедура PackBits в ROM Macintosh и стандарт TIFF.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP без предсказания.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP с предсказанием.

