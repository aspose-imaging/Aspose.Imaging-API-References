---
title: "CompressionMethod Перечисление"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

Определяет метод сжатия, используемый для данных изображения.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| RAW | Без сжатия. Данные изображения хранятся как необработанные байты в планарном порядке RGBA.<br/>            Это означает, что сначала записываются все данные R, затем все данные G, затем B и, наконец, все данные A. |
| RLE | При сжатии RLE данные изображения начинаются с подсчётов байтов для всех строк сканирования (строки * каналы), при этом каждый<br/>            подсчёт хранится как двухбайтовое значение. Затем следуют сжатые данные RLE, при этом каждая строка сканирования сжимается отдельно.<br/>            Сжатие RLE использует тот же алгоритм сжатия, что и процедура PackBits в ROM Macintosh и стандарт TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP без предсказания. |
| ZIP_WITH_PREDICTION | ZIP с предсказанием. |
