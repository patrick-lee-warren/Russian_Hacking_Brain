# Russian_Hacking_Brain
Data for "“THE RUSSIANS ARE HACKING MY BRAIN!” investigating Russia's internet research agency twitter tactics during the 2016 United States presidential campaign" 

Published: https://www.sciencedirect.com/science/article/abs/pii/S074756321930202X
Working: http://pwarren.people.clemson.edu/Linvill_etal_RHMB.pdf

Codebook


publish_date (str): Date of Troll Tweet
author (str): Twitter handle of troll
content (str): Text of tweet
atype2 (str): Troll type, from Linvill & Warren (2020) Details: https://github.com/patrick-lee-warren/IRA-Troll-Types

Code One (numerical categorical):
1. attack left
2. support left
3. attack right
4. support right
5. attack on media
6. attack on civil institutions
7. camo
8. unknown

Code Two (numerical categorical):
0. Not ideological or partisan attack.
1. attacked Clinton/Clinton campaign
2. supported Clinton/Clinton campaign
3. attacked Trump/Trump campaign
4. supported Trump/Trump campaign
5. not about either candidate

post_type (str): RETWEET, QUOTE_TWEET, (null)

