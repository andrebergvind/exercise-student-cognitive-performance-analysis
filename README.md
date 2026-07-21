# Exercise & Student Cognitive Performance

## Project Overview
This research project explores the relationship between exercise, cognitive functioning, and short-term academic productivity among university students.

For the purpose of this study, short-term productivity refers to an individual's perceived ability to perform academic tasks immediately following exercise.

The research aimed to contribute to a deeper understanding of the relationship between physical activity and cognitive outcomes, while also providing practical recommendations that may help students optimise their exercise routines to enhance productivity.

The analysis leveraged both quantitative and qualitative data collected through surveys and interviews. This mixed methods approach allowed for measurable behavioural patterns, while also enabling a deeper understanding of individual experiences and perceptions.

Inspiration for the study originated from personal observations regarding increased cognitive functioning and productivity immediately following exercise.

While this project built upon existing literature, the following analysis focuses exclusively on the primary research conducted.

The sample examined in this study consisted of 51 university students aged 18 to 30.

## Project Structure

[Background & Justification](#background--justification)

[Hypothesis](#hypothesis)

[Research Questions](#research-questions)

[Tools Used](#tools-used)

[Data Collection](#data-collection)

[Data Cleaning & Transformation](#data-cleaning--transformation)

[Methodology](#methodology)

[Quantitative Analysis](#quantitative-analysis)

[Dashboards](#dashboards)

[Qualitative Analysis](#qualitative-analysis)

[Discussion](#discussion)

[Key Insights](#key-insights)

[Conclusion](#conclusion)

[Result](#result)

[Recommendations](#recommendations)

## Background & Justification
In modern society, the positive effect of physical exercise is frequently praised due to its benefits related to long term health. An extensive body of research on the subject suggests that exercising does not only enhance one's physical state but also improves emotional well-being.

In biochemical terms, the benefits emerging from engaging in physical activity include the stimulated release of endorphins and serotonin, neurotransmitters that contribute to improved mood and reduced tension. At the same time, regular exercise is believed to mitigate the production of stress hormones like adrenaline and cortisol, leaving individuals feeling less stressed.

In an academic setting where students are constantly faced with new learning materials and relentless deadline pressures, managing stress and finding strategies to support optimal cognitive functioning are essential.

Yet, maintaining physical activity can be difficult, particularly when an individual's health is compromised by stress or a lack of energy, a reality especially relevant to the life of a student.

In this scenario, the role of exercise as a method to relieve stress and enhance cognitive functioning becomes paradoxical. However, when discussing physical activity as an intervention to achieve increased short-term productivity rather than long-term health, it becomes particularly interesting due to its established benefits, such as increased arousal and reduced levels of anxiety.

In neuroscience, dopamine, acetylcholine, and noradrenaline, neurochemicals stimulated by physical activity, are often recognised as modulators of attention, memory encoding, and alertness, factors that directly underpin productivity. 

Given its suggested neurological benefits, one might conclude that acute exercise should result in improved productivity. However, whether these benefits apply universally to all individuals remains uncertain.

For instance, while exercise-induced neurobiological mechanisms can certainly bear significant change to one's ability to feel more relaxed in a stressful situation, psychosocial factors may be just as vital as biophysical mechanisms for overall cognitive improvement. For this reason, the relationship between physical activity and mental performance becomes far more complex.

In this study, I examine over 50 university students aged 18 to 30 to determine if there is a connection between exercising, cognitive functioning, and short-term productivity.

The research aims to contribute to sports science and cognitive psychology by providing empirical data on the acute, immediate executive effects of exercise, rather than its well documented long-term physical benefits.

Examining the relationship between exercise and immediate productivity on university students might spark questions of reformed pedagogical strategies, study habits, and exam preparations, along with the implementation of necessary campus resources.

Gaining more insight into the effect that exercise has on students' ability to perform in an educational setting may provide us with a deeper understanding of the needs they have to achieve overall academic success, paramount not only for the students themselves but also for university institutions.

## Hypothesis
The study hypothesised that exercise has an immediate positive effect on an individual's cognitive functioning and their ability to achieve increased academic productivity.

## Research Questions
- How does exercise affect cognitive functioning?
- Which cognitive and psychological functions experience the greatest change and are most strongly associated with increased productivity?
- Does exercise frequency influence productivity?
- Which exercise types are associated with increased productivity?

## Tools Used
- Google Forms
- Google Sheets
- Microsoft Teams
- Tableau

## Data Collection
### Quantitative Data
The dataset was collected through a Google Forms survey targeting students aged 18 to 30. Respondents were presented with a series of statements regarding changes in cognitive and psychological states following exercise.

Participants evaluated each statement using a 5-point Likert scale:
1 = Strongly Disagree
2 = Disagree
3 = Neutral
4 = Agree
5 = Strongly Agree

Statements measured perceived short-term changes in:
- Energy levels
- Motivation
- Stress reduction
- Focus
- Mood
- Academic productivity
- Motives for exercising
- Overall general impact

In addition, respondents reported their typical:
- Exercise frequency
- Exercise intensity
- Exercise types

### Qualitative Data
The qualitative component involved semi structured interviews with five selected participants and was used to provide additional depth to the measurable data. It sought to explore underlying causes, further developing on the reasoning and challenges behind trends and patterns.

These interviews were conducted using Microsoft Teams and focused on identifying habits, routines, and behavioural factors that may influence cognitive functioning and perceived productivity.

In order to create a natural and open discussion environment, the interviews did not strictly follow a fixed set of questions. Instead, they were designed to allow conversations to flow freely, enabling participants to elaborate on personal experiences and perspectives in greater detail.

## Data Cleaning & Transformation
Data cleaning and transformation were performed in Google Sheets before importing the dataset into Tableau.

The process included:
- Cleaning and standardising categorical variables
- Handling missing values and replacing undefined categories with appropriate labels
- Creating midpoint variables for grouped responses including age group and exercise frequency
- Structuring the dataset into two tables (clean_data) and (clean_exercise_type) connected through a unique respondent identifier

In addition, to easier facilititate the analysis, values recorded in statements concerning the same variables where combined.
These steps ensured data quality and allowed for a fair and accurate analysis.

## Methodology
Initially the study applied a descriptive method, summarising participant responses across all variables to provide an overall understanding of individuals' perceptions.

This included:
- Calculating average, median, min, and max Likert scores for cognitive and productivity related variables
- Examining the distribution of responses for each statement
- Identifying general trends in perceived cognitive and psychological effects following exercise

Thereafter, followed an exploratory relationship analysis, using bar charts and scatter plots to identify patterns and associations between exercise types, cognitive functions and short-term productivity.

Finally, the study was complemented by a qualitative analysis, providing deeper insight into the trends and relationships identified in the quantitative analysis.

## Quantitative Analysis
### Descriptive Statistics

**Focus**
Participants reported relatively high levels of focus following exercise, indicating that exercise may contribute to immediate enhanced concentration and increased attention span. 
The recorded mean of 3.95 and median of 4 suggest that a large portion of the population agrees with exercise resulting in enhanced focus. The standard deviation of 0.687 in this case, indicates that the population is moderately agreeing to the effect of its nature. 
With responses ranging from 2 to 5, noticeable is that no respondent claimed to strongly disagree with exercise resulting in increased focus.

**Motivation** 
The motivation score presents slightly lower levels and a wider distribution of perceived positive immediate impact following exercise. 
The mean was calculated at 3.64, and the median recorded 3.5, indicating that the most common perceptions were positive or neutral. 
However, the standard deviation presents a fairly high number of 0.837, showcasing a noticeable lack of consistency within the population in regard to exercise boosting willingness to complete academic tasks.

**Stress**
The second highest mean of 4.27, and the strongest consensus of the population regarded an immediate stress reduction following exercise. 
No respondent recorded that stress does in fact increase following exercise, but rather that it either remains neutral or decreases. 
This result highlights stress reduction as one of the main variables most positively affected by exercise.

**Energy**
The energy score, entailing both physical and mental energy, was undeniably another factor positively affected following exercise. 
The mean recorded a value of 4.17, similar to the median of 4, indicating that a large proportion of the population agrees with exercise boosting their energy levels. 
The standard deviation on the other hand showcases a value of 0.719, suggesting some variation in the responses.

**Mood**
The highest mean of 4.42, and median of 4.5, was recorded for the mood score, indicating that exercise has the strongest positive effect on students' overall mood and well-being. 
The standard deviation of 0.643 tells us that the data is fairly consistent, and the main part of the population perceive exercise as a method to improve their overall mood.

**Productivity**
The productivity score recorded a mean of 3.37, and a median of 3.5, making it one of the lowest average perceived factors following exercise. 
Generally, the majority of the population seemed to be neutral about its outcome. 
The standard deviation however, recorded 0.741, suggesting that the sample is divided regarding this matter, with the highest score recording 4.5 and the lowest 1.

**Motives**
With the lowest mean of 2.81, and median of 3, the motives score indicates that the majority did not agree with academic productivity being a reason for why they exercise. 
The standard deviation, however, shows the highest variability of 0.996, suggesting that there is a firm disagreement within the population. 
The large variation tells us that participants possess different motives for why they exercise, with some strongly agreeing, and others strongly disagreeing to whether their physical activities are conducted as a method to achieve higher academic productivity.

**General Impact**
The general impact score showcases the second most consistent values with a standard deviation recorded at 0.591. 
The mean of 4.01 and median of 4, indicate that the majority of the sample generally perceive exercise as having a positive impact on their cognitive functioning, long term well-being, and overall academic achievements. 
Yet, the minimum recorded value suggests that there are in fact participants that do not consider exercise to have a positive general impact on their academic capabilities.

**Summary of Scores**
Notably, as suggested by the descriptive statistics, participants generally believe that exercise has a significant positive effect on their overall mood, and leads to reduced levels of stress and increased energy.

The scores related to motives for exercise being academic benefits, the motivation gained from it, and the short-term productivity it results in however, indicate a more divided sample.

Likewise, the perceived effects of increased focus demonstrates variability within the sample. Although this cognitive function shows a baseline improvement across the population, some respondents claimed to not experience this outcome.

In conclusion, while some participants strongly agree with the direct academic benefits catalysed by physical activity, others strongly disagree, suggesting that the benefits derived from engaging in exercise are not universal.

In fact, the data indicates that for a subset of the sample, exercise may have an insignificant or perhaps even negative impact on some students' cognitive functioning and immediate productivity. 

Following the descriptive overview, relationships between key variables were explored to identify potential patterns.

The dashboards below explore:
- Relationships between exercise behaviour and perceived productivity.
- Correlations between cognitive outcomes (energy, stress reduction, motivation) and productivity.
- Perceived changes in productivity across various exercise types, frequency, and intensity levels.

## Dashboards


### Cognitive Effects 
![Dashboard](dashboard_cognitive_effects.png)

### Exercise Behaviour
![Dashboard](dashboard_exercise_productivity.png)


In contrast to the descriptive statistics, these dashboards focus on highlighting potential relationships between exercise habits and cognitive functions rather than presenting individual variables in isolation.

Therefore, the following analysis built upon observed associations rather than statistical inference.

While an enhanced mood demonstrates the highest average increase among the cognitive functions affected by exercise, the strongest relationships to immediate productivity were found to be linked with increased energy, higher motivation, and reduced stress.

As showcased by the scatterplots on the first dashboard above, where one point represents one student, upward trending lines indicate positive relationships between perceived academic productivity and the aforementioned cognitive functions.

Students who reported enhanced cognitive changes related to these variables following exercise generally also reported higher increased short-term productivity. It should also be noted that some students who experience reduced energy and motivation, perceive impaired short-term productivity as a result from engaging in physical activity.

Although all three variables show some degree of correlation, motivation for academic productivity derived from exercise exhibit the strongest positive association with perceived immediate output.

As participants were provided with multiple options when presenting exercise types included in their routine, a variability in how they appear to affect individuals differently becomes apparent. 

Swimming and JAMBOX record the highest means, however, worth noting is that these two responses were recorded only once. In contrast, weightlifting and cardio showcase a more reliable finding as they are part of the majority of the population's workout habits.

However, the latter two, although reported frequently in the responses, showed significantly varying results in participants perceived productivity levels, and with means of 3.61 and 3.51 can not be justified as key physical activities to enhance cognitive functioning.

While examining frequency, and how it relates to direct academic productivity, no major differences are observed. However, before rejecting the possibility of frequency actually having a direct impact, it is important to consider that it may influence productivity indirectly. 

Factors such as energy, motivation, and stress reduction, all of which demonstrate positive relationships with short-term productivity could certainly be affected by how frequently one engages in physical activity. Therefore, it is worth highlighting even the small changes showcasing the possible advantage of exercising daily, and or seven to nine hours per week.

Exercise intensity shows a similar pattern. While some differences were observed, favouring vigorous intensity, these should be interpreted with caution. Much like frequency, effects of exercise intensity could be highly individual and may depend on factors such as fitness level, workout experience, and recovery capacity. 

It should be pointed out that although some correlations become apparent, these charts are unable to identify causal relationships.  From this data alone, we cannot determine whether exercising is the sole reason for improving short-term productivity, nor what underlying factors contribute to these outcomes.

However, the analysis does allow us to identify associations, which can be useful for generating insights and provide recommendations. These may be particularly relevant for individuals who appear to experience cognitive benefits from physical activity.

## Qualitative Analysis

The qualitative component of five semi-structured interviews included students who regularly engage in physical exercise, ranging from recreational to professional athletes. All participants had prior to the interviews completed the survey.

A thematic analysis approach was used to identify patterns in participants' responses. After familiarising myself with the data through repeated review, key excerpts were manually coded and grouped into broader themes reflecting shared perceptions of exercise, productivity, and cognitive functioning.

Themes derived from the analysis were:
- Exercise is used as a tool for stress relief and mental recovery.
- The perceived quality of exercise sessions influences academic motivation and productivity.
- Mental energy gained from exercise is perceived to enhance short-term productivity.
- The timing of exercise influences perceived cognitive and productivity-related benefits.

The interviews revealed a strong consensus regarding the positive impact of physical exercise on mood, stress reduction, and overall well-being. The majority of the participants linked improved mood to enhanced ability to manage academic tasks and long-term performance. For example, several respondents described exercise as a "tool" for stress relief and mental reset.

However, the perception of short-term productivity effects were mixed. Some participants reported increased energy and motivation immediately after exercise, while others claimed to experience fatigue, particularly after intense workouts, damaging their willingness to conduct academic tasks.

A recurring theme was that workout quality influence academic drive, with satisfying sessions boosting motivation and poor sessions reducing it. 

One respondent mentioned "If I am less satisfied with my workout, my mood gets worse, which leads to decreased willingness to study". Another, responded similarly, claiming that this is a "two-way street", indicating that a satisfying study session, or a well-executed exam, increases the motivation to work out.

Subsequently, a reciprocal relationship emerged between exercise and academic performance, where success in one area positively influences motivation in the other.

In response to exercise's effect on a cognitive function like focus, respondents reported experiencing a sense of mental calm after completing a work out session. As levels of stress hormones tend to decrease with physical activity, leading to enhanced relaxation, it is not uncommon that this will also sharpen one's ability to focus.

One participant claimed that "When being at the gym, i am able to disconnect from academic responsibilities". This psychological break from educational pressure can be explained by the temporary disengagement from stressors. 

While exercise, especially when conducted vigorously could cause physiological and at times even psychological exhaustion, it may simultaneously provide a temporary respite from academic demands, allowing individuals to mentally recover and return with renewed focus and reduced cognitive fatigue.

This raised the question of how exercise affects energy levels and, in turn, how these changes influence short-term productivity. 

Participants repeatedly mentioned exercise as a method to boost both mental and physical energy. However, the consensus was that physical energy mostly bears positive long-term health effects rather than immediate improvements in academic productivity. 

On the other hand, the perception of increased mental energy and its significance for short-term productivity, appeared instant and vital. This perceived boost emerged as a recurring theme throughout the interviews.

However, a related theme highlighted the importance of exercise timing, as participants noted that the effects varied depending on the time of day. When being asked to elaborate about the cognitive benefits gained from exercise, one participant stated, "It depends on what time of the day i work out. If it's in the evening or super early in the morning, i get mentally exhausted and lose any motivation for immediate productivity". 

While timing appeared to be an important factor, there was no universal agreement regarding the optimal time to exercise. Some participants argued that morning workouts were vital for achieving short-term productivity, claiming that exercise early in the day increased alertness, motivation, and focus for academic tasks. 

Others, however, reported experiencing greater cognitive benefits from exercising later in the day, suggesting that the effectiveness of exercise timing may depend on individual preferences and habits.

## Discussion
The descriptive statistics revealed that exercise is generally perceived as beneficial for students' overall well-being. Participants consistently reported improvements in mood, increased energy levels, and reduced stress following physical activity. 

However, the findings relating to cognitive functioning and short-term productivity were considerably more varied. While many respondents agreed that exercise enhanced their focus, motivation, and academic productivity, others reported little to no effect, and some even experienced negative outcomes. 

These findings suggest that although exercise is commonly associated with positive psychological benefits, its direct influence on academic performance is not universally experienced across all students.

Despite overall mood demonstrating the highest average increase among the variables measured, the strongest relationships with short-term productivity were found for enhanced motivation, increased energy, and reduced stress. 

Students who reported greater improvements in these areas generally also reported higher levels of immediate academic productivity. These findings suggest that exercise may contribute to productivity indirectly through its influence on psychological and cognitive states rather than through physical activity alone. 

While exercise types such as swimming and JAMBOX signalise potential for enhancing productivity, these results were gained from a single participant and should be interpreted with caution. On the other hand, calisthenics and weightlifting, which were supported by a larger and more reliable sample, demonstrate a relatively stable yet, not conclusive association with increased productivity.

Variances of increased levels of productivity in relation to frequency and intensity were detected, favouring students who exercise vigorously, daily, seven to nine hours per week, however, these differences were minimal.

Therefore, despite exercise frequency, intensity, and type showcasing some observable patterns, no definitive exercise profile emerged as universally superior.

The qualitative interviews largely reinforced the patterns observed in the quantitative data while also providing possible explanations for the variability present throughout the sample. Participants consistently described exercise as a valuable tool for improving mood, managing stress, and creating a mental break from academic demands. 

Furthermore, the interviews highlighted motivation and mental energy as particularly important factors contributing to immediate productivity. Several respondents explained that exercise increases their willingness to engage with academic tasks, while others emphasised the role of stress reduction in improving concentration and focus. 

At the same time, the interviews demonstrated that the benefits of exercise are not always immediate. Factors such as workout quality, exercise timing, intensity, and individual recovery requirements were repeatedly identified as influencing whether exercise results in enhanced or impaired productivity. These insights help explain why some participants may experience positive outcomes while others don't.

When comparing the analyses, a clear pattern emerges. Both methods support the finding that exercise is generally associated with positive changes in mood, stress reduction, and energy levels. However, the analyses also indicate that the relationship between exercise and short-term productivity may be more complex than initially expected. 

Rather than producing universally positive outcomes, exercise appears to affect individuals differently depending on personal preferences and individual characteristics. 

The descriptive statistics revealed this variability, the relational analysis identified the cognitive factors most closely associated with productivity, and the qualitative findings provided context for understanding why these differences may occur.

## Key Insights
- Exercise was consistently associated with improved mood, reduced stress, and increased energy across the majority of participants.
- Enhanced motivation, increased energy levels, and lower stress demonstrate the strongest relationships with perceived immediate academic productivity.
- The effects of exercise on cognitive functioning and productivity appear beneficial but not universal, with some students reporting neutral or negative effects.
- Factors such as exercise timing, workout quality, and individual preferences could explain the variability observed across the sample.

## Conclusion
The wide variation in perceptions detected in the descriptive statistics indicates a divided sample, with responses ranging from positive to negative cognitive changes following exercise. This highlights that the effects of exercise on short-term productivity is not uniform across the study population.

Although a fairly large portion of the sample reported perceived improvements in immediate productivity following physical activity, the findings suggest that these outcomes may be influenced by a range of individual factors.

Therefore, despite quantitative data revealing similarities, indicating correlations between exercise and cognitive functioning, no definitive conclusion can be drawn to whether exercise is conclusively a direct intervention for reaching higher levels of productivity for all students.

Instead, findings highlight that some individuals may be more susceptible to the productivity related benefits of exercise than others. As such, recommendations should not be uniform, but acknowledge individuals' differences to highlight possible initiatives while recognising that the effectiveness of such approaches may vary.

Overall, the findings suggest that exercise has the potential to positively influence students' cognitive functioning and perceived short-term productivity, particularly when it contributes to increased motivation, focus, and mental energy. However, as the benefits are not universal, they should not be assumed to occur equally across all individuals.

Therefore, while physical activity may represent a valuable strategy for supporting academic performance for some, students may achieve the greatest benefits by identifying exercise routines that align with their own needs and cognitive responses.

## Result
Based on the findings that emerged from the study, it is evident that some students perceive greater cognitive benefits from exercise than others. 

While the findings generally suggest a positive relationship between physical activity, cognitive functioning, and perceived short-term productivity, the perceived effects are not consistent across the entire sample.

As a result, it cannot be concluded that all students will achieve increased short-term productivity by exercising. Therefore, the findings only provide partial support for the hypothesis.

Nonetheless, the study does provide valuable insights into how exercise could be leveraged to support cognitive functioning and academic performance. 

While the findings should not be interpreted as universally applicable, the patterns identified throughout the analysis provide a basis for recommendations that may prove beneficial for some students.

## Recommendations
### Students
**Experiment to discover optimal approach** 
Primarily, students who currently do not experience cognitive benefits following exercise should experiment with different exercise routines in order to identify the approach that best supports their academic productivity. These adjustments could include variations in exercise timing, intensity, frequency, duration, and type of physical activity.

**Use exercise as a tool for preparation** 
Exercise should be viewed not only as a tool for physical health but also as a potential strategy for managing stress, enhancing motivation, and improving focus during periods of academic demand. Students who experience immediate positive cognitive change following exercise may therefore stand to benefit from scheduling their exercise sessions in close proximity to examinations and academic assessments.

**Know your limitations** 
Students experiencing fatigue or reduced productivity following physical activity may benefit from adjusting the timing of their exercise sessions. If cognitive or psychological functions appear impaired immediately following exercise, scheduling workouts further away from periods of academic demand may help reduce potential negative effects on academic performance.

### Universities
**Promote physical activity and increase awareness of potential benefits** 
Universities should promote physical activity as part of a holistic approach to student well-being and academic success. By increasing awareness of the potential cognitive and psychological benefits associated with exercise, students may be encouraged to explore how physical activity can support their learning and academic performance. Such an approach could be leveraged through workshops and seminars.

**Provide recreational sports facilities and initiatives** 
Universities should consider establishing facilities and campus initiatives dedicated to exercise. By providing students with accessible opportunities to engage in physical activity, institutions may help support both student well-being and the cognitive and psychological factors associated with academic performance. 

### Future Research
- Future studies conducted on the subject could benefit from a larger sample size and a longitudinal design, observing a greater number of participants over a longer period of time.
- Studies incorporating objective measures of productivity and cognitive performance may provide a more comprehensive understanding of exercise's effects on academic outcomes.
- Researchers should investigate the influence of exercise timing, workout quality, and individual preferences, as these factors emerged as important themes throughout the qualitative analysis.

