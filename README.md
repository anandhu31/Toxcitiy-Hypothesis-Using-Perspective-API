# Toxcitiy-Hypothesis-Using-Perspective-API

The purpose of this test was to conclude whether the use of exclamation marks in the comment list will lead to a higher score due to the greater intensity of words. I believe that the use of exclamation marks will increase the toxicity score given by the Perspective API program.

In my test, I obtained the toxicity scores of three short phrases with no punctuation, "no bi***", "f*** off", "h*** no", and received the scores of "0.94992846", "0.9885203", "0.33025458", respectively. From this data, we can analyze that these values are extemley high (except for "h*** no") as the scale for the toxicity score ranges from 0-1. 

For the second part of the test, I obtained the scores of the same three phrases, however this time, with two excalmation marks ("no bi***!!", "f*** off!!", "h*** no!!"). With these phrases, the score of "no bi***" increased from 0.94992846 to 0.95346254; the score of "f*** off" decreased from 0.9885203 to 0.9869635; the score of "h*** no" increased significantly from 0.33025458 to 0.4893326. 

From this we can conclude that the use of exclamation marks does increase the score, for the most part. The only exception was "f*** off", but the score decreased by less than 0.01. From the data, we can see that words like "h*** no" have a huge impact when two exclamation marks are added. 

My guess on why the phrase "f*** off" decreased with the added excamlation marks is that with the added punctuation, the system interpretted it as more sarcastic - therby decreasing its score slightly. Frankly, I am still very suprised that this phrases score decreased.

See the document in the repository for more analysis on the data.
