[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| Viriato - Escola de Condução    | Online platform to help driving school students        | [Information repository here] |




## B.1b. Detailed Competitor Analysis
>	As our main competitor, we chose "Viriato - Escola de Condução"'s website


### - Heuristic Evaluation

#### Method
For this evaluation we used Jakob Nielsen's heuristics which can be found in [this page](https://www.nngroup.com/articles/ten-usability-heuristics)


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

> **Note:** The issues each expert found will be highlighted in **bold**

| **Issue**                                                      | Expert 1 | Expert 2 | Expert 3 | Recommendations                             |
| -------------------------------------------------------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Homepage navbar doesn't match current page (shows as "Testes") ||**2**|| Fix selection problem                       |
| UI for contacting instructor doesn't feel like a chat          ||**3**|**1**| Change the form-like UI to a real-time chat |
| "Mudar Senha" page indicator looks like a button               ||**2**|| Remove bold page indicator                  |
| "Ver vídeo" button not working or opening new browser tabs     |**4**|**4**|**2**| Show "No videos available" or remove page until videos are uploaded |
| Website mostly white and colors don't go well together         |**1**|**1**|| Change CSS colors                                                            |
| Useless "Formação Teórica" page with no files                  ||**3**|| Show "No documents available" or remove page until files are uploaded        |
| "Formação Teórica" page includes "Material Didático", "Vídeo" and "Testes"'s contents ||**1**|| Remove "Material Didático", "Vídeos" and "Testes"'s pages                    |
| "Formação Teórica"'s contents are presented in a out-dated style (Index of Files)     |**2**|**2**|**1**| Completely redo the UI for file presentation                                 |
| "Mudar Senha" page in navbar                                                          ||**1**|| Change "Mudar Senha" from a page to a functionality in a "Profile"-like page |
| Font size too smal difficults reading |**2**|2|| Change font or increase font size |
| "Marcação de Aula Teórica" button and page do different things |**2**|3|| Change names to better specify the functionality |
| Video names don't specify video content |**3**|3|| Rename video files for better specification |
| "Tab" shortcut doesn't correctly identify its selection |**3**|2|| Fix "Tab" shortcut identification |
| Navbar disappears after iterating the whole page with the "Tab" shortcut |**4**|4|| Fix the issue |
| Confusing switch between files menu |**3**|3|| Change icons or add labels |
| Lack of documentation/help page |**2**|2|| Add a documentation/help page|

Não entendi (Bia):

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

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

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
