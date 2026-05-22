---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu sınıf, dış uygulamalarda dönüşüm ilerlemesini son kullanıcıya göstermek için kullanılabilecek görüntü yükleme/kaydetme/dışa aktarma işlemlerinin ilerleme bilgilerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Bu sınıf, dış uygulamalarda dönüşüm ilerlemesini son kullanıcıya göstermek için kullanılabilecek, görüntü yükleme/kaydetme/dışa aktarma işlemlerinin ilerleme bilgilerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDescription()](#getDescription--) | Olayın açıklamasını alır |
| [getEventType()](#getEventType--) | Olayın türünü alır. |
| [getMaxValue()](#getMaxValue--) | Üst ilerleme değer sınırını alır. |
| [getValue()](#getValue--) | Mevcut ilerleme değerini alır. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Yükleme/dışa aktarma işlemleri için ayrı işlem ilerleme olay işleyicilerinin örneği
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// STDOUT günlüğü şu şekilde görünebilir:
//        Yükleme olayı Başlatma : 1/4
//        Yükleme olayı Ön İşleme : 2/4
//        Yükleme olayı İşleme : 3/4
//        Yükleme olayı Sonlandırma : 4/4
//        Dışa aktarma olayı Başlatma : 1/4
//        Dışa aktarma olayı Ön İşleme : 2/4
//        Dışa aktarma olayı İşleme : 3/4
//        Dışa aktarma olayı Göreceli İlerleme : 1/1
//        Yükleme olayı Göreceli İlerleme : 1/1
//        Dışa aktarma olayı Sonlandırma : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Olayın açıklamasını alır

Değer: Açıklama.

**Returns:**
java.lang.String - olayın açıklaması
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Olayın türünü alır.

Değer: Olayın türü.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Üst ilerleme değer sınırını alır.

Değer: Üst ilerleme değer sınırı.

**Returns:**
int - üst ilerleme değer sınırı.
### getValue() {#getValue--}
```
public final int getValue()
```


Mevcut ilerleme değerini alır.

Değer: İlerleme değeri.

**Returns:**
int - mevcut ilerleme değeri.
