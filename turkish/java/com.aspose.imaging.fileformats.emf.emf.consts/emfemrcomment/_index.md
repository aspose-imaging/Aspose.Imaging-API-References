---
title: "EmfEmrComment"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmrComment sayımı, 2.3.3.4 bölümünde belirtildiği gibi bir genel yorum kaydının içerebileceği veri türlerini tanımlar."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfEmrComment extends System.Enum
```

EmrComment sayımı, 2.3.3.4 bölümünde belirtildiği gibi, bir genel yorum kaydının içerebileceği veri türlerini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EMR_COMMENT_WINDOWS_METAFILE](#EMR-COMMENT-WINDOWS-METAFILE) | Bu yorum kaydı, WMF içinde bir görüntünün belirtimini içerir. |
| [EMR_COMMENT_BEGINGROUP](#EMR-COMMENT-BEGINGROUP) | Bu yorum kaydı, bir çizim kayıtları grubunun başlangıcını tanımlar. |
| [EMR_COMMENT_ENDGROUP](#EMR-COMMENT-ENDGROUP) | Bu yorum kaydı, bir çizim kayıtları grubunun sonunu tanımlar. |
| [EMR_COMMENT_MULTIFORMATS](#EMR-COMMENT-MULTIFORMATS) | Bu yorum kaydı, bir metafilde bir görüntünün birden fazla tanımının dahil edilmesine izin verir. |
| [EMR_COMMENT_UNICODE_STRING](#EMR-COMMENT-UNICODE-STRING) | Bu yorum kaydı ayrılmıştır ve bir EMF metafilinde KULLANILMAMALIDIR. |
| [EMR_COMMENT_UNICODE_END](#EMR-COMMENT-UNICODE-END) | Bu yorum kaydı ayrılmıştır ve bir EMF metafilinde KULLANILMAMALIDIR. |
### EMR_COMMENT_WINDOWS_METAFILE {#EMR-COMMENT-WINDOWS-METAFILE}
```
public static final long EMR_COMMENT_WINDOWS_METAFILE
```


Bu yorum kaydı, WMF içinde bir görüntünün belirtimini içerir. Daha fazla bilgi için [MS-WMF] adresine bakın.

### EMR_COMMENT_BEGINGROUP {#EMR-COMMENT-BEGINGROUP}
```
public static final long EMR_COMMENT_BEGINGROUP
```


Bu yorum kaydı, bir grup çizim kaydının başlangıcını tanımlar. EMF metafilesi içinde bir nesneyi tanımlar.

### EMR_COMMENT_ENDGROUP {#EMR-COMMENT-ENDGROUP}
```
public static final long EMR_COMMENT_ENDGROUP
```


Bu yorum kaydı, bir grup çizim kaydının sonunu tanımlar. Her EMR\_COMMENT\_BEGINGROUP kaydı için, metafile içinde bir EMR\_COMMENT\_ENDGROUP kaydı ZORUNLUDUR ve bunlar İÇİNELEŞTİRİLEBİLİR.

### EMR_COMMENT_MULTIFORMATS {#EMR-COMMENT-MULTIFORMATS}
```
public static final long EMR_COMMENT_MULTIFORMATS
```


Bu yorum kaydı, metafile içinde bir görüntünün birden fazla tanımının eklenmesine izin verir. Örneğin bu yorumu kullanarak, bir uygulama kapsüllenmiş PostScript metnini ve ayrıca bir görüntünün EMF tanımını ekleyebilir.

### EMR_COMMENT_UNICODE_STRING {#EMR-COMMENT-UNICODE-STRING}
```
public static final long EMR_COMMENT_UNICODE_STRING
```


Bu yorum kaydı ayrılmıştır ve bir EMF metafilinde KULLANILMAMALIDIR.

### EMR_COMMENT_UNICODE_END {#EMR-COMMENT-UNICODE-END}
```
public static final long EMR_COMMENT_UNICODE_END
```


Bu yorum kaydı ayrılmıştır ve bir EMF metafilinde KULLANILMAMALIDIR.

