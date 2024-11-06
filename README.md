# Personal-Stat-Tracker
An app designed to track the answers to a series of personalised questions over time in order to derive insights on how certain behaviours affect mood, wellbeing and productivity.

# Restart the project in REACT

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

### General Metrics
- **Daily Consistency**: If you didn't fill out the form for yesterday, prompt to do so.
- **Sleep**: Did you sleep well (yes/no/kinda)
- **Physical Activity**: Did you excercise today (yes/no)
- **ADHD Medication**: Did you take ADHD medication (yes/no)
- **Other Medication**: Did you take other medication (drop down list that can be added to)
- **Headaches**: Did you experience headaches today (none, light, medium, heavy)

### Diet
- **Overall Diet Quality**: Rate each meal of the day from "greasy", "normal", "healthy".
- **Fruit/Vegetable Intake**: Yes/No (Did you eat at least 5 servings?).
- **Fiber Intake**: Yes/No (Did you consume enough fiber today?).
- **Hydration Level**: Rate from 1-10 how much water you drank.
- **Evening Munch**: Multiple choice (e.g., sweet, salty, carbs, protein) can choose more than one.
- **Notes**: Anything worth mentioning.

### Mood
- **Daily Mood Rating**: Rate from 1-10 on how you felt overall.
- **Social Interaction**: Rate from 1-10 on how much social interation you had.
- **Stress level**: Rate from 1-10 on how much stress you felt.
- **Mood Fluctuations**: Yes/No (Did you experience any mood swings?).
- **Energy Level**: Rate from 1-10 on how energized you felt.
- **Triggers**: Multiple choice (e.g.friends, stress, food, sex, existential dread).
- **Notes**: More detail on triggers.

### Bowel Movements
- **Regularity**: How many times did you go to the bathroom today.
- **Gas Based Discomfort**: Rate from 1-10 on stomach gas pressure and comfort.
- **Toot Frequency**: Multiple choice (e.g. barely, often, constant).
- **Stool Quality**: Multiple choice (e.g. normal, hard, loose).



