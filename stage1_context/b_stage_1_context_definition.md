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
>	As our main competitor, we chose "Viriato - Escola de Condução"'s website.


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

| **Issue**                                                      | Expert 1 | Expert 2 | Expert 3 | Average | Recommendations                             |
| -------------------------------------------------------------- | ------------ | -------- | -------- | -------- | ------------------------------------------- |
| Homepage navbar doesn't match current page (shows as "Testes") |3|**2**|1|2| Fix selection problem                       |
| UI for contacting instructor doesn't feel like a chat          |2|**3**|**1**|2| Change the form-like UI to a real-time chat |
| "Mudar Senha" page indicator looks like a button               |2|**2**|1|2| Remove bold page indicator                  |
| "Ver vídeo" button not working or opening new browser tabs     |**4**|**4**|**2**|3| Show "No videos available" or remove page until videos are uploaded |
| Website mostly white and colors don't go well together         |**1**|**1**|1|1| Change CSS colors                                                            |
| Useless "Formação Teórica" page with no files                  |2|**3**|2|2| Show "No documents available" or remove page until files are uploaded        |
| "Formação Teórica" page includes "Material Didático", "Vídeo" and "Testes"'s contents |2|**1**|2|2| Remove "Material Didático", "Vídeos" and "Testes"'s pages                    |
| "Formação Teórica"'s contents are presented in a out-dated style (Index of Files)     |**2**|**2**|**1**|2| Completely redo the UI for file presentation                                 |
| "Mudar Senha" page in navbar                                                          |2|**1**|2|2| Change "Mudar Senha" from a page to a functionality in a "Profile"-like page |
| Font size too smal difficults reading |**2**|2|2|2| Change font or increase font size |
| "Marcação de Aula Teórica" button and page do different things |**2**|3|2|2| Change names to better specify the functionality |
| Video names don't specify video content |**3**|3|2|3| Rename video files for better specification |
| "Tab" shortcut doesn't correctly identify its selection |**3**|2|0|2| Fix "Tab" shortcut identification |
| Navbar disappears after iterating the whole page with the "Tab" shortcut |**4**|4|3|4| Fix the issue |
| Confusing switch between files menu |**3**|3|2|3| Change icons or add labels |
| Lack of documentation/help page |**2**|2|3|2| Add a documentation/help page|

---
### - Cognitive Walkthrough

#### Method
>	[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]
- *1st* -> Identify the main tasks, the ones without which the system can't work.
- *2nd* -> Analyze the task and the steps required to do it.

#### Task Selection and Task Analysis

>	[Which tasks did you select and why. What are the subtasks entailed for each ]

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Schedule a Class** | Click on the "Marcação Aula" button     |
|                             | Choose a day from the available options on the calendar |
|                             | Choose a time for the class     |
|                             | Click on the button to submit the request                   |
---

| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **2. Get summaries about a topic** | Click on the "Material Didático" section |
|                               | Choose the document for the desired theme          |
---

| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **3. Ask a question to the instructor** | Click on the "Instrutor Online" button     |
|                             | Fill out the form with informations such as email and phone number |
|                             | Write the question you want to ask    |
|                             | Click on the button "Enviar mensagem" to send the question to the instructor                   |

---


#### Results

Task: **1. Schedule a Class**

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Click on "Marcação Aula" button   | No | There are two buttons with the same name but different funcionalities | Yes | --------       | Yes                       |  Change the names of the buttons to make it clearer what each one does|     |
| 2      | Choose a day from the available options on the calendar   |  Yes  | --------------------      | Yes |--------        | Yes | ----------------------              |     |
| 3      | Choose a time for the class   | Yes | -------------------- | Yes | --------       | Yes | ----------------------|     |
| 4    | Click on the button to submit the request | Yes | -------------------- | Yes | -------- | Yes | ---------------------- |     |

---
Task: **2. Get summaries about a topic**

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Click on the "Material Didático" section   | Yes | --------- | Yes | -------- | Yes | ----------------------- |     |
| 2      | Choose the document for the desired theme   |  Yes  | ---------     | Yes |--------        | Yes | ----------------------              |     |

---
Task: **3. Ask a question to the instructor**

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Click on the "Instrutor Online" button   | Yes | --------- | Yes | --------       | Yes                       | ----------------------- |     |
| 2      | Fill out the form with informations such as email and phone number   |  Yes  | --------- | Yes |-------- | Yes | ---------------------- |     |
| 3      | Write the question you want to ask   | Yes | --------- | Yes | --------       | Yes | ----------------------|     |
| 4    | Click on the button "Enviar mensagem" to send the question to the instructor | Yes | --------- | Yes | -------- | Yes | ---------------------- |     |


## B.1c. Overall Analysis

>	[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

| **Strength** | **Weaknesses** | **Opportunities** | **Threats** |
|--------------|----------------|-------------------|-------------|
|Simple navigation and interface |Some visual flaws (showing the wrong current page for example) |Creating something like a chat between the instructor and the student. | Competing apps have better features (Tracking score, showing how prepared you are for the exam, etc) |
|Large variety of studying material, including questions and answers|They offer more material then needed to get the driving license (This can lead to people wasting time with irrelevant things or getting bored too quickly) | Allow students to make the payments through the website |				|
|				| Although it looks functional, it shows signals that it has been abandoned (It shows that there are no classes scheduled even though there are) | Allow students to request exams through the website | 			|
|				| In the “Formação teórica”  tab, after you open a file, your only option is to close the window. If you want to open a file in the same directory, you have to go all the way from the starting point |
|				| Although it is possible to contact an online instructor, you must fill a form with your email and, optionally, your phone number|



---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

>	[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]

In our study, we focused on three key user types for the interviews: students, instructors and driving school employees.

We began by prepared a guide with essential questions we wanted to ask. Our goal was to understand the driving school's working method, including whether they currently use a platform of this kind and, if not, their thoughts on adopting one.

After establishing these general aspects, we moved on to more specific questions about the platform, examining the features available to each user type and how they interact with them.

## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 27-02-2025 | Anonymous / Student      | Consider important to implement more features for the practical part of driving lessons | [📄 Notes Student](interview-Student.md) |     |
| 28-02-2025 | Anonymous / Instructor | Would like to access his lesson calendar directly |[📄 Notes Instructor](interview-Instructor.md) |     |
| 28-02-2025 | Anonymous / Employee | Implement a payment functionality and a scheduling system where instructors can access their lesson calendar directly on the platform|[📄 Notes Employee](interview-Employee.md) |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Instructors cannot access their lesson schedules through the platform.
	- Payments need to be manually recorded, which is time-consuming.

- **Frequently Used Tools:** 
	- Student registration and exame scheduling system.
	- Lesson registration via QR Code.
  
- **Desired Features / Solutions:** 
	- A shared calendar where instructors can view their scheduled lessons.
	- An integrated payment system that updates student accounts automatically.

---
[Back to main Logbook Page](../hci_logbook.md)

---
