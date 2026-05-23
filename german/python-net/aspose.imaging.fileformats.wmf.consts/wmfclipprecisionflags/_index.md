---
title: "WmfClipPrecisionFlags Enumeration"
type: docs
weight: 50
url: /de/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

ClipPrecision‑Flags geben die Clipping‑Präzision an, die definiert, wie Zeichen abgeschnitten werden, die<br/>                teilweise außerhalb einer Clipping‑Region liegen. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| CHARACTER | Dieser Wert SOLLTE NICHT verwendet werden. |
| STANDARD | Gibt an, dass das Standard‑Clipping VERWENDET WERDEN MUSS. |
| DFA_DISABLE | Dieser Wert gibt an, dass die Schriftartenzuordnung [35] deaktiviert werden SOLLTE.<br/>
                [35] Dieser Wert wird in Windows 95, Windows 98 und Windows Millennium Edition nicht unterstützt.<br/>
                Die Schriftartenzuordnung ist in Windows 2000, Windows XP und Windows Server 2003 deaktiviert.<br/>
                Dieser Wert wird in den folgenden Windows‑Versionen ignoriert:<br/>
                - Windows Vista<br/>
                - Windows Server 2008<br/>
                - Windows 7<br/>
                - Windows Server 2008 R2<br/>
                - Windows 8<br/>
                - Windows Server 2012<br/>
                - Windows 8.1<br/>
                - Windows Server 2012 R2 |
| EMBEDDED | Dieser Wert gibt an, dass die Schriftart‑Einbettung VERWENDET WERDEN MUSS, um Dokumenten‑<br/>
                inhalte zu rendern; eingebettete Schriftarten sind schreibgeschützt. |
| LH_ANGLES | Dieser Wert wird verwendet, um die Schriftart‑Drehung zu steuern, wie folgt:<br/>
                - Wenn gesetzt, SOLLTE die Drehung für alle Schriftarten durch die Orientierung<br/>
    des Koordinatensystems bestimmt werden; das heißt, ob die Orientierung linkshändig<br/>
    oder rechtshändig ist.<br/>
                - Wenn nicht gesetzt, SOLLTEN Geräteschriftarten gegen den Uhrzeigersinn drehen, aber die Drehung von<br/>
    anderen Schriftarten SOLLTE durch die Orientierung des Koordinatensystems bestimmt werden. |
| STRICH | Dieser Wert KANN zurückgegeben werden, wenn rasterisierte, TrueType‑ und<br/>
                Vektorschriftarten aufgezählt werden.<br/>
                [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0,<br/>
                Windows 2000 und Windows XP: Dieser Wert wird immer zurückgegeben, wenn Schriftarten aufgezählt werden.) |
| TT_ALWAYS | Dieser Wert SOLLTE NICHT [34] verwendet werden.<br/>
                [34] Dieser Wert wird in den folgenden Windows‑Versionen ignoriert:<br/>
                - Windows Vista<br/>
                - Windows Server 2008<br/>
                - Windows 7<br/>
                - Windows Server 2008 R2<br/>
                - Windows 8<br/>
                - Windows Server 2012<br/>
                - Windows 8.1<br/>
                - Windows Server 2012 R2 |
