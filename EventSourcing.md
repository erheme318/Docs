## Event sourcing & CQRS

Event: Something that happend in the past. (e.g DepositPerformed)

Event Sourcing:
 - Persist only changes in state
 - Replay can be side-effect free ( replay - here refers to listeners such as SendEmails, log ... etc)

Problem: Side-effects
Solutions:
 1. Separate side-effect and state change
 2. Saving event triggers side-effect (You know how the system got into the current state)

### The advantages of Event Sourcing
 - Complete log of every state change ever
 - Traceability and debugability
 - 

## Reference 
 1. Brief intro & references http://ookami86.github.io/event-sourcing-in-practice/
 2. Event sourcing basics https://github.com/eventstore/eventstore/wiki/Event-Sourcing-Basics
