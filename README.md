# Data Analysis Project: Leveraging data analysis to drive business improvement and boost profits

As a student who is eager to develop my data analysis abilities and make a tangible impact, I approached The Track Fitness Club, a struggling gymnasium located in my hometown, and convinced the owner to allow me to comb through the business's raw data, I analyzed various aspects of the business and identified underlying problems that may be hurting the business's profit-making capacity. I then developed data-driven recommendations for improvement and presented these findings in a final report.

The proposed solutions focus on increasing profits and address specific areas of the business identified through the analysis. I am proud to have been able to help The Track Fitness Club identify areas for improvement and develop strategies to increase profits.

# Executive summary

The Track fitness gym, located in Chandrapur, Maharashtra, has struggled with issues that have caused fluctuations in revenue and made it difficult for the gym to achieve its financial goals. This data analysis project aims to identify the root causes of these issues and provide recommendations for improvement through analysis of data on membership demographics, usage patterns, and client feedback. The project aims to provide the gym owner with valuable insights and recommendations for improving retention and increasing revenue.

 # Data

 "The data for this analysis was obtained from the gym's point of sale management software. I approached the reception desk, explained the situation to the staff, and set up a meeting with the business owner. I was able to convince the owner to give me access to the data for a period of 8 months, which included information about invoices generated, client personal information, and entry-exit digital logs. There were a total of three files collected: 
 1. 'invoice entries raw.xlsx', which contained digital entries for every invoice generated (1014 records with 17 features)
 2. 'PIPO raw.xlsx', (Punch-In-Punch Out) which included digital logs of every successful/unsuccessful attempt to enter the workout space (about 32,000 recorded observations with 3 columns)
 3. 'PII raw.xlsx', (Personally Identifiabe Information) which included personal information for clients (495 observations with 6 features). 
 
 The raw data was preprocessed using Microsoft Excel and Python as necessary. The data cleaning process included adding and removing features as needed, removing records that were not relevant to the analysis, and changing data types.


 # Navigating Turbulent Waters: The Current Challenges Facing Our Fitness business

After organizing the data, I created visualizations to highlight key markers like monthly revenue, new clients per month, and busiest time slots for workouts. This revealed two significant issues.

1. poor client retention rate
2. overcrowding at peak hours. 

The client retention rate was a concern because it showed that the gym was losing a significant number of clients over time. The overcrowding issue was also problematic because it could lead to reduced customer satisfaction and even safety concerns. To address these issues, I set out to find a practical solution that I could easily pitch to the business owner. My goal was to find a simple yet effective solution to improve retention and manage capacity at the gym.

# "Effective strategies for improving retention and managing overcrowding"

1. To improve retention , I compiled a list of "High AR clients" ( Adherence Rate) - individuals who have demonstrated a high level of commitment to the gym through consistent use of facilities over a period of at least six months. By increasing the number of clients on this list, we can work towards improving retention rates. To do this, we can examine the personally identifiable information (PII.xlsx) of these high AR clients to identify differences between them and other clients. 

2. To address overcrowding at the gym, I identified clients with flexible workout schedule who could be encouraged to visit during less popular hours through personalized offers. By encouraging these individuals to work out during less crowded times, we can help to alleviate congestion during peak hours and improve the overall customer experience. These flexible clients can be identified by analyzing the PIPO.xlsx files, which contain digital entry exit logs of every client

# "Results"

After all the heavy lifting I was left with two lists namely "high AR client list" and "flexible client list", I put two and two together and came up with the following results:

1. 19% of the total clients were registered with personal trainers through the history of the 12 month data collection, whereas 69% of the 35 high AR clients  were registered with the personal trainers. It is evident that the difference between a High AR client and other clients was that most of them opted for personal trainers.

2. There are about 22% female clients registered with the gym, The % of females dropped to 14% within the high AR client list, This can be th result of not having a female instructor at the gym.

3. out of 494 unique clients registered with the gym, 97 clients were flexible with their workout schedules through out their subscription validity. out of the 97 flexible clients 37 clients had an active subscription along with inclination towards the afternoon slot.meaning this 37 clients preferred afternoon slot but somehow ocasionally took part in the congestion at peak hours.

4. The business offered a monsoon discount in the month of june, the discount only lead to more overcrowding, no significant increase in revenue/profit and the clients who were attracted with the offers didnt stick around so much.

5. I have ran a simulation of all the digital logs where i asumed that all 97 flexible clients strictly visited the gym in the afternoon slot, the overcrowding reduced by 15%

# Recommendations

	The gym needs to make efforts towards getting a personal trainer hired by the client at the time of client registration, when a new client enters the gym, they can be convinced to hire a personal trainer, hence my recommendation to the business will be to run a subscription + personal training offer rather than investing in monsoon or summer offers which are a waste of capital.

	To avoid overcrowding at peak hours the business needs to send an SMS to all the special flexible clients that I have identified thus alerting them of the special personalized offers exclusively made available for them

	Solving The Overcrowding issue is a marathon and not a sprint, a one-time solution is not enough to deal with this problem, active flexible clients had to be identified and contacted every month for as long as any significant results are seen.

# need more ??

To get a graphical representation of the business and an overall idea about the analysis, refer to the ppt called "track case study.ppt" in the repo.

To gain an indepth understanding of the 3 code files, take a look at "The Track Fitness Club Case Memo - 3" inside the case study folder in the repo. Before running any of the code files make sure the 3 files inside the "clean data" folder are in the same directory as the code files.

there 3 python notebook files with names clear enough to dictate what they do.
