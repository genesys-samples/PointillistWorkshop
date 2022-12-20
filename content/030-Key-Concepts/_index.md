---
title: "Key Pointillist Concepts"
chapter: true
weight: 30
---

## Key Pointillist Concepts 

### Events

Every data point brought into Pointillist is represented as an event. An Event is any single data record with an event type classification, a timestamp, and a customer identifier of any type (account #, tracking cookie, email address, etc) 

![Events](/images/ConceptsEvents.png)

### Paths

Path Discovery uses the power of AI to allow users to immediately see the most important sequences of events before, after, or between events. Users can easily see dropouts, channel switching, and success rates to quickly find areas of opportunity, and then build or expand journeys by selecting events along a path of interest. Paths lets you quickly discover the natural or most frequent path and turn it into a baseline journey. 

![Paths](/images/ConceptsPaths.png)

### Journeys

Pointillist’s behavioral query and business rules structure, which is visually represented, created and managed via the UI. A customer journey encompasses the series of steps customers take with your organization, within and beyond the contact center to achieve a goal.

![Journey](/images/ConceptsJourney.png)

### Reports

Tabular extracts run against a Journey. Combined, Journeys and Reports present a SQL-like capability, with Journeys acting as join conditions and Reports as select statements (with aggregations, math expressions, etc). 

![Reports](/images/ConceptsReports.png)

### Actors

As mentioned above, every event is associated with an identity, for instance a customer or account. The type of identity that all events will share is called the primary actor. If your Pointillist instance has Account as the primary actor, then every event will ultimately be associated with one, and only one account. An event may also be associated with other actor types (e.g. subscribers within an account or calls and web sessions associated with subscribers within an account). These other actor types are called secondary actors. 
