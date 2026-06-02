---
title: "EmfStretchMode Enumerazione"
type: docs
weight: 340
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---

L'enumerazione StretchMode è usata per specificare come i dati di colore vengono aggiunti o rimossi dalle bitmap che vengono allungate o compresse.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStretchMode

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| STRETCH_ANDSCANS | Esegue un'operazione Boolean AND utilizzando i valori di colore per i pixel eliminati e quelli esistenti.<br/>            Se il bitmap è un bitmap monocromatico, questa modalità conserva i pixel neri a scapito dei pixel bianchi |
| STRETCH_DELETESCANS | Elimina i pixel. Questa modalità elimina tutte le linee di pixel eliminate senza cercare di conservare le loro informazioni. |
| STRETCH_HALFTONE | Mappa i pixel dal rettangolo di origine in blocchi di pixel nel rettangolo di destinazione. <br/>            Il colore medio sul blocco di pixel di destinazione approssima il colore dei pixel di origine. |
| STRETCH_ORSCANS | Esegue un'operazione Boolean OR utilizzando i valori di colore per i pixel eliminati e quelli esistenti. <br/>            Se il bitmap è un bitmap monocromatico, questa modalità conserva i pixel bianchi a scapito dei pixel neri. |
