---
title: "How to: Set Up Locations to Use Bins"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "bins, setting up warehouses"
  - "warehouse management, setting up for bins"
ms.assetid: 2cb6fd76-c233-4338-a9ad-65a479053a80
caps.latest.revision: 8
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
# How to: Set Up Locations to Use Bins
Bins represent the basic warehouse structure and are used to make suggestions about the placement of items. When you have created your bins, you can define very specifically the contents that you want to place in each bin, or the bin can function as a floating bin without specified contents.  
  
 To use the bin functionality at a location, you first activate the functionality on the **Location** card. Then you design the item flow at the location by specifying bin codes in setup fields that represent the different flows.  
  
> [!NOTE]  
>  Before you can specify bin codes on the location card, the bin codes must be created. For more information, see [How to: Create Bins in the Bin Creation Worksheet](../WarehouseActivities/how-to-create-bins-in-the-bin-creation-worksheet.md).  
  
### To set up a location to use bins  
  
1.  In the **Search** box, enter **Locations**, and then choose the related link.  
  
2.  Select the location where you want to use bins.  
  
    > [!NOTE]  
    >  You cannot edit the setup of locations that have item ledger entries.  
  
3.  On the **Home** tab, in the **Manage** group, choose **Edit**.  
  
4.  On the **Warehouse** FastTab, select the **Bins Mandatory** field.  
  
5.  If you are not using directed put\-away and pick for the location, fill in the **Default Bin Selection** field with the method the system should use when assigning a default bin to an item.  
  
6.  Open the location you want to set up bins for. On the **Bins** FastTab, select the bins you want to use as the default for receipts, shipments, inbound, outbound, and open shop floor bins.  
  
7.  The bin codes you fill in here will appear automatically on the headers and on the lines of various warehouse documents. The default bins define all starting or ending placements of items in the warehouse.  
  
8.  If you are using directed put\-away and pick, select a bin for your warehouse adjustments. The bin code in the **Adjustment Bin Code** field defines the virtual bin in which to record discrepancies in inventory when you register either observed differences registered in the warehouse item journal, or differences calculated when you register a warehouse physical inventory.  
  
9. Fill in the fields on the **Bin Policies** FastTab if they are relevant to your warehouse. The most important fields are **Bin Capacity Policy**, **Allow Breakbulk**, and **Put\-away Template Code** fields.  
  
10. On the **Warehouse** FastTab, fill in the **Outbound Whse. Handling Time**, **Inbound Whse. Handling Time**, and the **Base Calendar Code** fields.  
  
## See Also  
 [Bin Content](../Topic/\($%20N_7304%20Bin%20Content%20$\).md)   
 [Configure Warehouse Processes](../WarehouseActivities/configure-warehouse-processes.md)   
 [Design Details: Warehouse Management](../ApplicationDesign/design-details-warehouse-management.md)   
 [How to: Set Up Warehouse Management](../WarehouseActivities/how-to-set-up-warehouse-management.md)