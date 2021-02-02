
*   _Please Apply ‘QA’ tag from the Direct when you are running a Bug Hunt Challenge._
*   _Please check the Orange highlighted sections carefully and adjust accordingly._
*   _Please remove the green highlighted section after filling all the details_
*   _If there are multiple prizes please set them in OR._
*   _All the bug hunts have **24hr notification period** without posting the testing data. For that period you can post a notification like below._
*   _Remove this section before posting the challenge._

_This challenge will have 24hr for the registration (during this phase no one will see details) and 2 days for bug hunting. Details will be posted on [[Submission Start Time]] EST_

### Challenge Objectives

_(Never more than 3 bullet points. The objective must be very clear and concise. The goal is to have members understand what we want, in under 2 seconds. You may repeat information from this section elsewhere in the spec too.)_

*   Unstructured/Structured/Automation/Load Test
*   iOS App, Android App, Desktop site, Mobile Site
*   American publishing company

### About the Application

_(Never more than 2 paragraphs. The background must be very clear and concise.)_

The McClatchy Company is a publicly traded American publishing company based in Sacramento, California. It operates 29 daily newspapers in 14 states and has an average weekday circulation of 1.6 million and Sunday circulation of 2.4 million. In 2006, it purchased Knight Ridder, which at the time was the second-largest newspaper company in the United States (Gannett was and remains the largest). In addition to its daily newspapers, McClatchy also operates several websites and community papers, as well as a news agency, McClatchyDC, focused on political news from the U.S. capital.

### Assets

_(List the assets here -- make sure the project input form is always included. Always post assets in the challenge forum.)_



*   Wireframes/Prototype
*   User Interface Design
*   GitHub/GitLab Source Code for deployment
*   Zeplin Links

### What to Test (Scope)

_(Please specify the scope of this testing application.)_

In this challenge you have to test the **Digital subscription process to validate it is fast, easy, and works flawlessly.** Also you have to test the Digital subscription process on Smart phones, Tablets and Desktop. Need to test the Subscription, E-Edition, Rewards and Newsletter process.



1. **Exploratory testing should be done around all areas associated with McClatchy’s digital subscription platform. Any feedback regarding user flows, bugs, performance issues, etc. is the goal of the engagement. **
2. Test the Digital subscription process to validate it is fast, easy, and works flawlessly across different browsers on Smart phones, Tablets and Desktops.
3. Test the Subscription, E-Edition, Rewards and Newsletter process.
4. Users pay for various Subscription options using their credit card and sign up for promotional offer of $1.99 per month to $129 for Annual Subscription.

_(Please specify the additional limitations and concerns of this test cycle here.)_



*   **Test URL:** [http://www.topcoder.com](https://somesitetotesst.topcoder.com)
*   **Accepted types of bugs:** Functional, UI, UX, Usability, Load Test, Web Accessibility Testing
*   **Subdomains**: Pages to be tested are only that are within the main domain (eg: optus.com.au). Pages apart from the main domain will be rejected. Subdomains are out of scope
*   **Primary target device(s)**: Desktop, Mobiles and tablets
*   **Browser requirements**: Latest Google Chrome, Firefox, Safari and Internet Explorer (Edge) on Windows/macOS. IE11 and below versions are out of scope. Safari on Windows is out of scope.
*   Content Bugs are OUT OF SCOPE/IN SCOPE [Spelling and Grammar, Text spacing issues inside a paragraph, Tooltips, Missing/Broken Images/Videos inside an article, Font mismatch, Broken links on news articles, blog posts, products details pages, FAQ, Privacy, Terms and Conditions and articles.]
*   Also other minor UI, Usability, Content issues, Tooltip, Broken Link issues that are not affecting to the core functionality of the application are likely to be REJECTED.
*   DON'T test the functions in the Login menu and also functionality of the login and registration. They are out of scope.
*   **Important: Because you are testing a live website DO NOT Test/send data via contact forms. They are out of scope.**
*   An edge case would be anything that does not reflect typical user behavior. They are accepted accordance to the impact to the end-user and based on the workarounds available.


### How to Create New Bug Report

1. Create an account on GitHub/GitLab (if you do not already have one): [https://github.com](https://github.com) | [https://gitlab.com](https://gitlab.com). \
2. **You can get access to the GitHub/GitLab repo using [‘Ragnar’ tool ](#)specified in the challenge forum thread to create new bugs OR If you are still getting 404 error, request access to the repo using correct forum thread.** \
3. There is an issue template whenever you click New Issue in GitHub/GitLab. Please use these template to report your issues. \
4. Issues/Bugs found in this application/App must create here: (URL for creating Bugs) [https://github.com/topcoderinc/mcclatchy-digital-subscription/issues](https://github.com/topcoderinc/mcclatchy-digital-subscription/issues). DON'T use any other link to create new issues OR submit a document, they won't be counted and won't be paid. \
5. Please label issues with the appropriate browser type and mode, bug type, and platform type.  The labels can be viewed here: [https://github.com/topcoderinc/mcclatchy-digital-subscription/labels](https://github.com/topcoderinc/mcclatchy-digital-subscription/labels)

### Issue Reporting Guidelines

For each report of a limitation or bug, we need the following information:

1. Steps to reproduce, including any needed information (Must list all the steps that need to reproduce the bug, DON'T list only the URL without test data)
2. Current result(s) before the bug is fixed
3. Expected result(s), after the bug, is fixed
4. If it is a UI bug attach a Screenshots (Mark the area where the bug is) | Functional Bug - Videos (You can attach videos directly on GitLab, if not use services like [www.screencast.com](https://www.screencast.com/) Don’t use [www.youtube.com](www.youtube.com) to host the videos) | Crash - Console/Crash Logs. | Performance testing - Support documents
5. Attach the high-level labels. **If you are selecting multiple labels (Platform/Device); You have to provide screenshots for each and every Device/Platform you have selected; If not Bug will be REJECTED. **[Eg: If you select labels Device: iPhone, Device: Android you have to provide screenshots of all the device types you have selected]. Same applies to Platform.
6. Attach detailed platform, device model (iPhone, iPad, Laptop, Desktop), operating system (Window 7 64 bit, iOS 11, Android 7.0 etc.), Frequency in the issue detail.  The high-level labels aren’t sufficient for issue replication and diagnosis.  
7. If it is a comparison, you must provide the URL and Screenshot/video of that location.

### IMPORTANT NOTE:

**Missing or Incorrect details to ANY of the above fields will mark the bug report as INCOMPLETE. **

For example, Incorrect Steps, Missing Screenshot/Screencast (If it is a UI issue, you have to mark it on the screenshot), Incorrect Actual and Expected results etc.

Be careful when you are providing only the direct URL and not listing the steps to go to that particular page in 'Steps to reproduce' section. Sometimes the Provided URL with parameters won't load the page to the reviewer and the bug may be get closed as 'CAN'T REPRODUCE'. So better to list all the steps till the end or double check the URL is loading or not.


### Issue Weights and Scoring

*   Scoring will be based on the number of bugs by weight.  Be sure to correctly attach a weight to your bug.  The delivery team has the right to change a severity at their discretion.
*   Only verified issues will be counted.  Tickets created for enhancements or that are not bugs will not be counted. Duplicate issues will be closed and not counted. Log issues according to the guidelines above issues that do not follow these guidelines may reject due to lack of information.
*   For challenge scoring, the user with the most verified issues/points will be selected as the winner. If two users submit the same issue, the user that submitted the issue first will receive credit.
*   Please focus on functionality/UI testing based on the requirements, **all bug reports based on your own assumptions will be rejected.**

_(Prizes and number of placements can be vary)_

#### METHOD 01**

*   Functional Issues 	- 10 Points
*   User Interface Issues 	- 5 Points
*   Usability/UX Issue 	- 2 Point
*   Content Bug 		- 1 Point

Submitters that do not take 1st, 2nd or 3rd place will be paid **$5** for each non-duplicate and verified issue up to a maximum of the 3rd place prize. 

---------------------------------------------------------------- OR ---------------------------------------------------------------------

#### METHOD 02

In addition to the first place prize, we will be awarding the following prize money to other competitors.



*   Blocker/ Critical		: $10 [10 Points]
*   Major			: $8 [8 Points]
*   Minor			: $5 [5 Points]
*   Enhancement		: $2 [2 Points]

P1 - Blocker		: This bug causes the app to fail. No workaround exists. E.g. app crashes, app freezes.

P2 - Critical		: This bug causes the app to fail for some specific cases. No workaround exists.

P3 - Major		: This bug causes the app to fail, but there’s a workaround to prevent that issue.

P4 - Minor		: This is an annoyance, but won’t prevent the app from running normally.

P5 - Enhancement	:  Something noticed by testers that should be fixed, but isn’t considered a bug.

The additional prizes will be **up to** $250 for 2nd position, $200 for 3rd position and $150 for 4th position. 

(CHOOSE ONE:) 
No prizes will be awarded beyond the 4th position for any bugs. 
(OR)
Submitters that do not take 1st, 2nd, 3rd or 4th place will be paid each non-duplicate and verified issue up to a maximum of the 4th place prize using the prize guideline above. 

---------------------------------------------------------------- OR ---------------------------------------------------------------------

#### METHOD 03

*   Functional Issues 	- 10 Points
*   User Interface Issues 	- 5 Points
*   Usability/UX Issue 	- 2 Point
*   Content Bug 		- 1 Point

Submitters that do not take 1st, 2nd or 3rd place will be paid **$5** for each non-duplicate and verified issue up to a maximum of the 3rd place prize. You need to find issues worth 100 points to earn the 1st and 2nd prizes, and you will receive half prize if total points of the issues >= 50 and &lt; 100.

### Important Notice

*   Follow the standard [topcoder Bug Hunt Rules](https://help.topcoder.com/hc/en-us/articles/115008845167-What-is-a-Bug-Hunt-).
*   If you do not properly document your bug reports, they will likely be rejected due to lack of information or documentation. If you submit the same bug in multiple areas/pages, (for instance, Same validation issue of a form can be found in different pages/sections) you will likely get credit for the original bug report only. The others will all be closed as duplicates.
*   If you duplicate an issue on a platform or browser that hasn’t been tested yet, you should create a new issue and add a link/reference in the issue description to the existing issue number. Our copilot will review these items and consolidate them later. Please don’t make adjustments or change labels of existing issues logged by other competitors.
*   DON'T RE-OPEN the issues in the review phase and anyone who RE-OPENS a ticket will be disqualified from the challenge.
*   If Mobile and Tablet testing are available DON'T create the same issue on different platforms; instead, merge them into one; All the others will be marked as Duplicate.
*   If you see multiple broken links on the same page combine them into one ticket. Others will be marked as DUPLICATE.
*   You must not edit the bug report once created, so make sure you enter all the details at the time you create the issue, otherwise, your issue will be moved to the end of the queue. If you really need to edit an issue you must use the comments section for this (i.e. add a comment to describe any changes you want to make to the issue), and we'll decide whether the changes are major enough to move the issue to the end of the queue. You are allowed to add screen shots in the comments section though, assuming your issue report contains all the details when created.
*   You must specify the test data you have used in the 'Reproduction Steps', All the issues will be marked as 'Incomplete', if the correct test data is not provided.
*   Keep an eye on the issues being submitted by other participants to minimize the time you may be spending on duplicate efforts. Knowing what has already been reported will allow you to better focus your time on finding yet undiscovered issues.
*   **There will be no appeals phase. The decision of PM/Copilot for validity and severity of each filled issue will be final.**

### Final Deliverables

Submit all your bugs directly to GitHub/GitLab. When you are done with your submissions please submit a .txt file using the “Submit” button before the submission phase ends. In this file include:

*   Copies of all Test Execution Summaries which you participated in.
*   topcoder handle (The one displayed in the top right corner near the Profile picture)
*   GitHub/GitLab handle used to raise the issues. (Login to GitHub and click on the Profile picture > Your Profile. Check the URL https://github.com/[Your Username] | https://gitlab.com/[Your Username]

- ALL THE SUBMISSIONS WITHOUT ABOVE INFORMATION WILL BE REJECTED AND WON’T BE PAID.

- IMPORTANT: Submit the above details before the Submission Phase ends. If you can't submit due to technical difficulties within the Submission Phase please email your submission with above details to support@topcoder.com.

- Participants who haven't submitted will not be paid.

- DON'T use any other link to create new issues OR submit as document, they won't count and won't be paid.
