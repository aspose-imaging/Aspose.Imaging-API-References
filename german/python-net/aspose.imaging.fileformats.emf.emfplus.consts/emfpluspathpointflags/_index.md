---
title: "EmfPlusPathPointFlags Aufzählung"
type: docs
weight: 290
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---

Ein 32‑Bit‑vorzeichenloser Integer, der angibt, wie die von diesem Objekt definierten Punkte und zugehörigen Punkttypen zu interpretieren sind.<br/>            C (1 Bit): Wenn gesetzt, gibt das PathPoints‑Array absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an.<br/>            Wenn nicht gesetzt, gibt das PathPoints‑Array absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.<br/>            Hinweis: Wenn das P‑Flag (unten) gesetzt ist, kann dieses Flag deaktiviert sein und MUSS ignoriert werden.<br/>            R (1 Bit): Wenn gesetzt, werden die Punkttypen im PathPointTypes‑Array durch EmfPlusPathPointTypeRle‑Objekte (Abschnitt 2.2.2.32) angegeben, <br/>            die Laufzeitkodierung (RLE) verwenden, und/oder durch EmfPlusPathPointType‑Objekte (Abschnitt 2.2.2.31). Siehe [MS-WMF] Abschnitt 3.1.6 für weitere Informationen zur RLE‑Kompression.<br/>            Wenn nicht gesetzt, werden die Punkttypen im PathPointTypes‑Array durch EmfPlusPathPointType‑Objekte angegeben.<br/>            P (1 Bit): Wenn gesetzt, gibt jedes Element im PathPoints‑Array einen Ort im Koordinatenraum an, der relativ zu dem<br/>            Ort ist, der vom vorherigen Element im Array angegeben wird. Für das erste Element in PathPoints wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen.<br/>            Wenn nicht gesetzt, gibt jedes Element im PathPoints‑Array einen absoluten Ort an.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPathPointFlags

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| C | Das c-Flag |
| P | Das p-Flag |
| R | Das r-Flag |
