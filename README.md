# Cinephile's SLackathon-Project2022
As a student of the Simplilearn PGP in Data Science program, this repository is for my SLackathon idea submission. 


### Cautionary Note. 
If you are expecting an idea that is going to solve a crucial problem for a humankind and/or change the world, this is certainly not the submission. Anyway, hope you enjoy reading it! ;)


## Brief Background
I consider myself a huge cinephile, or in more colloquial language – a  movie buff. Growing up, I was scolded a number of times for watching television for a prolonged period of time. My parents had almost given up hopes of my bright academic future, assuming that I was too distracted by movies, actors/actresses, dancing, songs, and whatnot. And, all this was because I loved watching movies... I still do! Anyway, I am not here to talk about how much I love watching them. Well…, in a way, I am here to talk about movies but with a slight (data science) twist. With this SLackathon submission, I am trying to combine what I love (movies) with what I want to love (data science)!

 

## What is the problem?
Due to the rise of online video streaming, several over-the-top (OTT) streaming services/platforms are competing for viewers' attention, money, and time (Lad et al., 2020). Needless to say, our email inboxes, social media pages, and/or television commercial breaks are inundated with "special offers" and advertisements from various OTTs, like Netflix, Amazon Prime, Hulu, Hotstar, HBO, Acorn to name a few. For an average household, subscribing to a limited number of OTTs may be possible; however, it may not be a wise option for specific populations (e.g., international students or young professionals living away from their families). I remember, as a poor international student back in the days, I would sign up for a free 1-month subscription to check out their offerings (and be confused which one to pick). But let's be honest - how much can you really gauge (and, more importantly, compare) their offerings on your specific selection criteria (e.g., cost, quality of movies and shows)? Perhaps not very well! And even if you are able to do it, it would be tremendously time-consuming (and likely a silly move). I am, therefore, proposing to find an answer to the question: Which OTT streaming service has the best offerings? 



## The idea
This submission idea stemmed from my desire to hopefully help myself and those who want to choose the right OTT streaming service, which will give them the most bang for their bucks. Among the top OTTs, Netflix (177.7 million viewers), Amazon Prime (152.6 million viewers), Hulu (125.8 million viewers), and Disney+ (109.8 million viewers) are the top four OTTs in the market (Insider Intelligence, 2022; Maglio, 2022). Note that, to limit my analyses, I have selected OTTs that have 100+ million viewership. My Plan is to use Kaggle datasets of these OTT service providers and specially compare these platforms on the available movies and TV shows that are uniquely offered by them. The lists of unique offerings across these four OTTs will be evaluated based on such specific criteria as range of release year, award winning content, and variety of content. Finally, the obtained results will be further evaluated in the light of their pricing models.         



## How can technology help?
I wish I were proficient in data science during my masters back in early 2010s to be able to solve this problem for me back then (note: I am still not very good but trying). My Plan is to use Python for analyses. I am yet to fully strategize how I plan to run the needed analysis, but here's how I think it will go: (a) clean each OTT data file, (b) merge them and remove redundancies (i.e., movies/shows common across all OTTs), (c) run descriptive analyses on the remaining unique entries based on variables of interest, (d) compare them to the 1927-2020 Oscars Award list, and lastly (e) inspect the results in the light of their pricing model. Note. The process may change slightly as I dive deeper into the data. 



## Step-by-step walkthrough
(1) To access datasets, I surfed Kaggle.com and found all four data files - Amazon Prime, Disney+, Hulu, and Netflix. Each file included the SAME feature, which made my work a bit easier.   
   
(2) To understand each OTT datafile, I ran basic exploratory analyses which indicated the following offerings across all 4 OTT platforms:
![image](https://user-images.githubusercontent.com/114754459/201593206-1b024e16-64b2-403b-b104-3145c668a6b1.png)   
![image](https://user-images.githubusercontent.com/114754459/201594259-e088b107-f7e8-4381-8255-9c147dc882d5.png)   
Purely, ***in terms of the raw quantity of content, Amazon Prime ranks 1st***, followed by Netflix which comes in a close second. By a fairly large margin, Hulu follows in the third place. And ***Disney+ ranks last with roughly ~1500 unique offerings***.   
   
(3) I needed to check how this ranking based on the number of offerings compares to the subscription cost of these OTT platforms. According to the latest information from *statista.com*, ***again, in terms of monthly subscription cost, Amazon Prime ranks the highest (8.99USD)***, followed by Netflix (9.99USD). And, Disney+ (10.99USD) was slightly higher than Netflix; however, ***Hulu is the costliest OTT platform, ranking last on the list (14.99USD)***.  
   
(4) Next, I needed to know how much of the content is overlapping. For instance: *The Rise of the planet of the apes* is on both Amazon Prime and Disney+. It was important to understand the extent of overlap across these OTT platform to run a clean cut analyses.   
A total of 236 content offerings were common across at least two of the OTT providers. Here, you will see the overlap of the other 3 OTT platforms with Amazon Prime.    
![image](https://user-images.githubusercontent.com/114754459/201597908-9d43e232-44aa-4e35-b509-0480414b5083.png)    
Here you will see the number of overlapping offerings across these 3 OTT platforms by *Content Type*:    
![image](https://user-images.githubusercontent.com/114754459/201597390-70b69424-4a30-488a-a8dc-59eb57bcb78d.png)   
Amazon Prime and Netflix have a comparatively higher content overlap although it accounts for just 2-3% of their total offerings. Note. The percentage was calculated from comparing n = 201 out of the total movies/TV shows both OTT platforms offer (9668 Amazon Prime / 8807 Netflix). On the other hand, Hulu and Disney+ offer fairly unique content with very little overlap with the other OTT platforms. So, ***in terms of uniqueness of the content, Disney+ ranks at the top***. This made me wonder if Disney+ is justified in charging close to 15USD monthly to its subscribers.   
   
(5) Now, I needed to check the quantity and variety of the UNIQUE content across these four OTT platforms. This step included a few Python coding tasks:    
   (5.1) Combining all four data files into a single csv file   
   (5.2) Identifying and removing redundant entries (which was done in Step 4)   
   (5.1) Saving all unique entries from all OTT platforms into a single usable file   
Note. I quickly realized that Python coding from this point on was tunring cumbersome, so I decided to run my summary analyses in Tableau Public. To me, it offered the ease of working with such a large dataset + it would help me present my results in a very palatable manner.    

***For more information, check out Cinephile's SLackathon-Project2022 Tableau Dashboard here: https://public.tableau.com/app/profile/bharati.b.belwalkar/viz/shared/XD62DWCYR***   



## Demo video   
https://youtu.be/GrAeod8awZg   


   


   













## Updated References:
1. Lad, A., Butala, S., & Bide, P. (2019, November). A comparative analysis of over-the-top platforms: Amazon Prime Video and Netflix. In International Conference on Communication and Intelligent Systems (pp. 283-299). Springer, Singapore.
2. Insider Intelligence (2022). Top OTT video streaming services in 2022 by viewer count and growth. Retrived from: https://www.insiderintelligence.com/insights/ott-video-streaming-services/
3. Maglio, T. (2021). Every Streamer Has Maxed Out Its U.S. Subscribers — Except These Two. Retrived from: https://www.indiewire.com/2022/10/netflix-hulu-amazon-disney-maxed-out-us-subscribers-1234771907/ 
4. Stoll, J. (2022, November). Monthly costs of streaming services most basic ad-free plan in the United States as of November 2022, by service. Retrieved from: https://www.statista.com/statistics/1110896/svod-monthly-subscription-cost-us/ 
