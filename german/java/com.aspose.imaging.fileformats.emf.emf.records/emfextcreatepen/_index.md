---
title: "EmfExtCreatePen"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EXTCREATEPEN-Datensatz definiert einen erweiterten logischen Stift für Grafikoperationen."
type: docs
weight: 52
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

Der EMR\_EXTCREATEPEN-Datensatz definiert einen erweiterten logischen Stift für Grafikoperationen. Ein optionales DIB kann angegeben werden, das als Linienstil verwendet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfExtCreatePen`-Klasse. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | Initialisiert eine neue Instanz der `EmfExtCreatePen`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhPen()](#getIhPen--) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des erweiterten logischen Stiftobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhPen(int value)](#setIhPen-int-) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des erweiterten logischen Stiftobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getElp()](#getElp--) | Liest oder schreibt ein LogPenEx‑Objekt (Abschnitt 2.2.20), das einen erweiterten logischen Stift mit Attributen einschließlich eines optionalen Linienstil‑Arrays definiert. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Liest oder schreibt ein LogPenEx‑Objekt (Abschnitt 2.2.20), das einen erweiterten logischen Stift mit Attributen einschließlich eines optionalen Linienstil‑Arrays definiert. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Liest oder schreibt einen optionalen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts ([MS-WMF] Abschnitt 2.2.2.9) enthält. |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Liest oder schreibt einen optionalen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts ([MS-WMF] Abschnitt 2.2.2.9) enthält. |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


Initialisiert eine neue Instanz der `EmfExtCreatePen`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Der Datensatz. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


Initialisiert eine neue Instanz der `EmfExtCreatePen`-Klasse.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des erweiterten logischen Stiftobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des erweiterten logischen Stiftobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Liest oder schreibt ein LogPenEx‑Objekt (Abschnitt 2.2.20), das einen erweiterten logischen Stift mit Attributen einschließlich eines optionalen Linienstil‑Arrays definiert.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Liest oder schreibt ein LogPenEx‑Objekt (Abschnitt 2.2.20), das einen erweiterten logischen Stift mit Attributen einschließlich eines optionalen Linienstil‑Arrays definiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Liest oder schreibt einen optionalen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts ([MS-WMF] Abschnitt 2.2.2.9) enthält. Es ist nicht erforderlich, dass er zusammenhängend mit dem festen Teil des EMR\_EXTCREATEPEN‑Datensatzes ist.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Liest oder schreibt einen optionalen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts ([MS-WMF] Abschnitt 2.2.2.9) enthält. Es ist nicht erforderlich, dass er zusammenhängend mit dem festen Teil des EMR\_EXTCREATEPEN‑Datensatzes ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

