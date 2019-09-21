# BetaNYC-Hackathon-2019-09-21

(\__/)    Still a little messy, but this code was written for the Mobility for All Abilities
(•ㅅ•)     on 9/21/2019 as part of the 'Reliable Access to Subways' team organized by
/ 　 づ    TransitCenter and United Equal Access NY.

Input is a PDF file in the local directory, the first page of the PDF and the last page of the PDF. The function adjusts the first page to account for zero-based numbering. It will output a csv file back into the directory.
    
There are a few issues with the code as-written.
- If an escalator or elevator is avialable 0.00% of the time, it will add an additional digit or character to the availability column.
- There is one other issue I've encountered where the subway lines aren't formatted properly.
- The comments will occaisonaly cut off and a fix for that is the first priority once this code is re-visited.
