---
title: "EmfExtTextOutA"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EXTTEXTOUTA-Datensatz zeichnet eine ASCII‑Textzeichenfolge mit der aktuellen Schriftart und den Textfarben."
type: docs
weight: 56
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutA extends EmfDrawingRecordType
```

Der EMR\_EXTTEXTOUTA-Datensatz zeichnet eine ASCII-Textzeichenfolge mit der aktuellen Schriftart und den Textfarben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfExtTextOutA(EmfRecord source)](#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der Klasse `EmfExtTextOutA`. |
| [EmfExtTextOutA()](#EmfExtTextOutA--) | Initialisiert eine neue Instanz der [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds()](#getBounds--) | Liest oder setzt ein WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt. |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt. |
| [getExScale()](#getExScale--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der X‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. |
| [setExScale(float value)](#setExScale-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der X‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. |
| [getEyScale()](#getEyScale--) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der Y‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. |
| [setEyScale(float value)](#setEyScale-float-) | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der Y‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. |
| [getAEmrText()](#getAEmrText--) | Liest oder setzt ein EmrText‑Objekt (Abschnitt 2.2.5), das die Ausgabestring in 8‑Bit‑ASCII‑Zeichen, Textattribute und Abstandswerte angibt. |
| [setAEmrText(EmfText value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | Liest oder setzt ein EmrText‑Objekt (Abschnitt 2.2.5), das die Ausgabestring in 8‑Bit‑ASCII‑Zeichen, Textattribute und Abstandswerte angibt. |
### EmfExtTextOutA(EmfRecord source) {#EmfExtTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutA(EmfRecord source)
```


Initialisiert eine neue Instanz der Klasse `EmfExtTextOutA`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfExtTextOutA() {#EmfExtTextOutA--}
```
public EmfExtTextOutA()
```


Initialisiert eine neue Instanz der [EmfExtTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfexttextouta)-Klasse.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liest oder setzt ein WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19). Es wird nicht verwendet und MUSS beim Empfang ignoriert werden.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Liest oder setzt ein WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19). Es wird nicht verwendet und MUSS beim Empfang ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt.

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Grafikmodus aus der GraphicsMode‑Aufzählung (Abschnitt 2.1.16) angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der X‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. Dieser SOLLTE nur verwendet werden, wenn der durch iGraphicsMode angegebene Grafikmodus GM\_COMPATIBLE ist.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der X‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. Dieser SOLLTE nur verwendet werden, wenn der durch iGraphicsMode angegebene Grafikmodus GM\_COMPATIBLE ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der Y‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. Dieser SOLLTE nur verwendet werden, wenn der durch iGraphicsMode angegebene Grafikmodus GM\_COMPATIBLE ist.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Skalierungsfaktor entlang der Y‑Achse angibt, um von Seiteneinheiten in .01 mm‑Einheiten zu konvertieren. Dieser SOLLTE nur verwendet werden, wenn der durch iGraphicsMode angegebene Grafikmodus GM\_COMPATIBLE ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getAEmrText() {#getAEmrText--}
```
public EmfText getAEmrText()
```


Liest oder setzt ein EmrText‑Objekt (Abschnitt 2.2.5), das die Ausgabestring in 8‑Bit‑ASCII‑Zeichen, Textattribute und Abstandswerte angibt.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setAEmrText(EmfText value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setAEmrText(EmfText value)
```


Liest oder setzt ein EmrText‑Objekt (Abschnitt 2.2.5), das die Ausgabestring in 8‑Bit‑ASCII‑Zeichen, Textattribute und Abstandswerte angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

