---
title: XmpPackage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Repräsentiert die Basisabstraktion für das XMP-Paket.
type: docs
weight: 11780
url: /de/net/aspose.imaging.xmp/xmppackage/
---
## XmpPackage class

Repräsentiert die Basisabstraktion für das XMP-Paket.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Item](../../aspose.imaging.xmp/xmppackage/item) { get; set; } | Ruft ab oder setzt dieObject mit dem angegebenen Schlüssel. |
| virtual [Keys](../../aspose.imaging.xmp/xmppackage/keys) { get; } | Ruft die Schlüssel im XMP-Paket ab. |
| [NamespaceUri](../../aspose.imaging.xmp/xmppackage/namespaceuri) { get; } | Ruft den Namespace-URI ab. |
| [Prefix](../../aspose.imaging.xmp/xmppackage/prefix) { get; } | Ruft das Präfix ab. |
| [XmlNamespace](../../aspose.imaging.xmp/xmppackage/xmlnamespace) { get; } | Ruft den XML-Namespace ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddValue](../../aspose.imaging.xmp/xmppackage/addvalue)(string, string) | Fügt den Wert hinzu. |
| virtual [Clear](../../aspose.imaging.xmp/xmppackage/clear)() | Löscht diese Instanz. |
| virtual [ContainsKey](../../aspose.imaging.xmp/xmppackage/containskey)(string) | Bestimmt, ob der angegebene Schlüssel Schlüssel enthält. |
| [GetEnumerator](../../aspose.imaging.xmp/xmppackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [GetXmlValue](../../aspose.imaging.xmp/xmppackage/getxmlvalue)() | Konvertiert den XMP-Wert in die XML-Darstellung. |
| virtual [Remove](../../aspose.imaging.xmp/xmppackage/remove)(string) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue)(string, IXmlValue) | Legt den Wert fest. |
| virtual [SetXmpTypeValue](../../aspose.imaging.xmp/xmppackage/setxmptypevalue)(string, XmpTypeBase) | Legt den XMP-Typwert fest. |

### Siehe auch

* interface [IXmlValue](../ixmlvalue)
* namensraum [Aspose.Imaging.Xmp](../../aspose.imaging.xmp)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->