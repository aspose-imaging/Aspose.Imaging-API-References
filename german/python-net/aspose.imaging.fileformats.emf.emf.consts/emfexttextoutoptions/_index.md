---
title: "EmfExtTextOutOptions Aufzählung"
type: docs
weight: 100
url: /de/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---

Die ExtTextOutOptions-Aufzählung gibt Parameter an, die verschiedene Aspekte der<br/>            Textausgabe durch EMR_SMALLTEXTOUT (Abschnitt 2.3.5.37)-Datensätze und in EmrText-Objekten steuern.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfExtTextOutOptions

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| ETO_CLIPPED | Dieses Bit gibt an, dass der Text SOLL an das Rechteck gekürzt werden. |
| ETO_GLYPH_INDEX | Dieses Bit gibt an, dass die Codes für Zeichen in einer Ausgabetextzeichenfolge tatsächlich <br/>            Indizes der Zeichen-Glyphen in einer TrueType-Schriftart sind. Glyphen-Indizes sind schriftspezifisch, <br/>            sodass zur Anzeige der korrekten Zeichen bei der Wiedergabe die verwendete Schriftart MUSS <br/>            identisch sein mit der Schriftart, die zur Erzeugung der Indizes verwendet wurde. |
| ETO_IGNORELANGUAGE | Dieses Bit gibt an, dass keine spezielle Betriebssystemverarbeitung für die Glyphenplatzierung <br/>            bei rechts-nach-links-Strings durchgeführt werden soll; das heißt, alle Glyphenpositionierungen SOLLEN von <br/>            Zeichen- und Zustandsaufzeichnungen in der Metadatei übernommen werden. |
| ETO_NO_RECT | Dieses Bit gibt an, dass der Datensatz kein Begrenzungsrechteck für die Textausgabe angibt. |
| ETO_NUMERICSLATIN | Dieses Bit gibt an, dass zur Anzeige von Zahlen europäische Ziffern SOLLEN verwendet werden. |
| ETO_NUMERICSLOCAL | Dieses Bit gibt an, dass zur Anzeige von Zahlen lokalspezifische Ziffern SOLLEN verwendet werden. |
| ETO_OPAQUE | Dieses Bit gibt an, dass die aktuelle Hintergrundfarbe SOLL verwendet wird, um das Rechteck zu füllen. |
| ETO_PDY | Dieses Bit gibt an, dass sowohl horizontale als auch vertikale Zeichenversatzwerte SOLLEN bereitgestellt werden. |
| ETO_REVERSE_INDEX_MAP | Dieses Bit ist reserviert und SOLL NICHT verwendet werden |
| ETO_RTLREADING | Dieses Bit gibt an, dass der Text RECHTS‑NACH‑LINKS angeordnet werden MUSS, <br/>            anstatt der standardmäßigen LINKS‑NACH‑RECHTS‑Reihenfolge. Dies SOLLTE nur angewendet werden, wenn die in den Wiedergabegeräte‑Kontext ausgewählte Schriftart entweder Hebräisch oder Arabisch ist |
| ETO_SMALL_CHARS | Dieses Bit gibt an, dass die Codes für Zeichen in einer Ausgabetextzeichenfolge 8 Bit groß sind, <br/>            abgeleitet von den niederwertigen Bytes der 16‑Bit Unicode UTF16‑LE Zeichen‑Codes, <br/>            wobei das höherwertige Byte als 0 angenommen wird. |
