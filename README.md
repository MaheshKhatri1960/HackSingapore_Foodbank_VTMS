# HackSingapore_Foodbank_VTMS

1.0 - <b>Overview </b> - <b>Volunteer to Task Management System (VTMS)</b> - Team MK Submission for HackSingapore's No Code Low Code Challenge for Food Bank Singapore (FB SG)

![Hack Singapore 2022 Food Bank Challenge - VTMS - Overview](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_intro_1175_369.png)

Our proposed solution <b> Volunteer Task Management System (VTMS)</b>  has two linked web cloud based software modules: a <b>Volunteer</b> module & an <b>Administration</b> module which are used for the frontend and backend work activities respectively.

![Hack Singapore 2022 Food Bank Challenge - VTMS - Module Activities](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_overview_1280_720.png)

As can be seen from the screen above, the proposed system is designed to be quite comprehensive for handling the volunteering activities in an efficient manner.

2.0 - <b>Solution</b> - The system is based on a web based cloud platform. Please see the following Login Screen 1.

![Hack Singapore 2022 Food Bank Challenge - VTMS - Login Screen](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_login_screen_990_528.png) <br><br>

<p align="center"> <b>Screen 1 - VTMS Login Screen with separate credentials for Volunteers and Administrators. </b></p> <br>

From the screen above, it can be seen that the volunteer can visit the Food Bank Singapore website as well as the various social media (Facebook, Instagram, LinkedIn) handle's web properties. On the top right hand side, a link to FB SG's latest media campaign for 100 SGD per month of donation is also provided. Also, in line with their main website showing the Clock Timer for ending Food Hunger in Singapore, to achieve a consistent brand image, the same is also shown here.

There is a provision for both volunteers and administrators to log in from the above web site as well as sign up for the first time. In the case of 'Sign Up', an email confirmation is sent to their email address. There is also a check incorporated to ensure that volunteers and administrators cannot log in by mistake into the other's website. This is for maintaining confidentiality & privacy of data. 

It is also proposed that the website will be compliant as per Singapore's Personal Data Protection Act (PDPA) framework. The same has been mentioned on the website.

2.1 - <b> Volunteer Module </b> - Allows volunteers to respond to FB SG volunteer tasks available, offer time based services, view FB SG volunteer job roles responsibilities, requirements, browse task related videos and manage their task related data & metrics. See Screen 2 below.

![Hack Singapore 2022 Food Bank Challenge - VTMS - Volunteer Module Screen](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_volunteer_module_898_535.png)

<p align="center"> <b>Screen 2 - VTMS Volunteer Module - Main Screen </b></p> <br>

At the top is a welcome message from Food Bank reflecting their mission.

It has the following functionalities as represented by the buttons shown above in a Top to Down, Left to Right sequence:

2.1.1 - <b>Essential Details</b> -Store Volunteer's basic essential profile data such as full name, telephone number, gender, etc. besides email address. This was as per our understanding that since the volunteers are young, they tend to be pretty fast on their devices and would like to store the minimal information to get started.

2.1.2 - <b>Additional Details</b> - Store a volunteer's additional profile details besides the above basic data. e.g. Driver's License Information, Personal Vehicle Ownership Information, Health Declaration Information, Open to Social Media Updates, Availability and Preferences. This is captured via a Pop Up Form.

2.1.3 - <b>Job Role Interests</b> - Enter a volunteer's job role interests based on a selection shown as defined by FB SG.

2.1.4 - <b>Job Role Details</b> - Browse available Food Bank Volunteer Job Role / Task details - Duties & Responsibilities, Requirements & Qualifications as defined by Food Bank in the administration module.

2.1.5 - <b>Job Role Videos</b> - Watch Food Bank's volunteer job role / task YouTube videos. These are proposed to be organized based on Food Bank Location wise, Work Area / Function wise & Job Role Task wise for easier viewing. 2 sample videos have been uploaded for viewing here. One for warehouse volunteers, another for outdoor delivery tasks.  

2.1.6 - <b>Apply Via Calendar</b> - Apply for Volunteer Job Roles offering services on an open calendar. This module has been currently optimized for Warehouse Volunteers. This will enable volunteers to offer their time based services on their personal time flexibility using the open calendar as a useful tool. Once they apply, they get an application confirmation email automatically. Organizational volunteers can use the apply via calendar module for offering their services to Food Bank.

2.1.7 - <b>Apply Against Task</b> - In addition to applying via a calendar, a volunteer can also respond to specific Volunteer Job Role Tasks as defined by Food Bank. Here too, once they apply, they get a task application confirmation email automatically. Further fine tuning needs to be done to handle the different time slot wise restrictions as may be applicable (similar to the 5 volunteers per morning / afternoon time slot) for different job roles across different work areas at the different locations.

2.1.8 - <b>Volunteer Metrics</B> - The system currently displays the number of volunteer applications and approvals received both for calendar based as well as task response applications. Since motivation of the volunteers is very important, based on further work interactions between Food Bank and the volunteers, their work activities can be appropriately acted upon as per the various stages shown: <b> Applied --> Assessed --> Approved --> Accepted --> Attended --> Appraised --> Appreciated. </b> The metrics for the same are proposed to be shown in this screen in the future.

The above are the current functionalities of the volunteer module. It is important to mention that currently the stress has been on getting the functionality in place first for the volunteer module. Once the same is accepted, then the main task would be to work on the responsive design aspect of the volunteer module across different devices. This will be a very important aspect for success of the module as regards its acceptance and usage by the volunteers. Of course, enhanced user interface can be strived for based on the most contemporary social media interaction platforms like Instagram, etc which are popular amongst the young volunteers.

2.2 - <b> Administration module </b> - Enables FB SG to browse volunteer profile & interests, create tasks, approve task applications, automatically send task application receipt & task approval emails. It also stores data relating to volunteer task management - FB SG locations, facilities, work shift timings, restrictions, work areas / functions, job role duties & responsibilities, requirements & qualifications and manage database along with other key stakeholders such as beneficiaries, donors & volunteer groups. This is for both individuals & organisations. See Screen 3 below. 

![Hack Singapore 2022 Food Bank Challenge - VTMS - Administration Module Screen](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_administration_module_976_438.png)

<p align="center"> <b>Screen 3 - VTMS Administration Module - Main Screen </b></p> <br>

The administration module has the following functionalities:

2.2.1 - <b> Administration Metrics </b> - This displays information as regards the numbers handled by the system with respect to 3 main categories currently: Volunteers & Job Role Task related, Food Bank Facilities related and lastly Stakeholder related. 

The next row displays the buttons representing four different master information types as shown below :

2.2.2 - <b>Work Shift / Timings</b> - This captures information as regards the different times followed by various Food Bank facilities. 

2.2.3 - <b>Location</b> - Different Food Bank location types, their sub types, addresses, work timings, etc are stored here.

2.2.4 - <b>Work Areas / Functions</b> - This lists the different functional work areas that are relevant to Food Bank operations. Volunteer Job Roles get defined within a parent work area / function. Or conversely, a work area / function can have multiple volunteer job roles. e.g. For 'Delivery Logistics' work area, one could have 'Delivery Assistant' and 'Driver Volunteer' as separate volunteer job roles.

2.2.5 - <b>Define Volunteer Job Role </b> - Here, for each job role, the duties & responsibilities, the requirements and qualifications are defined within a location & work area. 

In the next row, the other activities that can be done in the Administration module are shown:

2.2.6 - <b> Create Volunteer Task </b> - This allows the creation of new volunteer tasks for a specific location, volunteer job role, time range and number of persons required. These tasks will show up in the volunteer module from where interested volunteers can apply for the same.

2.2.7 - <b> Manage Individual Volunteer Details </b> - The administrator can manage the database of volunteers. As of now, only the basic essential volunteer fields are shown. It is proposed of course to show all the volunteer additional detail fields & job role interest as mentioned in 2.1.2 & 2.1.3 above at the earliest in the near future. There is also a search field which has been shown to filter. This search facility will be significantly enhanced in the future as it will be a very important tool for Food Bank to match volunteers to tasks or vice versa.

2.2.8 - <b> Approve Volunteer Calendar Applications</b> - This module approves the volunteer applications sent by them via the calendar interface. Once the approval is done, an email is sent to the candidate for the same. 

2.2.9 - <b> Approve Volunteer Task Applications</b> - This module approves the volunteer application responses against Food Bank tasks and similar to 2.2.8 above, once the approval is done, an email is sent to the candidate for the same. 

For both 2.2.8 & 2.2.9, it is possible to add additional functionality via buttons called as 'Reject' or 'Hold' for taking appropriate actions for rejecting or putting on hold a volunteer's application.    

2.2.10 - <b> Future Modules </b> - Based on our understanding of our interactions with Food Bank and the time limitations, we decided to put these modules on which we were working in abeyance. There are 3 categories of modules:

2.2.10.1 - <b> Linkages in proposed FBSG future ERP system </b> for which the software has been partially developed (creation of data). These modules are Beneficiary Organization / Centre, Industry / Organizational Donor and Volunteer Organization / Group. One can enter these modules and view the fields. In both the Beneficiary and Donor categories, extensive type information has been incorporated. 

2.2.10.2 - <b> Linkages to current VTMS </b> for which software has been partially created (addition of data). 

The Bank Box & Warehouse modules are working for creation of data but have been subsumed by the Location Module. 

The Country module is also working for creation of data but since the scope of current Food Book operations is only in Singapore, it has not been used. However, we have seen in various media properties on Food Bank co-founder Ms Nichol Ng stated plans to expand Food Bank operations to other Asian countries. Hence, the country module will be used in the future.

2.2.10.3 - <b>Software currently not created</b> - These pertain to the 'Employee', 'Individual Beneficiary', 'Individual Donor' & An Event / Program / Activity / Roadshow   Creation Module for which volunteers would be required. e.g. Food Bank's 'Joy In Every Bundle' Activity.  

3.0 - <b>Project Judging Parameters</b> - Please find below in Screen 4 our perspective as regards our project's features across the four judging criteria of Design, Technical Complexity, Mass Usability & Creativity. 

![Hack Singapore 2022 Food Bank Challenge - VTMS Project as per four judging criteria ](http://www.kaytek.co.in/images/fbsgvtms/vtms_judging_criteria_points_1280_720.png)

<p align="center"> <b>Screen 4 - VTMS - Salient features as regards the four judging criteria </b></p> <br>

A few points as regards the above are further articulated below:

3.1 - <b>Design</b> 

3.1.1 - <b>User Interface</b> - Needs to be consistent both between modules and also within individual screens. It is important to be functionally correct so that the system look and feel and behaviour appears uniform. We have strived this across the system.

3.1.2 - <b>Software Module Reusability</b> - In addition to a consistent user interface, it is also important to have consistent design patterns in both the backend database design as well as the logic flows in the software for a strong foundational base. This will help ensure reusability leading to better long term performance and lower costs.

3.2 - <b> Technical Complexity</b> 

3.2.1 - <b> Comprehensive Functionality</b> - Technical Complexity is a derivative of Business Functionality. Within the project scope, we have strived to provide comprehensive functionality based on our understanding of the both the volunteers and administrator's roles and responsibilities. We believe this is a good starting point for helping Food Bank create a comprehensive volunteer management system.  

3.2.2 - <b> ERP / Other System Linkages </b> - Based on our understanding of requirements from Food Bank, they would have decided by this time on a Tech Partner and an ERP system. We have strived to keep in mind the various Data interfaces or linkages that may be required between VTMS and the other systems as per the future requirements. Also, phased implementation of future software modules / functionality e.g. for verification of volunteer NRIC / FIN data or Driving License data from the relevant Singapore authorities has been planned.

3.3 - <b>Mass Usability</b> 

3.3.1 - <b> Global Platform</b> - To achieve FB SG goal of ending food hunger within the shortest time frame, their operations have to be scaled up in a disproportionate manner with higher degrees of automation and digital efficiencies without increasing Administration Staff Count. A global web based cloud platform based on a solution created on an automated software (no code low code) in a reusable modular fashion can help achieve the same. 

3.3.2 - <b>Responsive Design</b> - For mass adoption, the volunteer module user interface will need to be further enhanced with responsive mobile design to ensure attraction from a young volunteer base. The same will be done for the administration module too.
  
3.4 - <b> Creativity</b>
  
3.4.1 - <b>Balance</b> - One of the toughest challenges in this solution design is to strike a fine balance between time convenience of volunteers and administration staff versus the degree of data discipline and depth required for the unstructured complex nature of the volunteering tasks in an increasingly higher level of scale of operations. 
  
3.4.2 - <b> Best Practices</b> - We strived to look at global best practices to emulate for this project's design and implementation. These can be detailed appropriately. 

4.0 - <b>Usage Instructions for checking out the system </b> :

4.1 - <b>Volunteer Role - Sample User Credentials</b> :

Username - 'mahesh@kaytek.in' 
Password - 'omsairam'

The above volunteer user has some data associated with it.

Username - 'contact@kaytek.in'
Password - 'hacksg2022'

The above volunteer user does not have much data associated with it.

4.2 - <b>Administrator Role - Sample User Credentials </b>:

Username - 'khatrimahesh@gmail.com'
Password - 'omsairam'

Username - 'naraindaskkhatri@gmail.com'
Password - 'hacksg2022'

4.3 - <b>Important</b> - When a volunteer user signs up, his or her email address is automatically registered as a volunteer in the system. When the volunteer logs into the system, it is suggested that she or he update her basic details such as Full Name as per NRIC / FIN, phone number. The user's email address is the unique key to the volunteer data in the system. 

4.4 - <b> Email addresses </b> - Avoid using Hotmail, Yahoo, Outlook and Live email addresses for credentials as users have reported these email addresses as not being able to deliver by Bubble.

5.0 - <b>Known System Issues / Limitations / Points</b>
  
5.1 - Currently, the system has facilities for adding & viewing data only in the modules. For the volunteer data, it is possible to change the non-key details. ( details other than email address). A delete facility has not been provided in the absence of clarity of business rules for retention of stakeholder data as well as the hackathon time constraints.
  
5.2 - The future modules section in the Administrative module gives details on those modules which we felt after discussions with Food Bank to keep pending for the hackathon phase. For some of these modules as mentioned, the 'Add' / 'Create' and 'View' facilities are working. Some modules like Warehouse, Bank Box were subsumed into the Location module. 
  
5.3 - Currently, our system is not checking as to whether a newly signed user has clicked on the confirmation link sent by the VTMS module. Future system operations will check for 'User's Confirmed Email status'. In this hackathon phase, we found it prudent to focus on the functional requirements of the Volunteer Task activities.
  
5.4 - There is a check in the system of a volunteer user trying to log into the administration module or vice versa. An Error message is displayed and the user is logged out of the system.
  
5.5 - The Radio Button / Check Box viewing facility is not working for the volunteer data module. Due to lack of time, the same was not pursued.  
  
5.6 - VTMS functionality of sending Email confirmations to volunteers for task application as well as task approvals is functioning.
  
5.7 - We had planned to incorporate User Login / Signup via Facebook & Google but could not do so due to time limitation.

5.9 - We could not incorporate 'Junior Club' volunteers as a separate module though it can get covered within the existing system.
  
5.10 - It is recommended to listen to the video pitch using a microphone for a better experience.
  
5.11 - We apologize in advance for any software defects / bugs in the system due to the time constraint of the hackathon. You are kindly requested to bring this to our immediate attention at our email address. We shall strive to resolve them at the earliest. 

<b>Summary</b> - We sincerely thank you for the opportunity to enable us to participate in this project and also thanking you for your valued time in reviewing our submission.

(c) Hack Singapore, Food Bank Singapore, Mahesh Khatri 2022 onwards. All rights reserved.





