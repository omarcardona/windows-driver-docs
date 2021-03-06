---
title: WlanConnectionRoaming rule (ndis)
description: The WlanConnectionRoaming rule verifies the miniport driver correctly follows the Native 802.11 wireless LAN (WLAN) connection and roaming sequence.
ms.assetid: 7DB1881B-4DD8-4E06-AAF2-C6EAD0EEC5FC
ms.author: windowsdriverdev
ms.date: 5/21/2018
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
keywords: ["WlanConnectionRoaming rule (ndis)"]
topic_type:
- apiref
api_name:
- WlanConnectionRoaming
api_type:
- NA
---

# WlanConnectionRoaming rule (ndis)


The **WlanConnectionRoaming** rule verifies the miniport driver correctly follows the Native 802.11 wireless LAN (WLAN) connection and roaming sequence.

|              |      |
|--------------|------|
| Driver model | NDIS |

|                                   |                                                                                                                                        |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Bug check(s) found with this rule | [**Bug Check 0xC4: DRIVER\_VERIFIER\_DETECTED\_VIOLATION**](https://msdn.microsoft.com/library/windows/hardware/ff560187) ( 0x00093005) |

How to test
-----------

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">At run time</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Run [Driver Verifier](https://msdn.microsoft.com/library/windows/hardware/ff545448) and select the [NDIS/WIFI verification](https://msdn.microsoft.com/library/windows/hardware/hh454208) option.</p></td>
</tr>
</tbody>
</table>

 

Applies to
----------

[**MiniportHaltEx**](https://msdn.microsoft.com/library/windows/hardware/ff559388)
[**NdisMIndicateStatusEx**](https://msdn.microsoft.com/library/windows/hardware/ff563600)
See also
--------

[General Connection Operation Guidelines](https://msdn.microsoft.com/library/windows/hardware/ff552458)
[NDIS\_STATUS\_DOT11\_CONNECTION\_START](https://msdn.microsoft.com/library/windows/hardware/ff567328)
[OID\_DOT11\_RESET\_REQUEST](https://msdn.microsoft.com/library/windows/hardware/ff569409)
[NDIS\_STATUS\_DOT11\_ROAMING\_START](https://msdn.microsoft.com/library/windows/hardware/ff567360)
 

 





