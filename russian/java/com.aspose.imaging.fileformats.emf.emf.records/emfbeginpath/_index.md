---
title: "EmfBeginPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Эта запись открывает скобку пути в текущем контексте устройства воспроизведения."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

Эта запись открывает скобку пути в текущем контексте устройства воспроизведения. После открытия скобки пути приложение может начать обработку записей для определения точек, лежащих в пути. Приложение ДОЛЖНО закрыть открытую скобку пути, обработав запись EMR\\_ENDPATH. При обработке записью EMR\\_BEGINPATH все предыдущие пути ДОЛЖНЫ быть удалены из контекста устройства воспроизведения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | Инициализирует новый экземпляр класса `EmfBeginPath`. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


Инициализирует новый экземпляр класса `EmfBeginPath`.

