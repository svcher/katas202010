**Title:** Choosing Archtecture Style

**What:**  Should we choose a single acritecture style or a combination?

**Context:** We have a diverse environment, where there is a need for offline systems to process changes made to significant amount of data, while we have online systems which need to present up to date information to the participants. 

**Decision:** We will use a combination of the event driven design, service oriented architecture, and event stream design pattern. 

Event driven design will allow our analytic's pipeline to operate on data as it comes. It will allow applications like the shipper app or cook's terminal to receive notifications. 

Service Oriented Architecture will allow our application to be be separate from the data, and be able to control the flow of updates. 

The event steam pattern will allow multiple systems have the access to the same events and keep the data represented in multiple formats (e.g. offline storage and online storage)
