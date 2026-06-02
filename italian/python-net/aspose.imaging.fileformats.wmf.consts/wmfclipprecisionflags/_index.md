---
title: "WmfClipPrecisionFlags Enumerazione"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

I flag ClipPrecision specificano la precisione del ritaglio, che definisce come ritagliare i caratteri che sono<br/>                parzialmente fuori da una regione di ritaglio. Questi flag possono essere combinati per specificare più opzioni.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| CARATTERE | Questo valore NON DEVE essere usato. |
| DEFAULT | Specifica che il ritaglio predefinito DEVE essere usato. |
| DFA_DISABLE | Questo valore specifica che l'associazione dei caratteri DEVE [35] essere disattivata.<br/>                [35] Questo valore non è supportato in Windows 95, Windows 98 e Windows Millennium Edition.<br/>                L'associazione dei caratteri è disattivata in Windows 2000, Windows XP e Windows Server 2003.<br/>                Questo valore è ignorato in queste versioni di Windows:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
| INCORPORATO | Questo valore specifica che l'incorporamento dei caratteri DEVE essere usato per renderizzare il contenuto del documento<br/>                ; i caratteri incorporati sono a sola lettura. |
| LH_ANGLES | Questo valore è usato per controllare la rotazione dei caratteri, come segue:<br/>                - Se impostato, la rotazione per tutti i caratteri DEVE essere determinata dall'orientamento<br/>                del sistema di coordinate; cioè, se l'orientamento è sinistro o destro.<br/>                - Se non impostato, i caratteri del dispositivo DEVIANO ruotare in senso antiorario, ma la rotazione degli<br/>                altri caratteri DEVE essere determinata dall'orientamento del sistema di<br/>                coordinate. |
| STROKE | Questo valore POTREBBE essere restituito durante l'enumerazione di caratteri rasterizzati, TrueType e<br/>                vettoriali.<br/>                [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0,<br/>                Windows 2000 e Windows XP: Questo valore è sempre restituito durante l'enumerazione dei caratteri.) |
| TT_ALWAYS | Questo valore NON DEVE [34] essere usato.<br/>                [34] Questo valore è ignorato nelle seguenti versioni di Windows:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
