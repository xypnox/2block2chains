<div align="center">
    <img src='logo.png' />
    <p>Making the voting easier in India, one step at a time</p>
</div>

---

## Voting through Blockchain

India is a vast country with a huge population of 1.3 Billion. With such a large population, choosing a representative for the nation becomes a festival. It is a long dull event that drags on for weeks and months and that is one of the primary reasons for low voter turnout. If only the process was simpler and faster the voters would be much more enthusiastic to participate in the celebration of independence and democracy.

We intend to solve this dilemma through the use of Blockchain in maintaining and verification of voter ID cards. The first step begins through the issue of Voter ID card. Since, the government already has a verified age proof and identity of nationality: Aadhaar. We can auto generate the voter ID cards from the data available through aadhaar. and since Aadhaar already carries the Date of Birth of the person, the generation will become seamless. We will issue the voter ID card as soon as the person turns 18 and then the person can collect the Voter ID card from any kiosk near him by showing his aadhaar card. When the person receives the card, his details are added in a public blockchain with his voter ID number so as to verify that he posses the voting card.

When a voter visits a polling booth to cast a vote, he will show his voter ID card and his number will be confirmed through the data shared in the public blockchain. Thus, the user's identity can be confirmed and he can be allowed to vote from any location as the need for lists and specific voting booths is irrelevant with the commencement of public blockchain. A separate type of transaction can be introduced later to mark whether a person has voted or not. This will make the voting unique and make the method of using ink obsolete.

---

# Details

## What we are building?

We are building a blockchain based voter ID generation system and a voting status tracker. When a new person's voter ID card is generated, his name is added as a transaction to the blockchain. Then the verification of the voter ID card can be done using blockchain anywhere. Since the proof of work will be huge, faking the blockchain would be practically impossible.

Then, When the person casts a vote, his details again will be added to the blockchain. This blockchain will have a lower proof of work since insertions have to be rapid. However, since there will be several thousands of insertions every second, due to voting happening all over India, the blockchain would remain secure.

## How does this work?

Normally, each voter is given a specific booth to vote at and he can only vote inside his residential district. This dilemma makes it impossible for people living anywhere other than their hometown to cast a vote. However, since the blockchain is shared through the Internet, the barrier would be non-existent.

## How users can get started?

The first blockchain operation happens through the Electoral Office. Only specified personal can add data to the blockchain in the first step. After the voter ID card is generated the details are added in the public ledger and everyone can check if he is or is not on the voter list.

At the day of the voting, the client software at each voting booth can check whether the voter ID card issued is authentic by comparing the details on the card with those present in the blockchain. Since the details will be encrypted, it will be impossible for someone to forge a voter ID card. The blockchain can also be used to track the vote status of a person, i.e. has the person voted or not.

Also, since all the polls can thus be cast on the same day, the time taken to release the results will be significantly shortened.

## What Data set we are using?

Sample data has been taken from:

- https://uidai.gov.in/913-common-category/11308-data-and-downloads-section.html
- https://eci.gov.in/files/file/9401-e-roll-data-2019/

## What technologies are we using?

We are using the following for the project:

1. Azure Blockchain service
2. Python Backend
3. React Front End Client

---

## Notes

### Why not a Decision Helper?

A decision helper is a wonderful idea. It aims to remove all types of discrepancies between promises and actual accomplishments of the leaders. However, it faces one major obstacle. No leader in his sane mind would agree to sign a smart contract that will hold him responsible to all the promises he shall make. It is clear that the winning candidate is not the one who makes the most reasonable promises, but the one who promises of miracles and almost impossible feats. Hence, it is a great concept however, very unlikely to be implemented in the current political structure.
