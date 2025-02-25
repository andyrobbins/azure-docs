---
title: 'How to schedule a contact on Azure Orbital Earth Observation service' 
description: 'How to schedule a contact'
author: wamota
ms.service: orbital
ms.topic: how-to
ms.custom: public-preview
ms.date: 11/16/2021
ms.author: wamota
# Customer intent: As a satellite operator, I want to ingest data from my satellite into Azure.
---

# Schedule a contact

Schedule a contact with the selected satellite for data retrieval/delivery on Azure Orbital. At the scheduled time, the selected ground station will contact the satellite and start data retrieval/delivery using the contact profile.

## Prerequisites

- An Azure account with an active subscription. [Create an account for free](https://azure.microsoft.com/free/?WT.mc_id=A261C142F).
- A registered spacecraft. Learn more on how to [register spacecraft](register-spacecraft.md).
- A contact profile. Learn more on how to [configure a contact profile](contact-profile.md).

## Sign in to Azure

Sign in to the [Azure portal](https://portal.azure.com).

## Select an available contact

1. In the Azure portal search box, enter **Spacecrafts**. Select **Spacecrafts** in the search results.
2. In the **Spacecrafts** page, select the spacecraft for the contact.
3. Select **Schedule contact** on the top bar of the spacecraft’s overview.
 
   :::image type="content" source="media/orbital-eos-schedule.png" alt-text="Schedule a contact at spacecraft resource page" lightbox="media/orbital-eos-schedule.png":::

4. In the **Schedule contact** page, specify this information from the top of the page:

   | **Field** | **Value** |
   | --- | --- |
   | Contact profile | Specify the contact profile to be used for the contact |
   | Ground station | Specify the ground station(s) |
   | Start time | Identify a start time for the contact availability window |
   | End time | Identify an end time for the contact availability window |

    :::image type="content" source="media/orbital-eos-schedule-search.png" alt-text="Search for available contact schedules page" lightbox="media/orbital-eos-schedule-search.png":::

5. Select **Search** to view available contact times.
6. Select one or more contact windows and select **Schedule**.

   :::image type="content" source="media/orbital-eos-select-schedule.png" alt-text="Select an available contact schedule page" lightbox="media/orbital-eos-select-schedule.png":::

7. View scheduled contacts by selecting on the spacecraft page, and navigating to **Contacts**.

   :::image type="content" source="media/orbital-eos-view-scheduled-contacts.png" alt-text="View scheduled contacts page" lightbox="media/orbital-eos-view-scheduled-contacts.png":::

## Next steps

- [Quickstart: Register Spacecraft](register-spacecraft.md)
- [Quickstart: Configure a contact profile](contact-profile.md)