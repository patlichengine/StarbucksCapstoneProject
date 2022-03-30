# Starbucks Data Science Capstone Project
![Udacity Capstone Project](https://miro.medium.com/max/1400/0*4ouIYQzZVZSDIIfT.jpg)
### Starbuck’s Capstone Project Definition
This project represents an experiment. The project uses an experimental data collected over time to discover the different group and the offerings that excite them. It is intended to deploy the concept of Recommendation Engine to get the best offer using the sample population data to make recommendations.
In order to achieve this Starbucks provided simulated data from a certain population from a data collected through an experiment. So we have to follow the direction provided by the data to solve the problem for each individual.


## I. Business Understanding
   This phase consists of a very precise specification of the problem together with methods of evaluating the achievement of the goal.
   - The program used to create the data simulates how people make purchasing    
     decisions and how those decisions are influenced by promotional offers.
   - Each person in the simulation has some hidden traits that influence their   
     purchasing patterns and are associated with their observable traits. People produce various events, including receiving offers, opening offers, and making purchases.
   - As a simplification, there are no explicit products to track. Only the amounts of 
     each transaction or offer are recorded.
   - There are three types of offers that can be sent: buy-one-get-one (BOGO),      
     discount, and informational. In a BOGO offer, a user needs to spend a certain amount to get a reward equal to that threshold amount. In a discount, a user gains a reward equal to a fraction of the amount spent. In an informational offer, there is no reward, but neither is there a requisite amount that the user is expected to spend. Offers can be delivered via multiple channels.

## II. Data Understanding
   To understand the data used in the experiment, it is necessary to explain specific attribute that would allow us classify the data into categorical or qualitative and quantitative data. The data provided for the project were structured as follows:
   - profile.json: Rewards program users (17000 users x 5 fields): gender: 
     (categorical) M, F, O, or null, age: (numeric) missing value encoded as 118, id: (string/hash), became_member_on: (date) format YYYYMMDD, income: (numeric)
   - portfolio.json: Offers sent during 30-day test period (10 offers x 6 fields): 
     reward: (numeric) money awarded for the amount spent, channels: (list) web, email, mobile, social, difficulty: (numeric) money required to be spent to receive rewardduration: (numeric) time for offer to be open, in days, offer_type: (string) bogo, discount, informational, id: (string/hash)
   - transcript.json: Event log (306648 events x 4 fields): person: (string/hash), 
     event: (string) offer received, offer viewed, transaction, offer completed, value: (dictionary) different values depending on event type, offer id: (string/hash) not associated with any “transaction”, amount: (numeric) money spent in “transaction”, reward: (numeric) money gained from “offer completed” and time: (numeric) hours after start of test

### Appreciation
I want to appreciate Udacity and Starbucks for providing the data used for this project.

[Visit my Medium page](https://medium.com/@patlichengine/starbucks-data-science-capstone-project-e52fe32062b9)
