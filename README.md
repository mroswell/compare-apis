# Docs
Congress | Open States
--------     | ---
https://sunlightlabs.github.io/congress/ | http://sunlightlabs.github.io/openstates-api/
http://tryit.sunlightfoundation.com/congress | http://tryit.sunlightfoundation.com/openstates

### Base URL
Congress | Open States
--------     | ---
https://congress.api.sunlightfoundation.com/[METHOD] | http://openstates.org/api/v1/[METHOD]

### Methods

Congress | Open States
--------     | ---
/legislators  | legislators
/legislators/locate | ...
/districts/locate | ...
/committees | /committees
/bills | /bills
/bills/search | ...
/amendments | ...
/nominations | ...
/votes | ...
/floor_updates | ...
/hearings | ...
/upcoming_bills | ...
/congressional_documents/search | ...
/documents/search | ...
... | /bills/state/session/bill_id/
... | /metadata/
... | /metadata/state/
... | /legislators/leg_id/
... | /legislators/geo/?lat=latitude&long=longitude
... | /committees/committee_id/
... | /events/
... | /event/event_id/
... | /districts/state/[chamber/]
... | /districts/boundary/boundary_id/

### Fields
Congress     | Open States
--------     | ---
committee_id | id
...          | state
chamber (upper, lower, joint)    | chamber (senate, house, joint)
name        | committee 
subcommittee (true/false), and subcommittees (names)   | subcommittee (name)
parent_committee_id | parent_id
parent_committee | ...
... | sources
... |created_at
... | updated_at 
members (full detail, including district) | members (name, leg_id, role [chair, vice-chair, member]) 
url | ...
office | ...
phone | ...



