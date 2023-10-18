# Create Sales Order («Kundenauftrag anlegen»)

Link to INTEGRA master repository  
[INTEGRA](https://github.com/Integra-SUPERB/INTEGRA)


## Goal of this repository
Using the Create Sales Order repository, you’re able to create a Sales Order in the SAP ERP system and manage the complex process of selling configurable products assembled from individual components.

You can define constraints and settings for single or multi-level bill of materials resolution. The process ensures that the components are delivered together according to the customer's specifications, while providing flexibility for manual adjustments as per customer requirements.

Find the purpose, prerequisites, and process flow of the Sales Order here: [Process: Sales Order](https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/7b24a64d9d0941bda1afa753263d9e39/351db853dcfcb44ce10000000a174cb4.html).

## How does this API work?
Multiple links to the official SAP documentation will help you understand the different parameters and necessary pieces of information to use the API successfully.

For a quick and easy reference, we recommend starting by reviewing our empty Create Sales Order XML file [here](https://help.sap.com/docs/SAP_S4HANA_CLOUD/03c04db2a7434731b7fe21dca77440da/48ac12420a0a4d9daaefdc3de6a969f2.html?locale=en-US#create-sales-order). This file is designed to help you understand the structure and format of the request data you need to provide to use the API.

Find the description for replicating a Sales Order inbound here: [Sales Order (A2A)](https://api.sap.com/api/OP_SALESORDERBULKREQUEST_IN/overview).

The replication outbound is handled here: [Sales Order – Replicate (A2A)](https://api.sap.com/api/CO_SDSLS_ESR_SALES_ORDER_REPL/overview).

To learn more about the success message that the API should return after successful replication, find detailed information in the document [Sales Order – Send Processing Notification](https://api.sap.com/api/CO_SDSLS_ESR_SALES_ORDER_NOTIF/overview).

## Contact information
From the information provided above, you should have a high-level overview of the API's capabilities.

If you wish to use and work with the API, please contact us so we can review your application and provide the necessary credentials and information.

For further assistance with the API, the BIT technical support SAP team is available to answer your questions during regular office hours.

To contact us, please email [FachsupportSAP@bit.admin.ch](mailto:FachsupportSAP@bit.admin.ch).
