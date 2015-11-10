﻿<properties
   pageTitle="Non-technical pre-requisites for creating an offer for the Azure Marketplace | Microsoft Azure"
   description="Understand the requirements for creating and deploying an offer to the Azure Marketplace for others to purchase."
   services="marketplace-publishing"
   documentationCenter=""
   authors="HannibalSII"
   manager=""
   editor=""/>

<tags
  ms.service="marketplace-publishing"
  ms.devlang="na"
  ms.topic="article"
  ms.tgt_pltfrm="Azure"
  ms.workload="na"
  ms.date="10/09/2015"
  ms.author="hascipio; v-divte"/>

# General Pre-requisites for creating an offer for the Azure Marketplace
Understand the general, business process centric pre-requisites that are needed to move forward with the offer creation deployment process.

## Ensure you are registered as a seller with Microsoft
For detailed instructions on registering a seller account with Microsoft, go to [Account Creation & Registration](marketplace-publishing-accounts-creation-registration.md).

- If you are **already registered**, find out who in your company owns it or which credentials were used to register
- If you are **not the owner of the publishing account**, you can have the account owner add your Microsoft Account as a co-admin to the [Publishing portal](https://publish.windowsazure.com) -> **Publishers** tab -> **Administrators** link
- Ensure that stakeholders in the Azure publishing process receive the email that goes to this address. It must be monitored and responded to in order to complete the publishing process.
- Avoid having the account associated with a single person. If that person leaves your company, they could impact your ability to access information about and publish your SKUs.

> [AZURE.IMPORTANT] **You do not have to complete company tax and banking information if you are planning to publish only free offers (or bring your own license).**

> The company registration must be completed to get started. However, while your company works on the tax and bank information in the Seller Dashboard account, the developers can start working on creating the virtual machine image in the [Publishing Portal](https://publish.windowsazure.com), getting them certified and testing them in Azure Staging Environment. You will need the complete seller account approval only for the final step of publishing your offer to the Marketplace.

> If you have issues with Seller Registration completion, please log a Support ticket as below:
1. Contact [Support](http://go.microsoft.com/fwlink?LinkId=272975)
2. Choose **Seller Dashboard registration and your account**
3. Choose **Registering for a developer account**
4. Choose contact **method**


## Acquire an Azure "pay-as-you-go" Subscription
This is the subscription you will use to create your VM images and hand over the images to [Azure Marketplace](http://azure.microsoft.com/marketplace). If you do not have an existing subscription, then please sign up here, https://account.windowsazure.com/signup?offer=ms-azr-0003p

## "Sell-from" countries
> [AZURE.WARNING]
In order to sell your services on Microsoft Azure Marketplace, your registered entity needs to be from one of the approved “sell from” countries. This restriction is for payout and taxation reasons. We are actively looking to expand this list of countries in the near future, so please stay tuned. For the complete list, please see **Section 1b** of the [Microsoft Azure Marketplace Participation Policies](http://go.microsoft.com/fwlink/?LinkID=526833).

## Next Steps
Next are the technical pre-requisites for each offer type. Click the link to the article for the respective offer type you would like to create for the Azure Marketplace.

| Virtual Machine Image | Developer Service | Data Service | Solution Template |
|-----|-----|-----|-----|
| [VM Technical Pre-requisites](marketplace-publishing-vm-image-creation-prerequisites.md) | Developer Service Technical Pre-requisites | Data Service Technical Pre-requisites  | [Solution Template Technical Pre-requisites](marketplace-publishing-solution-template-creation-prerequisites.md) |

## See Also
- [Getting Started: How to publish an offer to the Azure Marketplace](marketplace-publishing-getting-started.md)
