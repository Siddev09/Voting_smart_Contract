# Voting_smart_Contract 🗳️

🌎ENTITY INVOLVED:

    Voter: Represents an individual who can vote. Each voter has a name, age, gender, voter ID, and a unique address.
    Candidate: Represents an individual who can be voted for. Each candidate has a name, party affiliation, age, gender,         candidate ID, and a unique address.
    Election Commission: A designated address responsible for overseeing the election process.
    Winner: The address of the candidate who wins the election.


1) Register Voter :
   
      Individuals register by providing their name, age, and gender.
      Ensures only individuals aged 18 or older can register.
      Each voter is assigned a unique voter ID and their address is stored.
3) Register Candidate:
   
      Individuals register by providing their name, party affiliation, age, and gender.
      Ensures only individuals aged 18 or older can register as candidates.
      Registration is limited to a maximum of two candidates.
      Each candidate is assigned a unique candidate ID and their address is stored.
5) Set Voting Period:
   
      The election commission sets the start and end times for the voting period.
      Ensures the end time is at least one hour after the start time.
7) Cast Vote:
   
      Registered voters cast their votes by specifying their voter ID and the candidate ID they want to vote for.
      Ensures voting is only allowed during the voting period.
      Each voter can vote only once.
9) Check Voting Status:
    
      Returns the current status of the voting process: Not Started, In Progress, or Ended.
11) Announce Results:
    
      The election commission announces the results by identifying the candidate with the highest number of votes.
      The address of the winning candidate is stored.
13) Emergency Stop:
    
      The election commission can stop the voting process in case of emergencies.
