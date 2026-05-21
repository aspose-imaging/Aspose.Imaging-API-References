---
title: "EmfGraphicsMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "GraphicsMode sayımı, dikdörtgen koordinatları gibi şekil verilerinin nasıl yorumlanacağını belirtmek için kullanılır."
type: docs
weight: 24
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

GraphicsMode sayımı, dikdörtgen koordinatları gibi şekil verilerinin nasıl yorumlanacağını belirtmek için kullanılır.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | TrueType text MUST sol taraftan sağa ve sağ tarafı yukarı bakacak şekilde yazılmalıdır, hatta geri kalan grafikler mevcut world-to-device transformation nedeniyle x ekseni ya da y ekseni etrafında döndürülmüş olsa bile playback device context içinde. |
| [GM_ADVANCED](#GM-ADVANCED) | TrueType text output MUST mevcut world-to-device transformation ile playback device context içinde tam uyumlu olmalıdır. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


TrueType text MUST sol taraftan sağa ve sağ tarafı yukarı bakacak şekilde yazılmalıdır, hatta geri kalan grafikler mevcut world-to-device transformation nedeniyle x ekseni ya da y ekseni etrafında döndürülmüş olsa bile playback device context içinde. Metnin yüksekliği yalnızca ölçeklenmelidir (SHOULD). Yaylar, playback device context içindeki mevcut yay yönü kullanılarak çizilmelidir, ancak mevcut world-to-device transformation'a (x ekseni ya da y ekseni etrafında bir dönüşüm gerektirebilir) uymamaları gerekir (MUST NOT). world-to-device transformation yalnızca pencere ve görüntüleme alanı genişlik ve başlangıç noktaları değiştirilerek, EMR\_SETWINDOWEXTEX (section 2.3.11.30) ve EMR\_SETVIEWPORTEXTEX (section 2.3.11.28) kayıtları ile, ayrıca EMR\_SETWINDOWORGEX (section 2.3.11.31) ve EMR\_SETVIEWPORTORGEX (section 2.3.11.30) kayıtları ile (SIRAYLA) değiştirilmelidir. bChanging dönüşüm doğrudan EMR\_MODIFYWORLDTRANSFORM (section 2.3.12.1) veya EMR\_SETWORLDTRANSFORM (section 2.3.12.2) kayıtları kullanılarak MAY NOT desteklenebilir. GM\_COMPATIBLE grafik modunda, dikdörtgenler çizilirken alt ve en sağ kenarlar MUST dışarıda bırakılmalıdır.

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


TrueType text output MUST mevcut world-to-device transformation ile playback device context içinde tam uyumlu olmalıdır. Yaylar, dünya uzayında counterclockwise yönde çizilmelidir; ancak yay kontrol noktaları ve yaylar kendileri mevcut world-to-device transformation'ı playback device context içinde tam olarak respekt etmelidir (MUST). world-to-device transform doğrudan EMR\_MODIFYWORLDTRANSFORM veya EMR\_SETWORLDTRANSFORM kayıtları kullanılarak, ya da dolaylı olarak pencere ve görüntüleme alanı genişlik ve başlangıç noktaları değiştirilerek, EMR\_SETWINDOWEXTEX (section 2.3.11.30) ve EMR\_SETVIEWPORTEXTEX (section 2.3.11.28) kayıtları ve EMR\_SETWINDOWORGEX (section 2.3.11.31) ve EMR\_SETVIEWPORTORGEX (section 2.3.11.30) kayıtları (SIRAYLA) değiştirilebilir (MAY). GM\_ADVANCED grafik modunda, dikdörtgenler çizilirken alt ve en sağ kenarlar MUST dahil edilmelidir.

