# PyPoll_Challenge
## Devin Monsen
### 08/02/2022
---
**Overview of Election Audit**
---
<sub>Our purpose in this challenge is extracting the results of a given data set. Specifically, determining the outcome of a democratic election. Firstly we were able to calculate total votes. This gives the project team an idea on how many particapants we're working with. Secondly, we found the votes from each county. Not only do we now know the how many, but now the where. This was also broken down into a percentage to simplify readability. Then just a quick if statement calculates the highest percentage to show the dominant county in our list.</sub>
---
**Election-Audit Results**
---
* >How many votes were cast in this congressional election?: 
---
<sub>After running our script we found a total of 369,711 total votes</sub>
---
* >Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.: 
---
<sub>After looking at our outcomes its clear that Denver is a high impact county. With 82% of votes coming from this county.</sub>
---
* >Which county had the largest number of votes?
---
<sub>Denver came out on top with 306,055 votes</sub>
---
* >Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
---
<sub>Looking a little deeper we see that Charles received 23% of votes and Diana received 73%. This shows that Denver isn't completely one sided and can be disected to get even more data.</sub>
---
* >Which candidate won the election, what was their vote count, and what was their percentage of the total votes?:
---
<sub>Dianna DeGette won the election with a total vote 272,892, consisting of 73.8% of our total votes.</sub>
---
**Election-Audit Summary**
---
<sub>In future elections we can reuse this script by appending a new dataset. We pull our data from the os.path, so all we must do is replace the file_to_load with a new data set. Or we can append, adding new data to our existing set. Our script already has an if statement that if the candidates name isnt in the data set, then append it to the list. By merging a new data set, the script will automatically append it to our data.
