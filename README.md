# Personal-Stat-Tracker
An app designed to track the answers to a series of personalised questions over time in order to derive insights on how certain behaviours affect mood, wellbeing and productivity.

## MVP Features
* Concise form to fill out at the end of each day
* Calendar that displays data snapshot for each day
* Visualisation for each data point over time

### Additional Features
* Ability for users to edit the form entries after submission 
* Comparative data visualization to glean insight
* Ability for users to save charts

## System Architecture
* __Frontend__: HTML, CSS (Tailwind), Javascript
* __Backend__: Django
* __Database__: SQLite
* __Hosting__: Render


# Daily Check-In App Metrics

## Diet
- **Overall Diet Quality**: Rate from 1-10 how healthy your meals were.
- **Fruit/Vegetable Intake**: Yes/No (Did you eat at least 5 servings?).
- **Hydration Level**: Rate from 1-10 how much water you drank.
- **Cravings**: Multiple choice (e.g., sweet, salty, carbs, protein).

## Mood
- **Daily Mood Rating**: Rate from 1-10 on how you felt overall.
- **Mood Fluctuations**: Yes/No (Did you experience any mood swings?).
- **Triggers**: Multiple choice (e.g., stress, sleep, food).
- **Energy Level**: Rate from 1-10 on how energized you felt.

## Bowel Movements
- **Regularity**: Yes/No (Did you have a bowel movement today?).
- **Comfort Level**: Rate from 1-10 on comfort after bowel movements.
- **Stool Quality**: Multiple choice (e.g., normal, hard, loose).
- **Fiber Intake**: Yes/No (Did you consume enough fiber today?).

## General Metrics
- **Daily Consistency**: Track how many days you filled out the form.
- **Trends Over Time**: Monitor mood, diet, and bowel movements weekly/monthly.
- **Alerts for Concerns**: Automated flags for concerning trends (e.g., persistent low mood or irregularity).
