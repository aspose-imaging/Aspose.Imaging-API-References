---
title: "EmfCreateMonoBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CREATEMONOBRUSH‑Datensatz definiert einen monochromen Musterpinsel für Grafikoperationen."
type: docs
weight: 39
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

Der EMR\_CREATEMONOBRUSH‑Datensatz definiert einen monochromen Musterpinsel für Grafikoperationen. Das Muster wird durch ein monochromes DIB angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfCreateMonoBrush`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des monochromen Musterpinselobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhBrush(int value)](#setIhBrush-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des monochromen Musterpinselobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getUsage()](#getUsage--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der angibt, wie Werte in der Farbtabell im DIB‑Header zu interpretieren sind. |
| [setUsage(int value)](#setUsage-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der angibt, wie Werte in der Farbtabell im DIB‑Header zu interpretieren sind. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Ruft einen Puffer ab oder legt ihn fest, der ein gepacktes DIB in Form eines WMF‑DeviceIndependentBitmap‑Objekts enthält ([MS-WMF] Abschnitt 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ruft einen Puffer ab oder legt ihn fest, der ein gepacktes DIB in Form eines WMF‑DeviceIndependentBitmap‑Objekts enthält ([MS-WMF] Abschnitt 2.2.2.9). |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfCreateMonoBrush`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des monochromen Musterpinselobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des monochromen Musterpinselobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im DIB‑Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen.

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im DIB‑Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Liest oder setzt einen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts enthält ([MS‑WMF] Abschnitt 2.2.2.9). Es ist nicht erforderlich, dass er zusammenhängend mit dem festen Teil des EMR\_CREATEDIBPATTERNBRUSHPT‑Datensatzes ist.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts enthält ([MS‑WMF] Abschnitt 2.2.2.9). Es ist nicht erforderlich, dass er zusammenhängend mit dem festen Teil des EMR\_CREATEDIBPATTERNBRUSHPT‑Datensatzes ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

