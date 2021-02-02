### Challenge Objectives

_(Never more than 3 bullet points. The objective must be very clear and concise. The goal is to have members understand what we want, in under 2 seconds. You may repeat information from this section elsewhere in the spec too.)_



*   User interface design
*   11-15 screens
*   iOS App


### Project Background

_(Never more than 3 bullet points. The background must be very clear and concise.)_



*   The purpose of this project is to develop a mobile application that will be used by Physicians to track order status and view order results for patients they have under their care. 
*   Through the order results, the application will also assist Physicians in determining which antibiotics to prescribe to patients.
*   The application will be used at hospitals across the US.


### Workflow

_(Please copy this section from the project input form)_

Please make sure your design incorporates this workflow.


<table>
  <tr>
   <td><strong>Workflow Step #</strong>
   </td>
   <td><strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td>Step 1
   </td>
   <td>The user launches the mobile app
   </td>
  </tr>
  <tr>
   <td>Step 2
   </td>
   <td>The user (without any log in) enters their basic information (Age, current salary, working years, Accumulated Saving amount in AFP, Gender… and if the user has worked before 1998 (Public Pension System - Legacy) the application asks for the number of years worked and the average salary earned in 1996 in order to be able to estimate the amount that should be transferred from the Public System to the AFP Pension System.
   </td>
  </tr>
  <tr>
   <td>Step 3
   </td>
   <td>The application generates the base simulation
   </td>
  </tr>
</table>



### Users/Roles

_(Please copy this section from the project input form.)_

Please make sure your design supports the following roles.


<table>
  <tr>
   <td><strong>User/Role</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Required</strong>
   </td>
  </tr>
  <tr>
   <td>Standard User
   </td>
   <td>-- Public Access for customers (Without Login) to generate basic estimation based on data input from the customer.
<p>
-- Private Access for customer (With Login) to generate estimation based on the own customer’s information retrieved from the CONFIA backend systems and data input from the customer.
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Admin User
   </td>
   <td>Private Access for administrators (With Login) to make changes to the parameters of the application.
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>Super Admin User
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### Screens/Features

(Please copy this section from the project input form.  Remove items that are not applicable.)

Please make sure your design includes the following screens:


<table>
  <tr>
   <td><strong>Feature</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td><strong>Required</strong>
   </td>
   <td><strong>User Role</strong>
   </td>
  </tr>
  <tr>
   <td>Enterprise Login
   </td>
   <td>App must integrate with an existing login mechanism. Typically this involves integration with an existing authorization/authentication mechanism. 
   </td>
   <td>
   </td>
   <td>All users
   </td>
  </tr>
  <tr>
   <td>Email Login
   </td>
   <td>Allow users to sign in using an email address/password. Select this option if you have an existing authentication/authorization service. 
   </td>
   <td>
   </td>
   <td>Standard User Only
   </td>
  </tr>
  <tr>
   <td>Social Login
   </td>
   <td>Allow users to register and login using third-party services such as Facebook, Twitter, and Google. 
   </td>
   <td>
   </td>
   <td>Admin User Only
   </td>
  </tr>
  <tr>
   <td>Registration
   </td>
   <td>Allow users to register and login using their email address and a password. We would build a new login from scratch. Users can also change their password or recover a forgotten one.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Invitations
   </td>
   <td>Allow users to invite others to use your app via email. This functionality is especially useful if you are building a social application or provide incentives for users to invite their friends. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Introductions
   </td>
   <td>Present your app and inform users of core functionality using a series of introductory screens before they sign up.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Onboarding
   </td>
   <td>Virtually walk your users through your application. This functionality is especially useful if you need new users to set up an account or express preferences after they sign up.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Search
   </td>
   <td>Provide the ability to search your app for specific content, such as products, members, or locations. Please specify below if you also would like autocomplete--suggesting appropriate search terms as a user starts typing.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Location Based Services
   </td>
   <td>App must support the identification of the users geographic location for location based features.  Ex. show store locations on a map or illustrating the progress of a delivery.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Camera (Audio & Video)
   </td>
   <td>Add this feature if your app will require using the camera to capture audio or video. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>File Upload
   </td>
   <td>Allow users to upload photos or other files. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Notifications
   </td>
   <td>Take advantage of notifications; for example, remind users to do certain tasks or update them on new content. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Dashboard
   </td>
   <td>App must have a central dashboard where users can access functionality
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Tagging
   </td>
   <td>Allow users to tag products, people or content; for example, in order to classify and easily retrieve notes. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Account Settings
   </td>
   <td>Allow your users to adjust settings or specify preferences, such as communication frequency. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Help/FAQs
   </td>
   <td>Include a section dedicated to FAQ or Help content.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Marketplace
   </td>
   <td>Allow users to buy, sell, or rent products or services. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Ratings & Reviews
   </td>
   <td>Let users rate or review people, products, or services. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Payments
   </td>
   <td>Allow users to pay in some way; for example, using credit cards, PayPal, or Bitcoin.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Shopping Cart
   </td>
   <td>Allow users to save items before purchasing.  Please specify your desired functionality below.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Product Listing
   </td>
   <td>Add this feature to shows lists of product or services, with individual detail pages for each one.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Activity Feed
   </td>
   <td>Show your users an activity feed of some kind, as they’re used to seeing on Facebook and Twitter, for example. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Profiles
   </td>
   <td>Add this feature if your app requires users to have a profile, including the ability to edit it.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Messaging
   </td>
   <td>Allow direct communication between two or more users. 
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Admin Tool 
   </td>
   <td>App must have an administrative tool or panel to enable direct management of users, content and the application.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Social Media Integration
   </td>
   <td>App must integrate with social media providers (Facebook, Instagram, Twitter, Google+, etc)
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Reporting
   </td>
   <td>App must have the ability to report/export data
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Contact Us
   </td>
   <td>App must have the ability to allow users to contact an administrator/send feedback to administrators.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>3D Touch
   </td>
   <td>If this is an iOS App -- should the designers make use of <a href="https://developer.apple.com/ios/human-interface-guidelines/user-interaction/3d-touch/">3D Touch</a>?
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### Form Factors

(Make sure to specify if it’s for desktop, tablet or phone, and if both portrait and landscape are required)

Please make sure your design supports these form factors:



*   In-scope
    *   Mobile portrait
*   Out of scope
    *   Desktop portrait and landscape
    *   Tablet portrait and landscape
    *   Mobile landscape


### Operating Systems



*   iOS only


### Branding Guidelines

(Pick any of the three options below)



*   Branding guidelines will be posted in the challenge forum.
*   Branding guidelines can be viewed here.
*   No branding guidelines exist -- please use your creativity.


### Design Assets

(List the assets here -- make sure the project input form is always included. Always post assets in the challenge forum.)



*   Wireframes
*   Project input form \



### Final Deliverables



*   All original source files.
*   Files should be created in Adobe Photoshop and saved as a layered PSD file, Adobe Illustrator or as a layered AI file or Sketch
*   Marvel Prototype
    *   We need you to upload your screens to Marvel App.
    *   Please send your marvel app request to XXXX@gmail.com 
    *   You MUST include your Marvel app URL as a text file in your final submission labeled “MarvelApp URL” (in your marvel app prototype, click on share and then copy the link).
