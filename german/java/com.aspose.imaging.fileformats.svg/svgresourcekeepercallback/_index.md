---
title: "SvgResourceKeeperCallback"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Ressourcen‑Keeper-Callback"
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

Der Ressourcen‑Keeper-Callback
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Aufgerufen, wenn die Bildressource zum Export bereit ist. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Aufgerufen, wenn die Schriftressource zum Export bereit ist. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | Aufgerufen, wenn das SVG-Dokument zum Export bereit ist. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Aufgerufen, wenn die Bildressource zum Export bereit ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageData | byte[] | Die Ressourcendaten. |
| imageType | int | Typ des Bildes. |
| suggestedFileName | java.lang.String | Name der vorgeschlagenen Datei. |
| useEmbeddedImage | boolean[] | Wenn auf `true` gesetzt, muss das eingebettete Bild verwendet werden. |

**Returns:**
java.lang.String - Gibt den Pfad zur gespeicherten Ressource zurück. Der Pfad sollte relativ zum Ziel‑SVG‑Dokument sein.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Aufgerufen, wenn die Schriftressource zum Export bereit ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | Die Optionen zum Speichern von Schriften. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


Aufgerufen, wenn das SVG-Dokument zum Export bereit ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlData | byte[] | Die SVG-Daten. |
| suggestedFileName | java.lang.String | Name der vorgeschlagenen Datei. |

**Returns:**
java.lang.String - Gibt den Pfad zum gespeicherten SVG-Dokument zurück.
