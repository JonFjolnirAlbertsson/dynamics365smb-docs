---
title: "Transfers"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "transfer orders, about"
  - "transfers, items between locations"
ms.assetid: ad7536ca-c5cf-4880-9832-70a5dfc199ff
caps.latest.revision: 3
ms.author: "sgroespe"
manager: "terryaus"
translation.priority.ht: 
  - "da-dk"
  - "de-at"
  - "de-ch"
  - "de-de"
  - "en-au"
  - "en-ca"
  - "en-gb"
  - "en-in"
  - "en-nz"
  - "es-es"
  - "es-mx"
  - "fi-fi"
  - "fr-be"
  - "fr-ca"
  - "fr-ch"
  - "fr-fr"
  - "is-is"
  - "it-ch"
  - "it-it"
  - "nb-no"
  - "nl-be"
  - "nl-nl"
  - "ru-ru"
  - "sv-se"
---
# Transfers
If your warehouse has more than one location, you can transfer items between locations.  
  
 To transfer items from one location to another, you must create a transfer order.  
  
 Before you can create an order you must set up an in\-transit location and a transfer route.  
  
## Transfer order  
 The transfer order is an order very similar to a sales order or a purchase order. The transfer order can be created from the transfer\-from or the transfer\-to location. The transfer order contains information about the transfer\-from and the transfer\-to location, and the dates connected to the shipping and receiving of the order. On the transfer order, you must also assign the in\-transit code that applies while the items are in transit.  
  
## In\-Transit Code  
 An in\-transit code is a temporary location created for transferring items only. When the order is shipped from the transfer\-from location, the program assigns the items an in\-transit code. When the order is received at the transfer\-to location, the program moves the items from the in\-transit code to the transfer\-to location.  
  
## Transfer Routes  
 You can set up transfer routes between locations. This enables you to assign a default in\-transit code, shipping agent and shipping agent service code. When you have done this, the program can use the information to calculate the receipt date.  
  
## See Also  
 [How to: Set Up Locations](../DesignAndEngineering/how-to-set-up-locations.md)   
 [How to: Set Up In\-Transit Codes](../DesignAndEngineering/how-to-set-up-in-transit-codes.md)   
 [How to: Set Up Transfer Routes](../DesignAndEngineering/how-to-set-up-transfer-routes.md)   
 [How to: Create Transfer Orders](../DesignAndEngineering/how-to-create-transfer-orders.md)   
 [How to: Ship Transfer Orders](../DesignAndEngineering/how-to-ship-transfer-orders.md)   
 [How to: Receive Transfer Orders](../DesignAndEngineering/how-to-receive-transfer-orders.md)   
 [How to: View Items in Transit](../DesignAndEngineering/how-to-view-items-in-transit.md)