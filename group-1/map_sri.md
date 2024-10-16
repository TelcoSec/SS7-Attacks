# MAP\_SRI

**SS/MAP MAP\_SRI (Send Routing Information)**

The MAP\_SRI (Send Routing Information) is a signaling message used in GSM mobile networks. It is part of the Mobile Application Part (MAP) protocol, implemented by the Signaling System No. 7 (SS7). The main purpose of MAP\_SRI is to obtain routing information necessary for delivering a call to the correct destination.

* **Purpose**: To fetch the International Mobile Subscriber Identity (IMSI) and Mobile Station Roaming Number (MSRN) for call routing purposes.
*   **Procedure**:

    1. When a call is initiated, the originating network sends an MAP\_SRI message to the Home Location Register (HLR) of the recipient.
    2. The HLR uses the recipient's information to determine their current location.
    3. The HLR responds with the IMSI and MSRN, allowing the network to route the call appropriately.

    This process is essential for seamless connectivity and efficient call delivery in GSM networks.

