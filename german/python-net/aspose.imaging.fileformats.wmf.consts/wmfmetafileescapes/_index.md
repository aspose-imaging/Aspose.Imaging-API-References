---
title: "WmfMetafileEscapes Aufzählung"
type: docs
weight: 150
url: /de/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---

Die MetafileEscapes‑Enumeration gibt die Druckertreiber‑Funktionalität an, die möglicherweise nicht<br/>                direkt über WMF‑Datensätze zugänglich ist, die in der RecordType‑Enumeration definiert sind (Abschnitt 2.1.1.1).

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfMetafileEscapes

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| ABORTDOC | Stoppt die Verarbeitung des aktuellen Dokuments. |
| BANDINFO | Ruft Einstellungen bezüglich der Bandbildung auf einem Gerät ab oder legt sie fest, wie zum Beispiel die<br/>                Anzahl der Bänder. |
| BEGIN_PATH | Öffnet einen Pfad. |
| CHECKJPEGFORMAT | Prüft, ob der Drucker ein JPEG‑Bild unterstützt. |
| CHECKPNGFORMAT | Prüft, ob der Drucker ein PNG‑Bild unterstützt. |
| CLIP_TO_PATH | Definiert einen Clip‑Bereich, der durch einen Pfad begrenzt ist. Die Eingabe MUSS eine 16‑Bit<br/>                Größe sein, die die auszuführende Aktion definiert. |
| CLOSE_CHANNEL | Das gleiche wie ENDDOC. Siehe OPEN_CHANNEL. |
| DOWNLOADFACE | Legt den Schriftartnamen auf einem Gerät fest. |
| DOWNLOADHEADER | Weist den Druckertreiber an, Sätze von PostScript‑Prozeduren herunterzuladen. |
| DRAFTMODE | Zeigt an, dass der Druckertreiber NUR Text und keine Grafiken drucken SOLLTE. |
| DRAWPATTERNRECT | Zeichnet ein Rechteck mit einem definierten Muster. |
| ENABLEDUPLEX | Aktiviert oder deaktiviert beidseitiges (Duplex‑)Drucken auf einem Gerät. |
| ENCAPSULATED_POSTSCRIPT | Sendet beliebige Daten direkt an den Druckertreiber. |
| ENDDOC | Benachrichtigt den Druckertreiber, dass der aktuelle Druckauftrag beendet wird. |
| END_PATH | Beendet einen Pfad. |
| ENUMPAPERBINS | Ruft Informationen zu den Quellen verschiedener Formulare auf einem<br/>                Ausgabegerät ab. |
| ENUMPAPERMETRICS | Fragt den Druckertreiber nach Papierabmessungen und anderen Formulardaten. |
| EPSPRINTING | Zeigt den Beginn und das Ende eines encapsulierten PostScript‑(EPS‑)Abschnitts an. |
| EXTTEXTOUT | Zeichnet Text mit der aktuell ausgewählten Schriftart, Hintergrundfarbe und Textfarbe. |
| FLUSHOUT | Veranlasst, dass alle ausstehenden Ausgaben zum Ausgabegerät geleert werden. |
| GETCOLORTABLE | Liest Farbtabellenwerte. |
| GETDEVICEUNITS | Liest die Geräteeinheiten, die derzeit auf einem Ausgabegerät konfiguriert sind. |
| GETEXTENDEDTEXTMETRICS | Liest erweiterte Textmetriken, die derzeit auf einem Ausgabegerät<br/>                konfiguriert sind. |
| GETFACENAME | Liest den Schriftartnamen, der derzeit auf einem Gerät konfiguriert ist. |
| GETPAIRKERNTABLE | Liest die Schriftart-Kern-Tabelle, die derzeit auf einem Ausgabegerät definiert ist. |
| GETPHYSPAGESIZE | Ermittelt die physische Seitengröße, die derzeit auf einem Ausgabegerät ausgewählt ist. |
| GETPRINTINGOFFSET | Ermittelt den Abstand von der oberen linken Ecke der physischen Seite<br/>                an dem der eigentliche Druck oder das Zeichnen beginnt. |
| GETSCALINGFACTOR | Ermittelt die Skalierungsfaktoren für die x-Achse und die y-Achse eines Druckers. |
| GETSETPAPERBINS | Ermittelt oder legt die Quelle der Ausgabeformen auf einem Gerät fest. |
| GETSETPAPERMETRICS | Ermittelt oder legt Papierabmessungen und andere Formulardaten auf einem<br/>                Ausgabegerät fest. |
| GETSETPRINTORIENT | Ermittelt oder legt die Papierausrichtung auf einem Gerät fest. |
| GETTECHNOLOGY | Ruft Informationen zur Grafiktechnologie ab, die auf einem<br/>                Gerät unterstützt wird. |
| GETVECTORBRUSHSIZE | Ermittelt die physische Pinselgröße, die derzeit auf einem Gerät definiert ist. |
| GETVECTORPENSIZE | Ermittelt die physische Stiftgröße, die derzeit auf einem Gerät definiert ist. |
| GET_PS_FEATURESETTING | Ruft Informationen zu einer angegebenen Feature-Einstellung für einen PostScript<br/>                Druckertreiber ab. |
| METAFILE_DRIVER | Fragt einen Druckertreiber nach der Unterstützung von Metadateien auf einem Ausgabegerät<br/>                ab. |
| META_ESCAPE_ENHANCED_METAFILE | Wird verwendet, um ein erweitertes Metadateiformat (EMF)<br/>                Metadatei in einer WMF-Metadatei einzubetten. |
| MXDC_ESCAPE | Ermöglicht Anwendungen, Dokumente in eine Datei oder an einen Drucker im XML Paper Specification (XPS)-Format zu schreiben. |
| NEWFRAME | Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf einer Seite abgeschlossen hat. |
| NEXTBAND | Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf einem Band abgeschlossen hat. |
| OPEN_CHANNEL | Entspricht STARTDOC, angegeben mit einem NULL-Dokument und Ausgabe<br/>                Dateinamen, Daten im Rohmodus und einem Typ von Null. |
| PASSTHROUGH | Dieser Datensatz leitet beliebige Daten weiter. |
| POSTSCRIPT_DATA | Sendet beliebige PostScript-Daten an ein Ausgabegerät. |
| POSTSCRIPT_IDENTIFY | Legt den Druckertreiber entweder auf PostScript- oder GDI-Modus fest. |
| POSTSCRIPT_IGNORE | Benachrichtigt ein Ausgabegerät, PostScript-Daten zu ignorieren. |
| POSTSCRIPT_INJECTION | Fügt einen Block roher Daten in einen PostScript‑Strom ein. Der Eingang<br/>                MUSS eine 32‑Bit‑Größe sein, die die Anzahl der einzufügenden Bytes angibt, eine 16‑Bit‑Größe<br/>                die den Injektionspunkt angibt, und eine 16‑Bit‑Größe die die Seitennummer angibt, gefolgt von<br/>                den einzufügenden Bytes. |
| POSTSCRIPT_PASSTHROUGH | Sendet beliebige Daten direkt an einen Druckertreiber, der<br/>                erwartet, diese Daten nur im PostScript‑Modus zu verarbeiten. [WmfMetafileEscapes.POSTSCRIPT_IDENTIFY](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/). |
| QUERYDIBSUPPORT | Fragt den Druckertreiber nach seiner Unterstützung für DIBs auf einem Ausgabegerät. |
| QUERYESCSUPPORT | Fragt einen Druckertreiber, um festzustellen, ob eine bestimmte Escape‑Funktion<br/>                auf dem von ihm gesteuerten Ausgabegerät unterstützt wird. |
| SETABORTPROC | Legt die anwendungsdefinierte Funktion fest, die es ermöglicht, einen Druckauftrag abzubrechen<br/>                während des Druckens. |
| SETCOLORTABLE | Legt Farbtabellenwerte fest. |
| SETCOPYCOUNT | Legt die Anzahl der Kopien fest. |
| SETDIBSCALING | Gibt die Skalierung von geräteunabhängigen Bitmaps (DIBs) an. |
| SETLINECAP | Gibt den zu verwendenden Linienzeichnungsmodus für die Ausgabe an ein Gerät an. |
| SETLINEJOIN | Gibt den zu verwendenden Linienverbindungsmodus für die Ausgabe an ein Gerät an. |
| SETMITERLIMIT | Legt die Grenze für die Länge von Gehrungsverbindungen fest, die in der Ausgabe an ein Gerät verwendet werden. |
| SETPAPERSOURCE | Legt die Quelle fest, z. B. ein bestimmtes Papierfach oder eine Schublade an einem Drucker, für<br/>                Ausgabemasken. |
| SETPENWIDTH | Legt die Breite eines Stifts in Pixeln fest. |
| SPCLPASSTHROUGH2 | Ermöglicht Anwendungen, private Prozeduren und andere beliebige<br/>                Daten in Dokumente einzufügen. |
| STARTDOC | Benachrichtigt den Druckertreiber, dass ein neuer Druckauftrag startet. |
