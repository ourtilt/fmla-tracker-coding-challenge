# FMLA Tracker Service
 
## Coding Challenge 
 
### Overview 
 
The Family and Medical Leave Act (FMLA) is designed to help employees balance their work and family responsibilities by allowing them to take a reasonable, job-protected, unpaid leave for certain qualifying reasons.
 
The toughest part of administering FMLA leave is the tracking. FMLA administrators use a variety of tools to help track FMLA including Excel sheets and sophisticated trackers. We’re going to simplify tracking with an FMLA Tracker service.
 
### The Challenge
 
Create a FMLA Tracker service that calculates FMLA leave. 
 
Given a company, employee, leave start date, leave end date, and a list of leave events, FMLA Tracker will calculate how much leave the employee has and return the balance. Note that this FMLA Tracker will keep track of past leave events to inform how many hours are left today.
 
### The Rules
 
An employee works 40 hours per week.
 
An employee can take FMLA leave in a defined 12-month period or “leave year.” 
 
When an employee’s need for FMLA leave extends beyond the 12-month leave year, any additional time the employee requests counts against his or hers entitlement for the next leave year.
 
You may choose any one of the following four methods for determining the 12-month period during which eligible employees may take up to 12 workweeks of leave:
 
The calendar year is January 1st through December 31st,
Any fixed 12 months, such as fiscal year or a leave year beginning on the first day of an employee’s employment,
A 12-month period measured forward from the first date an employee takes FMLA leave (the next 12-month period would begin the first time the employee takes FMLA leave after the completion of the prior 12-month period), or
A rolling 12-month period measured backward from the date an employee uses FMLA leave (each time an employee takes FMLA leave, the remaining leave is the balance of the 12 weeks not used during the immediately preceding 12 months).
 
		 	 						
`For example, an eligible employee requests two weeks of FMLA leave to begin on November 1st. The employer looks back 12 months (from November 1st back to the previous November 2nd) and sees that the employee had taken four weeks of FMLA leave beginning January 1st,four weeks beginning March 1st,and three weeks beginning June 1st.The employee has taken 11 weeks of FMLA leave in the 12-month period and only has one week of FMLA-protected leave available.After the employee takes the one week in November, the employee can next take FMLA leave beginning January 1st as the days of the previous January leave“roll off” the leave year.`
	
### Technical Spec
 
The architecture will be split between a back-end and a web front-end, for instance providing a JSON in/out RESTful API. Feel free to use any other technologies provided that the general client/service architecture is respected.
Choose one of the following technical tracks that best suits your skillset:
 
Full-stack: include both front-end and back-end.
 
Back-end track: include a minimal front-end (e.g. a static view or API docs). Write, document and test your API as if it will be used by other services.
 
Front-end track: include a minimal back-end, or use the data service directly. Focus on making the interface as polished as possible.
 
### Backend
 
The backend can be built in any language you prefer. Here are some technologies we're most familiar with: Python, Javascript, Ruby, PHP, Scala, C++, Java. You're also free to use any web framework. 
 
### Frontend
 
The front-end should ideally be a single page app with a single index.html linking to external JS/CSS/etc. 
 
### Host it!
When you're done, host it somewhere.
 
### Guidelines
 
* Description of the problem and solution.
* Whether the solution focuses on back-end, front-end or if it's full stack.
* Reasoning behind your technical choices, including architecture.
* Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project.
* Link to other code you're particularly proud of.
* Link to the hosted application where applicable.
 
### How we'll review
 
Your application will be reviewed by the CTO. We do take into consideration your experience level.
 
**We value quality over feature-completeness**. It is fine to leave things aside provided you call them out in your project's README. The goal of this code sample is to help us identify what you consider production-ready code. You should consider this code ready for final review with your colleague, i.e. this would be the last step before deploying to production.
 
The aspects of your code we will assess include:
* Architecture: how clean is the separation between the front-end and the back-end?
* Clarity: does the README clearly and concisely explain the problem and solution? Are technical tradeoffs explained?
* Correctness: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* Code quality: is the code simple, easy to understand, and maintainable?  Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* Security: are there any obvious vulnerability?
* Testing: how thorough are the automated tests? Will they be difficult to change if the requirements of the application were to change? Are there some unit and some integration tests?
* We're not looking for full coverage (given time constraint) but just trying to get a feel for your testing skills.
* UX: is the web interface understandable and pleasing to use? Is the API intuitive?
* Technical choices: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?
* Bonus point (those items are optional):
* Scalability: will technical choices scale well? If not, is there a discussion of those choices in the README?
* Production-readiness: does the code include monitoring? logging? proper error handling?

