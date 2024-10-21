---
cover: .gitbook/assets/8913c177-71d4-45a2-b2a5-13fa2fbb7066.webp
coverY: 671
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# SS7 Stack Overview

The Signaling System No. 7 (SS7) is a globally used set of telephony signaling protocols that enables call setup, routing, billing, and information exchange between telephone networks.&#x20;

{% hint style="danger" %}
The information provided in this page is intended for educational purposes only.
{% endhint %}

The SS7 protocol suite is organized into a stack, structured in levels, similar to the OSI model:

1. **MTP Level 1 (Physical Layer)**: This is the physical and electrical connection for the network, handling the delivery of signaling messages via the transmission medium.
2. **MTP Level 2 (Link Layer)**: Ensures error checking and message sequence control by detecting and correcting errors in the transmission of signaling information.
3. **MTP Level 3 (Network Layer)**: Provides message routing between exchanges and manages message distribution, ensuring the integrity of signaling message transfer.
4. **SCCP (Signaling Connection Control Part)**: Adds enhanced routing capabilities and supports connection-oriented and connectionless network services, facilitating a variety of telecommunications services beyond basic call control.
5. **TCAP (Transaction Capabilities Application Part)**: Enables the deployment of non-circuit-related queries and transactions, supporting features like number translation, roaming, and database queries.
6. **ISUP (ISDN User Part)**: Handles the setup and tear down of voice and data calls over the public switched telephone network (PSTN).
7. **MAP (Mobile Application Part)**: Utilized in mobile networks for functions such as roaming, location updating, handovers, and short message service (SMS) delivery.

<figure><img src=".gitbook/assets/RFSSecurity.png" alt=""><figcaption></figcaption></figure>

The SS7 stack is essential for communication between network elements in telecommunications networks, supporting efficient and robust call processing and management.
