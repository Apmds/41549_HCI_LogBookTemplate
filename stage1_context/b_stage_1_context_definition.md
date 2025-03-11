[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



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
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->

- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

<!-->	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.-->

| **Issue**       | Expert 1 | Expert 2 | Expert 3 | Recommendations                                 |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Select location when creating a post. | 2 | 4 | 4 | Display some type of indicator to the user know if the app is running or not. |
| There is no quick way to see a user's rating. | 3 | 2 | 2 | Add the respective rating to the user profile. |
| Category selection. | 2 | 2 | 2 | Choose the main categories first and then will the subcategories appear. |
| No clear customer support. | 4 | 4 | 3 | Add a button with an option to contact the help team. |
| Some notifications can go unnoticed (such as the trading confirmation). | 1 | 1 | 1 | Create a bigger presentation to confirm a trade, with more color highlights. |
| Some terms on the app might be unfamiliar with new users. | 2 | 1 | 3 | Create a simple tutorial on the main things of the app. |
| There is not a clear option to undo actions fast. | 3 | 3 | 3 | Add useful buttons. |
| Some buttons have the same style in different places for different purposes. | 3 | 3 | 2 | Use different buttons. | 
| Item exclusion doesn't show a clear warning, increasing the probability of removing a product by accident. | 3 | 4 | 3 | Add warnings. |
| Some important commands are held in hidden menus. | 2 | 2 | 2 | Organize the interface to give more options without searching. |
| Excessive use of white space, even though it shows the clear options available it gets boring. | 1 | 1 | 1 | Use light non-white colors. |
| When there are no available trading spots the system gives no information or error. | 4 | 4 | 4 | Show error or warning information to give user context. |
| Documentation could be more interactive. | 1 | 1 | 1 | Implement tutorials in video. |
| No feedback when trying to add interests. | 2 | 2 | 2 | Make the button darker on press/hold. |
| Blurry screen on expertise/"level" screen. | 2 | 2 | 3 | Remove the blur. |
| No indication of not being able to interact with the other levels on the expertise screen. | 1 | 1 | 1 | Grey out the other levels. |
| Terms like ISO and BTZ are used, but not explained directly. | 3 | 3 | 3 | Give an explanation of those terms when creating an account / Use more conventional names. |
| The use of volcanoes to show the level of expertise a user has does not make sense. | 2 | 3 | 3 | Use more common terms to describe the expertise of a user. |
| There is no way to delete a chat if one is started by accident. | 2 | 3 | 2 | Give that option on the chat's option menu. |
| Creating an ISO and a post has almost no difference in the UI. | 3 | 3 | 3 | Descriptions of the elements that differ, showing their differences clearly. |
| Logging out is instant. | 2 | 1 | 2 | Show a pop-up asking if the user is sure they want to log out. |
| First element in home page is a square button that displays an irrelevant message. | 1 | 2 | 3 | Place after the rest of the other squares so it does not take away from their information. |

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
| 3      | Fill out the post details. | Yes | Everywhere that information can be inputted in contains a clear label/description. | Yes* | The information shows up in the fields and the images show the loading progress, but when selecting the meeting spot, only a blank window shows up. | No | Fix the location selecting. |  |
| 4     | Press the "Post" button. | No | The button does not light up because a meeting stop can't be selected. | No | There is no way to progress. | No |  |  |


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

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

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
| 24-02-2025 | Gabriela / student      | Never traded books; Never found anyone with the same literary style | [📄 Notes](interviews/interview-Gabriela.md) |     |
| 24-02-2025 | Subject1(Anonymous) / public employee | Open to trading old books; Does not look for specific books | [📄 Notes](interviews/interview-Subject1.md) |     |
| 24-02-2025 | Rui / student | Open to trading books; Would trade books if he liked the app | [📄 Notes](interviews/interview-Rui.md) |     |

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

### SWOT Analysis

<!--
| SWOT Element  | HCI focus                  | Example in UX/UI             |
| ------------- | -------------------------- | ---------------------------- |
| Strengths     |                            |                              |
| Weaknesses    |                            |                              |
| Opportunities |                            |                              |
| Threats       |                            |                              |
-->

#### Strengths:

 - BTZ is a good idea for an in-app currency, since it cannot be used outside of the app.
 - Encourages the reuse of items not needed anymore by the user, reducing waste.
 - Multiple trading categories, catering to a vast array of users.

#### Weaknesses:

 - BTZ has no specific value, so any user can ask for large quantities of it.
 - The home page has almost no relevant information, and most of what is there must be found by scrolling to the side.
 - No function to send an image to chat.
 - No way of deleting a post after a chat about it has been created.
 - App only available in certain cities.

#### Opportunities:

 - Add more accessibility options (change colors for the coloblind, etc.)
 - Expand the app to more cities.
 - Create a quick guide for new users to learn the most basic aspects of the app.

#### Threats:

 - Negative oppinions of the userbase can lead to decline in interest in the platform, if not treated accordingly.
 - The bartering/trading principle is lost if users ask for money/gift cards instead of other items.

---
[Back to main Logbook Page](../hci_logbook.md)

---
