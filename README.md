Massachusetts Data Breaches, as compiled by the state, slightly cleaned up. Work in progress.


id:	integer, id within this data set
state_id:	integer, id in the state database
reported_date:	date, date it was reported to the state
organization:	text, name of the organization... more than a little messy. I tried normalizing this a little.
breach_type:	text, I think this is either "Electronic" or "Paper" but I haven't double-checked.
affected:	integer, the number of MA citizens affected
ssn:	boolean, whether social security numbers were exposed
account:	boolean, whether account numbers were exposed
license:	boolean, whether drivers license numbers were exposed
cards:	boolean, whether payment card numbers were exposed
monitoring:	boolean, whether credit monitoring was provided to those affected
encrypted:	boolean, whether the data was encrypted when exposed
mobile:	boolean, did this involve a lost mobile device
inserted_at:	timestamp, when it was ingested into this database
updated_at:	timestamp, when it was modified in this database... probably to clean up the name
