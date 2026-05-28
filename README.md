# Exercise and Student Cognitive Performance

## Project Overview

A life science and human performance research study conducted at University.

The study investigated whether exercising influences students' perceived cognitive functioning and short-term academic productivity. 
Its purpose was to contribute to a deeper understanding of the relationship between physical activity and academic performance, while also providing practical recommendations that may help students optimize their exercise routines to support optimal productivity in connection with academic tasks and studies.

The research applied a mixed methods approach, combining both quantitative and qualitative data collected through surveys and interviews. This provided measurable insights into behavioral patterns and perceived productivity outcomes, while also enabling a deeper understanding of individual experiences, perceptions, and attitudes toward exercise and academic performance.

Inspiration for the study originated from personal observations of increased cognitive functioning, motivation, and productivity immediately following exercise.

## Project Structure

[Hypothesis](#hypothesis)

[Research Questions](#research-questions)

[Tools Used](#tools-used)

[Data Collection](#data-collection)

[Data Cleaning & Transformation](#data-cleaning--transformation)

[Methodology](#methodology)

[Quantitative Analysis](#quantitative-analysis)

[Dashboards](#dashboards)

[Qualitative Analysis](#qualitative-analysis)

[Key Insights](#key-insights)

[Final Results](#final-results)

[Recommendations](#recommendations)



## Hypothesis
The study hypothesised that exercise has an immediate positive effect on one’s cognitive behaviour and direct ability to achieve increased academic productivity.

## Research Questions
- Does exercise frequency influence productivity?
- Do cognitive effects such as increased energy, higher motivation, or reduced stress influence productivity?
- Which exercise types are associated with higher productivity?

## Tools Used
- Google Forms
- Google Sheets
- Microsoft Teams
- Tableau

## Data Collection

***Quantitatve Data Collection***

The dataset was collected through a Google Forms survey targeting students aged 18-30. Respondents were presented with a series of statements regarding the cognitive effects they experience following physical exercise.

Participants evaluated each statement using a 5-point Likert scale:

1 = Strongly Disagree  
2 = Disagree  
3 = Neutral  
4 = Agree  
5 = Strongly Agree  

Statements measured perceived short-term changes in:
- energy levels
- motivation
- stress reduction
- focus
- mood
- academic productivity
- motives for exercising
- overall general impact

In addition, respondents reported their typical:
- exercise frequency
- exercise intensity
- exercise type

***Qualitative Data Collection***

The qualitative component involved semi structured interviews with selected participants and was used to provide additional depth to the measurable data.
It sought to explore underlying causes, further developing on the reasoning and challenges behind trends and patterns.

The inverviews were conducted using Microsoft Teams and focused on identifying habits, routines, and behavioral factors that may influence cognitive functioning, motivation, and perceived productivity.

In order to create the most natural and open discussion environment possible, the interviews did not strictly follow a fixed set of questions. Instead, they were designed to allow conversations to flow freely, enabling participants to elaborate on personal experiences and perspectives in greater detail.

## Data Cleaning & Transformation
Data cleaning and transformation were performed in Google Sheets before importing the dataset into Tableau.

The process included:

- Cleaning and standardizing categorical variables 
- Handling missing values and replacing undefined categories with appropriate labels
- Creating midpoint variables for grouped responses including age group and exercise frequency
- Structuring the dataset into two tables (`clean_data` and `clean_exercise_type`) connected through a respondent identifier

These steps ensured that the dataset could be properly analysed and visualized in Tableau.

## Methodology

The study applied descriptive methods to summarize participant responses, complemented by exploratory data analysis to identify patterns and relationships between exercise and various cognitive functions. 

The first step involved summarizing the distribution of responses across all key variables to provide an overall understanding of participants’ perceptions.

This included:
- Calculating average, median, min, and max Likert scores for cognitive and productivity related variables
- Examining the distribution of responses for each statement
- Identifying general trends in perceived cognitive effects following exercise

This step provided a baseline overview of how participants perceive the relationship between exercise and cognitive performance.

## Quantitative Analysis

### Descriptive Statistics
![Dashboard](descriptive_statistics_exercise_and_academic_productivity_analysis.png)

### Focus score
Participants have reported relatively high levels of focus following exercise, indicating that exercise may contribute to immediate enhanced concentration and increased attention span. The recorded mean of 3.95 and median of 4 suggest that a big part of the population agrees with exercise leading to an enhanced focus, and the standard deviation of 0.687 in this case, suggests that the population is moderately agreeing to the effect of its nature.

### Motivation score
The motivation score recorded slightly lower levels of perceived impact following exercise as the mean was calculated at 3.64, which however also was close to the median of 4. The standard deviation on the other hand, showed a fairly high number of 0.837, indicating a noticeable lack of consistency within the population of how exercise can boost the willingness to complete academic tasks.

### Stress score
With the second highest mean of 4.27 and the lowest score in standard deviation, 0.493, a reduced level of stress was unarguably perceived as the factor most positively affected by physical exercise.

### Energy score
The energy score, entailing both physical and mental energy, was undeniably another factor positively affected following exercise. The mean recorded a value of 4.17, similar to the median of 4, indicating that the main share of the population agreed with exercise having a positive impact on their energy levels. The standard deviation on the other hand showcased a value of 0.719, suggesting some variation in the responses.

### Mood score
With the highest mean of 4.42, and median of 4.5, the mood score implies that exercise has the strongest positive effect on students’ overall mood and well-being. The standard deviation of 0.643 tells us that the data is fairly consistent, and the main part of the population perceive that exercise improves their overall mood.

### Productivity score
The productivity score recorded a mean of 3.37, and a median of 3.5, making it one of the lowest average perceived factors following exercise. Generally, the majority of the population seemed to be neutral about its outcome after exercise. The standard deviation however, recorded 0.741, suggesting that opinions are divided regarding this matter.

### Motives score
With the lowest mean of 2.81, and median of 3, the motives score indicated that the majority did not agree with academic productivity being a reason for why they exercise. The standard deviation, however, showed the highest variability of 0.996, suggesting that there is a strong disagreement in the population. The large variation tells us that the population perceive different motives for why they exercise, with some participants strongly agreeing, and other strongly disagreeing with the idea that their physical activities are driven by their academic productivity goals.

### General Impact score
The general impact score showcased the second most consistent values due to the lowest standard deviation recorded, 0.591. The mean of 4.01 and median of 4, indicates that the majority of the participants generally perceive exercise as having a positive impact on their cognitive behaviour, long term well-being, and overall academic achievements. 

### Summary of Scores
Notably, we can tell that participants generally believe that exercise has a significant positive effect on their overall mood, reduced levels of stress, and increased energy. 

The motives for exercise in relation to academical benefits, the motivation gained from it, and the short-term productivity it leads to however, show lower scores, suggesting that exercise has an insignificant or perhaps even negative impact for some students on the perceived direct academic benefits of physical activity. However, looking at the high standard deviation, the data suggests that the population disagrees regarding these factors, indicating differing perceptions among the participants.



Following the descriptive overview, relationships between variables were explored to identify potential patterns.

**The dashboards below explore:**

- Relationships between exercise behaviour and perceived productivity
- Correlations between cognitive outcomes (energy, stress reduction, motivation) and productivity
- Differences in productivity across exercise types, frequency levels, and intensity
  
In contrast to the descriptive statistics, the visualisations were created to provide a comparison of exercise habits and perceived cognitive functions. Therefore, the following analysis focused on observed associations rather than statistical inference.


## Dashboards

### Cognitive Effects of Exercise
![Dashboard](dashboard_cognitive_effects.png)

### Exercise Behaviour and Productivity
![Dashboard](dashboard_exercise_productivity.png)

## Tableau Workbook
**Interactive Dashboard:** [View on Tableau Public](https://public.tableau.com/views/CapstoneProjectExerciseandAcademicProductivityAnalysis/CognitiveEffectsofExercise?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) 

The packaged Tableau workbook (.twbx) is also included in this repository.

## Qualitative Analysis

The qualitative component was based on five semi-structured interviews with students aged 18–30 who regularly engage in physical exercise, ranging from recreational to professional levels.

A thematic analysis approach was used to identify patterns in participants’ responses. After familiarizing with the data through repeated review, key excerpts were manually coded and grouped into broader themes reflecting shared perceptions of exercise, productivity, and cognitive behavior.

The findings reveal a strong consensus on the positive impact of physical exercise on mood, stress reduction, and overall well-being. Many participants linked improved mood to enhanced ability to manage academic tasks and long-term performance. For example, several respondents described exercise as a tool for stress relief and mental reset.

However, short-term productivity effects were mixed. Some participants reported increased focus and motivation immediately after exercise, while others experienced fatigue, particularly after intense workouts. A recurring theme was that workout quality influenced outcomes, with satisfying sessions boosting motivation and poor sessions reducing it.

Additionally, a reciprocal relationship emerged between exercise and academic performance, where success in one area positively influenced motivation in the other.

Overall, the qualitative insights complement the quantitative findings by highlighting how individual experiences, workout intensity, and psychological factors shape the relationship between physical activity and productivity.



## Key Insights
The analysis suggests several patterns in the relationship between exercise and perceived academic productivity:

- Higher exercise frequency is generally associated with higher reported productivity levels.
- Cognitive effects such as increased energy and motivation show strong positive relationships with productivity.
- Reduced stress following exercise also appears to contribute to improved productivity.
- Certain exercise types appear to be associated with higher productivity outcomes, although results vary across respondents.
- Responses indicate individual differences, with some participants experiencing neutral or even negative short-term effects.

Overall, the findings suggest that physical exercise can play a meaningful role in supporting students’ perceived cognitive performance and short-term academic productivity, although its impact is not uniform across all individuals.

## Final Results

- The majority of participants reported either neutral or positive immediate effects of physical exercise on their cognitive functioning and productivity levels.
- Swimming and JAMBOX showed the highest perceived productivity levels following exercise; however, these results were based on a single participant and should be interpreted with caution.
- Calisthenics and weightlifting demonstrated slightly lower average productivity scores, but were supported by a larger and more reliable sample size.
- Participants engaging in vigorous-intensity exercise and/or training 7–9 hours per week exhibited a slight advantage in reported productivity levels.

### Disclaimer

The wide variation in responses detected in the descriptive statistics indicates a divided sample, with responses ranging from very low to very high perceived cognitive effects. This highlights that the relationship between exercise and productivity is not uniform.

While the analysis indicates a positive trend, where individuals who exercise more frequently and report stronger cognitive benefits also tend to report higher productivity, these findings remain correlational.

Therefore, it can not be conclusively stated that physical exercise leads to immediate productivity improvements for all individuals. Outcomes appear to depend on personal factors, exercise intensity, and individual perception.

## Recommendations

- Students who perceive improved cognitive functioning and productivity after exercise should consider aligning their training sessions with study periods or exams to maximize potential performance benefits.
- As higher frequency and vigorous-intensity exercise were associated with slightly better productivity outcomes, students may benefit from maintaining a consistent weekly routine (e.g., 7–9 hours per week) to support cognitive and academic performance.
- Given the variation in results, students should experiment with different types, intensities, and timing of exercise to identify what best enhances their own cognitive functioning and productivity.
