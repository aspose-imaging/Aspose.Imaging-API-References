---
title: "EmfPolyTextOutA"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_POLYTEXTOUTA-Datensatz zeichnet ein oder mehrere ASCII-Textzeichenketten mit der aktuellen Schriftart und den Textfarben."
type: docs
weight: 97
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutA extends EmfDrawingRecordType
```

Der EMR\\_POLYTEXTOUTA-Datensatz zeichnet eine oder mehrere ASCII-Textzeichenketten mit der aktuellen Schriftart und Textfarben.

Die für die Ausgabe verwendete Schriftart und die Textfarben werden durch Eigenschaften im aktuellen Zustand des Wiedergabegerätekontexts festgelegt. EMR_POLYTEXTOUTA SOLLTE mit einer Reihe von EMR_EXTTEXTOUTW-Datensätzen (Abschnitt 2.3.5.7) emuliert werden, jeweils einer pro Zeichenkette. Dies erfordert, dass die ASCII-Textzeichenkette in jedem EmrText-Objekt in die Unicode‑UTF16‑LE‑Kodierung konvertiert wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPolyTextOutA(EmfRecord source)](#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPolyTextOutA`-Klasse. |
| [EmfPolyTextOutA()](#EmfPolyTextOutA--) | Initialisiert eine neue Instanz der [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck in Geräteeinheiten angibt. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck in Geräteeinheiten angibt. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den aktuellen Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt. |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den aktuellen Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt. |
| [getExScale()](#getExScale--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die X‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist. |
| [setExScale(float value)](#setExScale-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die X‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist. |
| [getEyScale()](#getEyScale--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Y‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist. |
| [setEyScale(float value)](#setEyScale-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Y‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist. |
| [getAEmrText()](#getAEmrText--) | Liest oder setzt ein Array von EmrText‑Objekten (Abschnitt 2.2.5), die die Ausgabestrings in 8‑Bit‑ASCII‑Zeichen mit Texteigenschaften und Abstandswerten angeben. |
| [setAEmrText(EmfText[] value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Liest oder setzt ein Array von EmrText‑Objekten (Abschnitt 2.2.5), die die Ausgabestrings in 8‑Bit‑ASCII‑Zeichen mit Texteigenschaften und Abstandswerten angeben. |
### EmfPolyTextOutA(EmfRecord source) {#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutA(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPolyTextOutA`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfPolyTextOutA() {#EmfPolyTextOutA--}
```
public EmfPolyTextOutA()
```


Initialisiert eine neue Instanz der [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta)-Klasse.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck in Geräteeinheiten angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck in Geräteeinheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den aktuellen Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt.

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den aktuellen Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die X‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die X‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Y‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die Y‑Skalierung von Seiteneinheiten zu .01 mm‑Einheiten angibt, wenn der Grafikmodus GM_COMPATIBLE ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText[] getAEmrText()
```


Liest oder setzt ein Array von EmrText‑Objekten (Abschnitt 2.2.5), die die Ausgabestrings in 8‑Bit‑ASCII‑Zeichen mit Texteigenschaften und Abstandswerten angeben. Die Anzahl der EmrText‑Objekte wird durch cStrings festgelegt.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setAEmrText(EmfText[] value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setAEmrText(EmfText[] value)
```


Liest oder setzt ein Array von EmrText‑Objekten (Abschnitt 2.2.5), die die Ausgabestrings in 8‑Bit‑ASCII‑Zeichen mit Texteigenschaften und Abstandswerten angeben. Die Anzahl der EmrText‑Objekte wird durch cStrings festgelegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

