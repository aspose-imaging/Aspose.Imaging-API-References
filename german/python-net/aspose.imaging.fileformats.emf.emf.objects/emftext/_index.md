---
title: "EmfText Klasse"
type: docs
weight: 260
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/
---

**Summary:** The EmrText object contains values for text output.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfText

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfText()](#EmfText__1) | Initialisiert eine neue Instanz der EmfText‑Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| chars | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Zeichen in der Zeichenkette angibt |
| dx_buffer | int[] | r/w | Liest oder setzt den optionalen Zeichenabstandspuffer<br/>            UndefinedSpace2 (Variable): Eine optionale Anzahl unbenutzter Bytes. Das Feld OutputDx muss nicht <br/>            unmittelbar auf den vorhergehenden Teil dieser Struktur folgen.<br/>            OutputDx (Variable): Ein Array von 32‑Bit vorzeichenlosen Ganzzahlen, das den Ausgabeabstand zwischen <br/>            den Ursprüngen benachbarter Zeichenzellen in logischen Einheiten angibt. Der Ort dieses Feldes wird durch <br/>            den Wert von offDx in Bytes vom Beginn dieses Datensatzes angegeben. Wenn ein Abstand definiert ist, enthält dieses Feld <br/>            die gleiche Anzahl von Werten wie Zeichen im Ausgabestring. Wenn das Optionsfeld des EmrText‑Objekts <br/>            das Flag ETO_PDY enthält, enthält dieser Puffer doppelt so viele Werte wie Zeichen im <br/>            Ausgabestring, jeweils einen horizontalen und einen vertikalen Versatz, in dieser Reihenfolge. Wenn ETO_RTLREADING angegeben ist, <br/>            werden Zeichen von rechts nach links statt von links nach rechts angeordnet. Keine anderen Optionen beeinflussen die Interpretation dieses Feldes. |
| glyph_index_buffer | int[] | r/w | Liest oder setzt den optionalen Glyphenindex-Puffer.<br/>            Wenn die Optionen das Flag ETO_GLYPH_INDEX enthalten, sind die Codes für Zeichen in einem Ausgabetextstring tatsächlich Indexe<br/>            der Zeichen-Glyphen in einer TrueType‑Schrift (2.1.11 ExtTextOutOptions‑Aufzählung). Glyphenindizes sind schriftspezifisch,<br/>            daher muss die zum Abspielen verwendete Schrift IDENTISCH sein mit der Schrift, die zur Erzeugung der Indizes verwendet wurde. |
| options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie das im Feld Rectangle angegebene Rechteck verwendet wird. Dieses Feld kann eine Kombination aus mehr als einem ExtTextOutOptions <br/>            Aufzählungswert (Abschnitt 2.1.11) sein. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein optionales WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das ein Clip‑ und/oder Undurchsichtigkeitsrechteck in logischen Einheiten definiert. Dieses Rechteck wird auf die Text<br/>            Ausgabe angewendet, die vom enthaltenden Datensatz durchgeführt wird. |
| reference | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein WMF PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15), das die Koordinaten des <br/>            Referenzpunkts angibt, der zur Positionierung der Zeichenkette verwendet wird. Der Referenzpunkt wird durch den letzten <br/>            EMR_SETTEXTALIGN‑Datensatz (Abschnitt 2.3.11.25) definiert. Wenn kein solcher Datensatz gesetzt wurde, <br/>            ist die Standardausrichtung TA_LEFT,TA_TOP. |
| string_buffer | string | r/w | Liest oder setzt den Zeichenketten‑Puffer<br/>            UndefinedSpace1 (Variable): Eine optionale Anzahl unbenutzter Bytes. <br/>            Das Feld OutputString muss nicht unmittelbar auf den vorhergehenden Teil dieser Struktur folgen.<br/>            OutputString (Variable): Ein Array von Zeichen, das die auszugebende Zeichenkette angibt. <br/>            Der Ort dieses Feldes wird durch den Wert von offString in Bytes vom Beginn dieses Datensatzes angegeben. <br/>            Die Anzahl der Zeichen wird durch den Wert von Chars angegeben. |


### Constructor: EmfText() {#EmfText__1}


```
 EmfText() 
```

Initialisiert eine neue Instanz der EmfText‑Klasse

