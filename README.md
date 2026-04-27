## Notes

1. Business Context 40 minutes 
2. Requirements 25 minutes 
3. Problem Decomposition 25 minutes 
4. KPIs & Acceptance Criteria 20 minutes 
5. Proposed Solution 30 minutes 
6. Justification 40 minutes 

Suggestions to potentially add:
 - Contactless Payment
 - Online Payment
 - APIs
 - AR/VR
 - AI and Algorithms
 - Cloud Computing/Software
 - Chatbots/Help agents

 Useful links:
 https://gdpr-info.eu/issues/fines-penalties/
 https://gdpr.eu/what-is-gdpr/
 https://www.gov.uk/service-manual/helping-people-to-use-your-service/understanding-wcag
 https://www.mybib.com/
 



## Activity A Checklist
### Business Context
- [ ] Client Brief Review
- Clear Understanding of goals
- Digital solution
- Assumptions stated (such as company size, budget, timeline)
- What they want in the solution
- Intrested in digitalising their product and why they should
- [ ] Stakeholders
- Internal stakeholders (Managers, Developers, Executives, Staff, Testers)
- External Stakeholders (Users, Suppliers, Investors, Government, Competitors, Media)
- Stakeholder Impact on design and delivery explained
- [ ] Constraints
- Legal constraint
- Budget constraint
- Time constraint
- [ ] Empathy Mapping
- Example user persona defined
- Says, Thinks, Does, Feels, Pains, Gains.
- Link user frustrations to system needs (complexity, cost, etc)
- [ ] SWOT Analysis
 - Strengths
 - Weaknesses
 - Opportunities
 - Threats
- [ ] User Stories and Acceptance
- Multiple user roles identified
- Clear format (example: "As a user, I want, so that, Acceptance criteria")
- Acceptance criteria defined for each scenario
- Compare against competitors
- [ ] Functional and Non-Functional requirements
- Anything that would be a webpage or feature (Functional requirement)
- UX principles, Security, Performance, Scalability, Maintainability (Non functional)
- [ ] Decomposition of Requirements
- Decomposition Diagram (Identify problems, func and non func requirements, user stories and acceptance criteria. User login, Data input, Report Generation, Admin Management, Notifications)
- Seperation of features
      
- [ ] KPI's and User Acceptance
- User growth
- Average spending
- Trends
- Reviews and ratings
- Feedback
- Quantified success/failed thresholds
- Clear measureable outcomes
- (Response time, System uptime, User satisfaction, Number of bugs/errors, Task completion rate, Cost within budget, Deadline met, Support ticket volume)
### Proposed Solution
- [ ] Description of the Proposed Solution
- Explaining the functional and non functional requirements alot further, and why they will improve the solution. Discuss architecture and databases. 
### Justification 
- [ ] ​Meet the Client and User Needs
- Link between user stories and features
- Improves satisfaction
- Reduces workload
- [ ] Risks, Mitigations and Wider issues
- Cybersecurity threats identified
- Mitigations for said threats
- Data accuracy and misinformation risks
- [ ] Regulatory Guidelines and legal requirements
- GDPR complaince explained with users rights and penalties
- WCAG accessibility principles covered
- Legal planning and land-use considerations included
- [ ] Appendix
- Make sure to discuss throughout






## Activity B Checklist

### Visual Interface Design
 - [ ] Wireframes Created
 - - [ ] Whitespace, common conventions, hierarchy
 - - [ ] UX Principles (1. User-centricity, 2. Consistency, 3. Hierarchy, 4. Context, 5. User control, 6. Accessibility, 7. Usability)
 - Color Scheme with WebAIM
 - Logo
 - Navbar
 - Footer
 - Many pages
 - Annotate wireframes
   
  
   
- [ ] Make look good
 - [ ] Accessibility Features Included
 - Alt text
 - Screen Reader
 - Font size
 - Transcript
 - Subtitles
 - Color contrats options
 - [ ] Annotations
 - Why each choice was made
 - [ ] User Journey
 - User Persona's (Their name, their age, their role, their goal with prototype, Accessibility, and quotes)
 - Journey (Action, Touchpoint, Thoughts, Pain Points, Opportunities)
 - [ ] Front end requirements
 - [ ] Back end requirements

### Data Requirements
 - [ ] ERD Completed
 - [ ] Use Case Diagram
 - [ ] Data Dictionary
 - Table name, Field name, Field definition, Data type & Length, Format/Validation Rules, PK, FK, Sample Data
 - [ ] Data Flow Diagram
### Algorithms
- [ ] Flow charting

 ### Test Strategy
- Talk about components like each page (Login, account register, Navbar, account settings, etc) and then give it a suitable testing method and justify it
- Then talk about backend functionalities, like a feedback system or a database, then test it.
 - [ ] Functionality testing
 - [ ] Usability testing
 - [ ] Interface testing
 - [ ] Database Testing
 - [ ] Compatability Testing
 - [ ] Performance Testing
 - [ ] Security Testing
 - [ ] Crowd Testing
 - [ ] Accessibility Testing
 - [ ] Acceptance Testing
 - [ ] Alpha Testing
 - [ ] Beta Testing
 - [ ] Black Box/White Box Testing
## Task 2
### Set up connection
 - [ ]Create a connection string (database location, security, timeout)
 - [ ]Create a SqlConnection using the connection string
 ### Prepare command
 - [ ]Create a SqlCommand
 - [ ]Set the stored procedure name
 - [ ]Attach it to the connection
 ### Configure command type
 - [ ]SetCommandType to StoredProcedure
### Get input data
- [ ]Read values from form inputs (e.g. name, age)
 - [ ]Convert data types if needed (e.g. string → int)
### Add parameters
 - [ ]Add parameters that match the stored procedure
 - [ ]Ensure names match exactly (e.g. @Name, @Age)
### Open connection
 - [ ] Open the database connection
### Execute command
 - [ ]Use ExecuteNonQuery() for INSERT/UPDATE procedures
### Close connection
 - [ ] Close the connection (or use using to do this automatically)
 
## Task 3a
1. Aims & Purpose

- Why collect feedback (pain points, issues, improvements)
- What we want to find out + who from (and why)
- Link to improving prototype (usability, performance, accessibility, navigation)
- Specify focus (UI, code, or both)
- Expected improvements from feedback

2. Target Users

- Technical users (roles, number, experience, reliability)
- Non-technical users (justification, insights)
- Age ranges
- Reducing bias

3. Feedback Methods

- Surveys (quantitative + qualitative)
- Observation (task-based)
- Justify each method + link to aims
- Behaviours measured (hesitation, misclicks, errors)
- Materials used (snippets, videos, images)
- Ethical considerations (consent, anonymity, data protection)

4. Practical Session Plan

- Location + test environment
- Tasks users complete
- Time per task + exploration time
- How prototype is presented

5. Data Recording

- Survey storage (forms → spreadsheets, security)
- Observation logging (checklists, timings, notes)
- Secure data storage
- Triangulation plan (survey + observation + interview)

6. Survey Design

- Platform (Microsoft/Google/SurveyMonkey)
- 5 rating questions + 3–5 open questions
- Focus: usability, navigation, clarity, accessibility, performance
- Clear, non-repetitive questions

7. Observation & Interview

- Watch users complete tasks
- Tools (e.g. Hotjar)
- Track behaviour (hesitation, confusion, errors, workarounds)
- Ask expectations + follow-ups
- Record: actions, comments, reflections

8. Data Analysis

- Calculate averages + compare scores
- Identify low scores + trends
- Group qualitative data into themes
- Compare technical vs non-technical users
- Triangulate (score + theme + evidence)
- Prioritise improvements

9. Themes & Organisation

- Key areas: navigation, layout, accessibility, performance, design, responsiveness, content clarity
- Identify patterns, strengths, weaknesses
- Count frequency + select key examples

10. Writing Analysis

- Quantitative evidence (scores)
- Qualitative insights (comments/themes)
- Observations (user behaviour)
- Interpretation (what it means + why)

11. Final Summary

- What worked / didn’t work
- Key differences between users
- Overall findings
- Priority improvements
- Highest scoring areas + positive behaviours
- Technical vs non-technical comparison

Type of Questions to be used on each form:
- Strongest & Weakest Part
- Reccommend?
- One feature, one non-feature
- Could this prototype compete with other competitors on the market?
- Potential security vulnerabilities
- Which part to optimise first
- How helpful are comments?
- Error handling and logging systems
- Naming conventions & structure
- Could this be added upon easily?
- Should any third-party systems/software/existing products have been used?
- Would you have changed anything about this code snippet?
- Is anything about this design confusing or distracting to you?
- Would this solve a real problem for you? Why or why not?
- How would you describe this product to a friend or teammate?
- What is one thing that felt missing or unnecessary? 

## Task 3b 
- [ ] Asset and content
- [ ] Requirement Evaluation
- [ ] Use of Evidence
- [ ] Improvements
- [ ] Writing Quality
