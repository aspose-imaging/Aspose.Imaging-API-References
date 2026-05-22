---
title: "WmfClipPrecisionFlags Énumération"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

Les indicateurs ClipPrecision spécifient la précision du découpage, qui définit comment découper les caractères qui sont<br/>                partiellement en dehors d'une région de découpage. Ces indicateurs peuvent être combinés pour spécifier plusieurs options.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| CHARACTER | Cette valeur NE DOIT PAS être utilisée. |
| DEFAULT | Spécifie que le découpage par défaut DOIT être utilisé. |
| DFA_DISABLE | Cette valeur spécifie que l'association de polices NE DOIT [35] être désactivée.<br/>                [35] Cette valeur n'est pas prise en charge dans Windows 95, Windows 98 et Windows Millennium Edition.<br/>                L'association de polices est désactivée dans Windows 2000, Windows XP et Windows Server 2003.<br/>                Cette valeur est ignorée dans les versions Windows suivantes :<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
| EMBEDDED | Cette valeur spécifie que l'incorporation de polices DOIT être utilisée pour rendre le contenu du document<br/>                ; les polices incorporées sont en lecture seule. |
| LH_ANGLES | Cette valeur est utilisée pour contrôler la rotation des polices, comme suit :<br/>                - Si elle est définie, la rotation de toutes les polices DOIVENT être déterminée par l'orientation<br/>                du système de coordonnées ; c'est‑à‑dire si l'orientation est gauchère<br/>                ou droitière.<br/>                - Si elle est désactivée, les polices du dispositif DOIVENT tourner dans le sens antihoraire, mais la rotation des<br/>                autres polices DOIT être déterminée par l'orientation du système de coordonnées. |
| STROKE | Cette valeur PEUT être renvoyée lors de l'énumération des polices rasterisées, TrueType et<br/>                vectorielles.<br/>                [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0,<br/>                Windows 2000 et Windows XP : cette valeur est toujours renvoyée lors de l'énumération des polices.) |
| TT_ALWAYS | Cette valeur NE DOIT PAS [34] être utilisée.<br/>                [34] Cette valeur est ignorée dans les versions Windows suivantes :<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
