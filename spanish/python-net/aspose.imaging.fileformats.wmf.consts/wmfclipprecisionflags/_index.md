---
title: "WmfClipPrecisionFlags Enumeración"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---

Los indicadores ClipPrecision especifican la precisión de recorte, que define cómo recortar caracteres que están<br/>                parcialmente fuera de una región de recorte. Estos indicadores pueden combinarse para especificar múltiples opciones.

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfClipPrecisionFlags

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| CHARACTER | Este valor NO DEBE ser usado. |
| DEFAULT | Especifica que el recorte predeterminado DEBE ser usado. |
| DFA_DISABLE | Este valor especifica que la asociación de fuentes DEBERÍA [35] desactivarse.<br/>                [35] Este valor no es compatible en Windows 95, Windows 98 y Windows Millennium Edition.<br/>                La asociación de fuentes está desactivada en Windows 2000, Windows XP y Windows Server 2003.<br/>                Este valor se ignora en estas versiones de Windows:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
| EMBEDDED | Este valor especifica que la incrustación de fuentes DEBE usarse para renderizar el contenido del documento<br/>                ; las fuentes incrustadas son de solo lectura. |
| LH_ANGLES | Este valor se usa para controlar la rotación de fuentes, de la siguiente manera:<br/>                - Si está activado, la rotación de todas las fuentes DEBERÍA determinarse por la orientación<br/>                del sistema de coordenadas; es decir, si la orientación es zurda<br/>                o diestra.<br/>                - Si está desactivado, las fuentes del dispositivo DEBERÍAN rotar en sentido antihorario, pero la rotación de<br/>                otras fuentes DEBERÍA determinarse por la orientación del sistema<br/>                de coordenadas. |
| STROKE | Este valor PUEDE ser devuelto al enumerar fuentes rasterizadas, TrueType y<br/>                fuentes vectoriales.<br/>                [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0,<br/>                Windows 2000 y Windows XP: Este valor siempre se devuelve al enumerar fuentes.) |
| TT_ALWAYS | Este valor NO DEBE [34] usarse.<br/>                [34] Este valor se ignora en las siguientes versiones de Windows:<br/>                - Windows Vista<br/>                - Windows Server 2008<br/>                - Windows 7<br/>                - Windows Server 2008 R2<br/>                - Windows 8<br/>                - Windows Server 2012<br/>                - Windows 8.1<br/>                - Windows Server 2012 R2 |
