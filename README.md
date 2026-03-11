Dataset Description
Overview
This dataset contains the longitudinal survey data used in the study “The role of context: A longitudinal study of grit, emotions and engagement among rural and urban Chinese senior secondary school EFL learners.” 
The dataset was collected from Chinese senior secondary school students learning English as a foreign language (EFL) across three waves within one academic year. The study investigates the developmental trajectories and within-person dynamics of L2 grit, achievement emotions, and learner engagement, with a particular focus on urban–rural contextual differences.
The final longitudinal sample consists of 289 students, including urban and rural learners, and includes both background variables and multiple psychometric scales measured at three time points. 

Data Structure
Each row represents one participant, and each column represents a variable or questionnaire item.
The dataset contains the following categories of variables:
Background variables
Wave 1 questionnaire items
Wave 2 questionnaire items
Wave 3 questionnaire items
Composite scale variables
Background Variable

Variable	Description
rural	Household registration (hukou) indicating contextual background	0 = urban, 1 = rural
time_learn	Age of onset of English learning	Continuous variable
gender	Student gender	0 = male, 1 = female
familyincome	Self-reported family socioeconomic status	Ordinal scale
These variables were treated as time-invariant covariates in the longitudinal models. 


Longitudinal Questionnaire Items
The dataset includes questionnaire items measuring L2 grit, achievement emotions, and learner engagement at three waves (T1, T2, T3).
The suffixes indicate measurement waves:
_1 = Wave 1
_2 = Wave 2
_3 = Wave 3

L2 Grit (GRIT)
Variables:
g1–g9
Example:
g1_1 g2_1 ... g9_1
g1_2 g2_2 ... g9_2
g1_3 g2_3 ... g9_3
These items measure L2 grit, including:
Perseverance of effort (POE)
Consistency of interest (COI)
The scale is adapted from the Second Language Grit Scale. 

Achievement Emotions
Three emotions were measured:
Foreign Language Anxiety (FLA)
Variables:
a1–a8
Example:
a1_1 ... a8_1
a1_2 ... a8_2
a1_3 ... a8_3
Based on an abridged version of the Foreign Language Anxiety Scale.

Foreign Language Learning Boredom (FLLB)
Variables:
b1–b8
Example:
b1_1 ... b8_1
b1_2 ... b8_2
b1_3 ... b8_3
Measured using the Foreign Language Class Boredom Questionnaire. 

Foreign Language Enjoyment (FLE)
Variables:
e1–e11
Example:
e1_1 ... e11_1
e1_2 ... e11_2
e1_3 ... e11_3
This scale captures students’ enjoyment in language learning contexts.

Learner Engagement
Variables:
eg1–eg21
Example:
eg1_1 ... eg21_1
eg1_2 ... eg21_2
eg1_3 ... eg21_3
These items measure L2 learning engagement across multiple dimensions:
Behavioral engagement
Emotional engagement
Cognitive engagement
Social engagement
The scale was adapted for Chinese EFL classroom contexts. 


Composite Scale Variables

The dataset also includes computed scale scores used in the longitudinal models.

Variable	Description
grit1, grit2, grit3	Composite scores of L2 grit at Waves 1–3
anxiety1, anxiety2, anxiety3	Composite FLA scores
bored1, bored2, bored3	Composite FLLB scores
enjoy1, enjoy2, enjoy3	Composite FLE scores
engage1, engage2, engage3	Composite engagement scores

Composite scores were calculated as the average of the corresponding item scores within each scale before longitudinal modeling. 


Measurement Scale

All questionnaire items were measured using Likert-type scales, where higher scores indicate stronger agreement with the statement or higher levels of the corresponding construct.

Longitudinal Design

The dataset follows a three-wave panel design:

Wave	Time interval
Wave 1	Beginning of academic year
Wave 2	Approximately 3 months later
Wave 3	Approximately 6 months later

This structure allows modeling of:

developmental trajectories (LGCM)

within-person reciprocal dynamics (RI-CLPM) 
