<h1>Benign Walkthrough</h1>

<h2>Answers</h2>

<b>Question 1: How many logs are ingested from the month of March, 2022?</b>
<br><br>
To find this information, I simply changed the time period of the logs to only show dates from March 2022. In this case, even when you choose "all time", this index shows the same results inlcuded all 13959 events.
<br><br>
<b>Answer:</b> 13,959

<b>Question 2: Imposter Alert: There seems to be an imposter account observed in the logs, what is the name of that user?</b>
<br><br>
For this answer, I used:
<br>
| table UserName <br>
| dedup UserName
<br><br>
This allowed me to see a list of the usernames only one time, which is where I found the imposter "Amel1a" where the imposter changed the "i" in Amelia in to a 1.
<br><br>
<b>Answer:</b> Amel1a

<b>Question 3: Imposter Alert: There seems to be an imposter account observed in the logs, what is the name of that user?</b>
<br><br>
For this answer, I used:
<br>
| table UserName <br>
| dedup UserName
<br><br>
This allowed me to see a list of the usernames only one time, which is where I found the imposter "Amel1a" where the imposter changed the "i" in Amelia to a 1.
<br><br>
<b>Answer:</b> Amel1a


