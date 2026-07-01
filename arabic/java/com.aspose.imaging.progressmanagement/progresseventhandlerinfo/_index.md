---
title: "ProgressEventHandlerInfo"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تمثل هذه الفئة معلومات حول تقدم عمليات تحميل/حفظ/تصدير الصورة التي يمكن استخدامها في تطبيق خارجي لعرض تقدم التحويل للمستخدم النهائي."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

هذه الفئة تمثل معلومات حول تقدم عمليات تحميل/حفظ/تصدير الصورة، والتي يمكن استخدامها في تطبيق خارجي لعرض تقدم التحويل للمستخدم النهائي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDescription()](#getDescription--) | يحصل على وصف الحدث |
| [getEventType()](#getEventType--) | يحصل على نوع الحدث. |
| [getMaxValue()](#getMaxValue--) | يحصل على الحد الأعلى لقيمة التقدم. |
| [getValue()](#getValue--) | يحصل على قيمة التقدم الحالية. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// مثال على استخدام معالجات أحداث تقدم العملية المنفصلة لعمليات التحميل/التصدير
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

// قد يبدو سجل STDOUT هكذا:
//        حدث التحميل التهيئة : 1/4
//        حدث التحميل ما قبل المعالجة : 2/4
//        حدث التحميل المعالجة : 3/4
//        حدث التحميل الإنهاء : 4/4
//        حدث التصدير التهيئة : 1/4
//        حدث التصدير ما قبل المعالجة : 2/4
//        حدث التصدير المعالجة : 3/4
//        حدث التصدير RelativeProgress : 1/1
//        حدث التحميل RelativeProgress : 1/1
//        حدث التصدير الإنهاء : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


يحصل على وصف الحدث

القيمة: الوصف.

**Returns:**
java.lang.String - وصف الحدث
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


يحصل على نوع الحدث.

القيمة: نوع الحدث.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


يحصل على الحد الأعلى لقيمة التقدم.

القيمة: الحد الأعلى لقيمة التقدم.

**Returns:**
int - الحد الأعلى لقيمة التقدم.
### getValue() {#getValue--}
```
public final int getValue()
```


يحصل على قيمة التقدم الحالية.

القيمة: قيمة التقدم.

**Returns:**
int - قيمة التقدم الحالية.
