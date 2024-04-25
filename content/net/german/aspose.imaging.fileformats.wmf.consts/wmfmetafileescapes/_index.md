---
title: WmfMetafileEscapes
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die MetafileEscapes-Enumeration spezifiziert Druckertreiberfunktionen auf die möglicherweise nicht direkt über WMF-Einträge zugegriffen werden kann die in der RecordType-Enumeration Abschnitt 2.1.1.1 definiert sind.
type: docs
weight: 8230
url: /de/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
## WmfMetafileEscapes enumeration

Die MetafileEscapes-Enumeration spezifiziert Druckertreiberfunktionen, auf die möglicherweise nicht direkt über WMF-Einträge zugegriffen werden kann, die in der RecordType-Enumeration (Abschnitt 2.1.1.1) definiert sind.

```csharp
public enum WmfMetafileEscapes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Newframe | `1` | Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf eine Seite beendet hat. |
| Abortdoc | `2` | Beendet die Verarbeitung des aktuellen Dokuments. |
| Nextband | `3` | Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf ein Band beendet hat. |
| Setcolortable | `4` | Legt Farbtabellenwerte fest. |
| Getcolortable | `5` | Ruft Farbtabellenwerte ab. |
| Flushout | `6` | Bewirkt, dass alle anstehenden Ausgaben an das Ausgabegerät gesendet werden. |
| Draftmode | `7` | Gibt an, dass der Druckertreiber nur Text und keine Grafiken drucken SOLLTE. |
| Queryescsupport | `8` | Fragt einen Druckertreiber ab, um festzustellen, ob eine bestimmte Escape-Funktion auf dem Ausgabegerät unterstützt wird, das sie ansteuert. |
| Setabortproc | `9` | Legt die anwendungsdefinierte Funktion fest, die das Abbrechen eines Druckauftrags während des Druckens ermöglicht. |
| Startdoc | `10` | Benachrichtigt den Druckertreiber, dass ein neuer Druckauftrag gestartet wird. |
| Enddoc | `11` | Benachrichtigt den Druckertreiber, dass der aktuelle Druckauftrag beendet wird. |
| Getphyspagesize | `12` | Ruft die derzeit auf einem Ausgabegerät ausgewählte physische Seitengröße ab. |
| Getprintingoffset | `13` | Ruft den Versatz von der oberen linken Ecke der physischen Seite ab, wo das eigentliche Drucken oder Zeichnen beginnt. |
| Getscalingfactor | `14` | Ruft die Skalierungsfaktoren für die x-Achse und die y-Achse eines Druckers ab. |
| MetaEscapeEnhancedMetafile | `15` | Wird verwendet, um eine erweiterte Metadatei (EMF) -Metadatei in eine WMF-Metadatei einzubetten. |
| Setpenwidth | `16` | Legt die Breite eines Stifts in Pixel fest. |
| Setcopycount | `17` | Legt die Anzahl der Kopien fest. |
| Setpapersource | `18` | Legt die Quelle für Ausgabeformulare fest, z. B. ein bestimmtes Papierfach oder Fach eines Druckers. |
| Passthrough | `19` | Dieser Datensatz durchläuft willkürliche Daten. |
| Gettechnology | `20` | Ruft Informationen zur Grafiktechnologie ab, die auf einem -Gerät unterstützt wird. |
| Setlinecap | `21` | Gibt den Linienzeichnungsmodus an, der bei der Ausgabe an ein Gerät verwendet werden soll. |
| Setlinejoin | `22` | Gibt den Linienverbindungsmodus an, der bei der Ausgabe an ein Gerät verwendet werden soll. |
| Setmiterlimit | `23` | Legt die Grenze für die Länge von Gehrungsverbindungen fest, die bei der Ausgabe an ein Gerät verwendet werden sollen. |
| Bandinfo | `24` | Ruft Einstellungen zum Banding auf einem Gerät ab oder gibt sie an, z. B. die Anzahl der Bänder. |
| Drawpatternrect | `25` | Zeichnet ein Rechteck mit einem definierten Muster. |
| Getvectorpensize | `26` | Ruft die derzeit auf einem Gerät definierte physische Stiftgröße ab. |
| Getvectorbrushsize | `27` | Ruft die derzeit auf einem Gerät definierte physische Pinselgröße ab. |
| Enableduplex | `28` | Aktiviert oder deaktiviert doppelseitigen (Duplex-)Druck auf einem Gerät. |
| Getsetpaperbins | `29` | Ruft die Quelle von Ausgabeformularen auf einem Gerät ab oder gibt sie an. |
| Getsetprintorient | `30` | Ruft die Papierausrichtung auf einem Gerät ab oder gibt sie an. |
| Enumpaperbins | `31` | Ruft Informationen zu den Quellen verschiedener Formulare auf einem Ausgabegerät ab. |
| Setdibscaling | `32` | Gibt die Skalierung von geräteunabhängigen Bitmaps (DIBs) an. |
| Epsprinting | `33` | Gibt den Anfang und das Ende eines Encapsulated PostScript (EPS)-Abschnitts an. |
| Enumpapermetrics | `34` | Fragt einen Druckertreiber nach Papierabmessungen und anderen Formulardaten ab. |
| Getsetpapermetrics | `35` | Ruft Papierabmessungen und andere Formulardaten auf einem -Ausgabegerät ab oder gibt sie an. |
| PostscriptData | `37` | Sendet beliebige PostScript-Daten an ein Ausgabegerät. |
| PostscriptIgnore | `38` | Benachrichtigt ein Ausgabegerät, PostScript-Daten zu ignorieren. |
| Getdeviceunits | `42` | Ruft die aktuell auf einem Ausgabegerät konfigurierten Geräteeinheiten ab. |
| Getextendedtextmetrics | `256` | Ruft erweiterte Textmetriken ab, die derzeit auf einem Ausgabegerät konfiguriert sind. |
| Getpairkerntable | `258` | Ruft die derzeit auf einem Ausgabegerät definierte Font-Kern-Tabelle ab. |
| Exttextout | `512` | Zeichnet Text mit der aktuell ausgewählten Schriftart, Hintergrundfarbe und Textfarbe. |
| Getfacename | `513` | Ruft den derzeit auf einem Gerät konfigurierten Schriftartnamen ab. |
| Downloadface | `514` | Legt den Schriftartnamen auf einem Gerät fest. |
| MetafileDriver | `2049` | Fragt einen Druckertreiber nach der Unterstützung für Metadateien auf einem Ausgabegerät ab. |
| Querydibsupport | `3073` | Fragt den Druckertreiber nach seiner Unterstützung für DIBs auf einem Ausgabegerät ab. |
| BeginPath | `4096` | Öffnet einen Pfad. |
| ClipToPath | `4097` | Definiert einen Clip-Bereich, der durch einen Pfad begrenzt ist. Die Eingabe MUSS eine 16-Bit -Menge sein, die die durchzuführende Aktion definiert. |
| EndPath | `4098` | Beendet einen Pfad. |
| OpenChannel | `4110` | Dasselbe wie STARTDOC, angegeben mit einem NULL-Dokument und einem Ausgabe -Dateinamen, Daten im Rohmodus und einem Typ von Null. |
| Downloadheader | `4111` | Weist den Druckertreiber an, Sätze von PostScript-Prozeduren herunterzuladen. |
| CloseChannel | `4112` | Dasselbe wie ENDDOC. Siehe OPEN_CHANNEL. |
| PostscriptPassthrough | `4115` | Sendet beliebige Daten direkt an einen Druckertreiber, der diese Daten nur im PostScript-Modus verarbeiten soll.PostscriptIdentify . |
| EncapsulatedPostscript | `4116` | Sendet beliebige Daten direkt an den Druckertreiber. |
| PostscriptIdentify | `4117` | Stellt den Druckertreiber entweder auf PostScript- oder GDI-Modus ein. |
| PostscriptInjection | `4118` | Fügt einen Rohdatenblock in einen PostScript-Stream ein. Die Eingabe MUSS eine 32-Bit-Menge sein, die die Anzahl der zu injizierenden Bytes angibt, eine 16-Bit-Menge , die den Injektionspunkt angibt, und eine 16-Bit-Menge, die die Seitennummer angibt, gefolgt von den einzufügenden Bytes. |
| Checkjpegformat | `4119` | Überprüft, ob der Drucker ein JPEG-Bild unterstützt. |
| Checkpngformat | `4120` | Überprüft, ob der Drucker ein PNG-Bild unterstützt. |
| GetPsFeaturesetting | `4121` | Ruft Informationen zu einer bestimmten Funktionseinstellung für einen PostScript -Druckertreiber ab. |
| MxdcEscape | `4122` | Ermöglicht Anwendungen, Dokumente im Format XML Paper Specification (XPS) in eine Datei oder auf einen Drucker zu schreiben. |
| Spclpassthrough2 | `4568` | Ermöglicht Anwendungen, private Prozeduren und andere willkürliche Daten in Dokumente aufzunehmen. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
