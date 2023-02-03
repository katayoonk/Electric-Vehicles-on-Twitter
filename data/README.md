# Project 1: Standardized Test Analysis

## Overview
The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry.

## Problem Statement
The new format for the SAT was released in March 2016. Since then, levels of participation in multiple states have changed with varying legislative decisions. This project aims to explore trends in SAT and ACT participation for the years 2017-2019 and seeks to identify states that have decreasing SAT participation rates.

## Datasets
* [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))

## Data Dictionary

|__Feature__|__Type__|__Dataset__|__Description__|
|---|---|---|---|
|__state__|object|ACT/SAT|Name of the the states|
|act_particitation_2017|float|ACT|percentage of participation in ACT in 2017|
|act_particitation_2018|float|ACT|percentage of participation in ACT in 2018|
|act_particitation_2019|float|ACT|percentage of participation in ACT in 2019|
|sat_particitation_2017|float|SAT|percentage of participation in SAT in 2017|
|sat_particitation_2018|float|SAT|percentage of participation in SAT in 2018|
|sat_particitation_2019|float|SAT|percentage of participation in SAT in 2019|
|states_geo|object|ACT/SAT|'E': eastern state, 'W': western state, 'C': central state|
 
## Brief summary of Analysis
- Which states have the highest and lowest participation rates for the 2017, 2019, or 2019 SAT and ACT?

|__Year__|__State of Minimum ACT Participation__|__State of Maximum ACT Participation__|
|---|---|---|
|2017|Maine|Alabama|
|2018|Maine|Alabama|
|2019|Maine|Alabama|

|__Year__|__State of Minimum SAT Participation__|__State of Maximum SAT Participation__|
|---|---|---|
|2017|    Iowa    |Connecticut|
|2018|North Dakota|Colorado|
|2019|North Dakota|Colorado|

- Which states have decreasing SAT participation rates?

|State|2017|2018|2019|
|---|---|---|---|
|Nevada|0.26|0.23|0.2|


- Which states have decreasing SAT participation rates?

23 states including: California, Colorado, Connecticut, Delaware, Florida, etc.

- Mean of ACT participation rate for eastern, western and central sttaes:

|group|2017|2018|2019|
|---|---|---|---|
|C|0.84|0.80|0.77|
|E|0.40|0.37|0.32|
|W|0.68|0.65|0.64|

- Mean of SAT participation rate for eastern, western and central sttaes:

|group|2017|2018|2019|
|---|---|---|---|
|C|0.14|0.24|0.25|
|E|0.71|0.75|0.83|
|W|0.35|0.38|0.38|
