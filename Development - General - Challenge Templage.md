_HOW TO USE THIS TEMPLATE:_

1. _The text enclosed in ( ) is meant to be instructional guidance for each section._
1. _Fill out each section with clear instructions. Be specific. The existing text is an example of what should be in the section.  Do not simply copy this.  Adjust it to fit your specific requirements._
1. _Remove any sections you decide not to use._
1. _Delete these instructions._
--------------------

**Challenge Objectives**

_(Never more than 3 bullet points. The objective must be very clear and concise. The goal is to have competitors understand what we want, in under 2 seconds. You may repeat information from this section elsewhere in the spec too.)_



*   **&lt;Describe the app environment>**: _iOS app development, Node web application, C++ embedded application_
*   **&lt;Basic requirements for this challenge>**:  _Implement app login and authorization, clean up a number of recent bug reports, add new screens and functionality_

**Project Background**

_(Never more than 3 bullet points.  The goal of the background is to cover what the final deliverable will be to the client and how the project will be used in production)_



*   **&lt;How will the finished project be used in production?>**  _Will be used by the client to track customer issue reports.  The application will be used by employees of the client to recommend new products to customers.  _
*   **&lt;Beyond what’s covered in Challenge Objectives, how will this challenge tie into the project?>**   _For instance, if you are running a challenge to build a backend service, describe what will consume the backend service.  Is it mobile apps?  A separate web service?  The goal is to give context to the challenge so that competitors can see the “big picture” a bit._
*   **&lt;After this challenge, what’s next in the project?> _If you can show to competitors that a particular challenge is the first of 5 challenges in a series, you’ll get more interest because it will give early competitors an advantage in later challenges._** 

**Technology Stack**

_(Please specify the technology stack for this code challenge, not the project itself.)_



*   **&lt;Programming language(s) / frameworks to be used>  _Note if there are multiple languages being used, make sure to have a review of the scope.  Challenges that cross multiple environments or programming languages have a much larger chance of failure.  This is where you would list things like NodeJS, Swift, Java / Android, C#, Angular, etc..._**
*   **&lt;Deployment environment requirements>  _As with the programming languages, if developers are required to test on multiple OS’s, like Windows and Mac, it will make it much harder to find developers for your challenge.  Consider splitting each platform into a separate, smaller challenge.  Also list here if you are using a cloud host like AWS or Heroku for your web application.  Some cloud hosts require a credit card to open an account, even if it isn’t billed, but that can cause problems for competitors._**
*   **&lt;Other key dependencies>  _List the big dependencies here.  For instance, if you are making a server app, list the database to be used and any large packages like Kafka or Redis that will be required._**
*   **&lt;Quirks>  _Every project has “quirks”.  Does the client require an old or obsolete version of a particular dependency?  Are there certain things that can only be accessed through a VPN or proxy?  Are there specific coding standards required by the client?_**

**Code access**

Most challenges will be extensions / additions / changes to existing code, not a fresh project.  If you are running a code challenge to change existing code you need to clearly define where the code is, what branch to use, and how to gain access to the code.

A public Github repository is easiest, but Ragnar can be used to give access to competitors.

**Make sure the existing code has up-to-date documentation!  **If your existing code isn’t well documented and is hard to deploy, it will frustrate competitors and will lessen the likelihood that you’ll get a submission.  It will also mean a lot of extra questions to answer in the challenge forum.

You want to get as many competitors up and running as quickly as possible for your challenge.  To do that, you need to ensure that your documentation is extremely clear and that you’ve taken steps to ensure setup is easy and can be done quickly with one or two commands.  For instance, when the UML Tool was being worked on, we had great member response and activity, and the UML Tool could be run by downloading the sources and executing “ant run”.  That made the development process easy for everyone involved.

**Individual requirements**

For each individual requirement, we want to cover these in enough detail to not only implement the requirement but also **review** the change.  You need to provide more detail than you would think necessary because reviewers need to evaluate all submissions against these requirements.

Please number each requirement, title it, and describe if it’s a major or minor requirement.  The numbering helps with forum questions, allowing competitors to quickly reference specific requirements.  Having the list of requirements explicitly defined also helps to see scope in a new light.  If your list of requirements becomes long and looks overwhelming, then it probably is and  you should strongly consider splitting up the requirements into multiple challenges. 

For instance:

**1. Login panel (Major requirement)**

**&lt;Requirements description>**

**General for all requirements**

Each requirement should be listed as a major or minor requirement, which will help reviewers properly score and evaluate submissions.  This also gives clarity to competitors so that they know where to focus their efforts if they can’t complete everything in the time given, and it clears up a lot of issues in appeals about “should requirement x,y,z be considered major or minor”

Each requirement has to cover positive and negative aspects of the implementation.  For instance, when a button is clicked in a web app, cover what _should_ happen in the UI and the expected result, but make sure to also cover what should happen in the event of a failure.  Think about:



*   How you want the error message displayed to the user (if a UI is required)?
*   Should the error be logged and at what level?
*   Should an action be retried?
*   What should be shown in the UI if a network request is being done?  A spinner?  A progress bar?
*   Should a success message be shown to the user if something works as expected?

If you don’t explicitly cover these sorts of items, submitters will make assumptions that may or may not be appropriate for your project and requirements.  

**UI Requirements:**

For a UI implementation, you should provide a MarvelApp link with descriptions of the pages in scope and how each button and screen element should be implemented.  

You should provide examples in simple language so that reviewers and submitters can have a few test cases and understand the flow.  For instance:



*   Button X, when clicked will
    *   Show a progress spinner that covers the page, ensuring the user can’t click any other screen elements
    *   Validate form Y to ensure it has been properly filled out by the user
    *   Make a request to service Z to save the content of form Y to the database
    *   Once the form has been saved successfully, redirect the user to page A.
    *   On a failure, show error message “An error has occurred” with buttons “Retry”, and “Cancel” to the user.
        *   If “Retry” is clicked, hide the error window and retry the call to service Z again
        *   If “Cancel” is clicked, just hide the error window
    *   On a failure, log the failure message and HTTP response code at the WARNING level to the app’s log

**Service requirements:**

Web / REST services can be tricky, but it would be best to provide a Swagger (or similar service) file generated **before** the challenge starts. Run a quick Code challenge to get a proper swagger spec defined.  This is ideal because it ensures that you know the contract that will be implemented by the submitters, and the reviewers know exactly what’s required to be reviewed.

If you provide a Swagger or other service description file, you **must** keep it up to date with clarifications from forum questions.  It’s unlikely that the initial Swagger file will be perfect, so as competitors point out issues and the file is updated, you need to keep the file updated so that reviewers and submitters all understand the changes and can implement the service accordingly.

One item to cover with service requirements is unit tests.  You must be clear if unit tests are required and how and when those are run.  Unit tests run at every checkin as part of a continuous integration environment may have different requirements in terms of resources and time limits than unit tests run once during deployment to smoke test an updated service.

If a Swagger file isn’t available but you are requiring competitors to submit one as part of their submission, make sure that you cover how positive **and** negative outputs will be handled in the services.  You want to make sure that the service requirements and how the services will work is covered, but you also need to explain how errors are handled in the service and how those errors are reported back down to the client.  HTTP error codes and messages need to be consistent so that callers can expect services to follow general best practices.  

It would be best to link to specific examples of services that are well implemented.  For instance:  [https://docs.gitlab.com/ee/api/](https://docs.gitlab.com/ee/api/)  

**Bug fixes:**

A lot of challenges are groups of general bug fixes that cover items found by QA or groups of small changes a customer has requested.  To ensure that these are implemented and reviewed properly you need to provide information about the bug or requested fix.

Include:



*   **&lt;Reproduction steps for a bug>**.  _If competitors can’t reproduce an issue, it’s not going to be fixed_
*   **&lt;A description of the current functionality>**  _Understanding what happens before the fix can help reviewers test before and after and contrast it with a fix_
*   **&lt;A description of what should happen after the fix has been applied>  _This helps reviewers quickly validate submissions.  Make sure you describe this in as much detail as possible.  Anything not listed or just assumed will likely be implemented different than you’d like_**

**Deployment guide and validation document**

Make sure to require two separate documents for validation.

A README.md that covers:



*   **&lt;Deployment>** _Make sure you mention if something other than just a local build is required.  For instance, do you want competitors and reviewers to ensure the app deploys successfully to Heroku?  Do you want the app tested on a specific version of Android or iOS?_
*   **&lt;Configuration>  _Most apps have configuration values.  Competitors need to know that they need to document the possible configuration values.  If configuration values already exist but are added to or changed by a challenge, competitors need to know that they need to update the documentation_**
*   **&lt;Dependency installation>  _Competitors will assume that reviewers and others are familiar with the build environment, no matter how complex it is.  Your spec should clearly describe that a step-by-step guide for installing dependencies is required and should be kept up to date with each new challenge for a particular project._**

A Validation.md that covers:



*   **&lt;Validation of each requirement>  _For each numbered requirement, there should be a matching numbered validation item in the Validation.md file that describes how the requirement can be validated by reviewers._**

Validation video / screencast



*   _This is optional, but can be quite helpful for review and validation.  If you are running a UI focused challenge, this can also give good insight into problems with submissions._

**Important Notes**

This section is optional, but would be a good place to document important information that may help a _competitors_ decide if they want to be part of this particular challenge.  For instance, is the timeline edited beyond the default for any reason?  Is the review timeline shortened?  Is an odd scorecard used?  Are there requirements for _competitors_ that compete in this challenge, like being a US citizen, having additional documentation on file beyond the NDA, odd hardware like a Raspberry Pi or anything else?  If we document those important notes at the beginning of a challenge specification, it will help _competitors_ quickly rule out challenges that don’t match what they’re looking for.

**What To Submit**

This section needs to cover what competitors need to provide in their submission.  Make sure to explicitly document the README.md and Validation.md described above.

Things to think about for submission requirements:



*   If you are having competitors work on code in Git, make sure to document the branch and commit hash they need to target with a patch file.  This is important so that reviewers can apply the changes easily
*   Do you want dependencies submitted?  This can increase the size of submissions but make review a bit easier.
*   Do you require an installable build of your app as part of the submission?
*   Do you require a link to a deployed version of the web app that can be used for quick validation?
*   Do you require a video for validation purposes?
*   Be specific about what will be reviewed.  For example, if you ask for both the code and a link to a working demo, then which one takes precedence?  If I have a great working demo deployed on Heroku, but by actual Code that I am submitting is incomplete, then what should the reviewers score?
