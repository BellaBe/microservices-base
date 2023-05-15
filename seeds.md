# Seven Essential Evolutiond of Design for Services
1. Identifying actors
    - Frequent flyer
    - Family vacationer
    - Airline customer service agent
    

2. Identifying jobs that actors have to do
    * Job as a unit of analysis (JTBD = job to be done)
    * when <a circumstance>, I want to <motivation>, so I can <goal>
    - Frequent flyer
        1. When Emma’s plans change and she is unable to travel on a previously booked flight, she wants to easily reschedule her flight, so she can get a flight that works for her new plans.
        2. When Emma prefers an available seat other than the one she has been currently assigned, she wants to select the alternative seat, so she can enjoy her flight more.

    - Family vacationer
        1. When Riley is planning a flight for their family vacation, they want to be able to filter available flights by multiple criteria, including: four adjacent seats available on the flight, the number of connections, connections that go through airports that have facilities friendly to young children, etc., so that their family can fly with maximum comfort.
        2. When Riley is planning a quick, unplanned family getaway for a long weekend, they want to get suggestions for interesting available trips that are affordable and a short flight so they can have a list of choices they can consider.
        
    - Airline customer service agent
        1. When a customer calls Sean, he wants to have a servicing ticket open pre-filled with customer information, so he can start tracking the progress towards the resolution of the customer need.
        2. When a customer is asking Sean to find them a convenient flight for their trip, he wants to be able to find a fitting flight using a flexible set of filtering criteria, so he can meet the customer need and book a flight.

3. Discovering interaction patterns with sequence diagrams

4. Deriving high-level actions and queries based on jobs to be done (JTBDs) and the interaction patterns

5. Describing each query and action as a specification, with an open standard (such as the OpenAPI Specification [OAS] or GraphQL schemas)

6. Getting feedback on the API specification

7. Implementing microservices