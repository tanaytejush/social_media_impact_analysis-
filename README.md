# Social Media Impact Analysis

How does social media addiction affect students' lives? This project looks at its impact on **academic performance, sleep and mental health**, using data analysis, visualisation and statistical tests.

## What I did

- Cleaned and explored a dataset on students' social media habits
- Built correlation heatmaps, scatter plots, boxplots and regression lines
- Ran independent t-tests to compare students who say social media affects their studies with those who do not
- Ran correlation analysis between addiction, sleep and mental health
- Summarised the results into practical insights

## Key insights

- **Most addictive platforms**: Instagram, TikTok and Snapchat had higher addiction scores than other platforms.
- **Academic impact**: students who said social media affects their academics had higher daily usage and addiction scores. The t-tests showed this difference is statistically significant.
- **Sleep and mental health**: addiction is negatively correlated with both. More addicted students tend to sleep less and report poorer mental health.
- **Mental health vs addiction**: as addiction rises, mental health scores fall.

### Two sides of social media

Social media helps students stay connected, learn and express themselves. Overused, it drains focus, disturbs sleep and fuels endless scrolling and unhealthy comparison.

## Files

| File | Description |
|------|-------------|
| `student_addiction_analysis.ipynb` | Overall exploration of addiction scores |
| `most_addictive_platform.ipynb` | Platform-by-platform comparison |
| `impact_of_social_media_on_academics.ipynb` | Academic impact and t-tests |
| `sleep_mental_health_analysis.ipynb` | Sleep and mental health correlations |
| `Students Social Media Addiction.csv` | Original dataset |
| `Cleaned_Social_Media_Students.csv` | Cleaned dataset |

## Run it

```bash
pip install pandas seaborn matplotlib scipy jupyter
jupyter notebook
```

Open any notebook and run the cells in order.

## Tech stack

Python, pandas, seaborn, matplotlib, SciPy (t-tests and correlations), Jupyter Notebook

> The things we give our attention to shape how we experience life. This project is a gentle reminder to be mindful of how we use social media.


---

<sub>Made by [tanaytejush](https://github.com/tanaytejush)</sub>
