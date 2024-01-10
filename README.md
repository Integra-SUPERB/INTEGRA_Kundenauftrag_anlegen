# Create Sales Order («Kundenauftrag anlegen»)

Link to INTEGRA master repository  
[INTEGRA](https://github.com/Integra-SUPERB/INTEGRA)


## Goal of this repository
Using the Create Sales Order repository, you’re able to create a Sales Order in the SAP ERP system and manage the complex process of selling configurable products assembled from individual components.

You can define constraints and settings for single or multi-level bill of materials resolution. The process ensures that the components are delivered together according to the customer's specifications, while providing flexibility for manual adjustments as per customer requirements.

Find the purpose, prerequisites, and process flow of the Sales Order here: [Process: Sales Order](https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/7b24a64d9d0941bda1afa753263d9e39/351db853dcfcb44ce10000000a174cb4.html).

## How does this API work?
Multiple links to the official SAP documentation will help you understand the different parameters and necessary pieces of information to use the API successfully.

For a quick and easy reference, we recommend starting by reviewing the example Create Sales Order XML file [here (A2A - asynchronous)](https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/19d48293097f4a2589433856b034dfa5/48ac12420a0a4d9daaefdc3de6a969f2.html?locale=en-US&version=2020.001) or [here (A2X - synchronous)](https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/19d48293097f4a2589433856b034dfa5/641bd0dc16bf406684ca2c614322c15e.html?locale=en-US&version=2020.001). This file is designed to help you understand the structure and format of the request data you need to provide to use the API.

Find the description for processing a Sales Order here: [Sales Order (A2X - synchronous)](https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/19d48293097f4a2589433856b034dfa5/00d244581efca007e10000000a441470.html?locale=en-US&version=2020.001), [Sales Order (A2A - asynchronous)](https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/19d48293097f4a2589433856b034dfa5/2b2fd9fb158e4629bf9106c80dcbf7ff.html?locale=en-US&version=2020.001).

The replication outbound is handled here: [Sales Order – Replicate (A2A - only asynchronous available)](https://api.sap.com/api/OP_CO_SDSLS_ESR_SALES_ORDER_REPL/overview).

To learn more about the success message that the API should return after successful replication, find detailed information in the document [Sales Order – Send Processing Notification (A2A - only asynchronous available)](https://api.sap.com/api/OP_CO_SDSLS_ESR_SALES_ORDER_NOTIF/overview).

## Contact information
From the information provided above, you should have a high-level overview of the API's capabilities.

If you wish to use and work with the API, please contact us so we can review your application and provide the necessary credentials and information.

For further assistance with the API, the BIT technical support SAP team is available to answer your questions during regular office hours.

To contact us, please email [FachsupportSAP@bit.admin.ch](mailto:FachsupportSAP@bit.admin.ch).
