## Survey Data Analysis by AI 

**Research Question/Goal** #AIUXDesign
: Can AI analysis tool reduce the time and procedure required for analysis and find correlations between data?


### AI Tools Researched 

1. Microsoft Survey
   Provide survey functionality with survey response visualization, insight and csv file.
2. Chat GPT4
   GPT4 accept not only words but also files.
3. Other Survey Analysis AI generators
   Used Ask Zia, Survey Vista, Datayaki to analyze the survey dataset(csv file).


### Implementation & Testing

The following steps were completed with each of the AI tools researched:

- Upload survey response dataset (CSV file from other research)
- Generate the analysis and insight
- Compare the result with other analysis

dataset: https://drexel0.sharepoint.com/:x:/r/sites/2023IDM-371/Shared%20Documents/General/Survey%20Data/SafePlate_Survey-Raw-Data.xlsx?d=w368adfabbb3f4027aaf427281531dd0b&csf=1&web=1&e=MZhUMK


### Evaluation of Tools

**Microsoft Survey**

- Provided the visualization of response for each questions.
- Provided insight related between the colunmns.
- Insight provided trend analysis: columns realated by numbers(People who select 'yes' in Q1, also selected 'yes' in Q4).
- No capability for content analysis(People who select 'peanut', also selected 'abc@drexel.edu').
  <div flex-direction="row"> 
<img width="800" alt="w1_microsoft_insigt1" src="https://github.com/DabinLee09/idmT380/assets/146892288/9a0649dc-c247-43eb-98f4-4867c593aab3">
<img width="550" alt="w1_microsoft_insigth" src="https://github.com/DabinLee09/idmT380/assets/146892288/2809a0bf-e96f-4d96-a6c4-7649bf32ef9b">
</div>


**ChatGPT4**

- It used python librarys to analylize the csv dataset.
- Did not Provided the viusalization of response.
- Provides content analysis - relation between the columns and solutions to the finding.
- Up to the question, gpt can generate Persona, UX findings, and painpoints.

**Others**

- Some of the free versions requires data cleaning.
- Provide data visualization. However there are no understanding of the content so the result was not accurate.
- Most of the analysis was data visualization, did not provide  content analysis.

Overall, insight of survey requires understanding of numbers and content. Microsoft can understand the numbers but not the context. So the insight were simple, and user have to cherry pick the analysis. Google survey is similar tools. Personally, google servey was more helpful for the insight. 
Chat GPT is great for other content analysis. This can defianly reduce the load of work on documentaion(insight, persona, ux finding, etc). However this tool was not bulit for the analysis, therefore it was little hard to tracking the questions and answers. Also if you ask for data visualization it provide python code.
Other generators, it is good for visualizaion. However depends on the platform it requires data cleaning. Which felt very annoying process. For the person who can use python, I would reccomend analysing with python and get the visuals. 


### Key Challenges

- AI's capabilities are all different
- Hard to find AIs that provide insight
- Hard to find AIs that accept CSV file without data cleaning


### Conclusion:

To get a insight from analysis, AI need understanding in numbers and context. Throughout the research only chatGPT has been used from insight derivation to other UX research. Therefore collaborating with GPT can reduce your effort and moreover it can find the things you missed.
