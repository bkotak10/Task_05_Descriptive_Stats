## Prompt 6: As a manager, what areas should I improve to win the league — attack or defence?

* Asked whether the team needs to improve in **attack** or **defence** to win the league.
* ChatGPT analyzed total shots (233), goals (25), shot accuracy (42.9%), and goal conversion rate (10.7%) from the dataset. Since no data was available on goals conceded, defence couldn't be assessed.
* Based on low conversion, it incorrectly concluded that the **attack** needs improvement — recommending focus on finishing, better decision-making in the final third, and improving chance quality.
* In this case, the LLM failed to give the correct answer. It did not take into consideration opponent stats and hence incorrectly suggested "attack." However, based on opponent shooting percentage and SOG%, the actual focus should be **defence**.

---

## Prompt 4: Which player had the highest impact per minute played, considering both goals and assists?

* Looking at the SU Men’s Soccer stats for the 2024 season, we calculated a simple impact-per-minute metric using total points (where goals = 2 pts, assists = 1 pt) divided by minutes played.
* ChatGPT pointed to **Michal Gradus**: 2 points in 19 minutes ≈ 0.1053 pts/min. However, with only 19 minutes played, it's not a valid comparison.
* After refining the prompt to include only players who played 10+ games, the correct output was **Michael Acquah**.

---

## Prompt 5: Player with the most shots but lowest accuracy

* Asked to name the player with the most shots but lowest shooting accuracy.
* ChatGPT answered **Nicholas Kaloukian**, but this was incorrect. Nicholas had 32 shots with 56% on target, which is not low.
* After clarifying that the player should have at least 10 shots and low accuracy (measured by SOG%), the correct answer was **Elton Chifamba**.

---

## Prompt 1: How many games did SU Men’s Soccer team play this season?

* Answer: **17 games**  
* ChatGPT gave the correct answer, as confirmed by Python code.

---

## Prompt 2: Who scored the most goals in the 2024 season?

* Answer: **Gabe Threadgold** with **4 goals** over 17 matches  
* ChatGPT and data analysis both aligned.

---

## Prompt 3: How many total goals were scored by the team?

* Answer: **25 total goals** during the 2024 season  
* ChatGPT correctly read this from the cumulative stats.