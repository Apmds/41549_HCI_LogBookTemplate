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

We decided to analyze the Bunz app, despite it not having the goal of trading only books. This stems from the fact that BookTrade is not available at any app store, and the only source of information from that application is a video on their website.

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

We identified the 3 most important tasks that Bunz performs and divided them into subtasks, analysing each subtask from the perspective of a new user and determining if they would know how to perform that subtask to complete the overall task.

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]

The most important tasks in a item trading app are all related to performing a trade. As it stands, the most relevant tasks are: "Creating a new post", "Searching for an item" and "Messaging another user".

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Creating a new post**  | Click on the '+' button.               |
|                             | Select "Post" from the options.        |
|                             | Fill out the post details.             |
|                             | Press the "Post" button.               |


| Task                          | Subtasks                                	    |
| ----------------------------- | --------------------------------------------- |
| **2. Searching for an item**  | Enter the search tab (press the button).      |
|                               | Write on the search bar.                      |
|                               | Press the magnifying glass button on the bar. |
|                               | Insert filters on the search.                 |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **3. Messaging another user** | Select a post.                          |
|                               | Press the "Start the chat" button.      |
|                               | Type a message in the text input.       |
|                               | Press "Send".                           |

#### Results

### Task: Creating a new post

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Click on the '+' button. | Yes | The button has a different color from the rest and has a symbol indicating the action. | Yes | A list of creatable options show up uppon clicking. | Yes |  |  |
| 2      | Select "Post" from the options. | Yes | The option is clearly visible and has a label indicating it is a Post. | Yes | The post creation page appears when pressing the button. | Yes |  |  |
| 3      | Fill out the post details. | Yes | Everywhere that information can be inputted in contains a clear label/description. | Yes and No | The information shows up in the fields and the images show the loading progress, but when selecting the meeting spot, only a blank window shows up. | No | Fix the location selecting. |  |
| 4     | Press the "Post" button. | Yes | The button lights up after filing every mandatory field. | Yes | A message confirming the post was created shows up. | Yes |  |  |


### Task: Searching for an item

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Enter the search tab (press the button). | Yes | The button is a magnifying glass symbol and is placed by the other "main" buttons. | Yes | The menu changes to the "Explore" section and the button changes to a brighter color. | Yes |  |  |
| 2      | Write on the search bar. | Yes | The search bar is proeminent at the top, with text indicating its function. | Yes | The text updates as the user is typing. | Yes |  |  |
| 4      | Press the magnifying glass button on the bar. | Yes | The button is positioned by the text. | Yes | The keyboard goes away and the results appear. | Yes |  |  |
| 3      | Insert filters on the search. | Yes | The button is right by the search bar. | Yes | A menu for inputting filters shows up and all fields are correctly labeled. | Yes |  |  |


### Task: Messaging another user

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Select a post. | Yes | Every post shows its most important details. | Yes | A bar at the top appears, showing the loading progression. | Yes |  |  |
| 2      | Press the "Start the chat" button. | Yes | The button is big and has a highlight color. | Yes | The button shows a loading icon when clicked and the chat interface after loading. | Yes |  |  |
| 3      | Type a message in the text input. | Yes | The text input is already selected and has placeholder text. | Yes | A "Send" button becomes visible and the text updates as the user is typing. | Yes | Make the text input take up the full phone width when not writing, instead of just half. |  |
| 4      | Press "Send". | Yes | The button is very visible and has a good icon. | Yes | The written message shows up in the full conversation. | Yes |  |  |


---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

# Interview questions 
- Tell me about your free time. What do you like to do?
- Do you usually read books?
- How do you discover new books to read? / How do you usually get new books?
- Tell me about the last time you read a book.
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
