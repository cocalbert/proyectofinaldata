**How the Data market is doing in Barcelona 👀:**

**Why did I do this project?**
I've been working with people in the HR sector for more than 6 years. Now that I help students to transition from their background to the tech world, I have thought that my project can be a very useful tool to always have a vision of how the tech world moves.

**How did I do it? 📝**
- First of all, I have created a "bot" with Selenium with the objective of scapping a large amount of DATA positions in Barcelona.  All of them published during the last two months. From each position I have extracted: Title, Company, Location, Modality, and Description. I've collected around 300 jobs.


- Data Cleaning with Python, & NLTK👨‍🔧
 
Once I collected the data, the major part of the cleaning, feature extraction, tokenization and lemmatization, has been in the description of each offer in order to facilitate the extraction of mostly, keywords for the tech tools, soft skills and hard skills and also (including the analysis of the title) to extract the seniority of one of them.

After that, with sklearn I  obtain the count frequencies of appearance of the keywords in the description. I did that using the TfidfVectorizer from sklearn.

 - Visualization with Tableau 📊
To finalize the analysis I wanted to visualize all the data and insights with Tableau. To do this, I first wanted to visualize an overview of the DATA world in Barcelona, then see the differences between categories (Analyst, Scientist and Engineer) and then focus on the Data Analyst positions.

**Most important insights 🚀**
**ALL JOBS:**
· 40,38% were Analyst positions, 30,28% were Data Engineer and 29,34 for Data Scientist.
· More than 60% of the positions are in hybrid mode
· More thant 80% positions are "senior" positions (Even if you are a junior, apply! Many companies are not very clear about what they are looking for!
· Power Bi & Tableau are the visualization tools more demanded
· ML, AI, Modeling, Reporting and Dashboard are the Hard Skills more demanded
· Management, Communication, Leadership, Creativity and Proactivty are the Soft Skills more requested

**BY CATEGORIES:**
· Unlike the analyst and engineer positions, the scientist positions require more python and r than SQL.
· There is a big difference in the level of visualization tools between analysts and the others. These tools are much more demanded for analysts, being Ppower BI and Tableau the most demanded (watch out for Qlik!).

**DA IN PARTICULAR:**
· Dashboard & Reporting are (with a lot of difference) the hard skills more demanded
· Obviously much more senior positions are requested (77,17% vs 22,83% - junior)
· Interesting: for junior positions: 56% are hybrid, 31% On-site & only 12,93% are remote.
· SQL is the programming tool more requested.
· Communication, leadership, decision making and proactivity are the soft skills more requested.

I hope you have enjoyed the project as much as I have (although there have been many ups and downs, especially in the data extraction)😁


See you✌🏼





    
