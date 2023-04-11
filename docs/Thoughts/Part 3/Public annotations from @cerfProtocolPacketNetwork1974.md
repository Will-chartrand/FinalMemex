---
cssclass: zotero-note
alias: ["A Protocol for Packet Network Intercommunication"]
---

> [!info]
> - **Cite Key:** [[@cerfProtocolPacketNetwork1974]]
> - **Link:** [Cerf and Kahn - 1974 - A Protocol for Packet Network Intercommunication.pdf](file://C:\Users\willc\Zotero\storage\UJCT39S3\Cerf%20and%20Kahn%20-%201974%20-%20A%20Protocol%20for%20Packet%20Network%20Intercommunication.pdf)
> - **Abstract:** A protocol that supports the sharing of resources that exist in different packet switching networks is presented. The protocol provides for variation in individual network packet sizes, transmission failures, sequencing, flow control, end-to-end error checking, and the creation and destruction of logical process-to-process connections. Some implementation issues are considered, and problems such as internetwork routing, accounting, and timeouts are exposed.

## Annotations
%% begin annotations %%
### Imported on 2023-04-09 2:24 pm

#### Relevant / important

> [!quote|#a28ae5] Highlight
> it would be extremely convenient if all the differences between networks could be economically resolved by suitable interfacing at the network boundaries
>
> [Page 2](zotero://open-pdf/library/items/UJCT39S3?page=2) [[2023-04-03#11:15 am]]

> [!quote|#a28ae5] Highlight
> Furthermore, we constrain the length of a segment to an integral number of 8-bit bytes. This uniformity is most helpful in simplifying the software needed with HOST machines of different natural word lengths.
>
> [Page 4](zotero://open-pdf/library/items/UJCT39S3?page=4) [[2023-04-08#5:07 pm]]

> [!quote|#a28ae5] Highlight
> Both Cases 1) and 2) provide for the demultiplexing and delivery of segments to destination processes, but only Case 2) does so without the introduction of potential interprocess interference. Furthermore, Case 1) introduces extra machinery to handle flow control on a HOST-to-HOST basis, since there must also be some provision for process level control, and this machinery is little used since the probability is small that within a given HOST, two processes will be coincidentally scheduled to send messages to the same destination HOST. For this reason, we select the method of Case 2) as a part of the internetwork transmission protocol.
>
>> This means that each packet will have a header which describes completely it's location
>
> [Page 5](zotero://open-pdf/library/items/UJCT39S3?page=5) [[2023-04-08#5:10 pm]]

#### Definitions / concepts

> [!quote|#2ea8e5] Highlight
> It is thus apparent that the interface between networks must play a central role in the development of any network interconnection strategy. We give a special name to this interface that performs these functions and call it a GATEWAY.
>
> [Page 2](zotero://open-pdf/library/items/UJCT39S3?page=2) [[2023-04-03#11:22 am]]


%% end annotations %%

%% Import Date: 2023-04-09T14:24:42.247-04:00 %%
