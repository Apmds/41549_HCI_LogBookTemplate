[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors

| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| BookTrade         | Mobile app to trade books with a Tinder-like UI. | [Analysis](<Competitor Analysis BookTrade.md>) |
| Bunz | Trading platform for anyhting. | [Analysis](<Competitor Analysis Bunz.md>) |


## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]


#### Individual Evaluations


- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Something wrong | 3            | 1        | 0        | Something could be done to the button to... |
| Another thing   | 4            | 3        | 4        | Other thing to recommend                    |
| ...             |              |          |          |                                             |



---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Buyng a grammar book** | Search for available grammar books     |
|                             | Identify a specific book from the list |
|                             | Add the selected book to the cart      |
|                             | Proceeed to checkout                   |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Booking a train ticket** | Select departure and destination cities |
|                               | Choose travel date and time             |
|                               | Pick a seat (if applicable)             |
|                               | Confirm booking and make payment        |


#### Results

Task: [This is the task]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Step 1 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | [Step 2 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | [Step 3 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| ...    | [Further steps]        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |



---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

<!-- To talk with the users from the set of people that would benefit from using our application (active book readers) we decided to ask them what would be the most important features to implement so that they could get the most out of the application.

The main goal of the interviews was to get a solid feedback on what other options did well and also what they lacked on, which is arguably more important since we can take advantage of that to be a serious competitor in the market.

### Some of the questions included:
### General usage and experience:
This section is mainly used to interact with the user to understand the context in which they would feel like using the app.

- How often would you use the app?
- What do you like the most about the app?
- What frustrates you the most when using the app?

### Matching and swipping experience:
The goal of the following questions is to see if the swipping system is actually useful or too abstract.

- How do you feel using the swiping system?
- Do you feel like the first suggestions are books of your interests / books that you would read in the future?
- What kind of filters would you like to have when searching for a new book (Pages, location of the owner, author or genre for example)?

### Chatting experience and trading proccess:
Used to understand the difficulties of the user to finish the trade as fast as possible after matching with the other book.

- How hard is it to arrange a meeting to exchange the books? What implementations could decrease its difficulty?
- What could stop you from completing a book trade after matching with another book?
- What options would you like to have access to while talking to the other user you matched with? (For example sending photos to show the state of the book)

### Functionality: -->

# Interview questions 
- Tell me about your free time. What do you like to do?
- Do you usually read books?
- How do you discover new books to read? / How do you usually get new books?
- Tell me about the last time you read a book.
- ~~Do you collect books, or are you mainly interested in reading new ones?~~
- When you finish reading a book, what do you do with it? Do you keep it if you want to read again in the future?
- If you had extra books at home, would you be more likely to sell, donate, or trade them? Why?
- Have you ever traded books with others before? 
	- Yes:
		- How do you usually find people to trade books with?
		- Can you walk me through the last time you did it?
		- How did you do it?
			- If response talks about a trading group(facebook, etc):
				- Was it simple to find the group?
				- How did you know the other person was trustworthy?
				- Was the book traded to you in a worse condition than what was told by the other person?
			- If response talks about a trading app:
				- How was the experience?
				- How can the experience be better?
		- What motivates you to trade books instead of buying or borrowing them?
		- What types of books do you usually trade?
		- Have you faced any challenges when trying to trade books with others?
		- What concerns do you have when trading books?
		- What's the biggest frustration you've had when trying to trade a book?
		- When trading books, are you looking for a specific book, or do you find one in a specific niche you enjoy?
		- What makes a book trade feel successful to you?
		
	- No:
		- Do you ever re-read books?
		- Have you ever thought about trading books before? Why or why not?
		- What's the biggest reason you haven't traded books before?
		- What would make you hesitant to trade a book with someone else?
		- Would you feel confortable trading a book with strangers, or would you prefer only friends?
		- What could make you want to trade books?


- Do you feel existing platforms offer enough security and accountability for fair trades?
- Would you trust an app to suggest book trades for you based on your interests, or do you prefer to pick them manually?
- If you were unsure about a trade, what extra info would help you decide?
- Do you think it's better to trade books in person with others or send them?
- Would you be open to shipping books, or do you prefer only local trades? Why?
- What would make you recommend a book trading app to a friend?


[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
