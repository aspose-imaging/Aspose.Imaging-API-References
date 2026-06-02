---
title: "WmfClipPrecisionFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les indicateurs ClipPrecision spécifient la précision de découpe qui définit comment découper les caractères qui se trouvent partiellement en dehors d'une région de découpe."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

Les indicateurs ClipPrecision spécifient la précision de découpe, qui définit comment découper les caractères qui se trouvent partiellement en dehors d'une région de découpe. Ces indicateurs peuvent être combinés pour spécifier plusieurs options.
## Champs

| Champ | Description |
| --- | --- |
| [Default](#Default) | Spécifie que la découpe par défaut DOIT être utilisée. |
| [Character](#Character) | Cette valeur NE DOIT PAS être utilisée. |
| [Stroke](#Stroke) | Cette valeur PEUT être renvoyée lors de l'énumération des polices rasterisées, TrueType et vectorielles. |
| [LhAngles](#LhAngles) | Cette valeur est utilisée pour contrôler la rotation des polices, comme suit : - Si elle est définie, la rotation de toutes les polices DOIT être déterminée par l'orientation du système de coordonnées ; c’est‑à‑dire, si l'orientation est gauchère ou droitière. |
| [TtAlways](#TtAlways) | Cette valeur NE DOIT PAS [34] être utilisée. |
| [DfaDisable](#DfaDisable) | Cette valeur indique que l'association de polices DOIT [35] être désactivée. |
| [Embedded](#Embedded) | Cette valeur indique que l'incorporation de polices DOIT être utilisée pour rendre le contenu du document ; les polices incorporées sont en lecture seule. |
### Default {#Default}
```
public static final byte Default
```


Spécifie que la découpe par défaut DOIT être utilisée.

### Character {#Character}
```
public static final byte Character
```


Cette valeur NE DOIT PAS être utilisée.

### Stroke {#Stroke}
```
public static final byte Stroke
```


Cette valeur PEUT être renvoyée lors de l'énumération des polices rasterisées, TrueType et vectorielles. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 et Windows XP : cette valeur est toujours renvoyée lors de l'énumération des polices.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


Cette valeur est utilisée pour contrôler la rotation des polices, comme suit : - Si elle est définie, la rotation de toutes les polices DOIT être déterminée par l'orientation du système de coordonnées ; c’est‑à‑dire, si l'orientation est gauchère ou droitière. - Si elle est désactivée, les polices du dispositif DOIVENT pivoter dans le sens inverse des aiguilles d’une montre, mais la rotation des autres polices DOIT être déterminée par l'orientation du système de coordonnées.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


Cette valeur NE DOIT PAS [34] être utilisée. [34] Cette valeur est ignorée dans les versions Windows suivantes : - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


Cette valeur indique que l'association de polices DOIT [35] être désactivée. [35] Cette valeur n'est pas prise en charge dans Windows 95, Windows 98 et Windows Millennium Edition. L'association de polices est désactivée dans Windows 2000, Windows XP et Windows Server 2003. Cette valeur est ignorée dans ces versions de Windows : - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


Cette valeur indique que l'incorporation de polices DOIT être utilisée pour rendre le contenu du document ; les polices incorporées sont en lecture seule.

