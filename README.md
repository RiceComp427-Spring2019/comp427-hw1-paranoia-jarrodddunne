# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Jarrod Dunne

_Student NetID_: jdd7

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Documents
- Assumptions:
  - The documents must be stored in some digital format, allowing for quick retrieval.
  - Both employees and clients must be able to access secured documents.
  - Some employees will need to travel occasionally, and offices will be located in different cities, requiring access to data outside of a single local area network (LAN)
- Assets:
  - Identity of clients
    - Some documents, cases, or entities (such as trusts, corporations) might involve clients that do not wish to have their identity known.
  - Sensitive information about specific clients
    - Social Security Numbers: with these, attackers would be able to easily steal someone's identity, potentially ruining the client's credit score.
    - Information about Trusts/Wills: some information about trusts and wills might compromise the identity and assets about clients and relatives/friends of clients.
  - Information about cases
    - Approaches to specific cases: these could be used by the opposition to prepare counter strategies.
    - Certain documents, such as non-disclosure or confidentiality agreements, may carry fines or punishments if details about the settlement are made known to the public.
  - Payment information
    - Certain people may pay by check or credit/debit card, which might be misused for fraud if the payment information is leaked.
  - Information about the company
    - Payroll, employee and client lists, revenue/profit are all information that the owners would rather not be made public for privacy reasons.
- Threats:
  - Phishing
    - Malicious actors can act pose as someone else in electronic correspondence, in an attempt to gain access to priveledged information or credentials of staff.
  - Social hacking
    - An attacker may pose as another client or an employee, either over the phone or in person, in an attempt to get information or physical access to the premises.
  - Man-in-the-Middle attacks
    - Since information must be shared internationally to various offices, and employees/clients may need to travel, the owners of intermediate hardware (such as WiFi routers at airports or coffee shops) may obtain access to communication to/from the firm's servers.
- Countermeasures:
  - Phishing
    - Train employees to recognize phishing attempts, and be cautious whenever clicking links in emails.
    - Implement firewalls between the firm and the Internet to block known malicious URLs.
    - Build in additional security measures, such as 2-factor-authentication for employee and client logins.
  - Social hacking
    - Request confirmation of ID, such as a photo ID for physical people, or digits of a social security number, to ensure that people are who they say they are.
    - Establish clear guidelines for what can be done over the phone, what requires a login or email communication, and what requires an in-person consultation or visit.
    - Limit access of specific employees to whatever locations, information they are working on, or priveledged to.
  - Man-in-the-Middle attacks
    - Enforce encryption (https) on all websites that may contain sensitive information, or require an employee or client to login.
    - Provide employees that travel often, or need to work remotely, access to a virtual private network (VPN), and enforce use of the VPN when accessing private company records.
## Problem 2
- Scenario: Grading
- Assumptions:
  - The homework will be submitted electronically.
  - The student will need to receive the 
- Assets:
  - Homework submissions
    - Do not want students being able to access other student submissions, either from the previous years or current years, in order to combat potential plagiarism/cheating.
    - Do not want students altering content/submission date of their own assignments after the submission deadline has passed.
    - Do not want students to be able to modify/delete the submissions of other students.
  - Homework solutions
    - Solutions will likely be developed to grade against, do not want students getting access to the solutions, as the homework problems will likely be repeated across semesters/years the class is offered, and solutions being posted online or shared with students would invalidate the homework.
  - Homework grades
    - Grades assigned to individual students must be kept private from other students and other people.
    - Grades may not be accessed earlier than a specific date and time determined by the professor.
    - Grades must not be altered by anyone other than authorized teachers, teaching assistants, and other authorized administrative staff.
- Threats:
  - Late submissions
    - Students may attempt to submit homework after the deadline, or edit submissions after a deadline.
    - Students may lie to teaching assistants about getting approval from teacher for late submissions.
    - Students may use formats that allow for editing after submission (such as google docs, or a github repo).
  - Modifying submissions
    - Only teachers and teaching assistants should have access to submissions from students after the submission deadline. Either password protect access to submissions,
- Countermeasures:
    - Teachers and teaching assistants should maintain written record of all authorized late submissions, and either programatically limit late submissions, or timestamp and cross-verify submission timestamp and authorized late submissions for each student.
    - Submissions in the form of Google Docs, or similar formats with  are not allowed.
  - explanatory_paragraph ...

## Problem 3
- Scenario: Your choice (give a brief explanation)
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph 
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

