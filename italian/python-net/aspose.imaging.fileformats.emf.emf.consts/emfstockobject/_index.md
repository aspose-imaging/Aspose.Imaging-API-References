---
title: "Enumerazione EmfStockObject"
type: docs
weight: 330
url: /it/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---

L'enumerazione StockObject specifica gli indici degli oggetti grafici logici predefiniti <br/>            che possono essere utilizzati nelle operazioni grafiche. Le strutture specifiche degli oggetti stock sono <br/>            dipendenti dall'implementazione; tuttavia, le proprietà degli oggetti stock DOVREBBERO essere equivalenti alle <br/>            proprietà degli oggetti creati esplicitamente dello stesso tipo. <br/>            Queste proprietà sono specificate, dove possibile, per gli oggetti stock definiti in questa enumerazione.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStockObject

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| ANSI_FIXED_FONT | Un font a larghezza fissa equivalente a un font logico con le seguenti proprietà:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | Un font a larghezza variabile equivalente a un font logico con le seguenti proprietà:<br/>            Charset: ANSI_CHARSET<br/>            PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| BLACK_BRUSH | Un pennello nero a tinta solida equivalente a un pennello logico con le seguenti proprietà:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00000000 |
| BLACK_PEN | Una penna nera a tinta solida equivalente a una penna logica con le seguenti proprietà:<br/>            PenStyle: PS_COSMETIC + PS_SOLID<br/>            ColorRef: 0x00000000 |
| DC_BRUSH | Il pennello a tinta solida attualmente selezionato nel contesto del dispositivo di riproduzione |
| DC_PEN | La penna a tinta solida attualmente selezionata nel contesto del dispositivo di riproduzione |
| DEFAULT_GUI_FONT | Un font a larghezza fissa garantito disponibile nel sistema operativo. <br/>            Il font effettivo specificato da questo valore dipende dall'implementazione |
| DEFAULT_PALETTE | La tavolozza predefinita definita per il dispositivo di output corrente. <br/>            La tavolozza effettiva specificata da questo valore dipende dall'implementazione |
| DEVICE_DEFAULT_FONT | Il font predefinito fornito dal driver del dispositivo grafico per il dispositivo di output corrente. <br/>            Il font effettivo specificato da questo valore dipende dall'implementazione |
| DKGRAY_BRUSH | Un pennello grigio scuro, a colore solido, equivalente a un pennello logico con le seguenti proprietà:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00404040 |
| GRAY_BRUSH | Un pennello grigio, a tinta solida, equivalente a un pennello logico con le seguenti proprietà:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00808080 |
| LTGRAY_BRUSH | Un pennello grigio chiaro, a tinta solida, equivalente a un pennello logico con le seguenti proprietà:<br/>            BrushStyle: BS_SOLID<br/>            Color: 0x00C0C0C0 |
| NULL_BRUSH | Un pennello nullo equivalente a un pennello logico con le seguenti proprietà:<br/>            BrushStyle: BS_NULL |
| NULL_PEN | Una penna nulla equivalente a una penna logica con le seguenti proprietà:<br/>            PenStyle: PS_NULL |
| OEM_FIXED_FONT | Un carattere a larghezza fissa, set di caratteri OEM, equivalente a un carattere logico <br/>            (oggetto LogFont, sezione 2.2.13) con le seguenti proprietà:<br/>            Charset: OEM_CHARSET (enumerazione WMF CharacterSet, [MS-WMF] sezione 2.1.1.5)<br/>            PitchAndFamily: FF_DONTCARE (enumerazione WMF FamilyFont, [MS-WMF] sezione 2.1.1.8) <br/>            + FIXED_PITCH (enumerazione WMF PitchFont, [MS-WMF] sezione 2.1.1.24) |
| SYSTEM_FIXED_FONT | Un font a larghezza fissa garantito disponibile nel sistema operativo. <br/>            Il font effettivo specificato da questo valore dipende dall'implementazione |
| SYSTEM_FONT | Un carattere garantito disponibile nel sistema operativo. <br/>            Il carattere effettivo specificato da questo valore dipende dall'implementazione |
| WHITE_BRUSH | Un pennello bianco, a tinta solida, equivalente a un pennello logico <br/>            (oggetto LogBrushEx, sezione 2.2.12) con le seguenti proprietà:<br/>            BrushStyle: BS_SOLID (enumerazione WMF BrushStyle, [MS-WMF] sezione 2.1.1.4)<br/>            Color: 0x00FFFFFF (oggetto WMF ColorRef, [MS-WMF] sezione 2.2.2.8) |
| WHITE_PEN | Una penna bianca, a tinta solida, equivalente a una penna logica (oggetto LogPen, sezione 2.2.19)<br/>            con le seguenti proprietà:<br/>            PenStyle: PS_COSMETIC + PS_SOLID (enumerazione PenStyle, sezione 2.1.25)<br/>            ColorRef: 0x00FFFFFF (oggetto WMF ColorRef). |
