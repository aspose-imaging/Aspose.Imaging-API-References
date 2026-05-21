---
title: "EmfCloseFigure"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu kayıt, bir yoldaki açık şekli kapatır."
type: docs
weight: 22
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

Bu kayıt, bir yoldaki açık bir şekli kapatır. EMR\_CLOSEFIGURE kaydının işlenmesi, şekli mevcut konumdan şeklin ilk noktasına bir çizgi çizerek kapatmalı ve ardından çizgi birleştirme stilini kullanarak çizgileri bağlamalıdır. Bir şekil, EMR\_CLOSEFIGURE kaydı yerine EMR\_LINETO kaydı işlenerek kapatılırsa, köşe birleştirme yerine uç kapakları kullanılır. EMR\_LINETO bölümü 2.3.5.13'te belirtilmiştir. EMR\_CLOSEFIGURE kaydı, yalnızca oynatma aygıt bağlamında açık bir yol parantezi varsa kullanılmalıdır. Bir yoldaki şekil, bu kayıt işlenerek açıkça kapatılmadıkça açıktır.

Not: Mevcut nokta ve şeklin başlangıç noktası aynı olsa bile bir şekil açık olabilir. EMR\_CLOSEFIGURE kaydı işlendiğinden sonra, yola bir çizgi veya eğri eklemek MUST yeni bir şekil başlatmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Yeni bir `EmfCloseFigure` sınıfı örneği başlatır. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Yeni bir `EmfCloseFigure` sınıfı örneği başlatır.

