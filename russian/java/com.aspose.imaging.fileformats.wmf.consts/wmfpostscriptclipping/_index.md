---
title: "WmfPostScriptClipping"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Перечисление PostScriptClipping определяет функции, которые могут применяться к пути отсечения, используемому для вывода PostScript."
type: docs
weight: 32
url: /ru/java/com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptclipping/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptClipping extends System.Enum
```

Перечисление PostScriptClipping определяет функции, которые могут применяться к пути отсечения, используемому для вывода PostScript.
## Поля

| Поле | Описание |
| --- | --- |
| [CLIP_SAVE](#CLIP-SAVE) | Сохраняет текущий путь отсечения PostScript. |
| [CLIP_RESTORE](#CLIP-RESTORE) | Восстанавливает путь отсечения PostScript до последнего пути, который был сохранён предыдущей функцией CLIP\_SAVE, применённой записью CLIP\_TO\_PATH (раздел 2.3.6.6). |
| [CLIP_INCLUSIVE](#CLIP-INCLUSIVE) | Пересекает текущий путь отсечения PostScript с текущим путем отсечения и сохраняет результат как новый путь отсечения PostScript. |
### CLIP_SAVE {#CLIP-SAVE}
```
public static final int CLIP_SAVE
```


Сохраняет текущий путь отсечения PostScript.

### CLIP_RESTORE {#CLIP-RESTORE}
```
public static final int CLIP_RESTORE
```


Восстанавливает путь отсечения PostScript до последнего пути, который был сохранён предыдущей функцией CLIP\_SAVE, применённой записью CLIP\_TO\_PATH (раздел 2.3.6.6).

### CLIP_INCLUSIVE {#CLIP-INCLUSIVE}
```
public static final int CLIP_INCLUSIVE
```


Пересекает текущий путь отсечения PostScript с текущим путем отсечения и сохраняет результат как новый путь отсечения PostScript.

