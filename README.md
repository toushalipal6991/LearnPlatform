# LearnPlatform COVID-19 Impact on Digital Learning
One of the very recent Kaggle Competitions, which was hosted by the Digital Learning Platform **LearnPlatform**.

## :point_down:Notebook for Proper Understanding of the Analysis

[Notebook](https://colab.research.google.com/drive/1hwnhJwNnZMoh5lvxIuNPY2_V7It-STI5?usp=sharing)

## Aim of this Project
- This project aims to analyze the impact of COVID-19 upon Digital Learning.
- It also aims to analyse whether & how has COVID-19 impacted the access of diital learning  across different race/ethnicity/district demographics/broadband access etc.

## Datasets
- Source :arrow_right: [Kaggle](https://www.kaggle.com/c/learnplatform-covid19-impact-on-digital-learning/overview)
- Pre-processing and Data Cleaning :arrow_right: All data files were cleaned and NaN values were dealt.

## :memo: Some important Conclusions Drawn
- All the places where the percentage of black/hispanic students is high, i.e. the percentage of Black/Hispanic students lie in the range [0.8,1], have a higher percentage of at-least 1 page-load event of a given product and on a single day.
- mean engagement_index (Total page-load events per one thousand students of a given product and on a given day) drastically reduced in the months of June and July in every type of locality. And this is expected, because, COVID-19 hit the most in these months and the rise of COVID-19 cases took a steep curve starting from May-June-July.
- The engegment_index started rising in the months after June-July, as compared to what they were, before June-July --> indicating that the quest of Digtal Learning and Usage of Digital learning platforms started rising post and during COVID after the dust started settling down.
- COVID-19 has influcenced the online and distance learning to such an extent that, this trend of high dependency and interest on it is pretty likely to continue in future as well (pandemic or not).
- North Dakota has the highest county_connections_ratio (`ratio` (residential fixed high-speed connections over 200 kbps in at least one direction/households) 
- Districts of New York, Indiana and Illinois have the highest Percentage of students in the districts eligible for free or reduced-price lunch (i.e. in the range [0.8-1]).
- Highest amount of Per-pupil total expenditure --> [32000-34000] has been done in districts of Rural areas.
- usage of LC-Digital Learning Platforms was high, all throughout 2020.
- Google LLC is the most used/favoured Company all throughout the states/districts/schools

## :file_folder: Libraries Used
:crayon: matplotlib :crayon: seaborn :crayon: numpy :crayon: pandas :crayon: prettytable :crayon: bokeh

## :hammer_and_wrench: :toolbox: Tools and Softwares Used
- Jupyter Notebook
