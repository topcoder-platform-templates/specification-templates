_HOW TO USE THIS TEMPLATE:_

1. _The text enclosed in ( ) is meant to be instructional guidance for each section._
1. _Fill out each section with clear instructions. Be specific. The existing text is an example of what should be in the section.  Do not simply copy this.  Adjust it to fit your specific requirements._
1. _Delete these instructions._

-------

**Challenge overview**	

_(Never more than 3 bullet points. The objective must be very clear and concise. The goal is to have members understand what we want, in under 2 seconds. You may repeat information from this section elsewhere in the spec too.)_

OVERVIEW OF THE APPLICATION

(We need your help to create a Progressive Web Application (PWA) / Mobile App / Desktop App / Responsive App …)

GOAL OF THIS CHALLENGE

(The goal of this challenge is to develop a ReactJS / AngularJS / HTML, JS , CSS  / ionic based application which will run on desktop only. ….)

TECHNOLOGY AND FRAMEWORKS

Example:

- ReactJS
- Redux
- CSS/SCSS

**Project background**	

- Prior to this challenge what type of challenges were used** to create the design or POC or design   guidelines.
- After this challenge, what’s the next process in development (if known)**

_(For the sections below it is preferred to use the exact headings. The idea is to use the these heading for keeping UI-challenge getting started documentation & scorecard documentation in sync with this template documentation.)_


**General requirements**

(This section should describe some of the common challenge goals listed below)


**Validation**

(Whether to use standard W3C validators (html: [https://validator.w3.org/](https://validator.w3.org/) , CSS: [http://jigsaw.w3.org/](http://jigsaw.w3.org/)) or linters for code validation. For Angular, ReactJS applications it is preferred to use linters)


**Layout Specification**

(Describe the basic layout of the application)

Example:

- Must support desktop, tablet and mobile views (browser).
- Must support retina display.
- Layout width should be fluid.

**Icon and image quality**

(Describe about the desired image & icon quality. Whether to use default quality icons or high quality retina supported icons or any.)


**Typography:**

(Typographic details should be listed if non standard fonts (custom fonts) are used in the storyboard.)

Example:

For creating this application custom fonts as in the storyboard should be used. The fonts are attached to the challenge.


**Server Side & Client Side Functions:** (Specify whether common functions (if any) like sorting, filtering, pagination should be handled through API calls or it should be implemented on client side.

**Automated tools for testing**

Some challenges may require to test the application using certain tools. Like lighthouse is required to test progressive web applications (PWA) and performance testing. Such details can be added under this heading.

(Note_: Do not always force these tools, using them may increase the challenge complexity and development time.)_


**Platform requirements**

Example:

- Desktop: IE11+, Latest Firefox, Latest Safari & Chrome Browsers (Mac & Windows). 
- Tablet: Latest Android and Safari Browsers.
- Mobile: Latest Android and Safari Browsers.


**Individual requirements**

For each individual requirement, we want to cover these in enough detail to not only implement the requirement but also **review** the change.  You need to provide more detail than you would think necessary because reviewers need to evaluate all submissions against these requirements.

Please number each requirement, title it, and describe if it’s a major or minor requirement.  The numbering helps with forum questions, allowing competitors to quickly reference specific requirements.  Having the list of requirements explicitly defined also helps to see scope in a new light.  If your list of requirements becomes long and looks overwhelming, then it probably is and  you should strongly consider splitting up the requirements into multiple challenges. 

For instance:

**1. Login panel (Major requirement)**

**&lt;Requirements description>**


- &lt;Add the marvel-app link and/or zeplin link details (if any)>.
- &lt;Describe the functional requirement, layout requirements and other briefings.>


**Deployment & maintainability	**

( Describe the details to be listed in README file that will help reviewers and other developers to run, test and understand the code)

Readme template: [https://github.com/Sande3p/topcoder-frontend/blob/master/tc-frontend-challenge-README-template.md](https://github.com/Sande3p/topcoder-frontend/blob/master/tc-frontend-challenge-README-template.md)

Example:

- Provide the environment details required to deploy & run the application on heroku.
- For this challenge provide a video to preview your application.

**HTML requirements**


- HTML should be valid HTML5 compliant.
- Provide comments on the page elements to give clear explanation of the code usage. The goal is to help future developers understand the code.
- Please use clean INDENTATION for all HTML code so future developers can follow the code.
- All HTML code naming should not have any conflicts or errors.
- Element and Attribute names should be in lowercase and use a "-" or camel naming to separate multiple-word classes (i.e.. "main-content", or "mainContent)
- Use semantically correct tags- use H tags for headers, etc. Use strong and em tags instead of bold and italic tags.
- No inline CSS styles- all styles must be placed in an external stylesheet.
- Validate your code- reviewers may accept minor validation errors, but please comment your reason for any validation errors. Use the validators listed in the scorecard.


**CSS requirements**

- Use CSS3 Media Queries to load different styles for each page. Do not build different page for different device/layout.
- You may use SCSS in the project.
- Autoprefixer can be set up as a part of build process.
- You may use Stylelint in the project.
- Provide comments on the CSS code. We need CSS comments to give a clear explanation of the code usage. The goal is to help future developers understand the code.
- Please use clean INDENTATION for all CSS so developers can follow the code.
- All CSS naming should not have any conflicts.
- As possible use CSS3 style when create all styling.
- Use CSS to space out objects, not clear/transparent images (GIFs or PNGs) and use proper structural CSS to lay out your page.
- Only use table tags for tables of data/information and not for page layout.


**JS requirements**

All JavaScript must not have a copyright by a third party. You are encouraged to use your own scripts, or scripts  that are free, publicly available and do not have copyright statements or author recognition requirements anywhere in the code.


**Framework specific requirements**


- Code should follow the best practices of [ECMAScript 5](https://en.wikipedia.org/wiki/ECMAScript) (ES5) or above.
- Split the code into Reusable components.
- For ReactJS based applications, there should be two types of component 
  - Container components (aka Smart components): Components those connect with the central store.
  - Presentational components (aka Dumb components): Components those rely on smart components for data.
  - For more visit  [https://redux.js.org/basics/usagewithreact#presentational-and-container-components](https://redux.js.org/basics/usagewithreact#presentational-and-container-components). 
- For AngularJS based applications these are the expected modules:  Core, Shared and lazy-loaded Feature modules.
  - Core Modules:  All services which have to have one and only one instance per application (singleton services) should be implemented here.
  - SharedModule: All the “dumb” components and pipes should be implemented here.
  - Lazy Loading: 	We should lazy load our feature modules whenever possible. 
- If the official framework documentation says specific way or approach to do something, and you did differently with no solid reason, that's valid for scoring down.
- For any other framework, follow the guidelines listed in _“Application Development Requirements” _section or else ask in challenge forums.

**Licenses & Attribution**


  - Third-party assets used to build your item must be properly licensed or free for commercial use. MIT, some modified BSD, Apache 2 licenses are ok. If a library is not commercial friendly you will need to get our approval first.
  - Sufficient information regarding third-party assets must be present in your documentation. This includes the author, license info and a direct link to the asset online.


**Deliverables**

(List the challenge deliverables)

Example:

- Provide all your files within a zip container.
