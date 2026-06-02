---
title: "TiffAlphaStorage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Указывает хранение альфа-канала для tiff‑документов."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffAlphaStorage extends System.Enum
```

Указывает хранение альфа-канала для tiff‑документов.
## Поля

| Поле | Описание |
| --- | --- |
| [Unspecified](#Unspecified) | Альфа не указана и сохранена в файле TIFF. |
| [Associated](#Associated) | Значение альфа сохранено в предумноженной форме. |
| [Unassociated](#Unassociated) | Значение альфа сохранено в несвязанной форме. |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


Альфа не указана и сохранена в файле TIFF.

### Associated {#Associated}
```
public static final int Associated
```


Значение альфа сохранено в предумноженной форме. При восстановлении альфа могут возникнуть некоторые эффекты округления, и восстановленное значение может отличаться от оригинального.

### Unassociated {#Unassociated}
```
public static final int Unassociated
```


Значение альфа хранится в несвязанной форме. Это означает, что восстановленное альфа точно такое же, как было сохранено в TIFF.

