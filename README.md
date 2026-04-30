
# M365-ITSM-Ticketing-System
A centralized ticketing system built to streamline maintenance requests across 17+ retail locations. This solution replaces manual email/text reporting with a structured intake process, automated department routing, and mobile-friendly communication for managers.


<img width="2816" height="1536" alt="Gemini_Generated_Image_cm9uc8cm9uc8cm9u" src="https://github.com/user-attachments/assets/f9cab0a8-53ce-4037-8721-8fc3f9c05e19" />


Problem: Maintenance requests were fragmented across emails and texts, leading to lost tickets and slow response times for 17+ locations.

Solution: A centralized "Single Source of Truth" system that automates the lifecycle of a ticket from submission to resolution.

The Result: 0% lost tickets, 100% accurate store data routing, and a professional mobile interface for managers on the move.

<img width="959" height="585" alt="M365TicketingSystem" src="https://github.com/user-attachments/assets/10626278-419a-438d-a68e-d23bb2aa9c51" />

How it Works (The "Engine" Under the Hood)
The Intake: Users submit a ticket via a simplified SharePoint interface. [Made a scannable QR Code]


The Brain (Power Automate): * Data Enrichment: The system "shaves" seconds off response times by looking up the store's physical address and phone number automatically from a secure Directory.
<img width="690" height="671" alt="M365Flow3" src="https://github.com/user-attachments/assets/e7ed7208-459c-4b65-bfe7-8dbe1afe9f33" />

Smart Routing: A logic-gate (Switch) identifies the department and pings the correct manager instantly.
<img width="1305" height="680" alt="M365Flow1" src="https://github.com/user-attachments/assets/e6110a15-b091-48dd-bd17-68784a202805" />


The Payload: The manager receives a "Clean-UI" email containing:

Direct-Dial Link: No looking up numbers.

GPS Quick-Link: No typing addresses.

Deep-Link to Item: No searching for the ticket.
