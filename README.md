# Exercise & Student Cognitive Performance

## Project Overview

A life science and human performance research study conducted at University.

The study investigated whether exercising influences students' perceived cognitive functioning and short-term academic productivity. 
Its purpose was to contribute to a deeper understanding of the relationship between physical activity and academic performance, while also providing practical recommendations that may help students optimise their exercise routines to support optimal productivity in connection with academic tasks and studies.

The research applied a mixed methods approach, combining both quantitative and qualitative data collected through surveys and interviews. This provided measurable insights into behavioral patterns and perceived productivity outcomes, while also enabling a deeper understanding of individual experiences and perceptions.

Inspiration for the study originated from personal observations regarding increased cognitive functioning, motivation, and productivity immediately following exercise.

The population included university students aged 18 to 30.

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

[Recommendations](#recommendations)



## Hypothesis
The study hypothesised that exercise has an immediate positive effect on one’s cognitive behaviour and direct ability to achieve increased academic productivity.

## Research Questions
- How does exercise affect cognitive functions?
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

- Cleaning and standardising categorical variables 
- Handling missing values and replacing undefined categories with appropriate labels
- Creating midpoint variables for grouped responses including age group and exercise frequency
- Structuring the dataset into two tables (clean_data) and (clean_exercise_type) connected through a respondent identifier

In addition, to easier facilititate the analysis, values recorded in statements concerning the same cognitive function where combined.

These steps ensured that the dataset could be properly analysed and visualised in Tableau.

## Methodology

The study applied descriptive methods to summarise participant responses along with an exploratory data analysis to identify patterns and relationships between exercise and various cognitive functions. 

These were later complemented by qualitative research, conducted on five carefully selected participants.

The first step involved summarising the distribution of responses across all key variables to provide an overall understanding of participants’ perceptions.

This included:
- Calculating average, median, min, and max Likert scores for cognitive and productivity related variables
- Examining the distribution of responses for each statement
- Identifying general trends in perceived cognitive effects following exercise

This step provided a baseline overview of how participants perceive the relationship between exercise and cognitive performance.

## Quantitative Analysis

### Descriptive Statistics
![Dashboard](descriptive_statistics_exercise_and_academic_productivity_analysis.png)

### Focus score
Participants reported relatively high levels of focus following exercise, indicating that exercise may contribute to immediate enhanced concentration and increased attention span. The recorded mean of 3.95 and median of 4 suggest that a large part of the population agrees with exercise resulting in enhanced focus. The standard deviation of 0.687 in this case, suggests that the population is moderately agreeing to the effect of its nature. With responses ranging from 2 to 5, noticabe is that no respondent claimed to strongly disagree with exercise contributing to increased focus.

### Motivation score
The motivation score presents slightly lower levels and a wider distribution of perceived positive immidate impact following exercise.
The mean was calculated at 3.64, and the median fell in at 3.5, indicating that the most common perceptions were positive or neutral.  
However, the standard deviation presents a fairly high number of 0.837, showcasing a noticeable lack of consistency within the population of how exercise can boost the willingness to complete academic tasks.

### Stress score
The second highest mean of 4.27, and the strongest consensus of the population regarded an immediate stress reduction following exercise.
No respondent recorded that stress does in fact increase following exercise, but rather that it either remains neutral or that it decreases.
This result highlights stress reduction as one of the main cognitive functionings most positively affected in the population.

### Energy score
The energy score, entailing both physical and mental energy, is undeniably another factor positively affected following exercise. The mean recorded a value of 4.17, similar to the median of 4, indicating that the main share of the population agrees with exercise having a positive impact on their energy levels. The standard deviation on the other hand showcases a value of 0.719, suggesting some variation in the responses.

### Mood score
With the highest mean of 4.42, and median of 4.5, the mood score implies that exercise has the strongest positive effect on students’ overall mood and well-being. The standard deviation of 0.643 tells us that the data is fairly consistent, and the main part of the population perceive that exercise improves their overall mood. 

### Productivity score
The productivity score recorded a mean of 3.37, and a median of 3.5, making it one of the lowest average perceived factors following exercise. Generally, the majority of the population seemed to be neutral about its outcome. The standard deviation however, recorded 0.741, suggesting that opinions are divided regarding this matter, with the highest score recording 4.5 and the lowest 1.

### Motives score
With the lowest mean of 2.81, and median of 3, the motives score indicates that the majority did not agree with academic productivity being a reason for why they exercise. The standard deviation, however, showed the highest variability of 0.996, suggesting that there is a strong disagreement within the population. The large variation tells us that the individuals perceive different motives for why they exercise, with some participants strongly agreeing, and other strongly disagreeing with the idea of their physical activities are driven by their academic productivity goals.

### General Impact score
The general impact score showcases the second most consistent values with a standard deviation recorded at 0.591. The mean of 4.01 and median of 4, indicates that the majority of the participants generally perceive exercise as having a positive impact on their cognitive behaviour, long term well-being, and overall academic achievements. Yet, the minimum recorded value suggests that there are in fact respondents that do not consider exercise to have a positive general impact on their academic capabilities.

### Summary of Scores
Notably, we can tell that participants generally believe that exercise has a significant positive effect on their overall mood, reduced levels of stress, and increased energy. 

The motives for exercise in relation to academic benefits, the motivation gained from it, and the short-term productivity it leads to however, show lower scores. These suggest that exercise may have an insignificant or perhaps even negative impact on some students cognitive functions and immediate productivity. However, the high standard deviation suggests a low level of consensus among participants regarding these factors, indicating differing perceptions within the sample.



Following the descriptive overview, relationships between variables were explored to identify potential patterns.

**The dashboards below explore:**

- Relationships between exercise behaviour and perceived productivity
- Correlations between cognitive outcomes (energy, stress reduction, motivation) and productivity
- Differences in productivity across exercise types, frequency levels, and intensity


## Dashboards

### Tableau Workbook
**Interactive Dashboard:** [View on Tableau Public](https://public.tableau.com/views/CapstoneProjectExerciseandAcademicProductivityAnalysis/CognitiveEffectsofExercise?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) 

### Cognitive Effects of Exercise
![Dashboard](dashboard_cognitive_effects.png)

### Exercise Behaviour and Productivity
![Dashboard](dashboard_exercise_productivity.png)


In contrast to the descriptive statistics, the visualisations were created to provide a comparison of exercise habits and perceived cognitive functions. Therefore, the following analysis focuses on observed associations rather than statistical inference.

Without adding too much emphasis on the mood score, which unarguably showcases a high consensus regarding its positive change following exercise, questions instead arose about how increased energy, reduced stress, and motivation relates to short-term productivity.

Indidated by the scatterplots, the upward lines reveal positive relationships between perceived academic productivity and all three cognitive factors examined. Participants who reported higher levels of these factors following exercise generally also reported higher productivity scores. Although all relationships showed some degree of variability,motivation appears to exhibit the strongest positive association with productivity.

As participants where provided with multiple options when presenting exercise types they typically engage in, we see a variability in how they affect individuals differently. Swimming and JAMBOX record the highest means throughout however, worth noting is that these two responses were only recorded once. In contrast, weightlifting and cardio showcase a more reliable finding as they are part of the majority of the population's workout habits.

When examining frequency, and how it relates to direct academic productvity, no major differences were observed. However, before rejecting the possibility of frequency actually having a direct impact, it is important to consider that it may influence productivity indirectly. Factors such as energy, motivation, and stress reduction, all of which demonstrate positive relationships with perceived productivity could certainly be affected by how frequently one engages in physical activity. Therefore, it is worth highlighting even the small changes showcasing the possible advantage of exercising daily, and or seven to nine hours per week.

Additionally, exercise intensity shows a similar pattern. While some differences were observed, favouring vigorous intensity, these should be interpreted with caution. 
Much like exercise frequency, exercise intensity could be highly individual and may depend on factors such as fitness level, workout experience, and recovery capacity. Nonetheless, the finding should not be disregarded as a potential way to increase productivity, especially for individuals experiencing positive cognitive changes following exercise.

In terms of the main question, to understand how exercise directly influence acamedic productivity, we see a divided population. Although the majority being either neutral or agreeing to perceived positive changes, there are respondents experiencing negative outcome.


## Qualitative Analysis

The qualitative component was based on five semi-structured interviews with students aged 18–30 who regularly engage in physical exercise, ranging from recreational to professional levels.

A thematic analysis approach was used to identify patterns in participants’ responses. After familiarising with the data through repeated review, key excerpts were manually coded and grouped into broader themes reflecting shared perceptions of exercise, productivity, and cognitive behavior.

The themes derived from the analysis were:
- Exercise increases focus levels and efficiency leading to enhanced productivity
- Exercise regulates stress and improves overall mood
- Exercise boosts productivity through increased levels of energy and motivation
- Poor exercise quality inhibits productivity outcome and vice versa

The findings reveal a strong consensus on the positive impact of physical exercise on mood, stress reduction, and overall well-being. Many participants linked improved mood to enhanced ability to manage academic tasks and long-term performance. For example, several respondents described exercise as a "tool" for stress relief and mental reset.

However, short-term productivity effects were mixed. Some participants reported increased energy and motivation immediately after exercise, while others experienced fatigue, particularly after intense workouts. A recurring theme was that workout quality influenced outcomes, with satisfying sessions boosting motivation and poor sessions reducing it.

Subsequently, a reciprocal relationship emerged between exercise and academic performance, where success in one area positively influenced motivation in the other.

Overall, the qualitative insights served to complement the quantitative findings by highlighting how individual experiences, workout intensity, and psychological factors shape the relationship between physical activity and productivity.


## Conclusion

Findings derived from the analyses indicate that exercise generally has a positive influence on students' cognitive functioning and overall mental well-being. Above all, exercise appears to enhance focus and efficiency while reducing stress, resulting in enhanced mental functionality.

However, notable to highlight is that not all participants experience similar outcomes following physical activity, in particular to if it in fact leads to immediate productivity.

On one hand, exercises like swimming and JAMBOX signalise potential for increasing productivity, however, these results were based on a single participant and should be interpreted with caution. On the other hand, Calisthenics and weightlifting demonstrate slightly lower average productivity scores, but were supported by a larger and more reliable sample size.

Although no large differences were detected, exercise frequency shows a slightly favourable outcome in increased productivity for students who exercise daily, seven to nine hours per week. 

Regarding what intensity level results in highest perceived immediate productivity, quantitative findings reveal a slight advantage for participants engaging in vigorous exercise. However, the qualitative analysis challenge these findings as some participants claims that exercising to exhaustion could have a negative effect on their cognitive functions and immediate productivity.

Although some respondents report an increased productivity following phsyical activity, findings show a fairly high differentiation within the population. Therefore, despite quantitative data revealing similarities and correlations between exercise and cognitive functions, no definitive conclusion can be drawn to whether exercise is conclusively a direct intervention for reaching higher levels of productivity.

Instead, results highlight that some individuals may be more susceptible to exercise increasing their academic productivity than others. 
Therefore, recommendations should not be uniform, but acknowledge individuals' differences to highlight possible initiatives while recognising that the effectiveness of such approaches may vary between individuals.


## Key Insights
The analysis suggests several patterns in the relationship between exercise and perceived academic productivity:

- Higher exercise frequency is generally associated with higher reported productivity levels.
- Cognitive effects such as increased energy and motivation show strong positive relationships with productivity.
- Reduced stress following exercise also appears to contribute to improved productivity.
- Certain exercise types appear to be associated with higher productivity outcomes, although results vary across respondents.
- Responses indicate individual differences, with some participants experiencing neutral or even negative short-term effects.

Overall, findings suggest that physical exercise can play a meaningful role in supporting students’ perceived cognitive performance and short-term academic productivity, although its impact is not uniform across all individuals.

### Disclaimer

The wide variation in responses detected in the descriptive statistics indicates a divided sample, with responses ranging from very low to very high perceived cognitive effects. This highlights that the relationship between exercise and productivity is not uniform.

While the analysis indicates a positive trend, where individuals who exercise more frequently and report stronger cognitive benefits also tend to report higher productivity, these findings remain correlational.

Therefore, it can not be conclusively stated that physical exercise leads to immediate productivity improvements for all individuals. Outcomes appear to depend on personal factors, exercise intensity, and individual perception.

## Recommendations

Based on the results of the study, students who experience positive cognitive change following physical activity may stand to benefit from adapting their exercise habits to daily participation. 

Although respondents' were divided on this matter, vigorous intensity could serve for increasing short term productivity. At the same time, weightlifting, and calisthenics exercises were associated with slightly better productivity outcomes and students may therefore benefit from incorporating these types of exercises into their routine. 

In addition, students that experience immediate productivity increases following exercise may consider aligning their training sessions with study periods or exams to maximise potential performance benefits. 

In contrast, individuals aware of negative immediate effects brought on by exercise should be mindful of their limitations and the timing in relation to study periods and exams in which they engage in physical activity. 

Additionally, with students being the target population for the study, universities may consider implementing measures to aid students in their quest for maximising productivity.

Therefore, universities should consider promoting physical activity in study routines and provide students with recreational sports programs. 

The institutions could also consider establishing or improving university facilities dedicated to physical exercise to foster a supportive environment and provide their students with the ability to achieve their best possible academic potential.
