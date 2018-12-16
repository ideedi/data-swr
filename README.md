# data-swr
Manage Schemas, Workers, and Renderers for your Enterprise Data

IDEEDI: A modern cloud-hosted Integrated Development Environment (IDE) for managing Electronic Data Interchange (EDI). 

Right now, connecting Enterprise Data applications such as NetSuite and Salesforce requires using extremely powerful commercial tools that provide incredibly crude programming environments.  IDEEDI is an open source project attempting to bring modern software practicies into this space, such as:
* single-click sandboxes and deploys
* explicit schema management
* centralized management of validations and alerts
* immutable data storage (via https://aws.amazon.com/qldb/)

Possible IDEs:
* repl.it
* cloudbox

It will initially leverage commercial ETL APIs such as Zapier, but the long-term goal is to build a complete Open Source solution.

Our first product is data-swr, pronounced "data sewer." The first version acts a Time Machine for your Enterprise Data, providing persistent storage of the entire history of your Enterprise Data (e.g., NetSuite transactions).  Future version intend to support:
* undo
* reporting and alerts
* multi-directional integrations 
