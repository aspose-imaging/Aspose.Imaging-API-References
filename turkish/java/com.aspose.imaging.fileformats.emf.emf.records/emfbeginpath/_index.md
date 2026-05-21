---
title: "EmfBeginPath"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu kayıt, geçerli oynatma cihaz bağlamında bir yol parantezi açar."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

Bu kayıt, geçerli oynatma cihaz bağlamında bir yol parantezi açar. Bir yol parantezi açıldıktan sonra, bir uygulama yoldaki noktaları tanımlamak için kayıtları işlemeye başlayabilir. Bir uygulama, EMR\\_ENDPATH kaydını işleyerek açık bir yol parantezini KAPATMALIDIR. Bir uygulama EMR\\_BEGINPATH kaydını işlediğinde, önceki tüm yollar oynatma cihaz bağlamından ATILMALIDIR.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | `EmfBeginPath` sınıfının yeni bir örneğini başlatır. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


`EmfBeginPath` sınıfının yeni bir örneğini başlatır.

