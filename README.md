# Election-Analysis
## Reson for Audit

The current digital voting trend blended with paper ballots makes the system of voting we currently have in place have a dire need for integrity and verification. While we are not expressly saying that the system is fradulent, we need safeguards to ensure fraud is not occuring. In this audit, we take a look at a handful of Colorado's counties to verify the voter turnout is matched with the ballots counted.

## Audit Results
*How many votes were cast this election?*
- The audit has counted 369,711 votes among Arapahoe, Denver, and Jefferson counties.

*How did the votes distribute per county?*
- The audit found that Jefferson county had 10.5% (38,855), Denver county had 82.8% (306,055), and Arapahoe county had 6.7% (24,801) of the total votes.

*Which county had the largest number of votes?*
- Denver county had the largest total votes with 306,055.

*How did the votes distribute among the candidates?*
- Charles Casper Stockham received 23.0% (85,213), Diana DeGette received 73.8% (272,892), and Raymon Anthony Doane received 3.1% (11,606) of the total votes.

*Who won and by how much?*
- Diana DeGette received 272,892 of the total votes. That was 73.8% of the total.

## Audit Summary
Commissioners, we currently are in a prescident where our democracy is evolving to meet with the demand that the last 2 years have put on this country. We need to ensure everyone's voice is heard and that no one is trying to tip the scales in anyone's favor. This script has shown in small scale that we can audit a selection of counties in the state. Since we have formatted it to be usable with new data and information, we can ramp up the data to be state-wide. This script will process all counties in national elections while also being relevant for the smaller elections. For those smaller elections, we can add sections of code to index down the city level making so the audit can be performed across the board.

This code is not just designed for elections. Since we've developed this as a counting and sorting system, we can utilize this code to better tally anything. For example, we can tally inventories at the registrar of voters. By replacing candidate names and counties with product names and brand. We also can utilize this code to better track voter turnout in regards to who votes how often. Assuming we keep the voter IDs unique to one person, we can track the IDs across all elections and see if someone skips an election. By replacing candidate information with the ID lookup, we can track when that ID votes and verify they didn't vote more than once.

![Inventory](https://github.com/Atros04/Election-Analysis/blob/main/Resources/Alt%20Code%201.PNG) ![Voter IDs](https://github.com/Atros04/Election-Analysis/blob/main/Resources/Alt%20Code%202.PNG)

These images are provided for proof of concept testing and are subject to change. For your consideration, we can take these audits and scale them for not only the state, but beyond the scope of our initial needs for anything that can be tallied.
