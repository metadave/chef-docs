.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


|chef actions| tracks the following types of data:

* The name organization in which the event occurred, e.g. "chef"
* The hostname for the node from which the request was initiated, e.g. "computer.getchef.com" or "some.node.FQDN.com"
* A unique identifier for the request, e.g. the |chef client| run identifier for events generated during a |chef client| run or the |reporting| run identifier for events generated during reporting
* The name of the entity that made the request, e.g. "grantmc"
* The type of entity, e.g. "user"
* The interface from which the request was initiated, e.g. |knife|, |chef manage|, and so on, including the version for that interface
* The requested action; this typically maps to a specific method in the |api chef server|, such as ``create``, ``read``, ``update``, and ``delete``
* The |chef server| object and type, e.g. "cookbook" and "apache" (for a cookbook named "apache")
* The version (and version number) for the |chef server| object, e.g. "version" and "1.2.3"
* The date and time at which the event happened 

