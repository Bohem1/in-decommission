# in-decommission
List of steps to take during decommission of servers

## Common

* Ensure valid backup exist
* Validate need to keep data
* Validate need to keep any system roles the server supports
* Validate system owner
* Validate existing dependencies
* Validate existing integrations


## Data

This needs to end up in a decision where we ether keep the data or destroy the data.
If we keep it we need to know where to store the data.
Follow the questions to end up doing the right thing.

* Do we need to keep this data?
* Who is the owner of the data?
* What kind of data is this?
* Any GDPR issues?


## System

Who is the owner of the system or who is enabled to make the call?
Are there any existing dependencies that hinders the decommisioning of the system?
Are there any existing integrations that hinders the decommisioning of the system?

Make a list and address all items on the list!
