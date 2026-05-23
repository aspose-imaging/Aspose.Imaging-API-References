---
title: "EmfPlusHeader Klasse"
type: docs
weight: 310
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| dual_mode | bool | r/w | Holt oder setzt einen Wert, der angibt, ob [dual mode] aktiviert ist.<br/>            Ist er gesetzt, zeigt dieses Flag an, dass diese Metadatei \"dual-mode\" ist, was bedeutet,<br/>            dass sie zwei Sätze von Datensätzen enthält, von denen jeder den Grafikinhalt vollständig definiert.<br/>            Ist das Flag nicht gesetzt, wird der Grafikinhalt durch EMF+-Datensätze definiert, ggf. ergänzt durch EMF‑Datensätze, die einem EmfPlusGetDC‑Datensatz vorausgehen.<br/>            Wenn dieses Flag gesetzt ist, sollten EMF‑Datensätze allein ausreichen, um den Grafikinhalt zu definieren.<br/>            Beachten Sie, dass unabhängig davon, ob das \"dual-mode\"‑Flag gesetzt ist, einige EMF‑Datensätze stets vorhanden sind, nämlich EMF‑Steuerdatensätze und die EMF‑Datensätze, die EMF+-Datensätze enthalten. EMF‑Steuerdatensätze sind in [MS-EMF] <br/>            Abschnitt 2.3.4 spezifiziert. |
| emf_plus_flags | int | r/w | Holt oder setzt die EMF‑plus‑Flags.<br/>            Eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die Informationen darüber enthält, wie diese Metadatei aufgezeichnet wurde.<br/>            Ist das 31. Bit des Feldes gesetzt, zeigt dieses Flag an, dass die Metadatei mit einem Referenz‑Geräte‑Kontext für ein Video‑Display aufgezeichnet wurde. Ist das Flag nicht gesetzt, wurde die Metadatei mit einem Referenz‑Geräte‑Kontext für einen Drucker aufgezeichnet. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| is_valid | bool | r | Liefert einen Wert, der angibt, ob diese Instanz gültig ist. |
| logical_dpi_x | int | r/w | Holt oder setzt das logische DPI x.<br/>            Eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die horizontale Auflösung angibt, für die die Metadatei <br/>            aufgezeichnet wurde, in Einheiten von Pixel pro Zoll. |
| logical_dpi_y | int | r/w | Holt oder setzt das logische DPI y.<br/>            Eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die vertikale Auflösung angibt, für die die Metadatei <br/>            aufgezeichnet wurde, in Einheiten von Zeilen pro Zoll. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Holt oder setzt die Version.<br/>            Ein EmfPlusGraphicsVersion‑Objekt (Abschnitt 2.2.2.19), das die Version der Betriebssystem‑Grafik angibt, die zur Erstellung dieser Metadatei verwendet wurde. |
| video_display | bool | r/w | Holt oder setzt einen Wert, der angibt, ob ein Video‑Display verwendet wird.<br/>            Ist das Flag gesetzt, zeigt es an, dass die Metadatei mit einem Referenz‑Geräte‑Kontext für ein Video‑Display aufgezeichnet wurde. Ist das Flag nicht gesetzt, wurde die Metadatei mit einem Referenz‑Geräte‑Kontext für einen Drucker aufgezeichnet. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

