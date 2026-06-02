---
title: "EmfPolyTextOutW"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_POLYTEXTOUTW-Datensatz zeichnet ein oder mehrere Unicode-Textzeichenketten mit der aktuellen Schriftart und den Textfarben."
type: docs
weight: 98
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

Der EMR\\_POLYTEXTOUTW-Datensatz zeichnet eine oder mehrere Unicode-Textzeichenketten mit der aktuellen Schriftart und Textfarben.

Die für die Ausgabe verwendete Schriftart und die Textfarben werden durch Eigenschaften im aktuellen Zustand des Wiedergabegeräte‑Kontexts festgelegt. EMR\_POLYTEXTOUTW SOLLTE mit einer Reihe von EMR\_EXTTEXTOUTW-Datensätzen (Abschnitt 2.3.5.7) emuliert werden, jeweils einer pro Zeichenkette.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPolyTextOutW`‑Klasse. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | Initialisiert eine neue Instanz der `EmfPolyTextOutW`‑Klasse. |
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
| [getWEmrText()](#getWEmrText--) | Ruft ab oder legt ein Array von EmrText‑Objekten (Abschnitt 2.2.5) fest, die die Ausgabestrings in 16‑Bit‑Unicode‑UTF16‑LE‑Zeichen mit Texteigenschaften und Abstandswerten angeben. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Ruft ab oder legt ein Array von EmrText‑Objekten (Abschnitt 2.2.5) fest, die die Ausgabestrings in 16‑Bit‑Unicode‑UTF16‑LE‑Zeichen mit Texteigenschaften und Abstandswerten angeben. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPolyTextOutW`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


Initialisiert eine neue Instanz der `EmfPolyTextOutW`‑Klasse.

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

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


Ruft ab oder legt ein Array von EmrText‑Objekten (Abschnitt 2.2.5) fest, die die Ausgabestrings in 16‑Bit‑Unicode‑UTF16‑LE‑Zeichen mit Texteigenschaften und Abstandswerten angeben. Die Anzahl der EmrText‑Objekte wird durch cStrings angegeben.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


Ruft ab oder legt ein Array von EmrText‑Objekten (Abschnitt 2.2.5) fest, die die Ausgabestrings in 16‑Bit‑Unicode‑UTF16‑LE‑Zeichen mit Texteigenschaften und Abstandswerten angeben. Die Anzahl der EmrText‑Objekte wird durch cStrings angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

