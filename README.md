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
  - Unauthorized grade access
    - Students may try to gain access to gradebooks, or graded submissions, for purposes of either viewing other student's grades, viewing their own grades early, modifying their grades or other student's grades.
    - Students may imitate other students in order to view grades or graded solutions, if assignments are returned in person.
  - Plagiarized submissions
    - Students may use solutions from other students (either in the same year, or previous years), or solutions found online or in other forms, and attempt to submit these solutions as their own work.
- Countermeasures:
  - Late submissions
    - Teachers and teaching assistants should maintain written record of all authorized late submissions, and either programatically limit late submissions, or timestamp and cross-verify submission timestamp and authorized late submissions for each student.
    - Submissions in the form of Google Docs, or similar formats where the submission can be edited after the fact are not allowed .
  - Unauthorized grade access
    - Physical gradebook
      - Maintain a 'log' of which teacher or teaching assistant has gradebook at any given time.
      - Only allow teachers and teaching assistants access to view and edit the gradebook.
      - Make copies, either through taking pictures of the pages, or entering in some other electronic or physical backup. Do this every so often, so you can verify if grades have been changed, and keep the original and backups in separate locations.
    - Electronic gradebook
      - Keep electronic gradebook accessible through some sort of login system, so that only teachers and teaching assistants have access to it.
      - Keep digital logs of edits to the gradebook.
      - Ensure there is a way to retrieve history of the gradebook, either through backups, or a revision history.
  - Plagarized submissions
    - Run submissions through a plagarism checker (if possible). If not, maybe have a single teacher or teaching assistant grade the same problem for every student, so that person can look for similarities in multiple student's submissions.
    - Only teachers and teaching assistants should have access to submissions from students after the submission deadline. Password protect access to all submissions.
## Problem 3
- Scenario: Company Financial Reports
  - You are responsible for releasing a publicly traded company's quarterly financial report to all stock investors and the public.
- Assumptions:
  - You must release this information at a specific time, to a public audience.
  - You will not receive this information yourself until a few days ahead of the release.
- Assets:
  - Company financial information
    - Upon release of this information, the company's stock price will likely jump or fall significantly. If this information is released ahead of time to certain people, this may cause certain investors to get an unfair advantage, and may cause people to be charged with insider trading. Releasing this incorrectly may also open up the company to lawsuits and legal action.
- Threats:
  - DDOS
    - An attacker might attempt to prevent the timely release of the financial report by overloading company servers releasing the information.
  - Misinformation
    - An attacker might pose as the company and release or leak incorrect financial reports to investors.
  - Early release
    - An attacker might work at the company, or know someone who does, and gain early access to the report in order to trade on the information before other investors receive the information. Alternatively, the hacker might be able to access the information themselves, if the data is stored or sent over insecure means.
- Countermeasures:
  - DDOS
    - Have backup servers or locations to 
