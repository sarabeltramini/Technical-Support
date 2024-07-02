# Technical Support Analysis
This project focuses on conducting a thorough analysis of technical support tickets using advanced analytical capabilities, prominently leveraging Qlik Sense. Developed with a sophisticated approach, the project utilizes Qlik Sense’s powerful features, including the layout container function, to explore various dimensions of each ticket's lifecycle and interactions.

## Data Description
The dataset contains the following fields:

- Status: Current status of the ticket within the support pipeline (Open, In Progress, Resolved, Closed).
- Ticket ID: Unique identifier assigned to each support ticket.
- Source: Channel through which the support request originated (chat, phone, email).
- Priority: Level of urgency assigned to the ticket (low, medium, high).
- Support Level: Difficulty tier of the ticket (Tier 1, Tier 2).
- Product Group: Category to which the product or service related to the ticket belongs.
- Topic: Subject matter of the customer's inquiry.
- Agent Group: Group classification of agents handling the ticket (1st level support, 2nd level support).
- Agent Name: Name of the agent currently responsible for the ticket.
- Created Time: Timestamp indicating when the ticket was first received.
- Expected SLA to First Response: Deadline by which the initial response is expected.
- First Response Time: Timestamp marking the initial response.
- SLA For First Response: Compliance status of the initial response (Within SLA, SLA Violated).
- Expected SLA to Resolve: Deadline by which the ticket is expected to be resolved.
- Resolution Time: Timestamp marking the resolution of the ticket.
- SLA For Resolution: Compliance status of the ticket resolution (Within SLA, SLA Violated).
- Close Time: Timestamp marking the closure of the ticket.
- Agent Interactions: Total count of interactions by agents for each ticket.
- Survey Results: Customer satisfaction rating based on feedback (scale of 1 to 5).
- Country: Country of origin for the customer who created the ticket.
- Latitude: Latitude coordinates corresponding to the customer's country.
- Longitude: Longitude coordinates corresponding to the customer's country.
