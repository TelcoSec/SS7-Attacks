# ATI - Any Time Interrogation

**Anythime Interrogation (ATI)** is a procedure in the SS7 Mobile Application Part (MAP) protocol that allows a network entity to request information about a subscriber from the Home Location Register (HLR) or Home Subscriber Server (HSS) at any time.&#x20;

This information can include subscriber location or other live data and plays a crucial role in delivering services like location-based services, fraud detection, and lawful interception.&#x20;

<figure><img src="../.gitbook/assets/unnamed.png" alt=""><figcaption></figcaption></figure>

The ATI operation is initiated by sending an ATI Invoke message to the HLR/HSS, which then processes the request and returns the desired subscriber information.

#### Process of Any Time Interrogation

1. **Request Initiation**: A network entity such as a Mobile Switching Center (MSC) or a Service Control Point (SCP) initiates an ATI request to the HLR/HSS.
2. **ATI Invoke Message**: This request is sent as an ATI Invoke message containing subscriber identifiers, which can include IMSI or MSISDN.
3. **Processing by HLR/HSS**: On receiving the ATI Invoke message, the HLR/HSS processes it to retrieve the requested subscriber information.
4. **Response**: The HLR/HSS sends a response back to the requesting network entity with the requested data.

#### Use Cases

* **Location-Based Services (LBS)**: Provides real-time location information, enabling services like navigation, tracking, and location-based advertising.
* **Fraud Detection**: Monitors location and usage patterns to identify and prevent fraudulent activities, ensuring secure subscriber transactions.
* **Lawful Interception**: Assists law enforcement agencies by providing information necessary for legal surveillance and data collection.

#### Security Considerations

Ensuring that ATI requests are only executed by authorized entities is critical to protect subscriber privacy and data integrity.&#x20;

Authentication and encryption mechanisms should be implemented to safeguard sensitive information throughout the process.
