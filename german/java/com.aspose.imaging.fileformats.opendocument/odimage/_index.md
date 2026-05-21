---
title: "OdImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das offene Dokument"
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

Das offene Dokument
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Ruft die Standardseite ab, die mit dem Bild verknüpft ist, und bietet essentiellen Zugriff auf die Hauptseite innerhalb der Bildsammlung. |
| [isCached()](#isCached--) | Ermittelt einen booleschen Wert, der angibt, ob die Daten des Objekts derzeit im Cache gespeichert sind, wodurch das erneute Lesen der Daten entfällt. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ruft die Anzahl der Bits pro Pixel des Bildes ab. |
| [getPageCount()](#getPageCount--) | Ruft die Gesamtzahl der Seiten im Bild ab. |
| [getOdMetadata()](#getOdMetadata--) | Ruft Metadaten ab, die spezifisch für OpenDocument-Dateien sind. |
| [getRecords()](#getRecords--) | Ruft die im Bild gespeicherten OpenDocument-Datensätze ab. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Ruft die Standardseite ab, die dem Bild zugeordnet ist, und bietet essentiellen Zugriff auf die Hauptseite innerhalb der Bildsammlung. Diese Eigenschaft erleichtert die Navigation und Manipulation von Bilddaten und erhöht die Effizienz von Softwareentwicklungs‑Workflows.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Erhält einen booleschen Wert, der angibt, ob die Daten des Objekts derzeit im Cache sind, wodurch das Lesen von Daten entfällt. Diese Eigenschaft dient als Optimierungsindikator und verbessert die Leistung, indem redundante Datenzugriffsoperationen minimiert werden.

**Returns:**
boolean – ein Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ruft die Anzahl der Bits pro Pixel für das Bild ab. Diese Eigenschaft liefert Einblick in das Detaillierungs‑ und Farbtiefenniveau des Bildes und unterstützt verschiedene Bildverarbeitungsaufgaben und Optimierungen.

**Returns:**
int – die Bit‑Pro‑Pixel‑Anzahl des Bildes.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Ruft die Gesamtzahl der Seiten im Bild ab. Diese Eigenschaft ist für Anwendungen, die mehrseitige Bilder verwalten, unerlässlich, da sie eine genaue Bestimmung der für Verarbeitung oder Anzeige verfügbaren Seiten ermöglicht.

**Returns:**
int – die Seitenanzahl.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


Ruft Metadaten ab, die spezifisch für OpenDocument‑Dateien sind. Diese Eigenschaft ermöglicht den Zugriff auf wesentliche Informationen, die in OD‑Dateien eingebettet sind, und erleichtert verschiedene Vorgänge wie das Extrahieren, Ändern oder Analysieren von Metadaten.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Ruft die im Bild gespeicherten OpenDocument‑Datensätze ab. Diese Eigenschaft gewährt Zugriff auf spezifische strukturierte Datenelemente, die in OpenDocument‑Dateien eingebettet sind, und erleichtert das Abrufen oder die Manipulation relevanter Informationen für weitere Verarbeitung oder Analyse.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - die Datensätze.
