# Python_WarlogClassification

The dataset found in the file warlog.csv contains a subset of military reports related to the war in Iraq between 2004 and 2009, published by WikiLeaks in 2010. The analysis of war situations is certainly important for both military and humanitarian reasons, to help populations affected by events and military attacks.

The following variables are available:

report_key | text: Identifier of the report.\
to_timestamp | timestamp: Report release date (updated to the minute).\
Type | text: Classification of events in each report.\
category | text: Specific classification of each report.\
region | text: Geographic area where the event occurred.\
attack_on | text: Target of the event/attack reported in the report.\
coalition_forces_wounded | integer: Number of coalition forces units wounded in the event/attack.\
coalition_forces_killed | integer: Number of coalition forces units killed in the event/attack.\
iraq_forces_wounded | integer: Number of Iraqi forces units wounded in the event/attack.\
iraq_forces_killed | integer: Number of Iraqi forces units killed in the event/attack.\
civilian_wia | integer: Number of civilians wounded in the event/attack.\
civilian_kia | integer: Number of civilians killed in the event/attack.\
enemy_wia | integer: Number of enemy units wounded in the event/attack.\
enemy_kia | integer: Number of enemy units killed in the event/attack.\
enemy_detained | integer: Number of enemy units captured in the event/attack.\
total_deaths | integer: Total number of deaths in the event/attack.\
st_x | numeric: Longitude of the event/attack location.\
st_y | numeric: Latitude of the event/attack location.\

It is of interest to understand what characterizes the different types (Type) of events described in the reports, seeking to identify, among other characteristics, if there is a higher probability of observing criminal events, enemy actions, friendly actions or those characterized by so-called "friendly fire," non-combat events, suspicious incidents, threats, etc., in certain time intervals, in specific geographical areas, or in specific spatial locations.

This problem has been faced as a multiple category classification problem.

