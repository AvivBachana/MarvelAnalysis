# Marvel Cinematic Universe – A Data Story

I wasn’t always an MCU fan — no comics, no quirky socks, no midnight premieres. But after binging the Infinity Saga with a True Believer, I was hooked. The humor, the heroes, the storytelling — it swept me away.

So when it came time to pick a project, I had one burning question:  
**What makes Marvel movies so successful?**  
Is it the heroes, the villains, the massive budgets, or the genre mashups?  
This data-driven journey was my way of finding out.

---

## 🧰 Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook  
- **Data Sources:** Kaggle, Wikipedia, MCU fan sites  

---

## 🧪 Workflow

1. Merged multiple datasets (budgets, ratings, character traits, screen time)  
2. Cleaned and completed data using public sources  
3. Conducted exploratory analysis (EDA)  
4. Created visualizations to answer key storytelling/business questions  
5. Summarized key insights  

---

## 🎬 MCU at a Glance

![Budget vs Revenue Overview](images/marvel1.png)  
*A snapshot of Marvel’s cinematic success through budget and revenue patterns*

I started with datasets from Kaggle, covering budgets, revenues, IMDB scores, and character screen time. Merging these datasets was just the beginning — filling gaps meant digging into Wikipedia, Marvel fan sites, and more.

---

## 💸 Blockbuster Budgets: Bigger Is Better?

![Budget vs Revenue](images/budget_vs_revenue.png)  
*Higher budgets correlate strongly with higher revenue (r = 0.91)*

Films like *Avengers: Endgame* demonstrate that Marvel's massive investments pay off. Phase 3 consistently outperformed earlier phases in revenue.

---

## 🎭 Genre Impact on Success

![Genre Breakdown](images/genre.png)  
*“Action, Adventure, Drama” performs best in both ratings and box office*

Marvel’s emotional depth (e.g., *Black Panther*) proved more impactful than lighter “Action-Comedy” blends.

---

## ⏱ The Length Effect: Longer Films, Bigger Wins

![Duration Heatmap](images/heatmaps.png)  
*High-budget + long duration = financial sweet spot*

Movies like *Infinity War* sit in the most profitable category.

---

## 🎬 Runtime and Ratings

![Duration vs Ratings](images/marvel2.png)  
*Longer films correlate with higher IMDB ratings*

Marvel’s longer runtimes seem to allow deeper narratives and character development.

---

## 🦸‍♂️ Heroes in the Spotlight

![Hero Screen Time](images/character_screen_time.png)  
*Lead characters with more screen time also drive better ratings and higher revenue*

Characters like Iron Man and Captain America have clear positive correlations.

---

## 😈 The Villain Effect

![Villain Impact](images/marvel3.png)  
*Villains like Thanos boost emotional stakes — and audience reception*

![Villain Screen Time](images/screentime.png)  
*Stronger villains correlate with higher IMDB ratings*

Narrative weight given to villains may be a hidden success factor.

---

## ⚖️ Gender & Representation in Marvel

![Gender Traits Breakdown](images/gender_attributes.png)  
*Male characters dominate in physical traits like strength and combat*

![Power Balance (Violin)](images/gender_attributes_violin.png)  
*Female characters show a more balanced range of powers*

Marvel’s shift toward inclusivity is seen not just in numbers — but in how power is represented.

---

## 🧩 Key Takeaways

- 🦸‍♂️ **Lead heroes drive success** – Screen time matters  
- 🧑‍🤝‍🧑 **The ensemble effect** – Group casts often perform better  
- 😈 **Villains matter too** – Their presence impacts ratings  
- 🎭 **Genre mashups** – Action + Drama resonates more than pure comedy  
- 💰 **Big budgets pay off** – High investment = high returns  
- ⌛ **The long game** – Runtime correlates with depth and success  
- ♀️ **Balanced representation** – Power dynamics are evolving

---

## 🧠 Final Thoughts

I didn’t crack Marvel’s formula, but I uncovered fascinating signals.  
More importantly, I learned how to merge, clean, and enrich complex data — and let it tell a story, even when it surprises you.

The MCU remains a mystery, but the tools I used here?  
They’re now part of my personal origin story.

---

## 📌 See More

- [🧠 Emergency Data Generator (Text + Audio)](https://github.com/AvivBachana/data_generator)  
- [📊 Predictive Classification Pipeline (Titanic)](https://github.com/AvivBachana/ML_FirstAssignment)  

---



I wasn't always an MCU fan - no comics, no quirky socks, no midnight premieres. But after binging the Infinity Saga with a True Believer, I was hooked. The humor, the heroes, the storytelling - it swept me away. So, when it came time to pick a project, I had one burning question: What makes Marvel movies so successful? Is it the heroes, the villains, the massive budgets, or the genre mashups? This data-driven journey was my way of finding out.

![Budget vs Revenue](images/marvel1.png)

I started with datasets from Kaggle, covering details like budgets, revenues, IMDB scores, and character screen time. Merging these datasets was just the beginning - filling gaps meant digging into Wikipedia, Marvel fan sites, and more. After stitching everything together and cleaning the data, I was ready to uncover what makes Marvel movies such a phenomenon.

---

## Setting the Stage: The Marvel Universe by the Numbers

To begin, I gathered a dataset encompassing movie details such as release dates, budgets, gross revenues, IMDB scores, and even detailed breakdowns of character screen time and attributes. After a thorough cleaning process, I was ready to dive into the data.
But where to start? Marvel's budgets often make headlines, so I asked a simple question: Do bigger budgets guarantee bigger payoffs?

---

## Blockbuster Budgets: Bigger Is Better?

Marvel doesn't shy away from massive budgets, with films like Avengers: Endgame boasting some of the highest production costs in cinematic history. When plotting budget vs. gross revenue, a clear pattern emerged: more money spent often means more money earned. With a strong correlation of 0.91, it became evident that Marvel's high-budget films are their most successful.
Interestingly, Phase 3 movies consistently outperformed earlier phases, suggesting Marvel's ability to refine its storytelling and marketing strategies over time.

![Budget vs Revenue](images/budget_vs_revenue.png)

---

## The Power of Genre: Action, Adventure, Drama

Next, I turned to the question of genre. Marvel's films often blend action, adventure, and sci-fi, but how do these combinations impact ratings and revenue?
The "Action, Adventure, Drama" genre emerged as a fan favorite, with the highest IMDB ratings and gross revenues. Films like Black Panther combine emotional depth with thrilling action - a combination audiences clearly love.

In contrast, lighter genres like "Action, Adventure, Comedy" tended to underperform in ratings, signaling that Marvel fans may prefer deeper storytelling when it comes to their superheroes.

![Genre Gross](images/genre.png)

---

## The Length Effect: Why Longer Films Win

One unexpected trend was the impact of movie duration. Marvel's longer films consistently outperformed shorter ones in both ratings and revenue. When breaking down movies by budget and duration, the most profitable category included long, high-budget films, exemplified by blockbusters like Avengers: Infinity War.

![Duration vs Gross](images/heatmaps.png)


---

## Marvel's Metrics: Explore the Numbers

To better understand Marvel's formula for success, I created an interactive Tableau visualization titled "Movie Metrics". This visualization dives deep into the key metrics for each movie, including the number of female characters, total gross, IMDB ratings, and budget.

*View the Tableau Sheet Here*

---
![Duration vs Ratings](images/marvel2.png)


## Heroes in the Spotlight: A Tale of Screen Time and Success

Marvel's characters are the heart of its universe, and their screen time often reflects their narrative importance. But does more screen time translate to better ratings or higher revenues?

![Character Screen Time](images/character_screen_time.png)

When analyzing the screen time of Marvel's iconic heroes, a fascinating pattern emerges: characters like Tony Stark (Iron Man) and Steve Rogers (Captain America) consistently demonstrate positive correlations between their screen time and metrics such as IMDB scores and gross revenue.

---


## The Villain Effect

![Villain Screen Time vs Ratings](images/marvel3.png)

The analysis didn't stop with heroes. I also explored the impact of villains, like Thanos and Loki, on movie success.

![Villain Screen Time vs Ratings](images/screentime.png)

Villains like Thanos, who dominated the narrative in Avengers: Infinity War and Avengers: Endgame, show strong positive correlations with metrics like IMDB scores.

---

## Gender and Representation in Marvel

Marvel's evolving representation of male and female characters reflects a broader industry shift toward inclusivity.

![Gender Attributes](images/gender_attributes.png)
![Gender Attributes](images/gender_attributes_violin.png)

An analysis of power features by gender revealed a stark contrast: while male characters overwhelmingly dominate in traditional traits like strength and combat, female characters often showcase more balanced power distributions.

---

## Bringing All These Insights Together: Marvel's Winning Formula

Through our deep dive into the Marvel Cinematic Universe's data, we've uncovered several key ingredients that contribute to its unparalleled success:

- Central Heroes Drive Success
- The Ensemble Effect
- Villains Matter Too
- Genre Mastery
- Big Budgets Pay Off
- The Long Game
- Balanced Representation

---

## Final Thoughts

If this project taught me one thing, it's that crafting the next MCU is definitely not in my skillset. My initial speculations? Most of them didn't align with the data. Some results left me scratching my head, wondering how Marvel pulls it off. Clearly, Stan Lee and the team had a magic touch I can't replicate.

But while I didn't crack the Marvel formula, the journey was its own reward. I learned how to tackle complex datasets, pull insights from multiple sources, and let the data tell its story - even when it didn't fit my expectations.

The MCU remains a mystery, but the skills and lessons I gained are my real superhero origin story.


