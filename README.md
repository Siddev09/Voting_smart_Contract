# Voting_smart_Contract

Register Voter:

Individuals register by providing their name, age, and gender.
Ensures only individuals aged 18 or older can register.
Each voter is assigned a unique voter ID and their address is stored.
Register Candidate:

Individuals register by providing their name, party affiliation, age, and gender.
Ensures only individuals aged 18 or older can register as candidates.
Registration is limited to a maximum of two candidates.
Each candidate is assigned a unique candidate ID and their address is stored.
Set Voting Period:

The election commission sets the start and end times for the voting period.
Ensures the end time is at least one hour after the start time.
Cast Vote:

Registered voters cast their votes by specifying their voter ID and the candidate ID they want to vote for.
Ensures voting is only allowed during the voting period.
Each voter can vote only once.
Check Voting Status:

Returns the current status of the voting process: Not Started, In Progress, or Ended.
Announce Results:

The election commission announces the results by identifying the candidate with the highest number of votes.
The address of the winning candidate is stored.
Emergency Stop:

The election commission can stop the voting process in case of emergencies.
