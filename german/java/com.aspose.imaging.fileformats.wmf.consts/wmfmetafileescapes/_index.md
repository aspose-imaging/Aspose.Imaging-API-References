---
title: "WmfMetafileEscapes"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die MetafileEscapes Enumeration gibt die Druckertreiberfunktionalität an, die möglicherweise nicht direkt über WMF‑Datensätze zugänglich ist, die im RecordType‑Enumeration‑Abschnitt 2.1.1.1 definiert sind."
type: docs
weight: 24
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfMetafileEscapes extends System.Enum
```

Die MetafileEscapes-Aufzählung spezifiziert Druckertreiber-Funktionalität, die möglicherweise nicht direkt über WMF‑Datensätze zugänglich ist, die in der RecordType‑Aufzählung definiert sind (Abschnitt 2.1.1.1).
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Newframe](#Newframe) | Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf eine Seite abgeschlossen hat. |
| [Abortdoc](#Abortdoc) | Stoppt die Verarbeitung des aktuellen Dokuments. |
| [Nextband](#Nextband) | Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf ein Band abgeschlossen hat. |
| [Setcolortable](#Setcolortable) | Setzt Farbtabellenwerte. |
| [Getcolortable](#Getcolortable) | Liest Farbtabellenwerte. |
| [Flushout](#Flushout) | Veranlasst, dass alle ausstehenden Ausgaben an das Ausgabegerät weitergeleitet werden. |
| [Draftmode](#Draftmode) | Zeigt an, dass der Druckertreiber NUR Text und keine Grafiken drucken SOLLTE. |
| [Queryescsupport](#Queryescsupport) | Fragt einen Druckertreiber ab, um festzustellen, ob eine bestimmte Escape‑Funktion auf dem von ihm gesteuerten Ausgabegerät unterstützt wird. |
| [Setabortproc](#Setabortproc) | Setzt die von der Anwendung definierte Funktion, die das Abbrechen eines Druckauftrags während des Druckvorgangs ermöglicht. |
| [Startdoc](#Startdoc) | Benachrichtigt den Druckertreiber, dass ein neuer Druckauftrag startet. |
| [Enddoc](#Enddoc) | Benachrichtigt den Druckertreiber, dass der aktuelle Druckauftrag beendet wird. |
| [Getphyspagesize](#Getphyspagesize) | Ermittelt die derzeit auf einem Ausgabegerät ausgewählte physische Seitengröße. |
| [Getprintingoffset](#Getprintingoffset) | Ermittelt den Versatz von der oberen linken Ecke der physischen Seite, an dem das eigentliche Drucken oder Zeichnen beginnt. |
| [Getscalingfactor](#Getscalingfactor) | Ermittelt die Skalierungsfaktoren für die X‑Achse und die Y‑Achse eines Druckers. |
| [MetaEscapeEnhancedMetafile](#MetaEscapeEnhancedMetafile) | Wird verwendet, um ein Enhanced Metafile-Format (EMF) Metafile in ein WMF Metafile einzubetten. |
| [Setpenwidth](#Setpenwidth) | Setzt die Breite eines Stifts in Pixeln. |
| [Setcopycount](#Setcopycount) | Setzt die Anzahl der Kopien. |
| [Setpapersource](#Setpapersource) | Setzt die Quelle, z. B. ein bestimmtes Papierfach oder Fach eines Druckers, für Ausgabeformen. |
| [Passthrough](#Passthrough) | Dieser Datensatz leitet beliebige Daten weiter. |
| [Gettechnology](#Gettechnology) | Liest Informationen über die Grafiktechnologie, die von einem Gerät unterstützt wird. |
| [Setlinecap](#Setlinecap) | Gibt den zu verwendenden Linienzeichnungsmodus für die Ausgabe an ein Gerät an. |
| [Setlinejoin](#Setlinejoin) | Gibt den zu verwendenden Linienverbindungsmodus für die Ausgabe an ein Gerät an. |
| [Setmiterlimit](#Setmiterlimit) | Setzt die Grenze für die Länge von Gehrungsverbindungen, die bei der Ausgabe an ein Gerät verwendet werden. |
| [Bandinfo](#Bandinfo) | Ruft Einstellungen bezüglich der Bandbildung auf einem Gerät ab oder legt sie fest, z. B. die Anzahl der Bänder. |
| [Drawpatternrect](#Drawpatternrect) | Zeichnet ein Rechteck mit einem definierten Muster. |
| [Getvectorpensize](#Getvectorpensize) | Ruft die aktuell auf einem Gerät definierte physische Stiftgröße ab. |
| [Getvectorbrushsize](#Getvectorbrushsize) | Ruft die aktuell auf einem Gerät definierte physische Pinselgröße ab. |
| [Enableduplex](#Enableduplex) | Aktiviert oder deaktiviert den beidseitigen (Duplex‑) Druck auf einem Gerät. |
| [Getsetpaperbins](#Getsetpaperbins) | Ruft die Quelle der Ausgabemasken auf einem Gerät ab oder legt sie fest. |
| [Getsetprintorient](#Getsetprintorient) | Ruft die Papierausrichtung auf einem Gerät ab oder legt sie fest. |
| [Enumpaperbins](#Enumpaperbins) | Ruft Informationen zu den Quellen verschiedener Formulare auf einem Ausgabegerät ab. |
| [Setdibscaling](#Setdibscaling) | Legt die Skalierung von geräteunabhängigen Bitmaps (DIBs) fest. |
| [Epsprinting](#Epsprinting) | Kennzeichnet den Beginn und das Ende eines encapsulated PostScript (EPS)-Abschnitts. |
| [Enumpapermetrics](#Enumpapermetrics) | Fragt einen Druckertreiber nach Papierabmessungen und anderen Formulardaten. |
| [Getsetpapermetrics](#Getsetpapermetrics) | Ruft Papierabmessungen und andere Formulardaten auf einem Ausgabegerät ab oder legt sie fest. |
| [PostscriptData](#PostscriptData) | Sendet beliebige PostScript-Daten an ein Ausgabegerät. |
| [PostscriptIgnore](#PostscriptIgnore) | Benachrichtigt ein Ausgabegerät, PostScript-Daten zu ignorieren. |
| [Getdeviceunits](#Getdeviceunits) | Ermittelt die aktuell auf einem Ausgabegerät konfigurierten Geräteeinheiten. |
| [Getextendedtextmetrics](#Getextendedtextmetrics) | Ermittelt die aktuell auf einem Ausgabegerät konfigurierten erweiterten Textmetriken. |
| [Getpairkerntable](#Getpairkerntable) | Ermittelt die aktuell auf einem Ausgabegerät definierte Schriftart‑Kerntabelle. |
| [Exttextout](#Exttextout) | Zeichnet Text mit der aktuell ausgewählten Schriftart, Hintergrundfarbe und Textfarbe. |
| [Getfacename](#Getfacename) | Ermittelt den aktuell auf einem Gerät konfigurierten Schriftartnamen. |
| [Downloadface](#Downloadface) | Legt den Schriftartnamen auf einem Gerät fest. |
| [MetafileDriver](#MetafileDriver) | Fragt einen Druckertreiber nach der Unterstützung von Metadateien auf einem Ausgabegerät. |
| [Querydibsupport](#Querydibsupport) | Fragt den Druckertreiber nach seiner Unterstützung von DIBs auf einem Ausgabegerät. |
| [BeginPath](#BeginPath) | Öffnet einen Pfad. |
| [ClipToPath](#ClipToPath) | Definiert einen Clip‑Bereich, der durch einen Pfad begrenzt ist. |
| [EndPath](#EndPath) | Beendet einen Pfad. |
| [OpenChannel](#OpenChannel) | Das gleiche wie STARTDOC, angegeben mit einem NULL-Dokument und Ausgabedateinamen, Daten im Rohmodus und einem Typ von Null. |
| [Downloadheader](#Downloadheader) | Weist den Druckertreiber an, Sätze von PostScript‑Prozeduren herunterzuladen. |
| [CloseChannel](#CloseChannel) | Das gleiche wie ENDDOC. |
| [PostscriptPassthrough](#PostscriptPassthrough) | Sendet beliebige Daten direkt an den Druckertreiber, der diese Daten nur im PostScript‑Modus verarbeiten soll. |
| [EncapsulatedPostscript](#EncapsulatedPostscript) | Sendet beliebige Daten direkt an den Druckertreiber. |
| [PostscriptIdentify](#PostscriptIdentify) | Setzt den Druckertreiber entweder in den PostScript‑ oder GDI‑Modus. |
| [PostscriptInjection](#PostscriptInjection) | Fügt einen Block roher Daten in einen PostScript‑Stream ein. |
| [Checkjpegformat](#Checkjpegformat) | Prüft, ob der Drucker ein JPEG‑Bild unterstützt. |
| [Checkpngformat](#Checkpngformat) | Prüft, ob der Drucker ein PNG‑Bild unterstützt. |
| [GetPsFeaturesetting](#GetPsFeaturesetting) | Ruft Informationen zu einer angegebenen Funktions­einstellung für einen PostScript‑Druckertreiber ab. |
| [MxdcEscape](#MxdcEscape) | Ermöglicht Anwendungen, Dokumente in das XML Paper Specification (XPS)‑Format in eine Datei oder an einen Drucker zu schreiben. |
| [Spclpassthrough2](#Spclpassthrough2) | Ermöglicht Anwendungen, private Prozeduren und andere beliebige Daten in Dokumente einzufügen. |
### Newframe {#Newframe}
```
public static final int Newframe
```


Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf eine Seite abgeschlossen hat.

### Abortdoc {#Abortdoc}
```
public static final int Abortdoc
```


Stoppt die Verarbeitung des aktuellen Dokuments.

### Nextband {#Nextband}
```
public static final int Nextband
```


Benachrichtigt den Druckertreiber, dass die Anwendung das Schreiben auf ein Band abgeschlossen hat.

### Setcolortable {#Setcolortable}
```
public static final int Setcolortable
```


Setzt Farbtabellenwerte.

### Getcolortable {#Getcolortable}
```
public static final int Getcolortable
```


Liest Farbtabellenwerte.

### Flushout {#Flushout}
```
public static final int Flushout
```


Veranlasst, dass alle ausstehenden Ausgaben an das Ausgabegerät weitergeleitet werden.

### Draftmode {#Draftmode}
```
public static final int Draftmode
```


Zeigt an, dass der Druckertreiber NUR Text und keine Grafiken drucken SOLLTE.

### Queryescsupport {#Queryescsupport}
```
public static final int Queryescsupport
```


Fragt einen Druckertreiber ab, um festzustellen, ob eine bestimmte Escape‑Funktion auf dem von ihm gesteuerten Ausgabegerät unterstützt wird.

### Setabortproc {#Setabortproc}
```
public static final int Setabortproc
```


Setzt die von der Anwendung definierte Funktion, die das Abbrechen eines Druckauftrags während des Druckvorgangs ermöglicht.

### Startdoc {#Startdoc}
```
public static final int Startdoc
```


Benachrichtigt den Druckertreiber, dass ein neuer Druckauftrag startet.

### Enddoc {#Enddoc}
```
public static final int Enddoc
```


Benachrichtigt den Druckertreiber, dass der aktuelle Druckauftrag beendet wird.

### Getphyspagesize {#Getphyspagesize}
```
public static final int Getphyspagesize
```


Ermittelt die derzeit auf einem Ausgabegerät ausgewählte physische Seitengröße.

### Getprintingoffset {#Getprintingoffset}
```
public static final int Getprintingoffset
```


Ermittelt den Versatz von der oberen linken Ecke der physischen Seite, an dem das eigentliche Drucken oder Zeichnen beginnt.

### Getscalingfactor {#Getscalingfactor}
```
public static final int Getscalingfactor
```


Ermittelt die Skalierungsfaktoren für die X‑Achse und die Y‑Achse eines Druckers.

### MetaEscapeEnhancedMetafile {#MetaEscapeEnhancedMetafile}
```
public static final int MetaEscapeEnhancedMetafile
```


Wird verwendet, um ein Enhanced Metafile-Format (EMF) Metafile in ein WMF Metafile einzubetten.

### Setpenwidth {#Setpenwidth}
```
public static final int Setpenwidth
```


Setzt die Breite eines Stifts in Pixeln.

### Setcopycount {#Setcopycount}
```
public static final int Setcopycount
```


Setzt die Anzahl der Kopien.

### Setpapersource {#Setpapersource}
```
public static final int Setpapersource
```


Setzt die Quelle, z. B. ein bestimmtes Papierfach oder Fach eines Druckers, für Ausgabeformen.

### Passthrough {#Passthrough}
```
public static final int Passthrough
```


Dieser Datensatz leitet beliebige Daten weiter.

### Gettechnology {#Gettechnology}
```
public static final int Gettechnology
```


Liest Informationen über die Grafiktechnologie, die von einem Gerät unterstützt wird.

### Setlinecap {#Setlinecap}
```
public static final int Setlinecap
```


Gibt den zu verwendenden Linienzeichnungsmodus für die Ausgabe an ein Gerät an.

### Setlinejoin {#Setlinejoin}
```
public static final int Setlinejoin
```


Gibt den zu verwendenden Linienverbindungsmodus für die Ausgabe an ein Gerät an.

### Setmiterlimit {#Setmiterlimit}
```
public static final int Setmiterlimit
```


Setzt die Grenze für die Länge von Gehrungsverbindungen, die bei der Ausgabe an ein Gerät verwendet werden.

### Bandinfo {#Bandinfo}
```
public static final int Bandinfo
```


Ruft Einstellungen bezüglich der Bandbildung auf einem Gerät ab oder legt sie fest, z. B. die Anzahl der Bänder.

### Drawpatternrect {#Drawpatternrect}
```
public static final int Drawpatternrect
```


Zeichnet ein Rechteck mit einem definierten Muster.

### Getvectorpensize {#Getvectorpensize}
```
public static final int Getvectorpensize
```


Ruft die aktuell auf einem Gerät definierte physische Stiftgröße ab.

### Getvectorbrushsize {#Getvectorbrushsize}
```
public static final int Getvectorbrushsize
```


Ruft die aktuell auf einem Gerät definierte physische Pinselgröße ab.

### Enableduplex {#Enableduplex}
```
public static final int Enableduplex
```


Aktiviert oder deaktiviert den beidseitigen (Duplex‑) Druck auf einem Gerät.

### Getsetpaperbins {#Getsetpaperbins}
```
public static final int Getsetpaperbins
```


Ruft die Quelle der Ausgabemasken auf einem Gerät ab oder legt sie fest.

### Getsetprintorient {#Getsetprintorient}
```
public static final int Getsetprintorient
```


Ruft die Papierausrichtung auf einem Gerät ab oder legt sie fest.

### Enumpaperbins {#Enumpaperbins}
```
public static final int Enumpaperbins
```


Ruft Informationen zu den Quellen verschiedener Formulare auf einem Ausgabegerät ab.

### Setdibscaling {#Setdibscaling}
```
public static final int Setdibscaling
```


Legt die Skalierung von geräteunabhängigen Bitmaps (DIBs) fest.

### Epsprinting {#Epsprinting}
```
public static final int Epsprinting
```


Kennzeichnet den Beginn und das Ende eines encapsulated PostScript (EPS)-Abschnitts.

### Enumpapermetrics {#Enumpapermetrics}
```
public static final int Enumpapermetrics
```


Fragt einen Druckertreiber nach Papierabmessungen und anderen Formulardaten.

### Getsetpapermetrics {#Getsetpapermetrics}
```
public static final int Getsetpapermetrics
```


Ruft Papierabmessungen und andere Formulardaten auf einem Ausgabegerät ab oder legt sie fest.

### PostscriptData {#PostscriptData}
```
public static final int PostscriptData
```


Sendet beliebige PostScript-Daten an ein Ausgabegerät.

### PostscriptIgnore {#PostscriptIgnore}
```
public static final int PostscriptIgnore
```


Benachrichtigt ein Ausgabegerät, PostScript-Daten zu ignorieren.

### Getdeviceunits {#Getdeviceunits}
```
public static final int Getdeviceunits
```


Ermittelt die aktuell auf einem Ausgabegerät konfigurierten Geräteeinheiten.

### Getextendedtextmetrics {#Getextendedtextmetrics}
```
public static final int Getextendedtextmetrics
```


Ermittelt die aktuell auf einem Ausgabegerät konfigurierten erweiterten Textmetriken.

### Getpairkerntable {#Getpairkerntable}
```
public static final int Getpairkerntable
```


Ermittelt die aktuell auf einem Ausgabegerät definierte Schriftart‑Kerntabelle.

### Exttextout {#Exttextout}
```
public static final int Exttextout
```


Zeichnet Text mit der aktuell ausgewählten Schriftart, Hintergrundfarbe und Textfarbe.

### Getfacename {#Getfacename}
```
public static final int Getfacename
```


Ermittelt den aktuell auf einem Gerät konfigurierten Schriftartnamen.

### Downloadface {#Downloadface}
```
public static final int Downloadface
```


Legt den Schriftartnamen auf einem Gerät fest.

### MetafileDriver {#MetafileDriver}
```
public static final int MetafileDriver
```


Fragt einen Druckertreiber nach der Unterstützung von Metadateien auf einem Ausgabegerät.

### Querydibsupport {#Querydibsupport}
```
public static final int Querydibsupport
```


Fragt den Druckertreiber nach seiner Unterstützung von DIBs auf einem Ausgabegerät.

### BeginPath {#BeginPath}
```
public static final int BeginPath
```


Öffnet einen Pfad.

### ClipToPath {#ClipToPath}
```
public static final int ClipToPath
```


Definiert einen Clip‑Bereich, der durch einen Pfad begrenzt ist. Die Eingabe MUSS eine 16‑Bit‑Größe sein, die die auszuführende Aktion definiert.

### EndPath {#EndPath}
```
public static final int EndPath
```


Beendet einen Pfad.

### OpenChannel {#OpenChannel}
```
public static final int OpenChannel
```


Das gleiche wie STARTDOC, angegeben mit einem NULL-Dokument und Ausgabedateinamen, Daten im Rohmodus und einem Typ von Null.

### Downloadheader {#Downloadheader}
```
public static final int Downloadheader
```


Weist den Druckertreiber an, Sätze von PostScript‑Prozeduren herunterzuladen.

### CloseChannel {#CloseChannel}
```
public static final int CloseChannel
```


Das gleiche wie ENDDOC. Siehe OPEN\_CHANNEL.

### PostscriptPassthrough {#PostscriptPassthrough}
```
public static final int PostscriptPassthrough
```


Sendet beliebige Daten direkt an den Druckertreiber, der diese Daten nur im PostScript‑Modus verarbeiten soll. [PostscriptIdentify](../../com.aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes\#PostscriptIdentify).

### EncapsulatedPostscript {#EncapsulatedPostscript}
```
public static final int EncapsulatedPostscript
```


Sendet beliebige Daten direkt an den Druckertreiber.

### PostscriptIdentify {#PostscriptIdentify}
```
public static final int PostscriptIdentify
```


Setzt den Druckertreiber entweder in den PostScript‑ oder GDI‑Modus.

### PostscriptInjection {#PostscriptInjection}
```
public static final int PostscriptInjection
```


Fügt einen Block roher Daten in einen PostScript‑Stream ein. Die Eingabe MUSS eine 32‑Bit‑Größe sein, die die Anzahl der einzufügenden Bytes angibt, eine 16‑Bit‑Größe, die den Einfügepunkt angibt, und eine 16‑Bit‑Größe, die die Seitennummer angibt, gefolgt von den einzufügenden Bytes.

### Checkjpegformat {#Checkjpegformat}
```
public static final int Checkjpegformat
```


Prüft, ob der Drucker ein JPEG‑Bild unterstützt.

### Checkpngformat {#Checkpngformat}
```
public static final int Checkpngformat
```


Prüft, ob der Drucker ein PNG‑Bild unterstützt.

### GetPsFeaturesetting {#GetPsFeaturesetting}
```
public static final int GetPsFeaturesetting
```


Ruft Informationen zu einer angegebenen Funktions­einstellung für einen PostScript‑Druckertreiber ab.

### MxdcEscape {#MxdcEscape}
```
public static final int MxdcEscape
```


Ermöglicht Anwendungen, Dokumente in das XML Paper Specification (XPS)‑Format in eine Datei oder an einen Drucker zu schreiben.

### Spclpassthrough2 {#Spclpassthrough2}
```
public static final int Spclpassthrough2
```


Ermöglicht Anwendungen, private Prozeduren und andere beliebige Daten in Dokumente einzufügen.

