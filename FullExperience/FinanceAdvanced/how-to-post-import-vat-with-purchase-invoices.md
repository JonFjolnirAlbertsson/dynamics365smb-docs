---
title: "How to: Post Import VAT with Purchase Invoices"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "import VAT, posting with invoices"
  - "VAT, posting with purchase invoices"
  - "VAT, posting import"
ms.assetid: df951ad4-ae11-402a-8be5-22099440ef06
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
# How to: Post Import VAT with Purchase Invoices
Instead of using a general journal to post an import VAT invoice, you can use a purchase invoice.  
  
### To set up purchasing for posting import VAT invoices  
  
1.  Set up a vendor card for the import authority that sends you the import VAT invoice. The **Gen. Bus. Posting Group** and **VAT Bus. Posting Group** must be set up in the same way as the general ledger account for the import VAT. For more information, see [How to: Register New Vendors](../Purchasing/how-to-register-new-vendors.md).  
  
2.  Create a **Gen. Product Posting Group** for the import VAT and set up an import VAT **Def. VAT Product Posting Group** for the related **Gen. Product Posting Group**.  
  
3.  In the **Search** box, enter **Chart of Accounts**, and then choose the related link.  
  
4.  Select the import VAT general ledger account, and then on the **Home** tab, in the **Manage** group, choose **Edit**.  
  
5.  On the **Posting** FastTab, select the **Gen. Prod. Posting Group** setup for import VAT. [!INCLUDE[navnow](../ApplicationDesign/includes/navnow_md.md)] automatically fills in the **VAT Prod. Posting Group** field.  
  
6.  In the **Search** box, enter **General Posting Setup**, and then choose the related link.  
  
     In the **General Posting Setup** window, create a combination of the **Gen. Bus. Posting Group** for the VAT authority and the **Gen. Prod. Posting Group** for import VAT. For this new combination, in the **Purchase Account** field, select the import VAT general ledger account.  
  
### To create a new invoice for the import authority vendor once you have completed the setup  
  
1.  In the **Search** box, enter **Purchase Invoices**, and then choose the related link.  
  
2.  Create a new purchase invoice.  
  
3.  In the **Buy\-from Vendor No.** field, select the import authority vendor, and then choose the **OK** button.  
  
4.  In the purchase line, in the **Type** field, select **G\/L Account**, and in the **No.** field, select the import VAT general ledger account.  
  
5.  In the **Quantity** field, type **1**.  
  
6.  In the **Direct Unit Cost Excl. VAT** field, specify the VAT amount.  
  
7.  Post the invoice.  
  
## See Also  
 [How to: Post Import VAT](../Finance/how-to-post-import-vat.md)   
 [How to: View VAT Entries](../Finance/how-to-view-vat-entries.md)