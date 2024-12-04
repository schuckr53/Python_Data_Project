# Introduction
My journey with Data Analytics continues with an education on Python, a skill that had been highlighted in my SQL project to understand what competencies best serve would-be data analysts as they break into the job market.

# Background
The results of my SQL project highlighted a wide range of technical skills that would serve any aspiring Data Analyst, both in their current role and if they wished to pursue new opportunities in the data industry. Alongside SQL, Python was counted in 90% of those roles which had the highest-paying salaries. Python was also shown to be in high demand for openings that required coding expertise (alongside SQL and R); the data job market values candidates that can claim proficiency with Python as part of their toolkit, which makes sense as this language can navigate data sets and produce visualizations all in one place.

The merit in becoming at least familiar with Python is clear: companies want individuals who can utilize this powerful language to gleam insights from data and share those insights with others, and this pursuit is becoming more commonplace in the data job market. 

With that understood, I began my education on Python using Luke Barousse's [Python for Data Analytics course](https://www.lukebarousse.com/python). Both the training and practice provided here are incredibly efficient, as Luke offers a valid data set he cultivated with Python to explore the data job market.

### The project works through the following questions, drawn from the data provided:

1. What are the most demanded skills for the top 3 most popular data roles?
2. What are the trends of in-demand skills for Data Analysts?
3. What are the compensation ranges for different data jobs and skills?
4. What is the most optimal skill to learn for Data Analysts? (High Demand, High Paying)

# Tools I Used
I learned to use the following tools to analyze and manipulate the data for visualization, as part of this course and project:

- **Python**: the backbone of my project - this is the coding language I became familiar with as a result of working through Luke's course. The libraries I used were geared towards data analytics and visualization, honing in on valuable insights gleamed from the dataset and producing different perspectives through complimentary charts.
- **Python Libraries**: Pandas, Matplotlib, and Seaborn were the libraries that I used in manipulating and visualizing the data available via Luke's course. 
- **VS Code**: the workplace for writing my Python scripts and troubleshooting errors in order to refine my analysis of the available data Luke provided. I was able to utilize virtual environments on a local machine to contain libraries and modules.
- **Jupyter Notebooks**: the environment used between Google Colab and VS code I composed and troubleshot my Python code - I became familiar with both local and cloud notebook usage as well as their respective benefits and drawbacks.
- **Git & GitHub**: version control tools that allowed for sharing my work and analysis, providing the ability for further collaboration with friends and the "data nerd" community at large.

# The Analysis
Each stage of this project is intended to answer different questions that are foundational to understand the data job market and its appeal to candidates. Python is used to manipulate data provided through Luke's course, then drill down on specifics, and finally produce visualizations to gleam insights. My full code compilations are available in the associated folders of this repository (for the sake of concision in this section).The goals are as follows:

### 1. What are the most demanded skills for the top 3 most popular data roles in the US?
I focused on the skills most called for in "Data Analysts", "Data Engineers", and "Data Scientists", specifically in the United States:

![Counts of Top Skills in Job Postings](https://github.com/user-attachments/assets/4d6ee08c-fc27-4b2d-9bf7-a47fa202a9f4)

- Initially, this shows how each of these roles calls for similar skills: Analysts and Engineers both need SQL to clean and review the data perhaps already available in databases (privately maintained or publicly available for use) and some means to manipulate it into more digestible formats (both Excel and Python have the ability to produce visualizations). Python provides Engineers and Scientists a flexible tool to build, maintain, refine, and conceptualize their data. It lets Scientists make data-backed decisions and showcase their reasoning while Engineers employ this language in their construction and maintenance of data infrastructure.

- A more interesting take-away is the gap to be found between each skill in their respective jobs. Analyst openings have a noticeable drop-off between their #1 requested skill, SQL, and its runner-up, Excel. Both SQL and Python are comparable in their request counts in the Data Engineer field, but its #3 skill, AWS, comes in after a ~35% decline in demand. Data Scientists have a severe drop between the #1 and #2 skills Python and SQL, respectively, indicating a need for specialization in Python before reliance on a wider toolkit.

As the initial plot shows, each role may have a greater need to use specialized skills on their own or the ability to use just a couple in a complimentary way. The counts of each role and their underlying skills can therefore be used to estimate the probability of seeing these skills in the US data job market:

![Probability of Requested Skills in US Job Postings](https://github.com/user-attachments/assets/bbf59fa3-80b8-49b0-99cb-1091686111f5)

Showcasing these probabilities can give any aspiring candidate a better understanding of what discipline they may already be qualified for or even what they may want to develop to make a career change. At the very least, I can tell from my own desire to become a data analyst that I'll need to prioritize SQL alongside Excel in order to bolster my chances. Tableau and Python, while very helpful in their own rights, shouldn't take immediate precedence if Analyst work is my goal.

### 2. What are the trends of in-demand skills for Data Analysts?
Focus on the top 5 skills for Data Analysts and see their respective trends over the course of a year:

![Trending Skills for US Data Analysts](https://github.com/user-attachments/assets/d110b742-823f-44e1-a8ad-0868c30427fa)

Taking a look at the top 5 skills demanded in the US job market for Data Analysts, we see that there are fluctuations in their appeal throughout the course of a year (2023).
- **SQL**: As the top skill, SQL maintains its appeal throughout the year by a sizeable margin compared to the #2 skill. Trending downward overall between January through December, though, may indicate a desire from employers to have candidates supplement SQL with other skills. Perhaps pairing SQL with a visualization or  tool would be prudent, as we see Python and Excel enjoying a sharp uptick by the end of the year alongside SQL's slight decline.
- **Excel**: Excel experiences a stable probability of inclusion at ~43% through the first half of the year before noticeable flux starting in June. This incline, plateau, extended dip, then climb would be worth exploring further, but overall: Excel maintains its second-most probable inclusion throughout the year without any competition.
- **Tableau**: Tableau undergoes an overall decline that results in it being overtaken by Python at year's end for third-most probable inclusion in data analyst job postings. This is the only instance of one of these top 5 skills being beaten out in 2023, so it's important to recognize what the job market calls for at any given time - we can't assume these skills will remain in a static level of demand over the course of time.
- **Python**: Python experienced a mostly upward movement in demand over the course of 2023, eventually overtaking Tableau as the third-most trending skill in data analyst job postings. Having started out in 4th place, this coding language saw a noticeable uptick in the last 2 months of the year alongside Excel in an almost identical fashion.
- **Power BI**: Power BI remained the fifth-most probable skill to appear in data analyst job postings without much final change in this value by year's end. Despite this lack of overall change, it still retains an approximate 20% chance of appearing in data analyst roles, making it an important skill to gain proficiency with down the road.

## 3. What are the compensation ranges for different data jobs and skills?
Outline the salary ranges for titled data jobs, then narrow in the top 10 highest-paid and in-demand skills for Data Analysts by displaying associated median salaries.

![Data Jobs Salary Distribution in the United States](https://github.com/user-attachments/assets/53dde20e-3831-429d-ba48-22b3f081a440)

- This box chart displays the distribution of posted wages for each of the types of data jobs I've been showcasing so far, providing a look at the median and outliers to consider. Another layer to this visualization is the inclusion of senior-level roles with their respective counterparts - a side-by-side comparison can be made to understand compensation differences at different levels of the same role. The results are interesting: senior roles are shown to have higher median salaries than their standard version, but both the Scientist and Engineer (and their senior levels) outmatch the senior data analyst role's median salary. This data indicates that it, perhaps, pays better out of the gate to enter into data scientist and data engineer roles rather than a data analyst and even senior analyst position.

- A secondary note, though, is that all of these positions have median salaries at least approaching if not exceeding $100,000 annual salaries, which confirms data careers are very attractive when recalling the 2023 median individual salary was $59,540 (ref. [Bureau of Labor Statistics](https://www.bls.gov/opub/ted/2024/median-weekly-earnings-of-full-time-workers-were-1145-in-the-fourth-quarter-of-2023.htm)).

With this in mind, I move into the breakdown of skill associations with median salaries for data analysts:

![Skill Demand vs. Compensation for Data Analysts](https://github.com/user-attachments/assets/9d484229-bcaa-4370-9891-83971e915096)

- The contrast in these two plots is clear when understanding how those top 10 highest-paid skills are generally more specialized than the top 10 in-demand skills for data analysts. Those highest paid skills are shown to be approaching the $200,000 median salary mark - analysts can anticipate higher levels of skill in niche tools not commonly found in the market result in a greater level of pay. These top-paid skills are spread between cloud-based infrastructure, coding subset languages / libraries, and machine learning / AI tools. 

- The top 10 in-demand skills for data analysts are associated with a tighter range for median salaries, highlighting the merit in a multi-discipline toolkit as a candidate. Coding languages like Python, R, and SQL are joined by more common office software like Power BI, PowerPoint, Excel, and Microsoft Word. Python tops this list of demand while aligning with a median annual salary close to $100,000, suggesting data analysts would be well-served in becoming proficient with this tool eventually.

## 4. What is the most optimal skill to learn for Data Analysts?
Identify likelihood of skills to be included in US job postings, then reference this value with the median salaries. Group skills by technology type to check prevalence in US data analyst job market.

![Optimal Skills for Data Analysts](https://github.com/user-attachments/assets/b4f3cf88-0fd0-40ce-bc2a-95a334075c6c)

- High-paying and high-demand skills can be identified by the plot's values, showing Python and SQL far along the bars of median salary and prevalence in Analyst roles. SQL stands out by far as the highest desired skill that is tied to a ~$91,000 salary while Python has a ~34% prevalence in the Analyst job market, but is the highest-paying skill of them all with ties to a ~$97,000 median salary.
- The technology grouping shows that programming (Python, SQL, R, Go, SaS) and analyst tools (Tableau, Power BI, PowerPoint, Excel, Word) should be considered strongly when setting out to apply for data analyst roles, with an emphasis on the individual skills of Python, Tableau, SQL, and Excel. High pay and high demand reveal what employers want when reviewing applicants' resumes and skillsets.

# Data Insights
1. **Coding is Key**: SQL remains the top skill to cultivate when looking to secure data analysts and associated positions, but it's not the only programming language deserving of attention. Python and R also make an appearance in the counts of top skills included with job postings between data analysts, data engineers, and data scientists, revealing that candidates should understand at least the basics of more than one coding language. Both SQL and Python are clear favorites for the data job market across the board, so proficiency with these skills would be prudent.
2. **Monitor the Trends**: Staying grounded in what abilities the job market calls for is essential; candidates need to regularly check in on what skills potential employers value, seeing as they can change over the course of time. Like we saw with Tableau being overtaken by Python at the end of 2023, the same openings we see for data analyst may experience shifts in necessary abilities should the roles themselves be adjusted for particular tasks.
3. **Compensation is Substantial**: Data jobs, ranging from Analysts, Engineers, and Scientists (alongside their senior counterparts), typically enjoy a substantial base salary when we compare to the US's median individual salary ($59,540, ref. [Bureau of Labor Statistics](https://www.bls.gov/opub/ted/2024/median-weekly-earnings-of-full-time-workers-were-1145-in-the-fourth-quarter-of-2023.htm)). Even standard and senior data analysts, who reside at the bottom of the job index when ranked against the other referenced positions, see strong potential for high earnings. The one wrinkle, though, is understanding that a senior-level role doesn't necessarily guarantee higher compensation than a lower-level role - we see that senior data analysts reside below Engineer and Scientists postings at the standard and senior levels by median yearly salaries.
4. **Specialized vs. Optimal Skills**: Niche specialties including cloud-based software and machine learning / AI are certainly attractive when considering their associated compensation - the top 3 highest paying data analyst salaries included some of these skills and easily outpaced $175,000/year. When measured against the prevalence of certain skills in the job market, however, practicality calls for data analysts to prioritize programming languages like SQL and Python. SQL can be found in almost 60% of the data analyst roles out there while Python is found in those openings with the highest median salaries at ~$98,000/year. Entry-level data analyst candidates would be best served in pursuing these 2 skills before turning attention to those niche abilities during their job search.

# Conclusions

## What I Learned
I finish this course and project having gained a familiarity in coding with Python, both in manipulating data sets and creating resulting visualizations. The two halves of this proficiency will no doubt be invaluable in my pursuit of data analyst openings having also achieved the following:
- **Understanding of Python** - this coding language adds complexity to my toolkit alongside SQL, allowing me to perform more comprehensive analyses. I can now comfortably write Python scripts that deal with manipulating data, refining my queries, and creating visualizations that showcase the insights I can share with others.
- **Coding Library Reference** - using Pandas, Matplotlib, and Seaborn as supplemental tools for this course introduced me to the different instruments present within coding languages, starting with Python. Employing each library for my project required me to refer to each one's documentation and I now understand each one to use in the future.
- **Continued Analysis of Data Jobs** - the opportunity to build off of my SQL project provides me a more comprehensive sense of the job market for data analysts and their related roles. The insights I gained through Luke's data set has outlined where else I can go while on this journey to improve my technical skill set and keep an awareness of what employers are looking for in candidates.

## My Take-away
Luke's Python for Data Analytics course and the associated project have given me another palpable skill to add to my professional tool kit. Python and its ability to analyze data relevant to my own career present an exciting opportunity to dive deeper into the world of data science, all while building a portfolio that showcases the work and results of my efforts. The fruits of my labor in this course are made even more satisfying with the triumph over coding bugs, virtual environment set-ups, and troubleshooting across local and cloud environments (all in a day's work, as I understanding coding to be). The experience has been incredibly rewarding as I continue to develop my technical skill set, presenting my findings in a style that can hopefully help others as well as myself.

