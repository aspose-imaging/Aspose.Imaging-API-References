---
title: "EmfPlusObject-klass"
type: docs
weight: 330
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Initierar en ny instans av klassen [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| is_continuable | bool | r/w | Hämtar eller anger ett värde som indikerar om den här instansen är fortsättningsbar.<br/>            Anger att objektdefinitionen fortsätter i nästa EmfPlusObject<br/>            post. Denna flagga sätts aldrig i den sista posten som definierar objektet. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Hämtar eller anger en bytearray som innehåller data för den objekttyp som anges i<br/>            Flags-fältet. Innehållet och formatet på data kan variera för varje objekttyp. Se<br/>            de enskilda objektsdefinitionerna i avsnitt 2.2.1 för ytterligare information. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet i EMF+ Object Table som ska associeras med objektet<br/>            som skapas av denna post. Värdet MÅSTE vara 0 till 63, inklusive. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Hämtar eller anger objektets typ. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| total_object_size | int | r/w | Hämtar eller anger den totala storleken på objektet.<br/>            Om posten är fortsättningsbar, när fortsättningsbiten är satt, kommer detta fält<br/>            att finnas. Fortsättande objekt har flera EMF+ poster som börjar med<br/>            EmfPlusContineudObjectRecord. Varje EmfPlusContinuedObjectRecord kommer att innehålla en<br/>            TotalObjectSize. När antalet byte motsvarande TotalObjectSize har lästs, kommer nästa EMF+<br/>            post inte att behandlas som en del av det fortsättande objektet. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Initierar en ny instans av klassen [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

