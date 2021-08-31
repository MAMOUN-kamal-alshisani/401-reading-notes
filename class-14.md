## Readings: Event Driven Architecture


### ``What’s the difference between a FIFO and a standard queue?``
***Actually, it is the other way around. A FIFO uses a Queue data structure. A queue is just a data structure that allows easy access (insertion and deletion) to the head or tail of a queue. And you can access the n-th element of a queue. A FIFO enforces first-in-first-out access to the queue.***

## ``How can the server be assured a message was properly received?``
***By having the client emit a “received” event back to the server upon receipt of the message***

## ``What classic design pattern is best represented by event driven programming?``
***Probably one of the best known design patterns for event driven systems is the observer pattern***

## ``How do you test an event driven system?``
***event-driven applications must be tested in as thorough a manner as is reasonable. The first place to start is with logging. Effective logging is critical in any application architecture, but when it comes to event-driven application architecture, it’s essential.***


## ``Term``

### FIFO Queue
***What is a FIFO queue? A FIFO queue is a queue that operates on a first-in, first-out (FIFO) principle. This means that the request (like a customer in a store or a print job sent to a printer) is processed in the order in which it arrives.***

### Pub/Sub
***Pub/Sub is a HIPAA-compliant service, offering fine-grained access controls and end-to-end encryption. Google Cloud–native integrations. Take advantage of integrations with multiple services, such as Cloud Storage and Gmail update events and Cloud Functions for serverless event-driven computing. Third-party and OSS integrations.Pub/Sub is a HIPAA-compliant service, offering fine-grained access controls and end-to-end encryption. Google Cloud–native integrations. Take advantage of integrations with multiple services, such as Cloud Storage and Gmail update events and Cloud Functions for serverless event-driven computing. Third-party and OSS integrations.***
