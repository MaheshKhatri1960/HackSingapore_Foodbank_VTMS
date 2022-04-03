# HackSingapore_Foodbank_VTMS

1.0 - <b>Overview </b> - Volunteer to Task Management System (VTMS) - Team MK Submission for HackSingapore's No Code Low Code Challenge for Food Bank Singapore

![Hack Singapore 2022 Food Bank Challenge - VTMS - Overview](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_intro_1175_369.png)

Our proposed solution <bVolunteer Task Management System (VTMS)</b>  has two linked web cloud based software modules: a Volunteer module & an Administration module which are used as the frontend and backend work activities respectively.

![Hack Singapore 2022 Food Bank Challenge - VTMS - Module Activities](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_overview_1280_720.png)

The system is based on a web based cloud platform. Please see the following Login Screen 1.

![Hack Singapore 2022 Food Bank Challenge - VTMS - Login Screen](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_login_screen_990_528.png) <br><br>

<p align="center"> <b>Screen 1 - VTMS Login Screen with separate credentials for Volunteers and Administrators. </b></p> <br>

1.1 - <b> Volunteer Module </b> - Allows volunteers to respond to FB SG volunteer tasks available, offer time based services, view FB SG volunteer job roles responsibilities, requirements, browse task related videos and manage their task related data & metrics. See Screen 2 below.

![Hack Singapore 2022 Food Bank Challenge - VTMS - Volunteer Module Screen](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_volunteer_module_898_535.png)

<p align="center"> <b>Screen 2 - VTMS Volunteer Module - Main Scren </b></p> <br>

1.2 - <b> Administration module </b> - Enables FB SG to browse volunteer profile & interests, create tasks, approve task applications, automatically send task application receipt & task approval emails. It also stores data relating to volunteer task management - FB SG locations, facilities, work shift timings, restrictions, work areas / functions, job role duties & responsibilities, requirements & qualifications and manage database along with other key stakeholders such as beneficiaries, donors & volunteer groups. This is for both individuals & organisations. See Screen 3 below. 

![Hack Singapore 2022 Food Bank Challenge - VTMS - Administration Module Screen](http://www.kaytek.co.in/images/fbsgvtms/mk_vtms_administration_module_976_438.png)

<p align="center"> <b>Screen 3 - VTMS Administration Module - Main Scren </b></p> <br>

2.0 - <b>Project Judging Parameters</b> - Please find below in Screen 4 our perspective  as regards our project's features across the four judging criteria of Design, Technical Complexity, Mass Usability & Creativity. 

![Hack Singapore 2022 Food Bank Challenge - VTMS Project as per four judging criteria ](http://www.kaytek.co.in/images/fbsgvtms/vtms_judging_criteria_points_1280_720.png)

<p align="center"> <b>Screen 4 - VTMS - Salient features as regards the four judging criteria </b></p> <br>

A few points as regards the above are further articulated below :

2.1 - <b>Design</b> 

2.1.1 - <b>User Interface</b> - Needs to be consistent both between modules and also within individual screens. It is important to be functionally correct so that the system look and feel and behaviour appears uniform. We have strive this across the system.

2.1.2 - <b>Software Module Reusability</b> - In addition to a consistent user interface, it is also important to have consistent design patterns in both the backend database design as well as the logic flows in the software for a strong foundational base. This will help ensure reusability leading to better long term performance and lower costs.

2.2 - <b> Technical Complexity</b> 

2.2.1 - <b> Comprehensive Functionality</b> - Technical Complexity is a derivative of Business Functionality. Within the project scope, we have strived to provide comprehensive functionality based on our understanding of the both the volunteers and administrator's roles and responsibilities. We believe this is a good starting point for helping Food Bank create a comprehensive all encompassing Volunteer management system.  

2.2.2 - <b> ERP / Other System Linkages </b> - Based on our understanding of requirements from Food Bank, they would have decided by this time on a Tech Partner and an ERP system. We have strived to keep in mind the various Data interfaces or linkages that may be required between VTMS and the other systems as per the future requirements. Also, phased implementation of future software modules / functionality e.g. for verification of volunteer NRIC / FIN data or Driving License data from the relevant Singapore authorities has been planned.

2.3 - <b>Mass Usability</b> 

2.3.1 - <b> Global Platform</b> - To achieve FB SG goal of ending food hunger within the shortest time frame, their operations have to be scaled up in a disproportionate manner with higher degrees of automation and digital efficencies without increasing Administration Staff Count. A global web based cloud platform based on a solution created on an automated software (no code low code) in a reusable modular fashion can help achieve the same. 

2.3.2 - <Responsive Design> - For mass adoption, the volunteer module user interface will need to be further enhanced with responsive mobile design to ensure attraction from a young volunteer base. The same will be done for the administration module too.
  
2.4 - <b> Creativity</b>
  
2.4.1 - <b>Balance</b> - One of the toughest challenges in this solution design is to strike a fine balance between time convenience of volunteers and administration staff versus the degree of data discipline and depth required for the unstructured complex nature of the volunteering tasks in an increasingly  higher level of scale of operations. 
  
2.4.2 - <b> Best Practices</b> - We strived to look at global best practices to emulate for this project's design and implementation. These can be detailed appropriately. 

3.0 - <b>Usage Instructions for checking out the system </b> :

3.1 - <b>Volunteer Role - Sample User Credentials</b> :

Username - 'mahesh@kaytek.in' 
Password - 'omsairam'

The above volunteer user has some data associated with it.

Username - 'contact@kaytek.in'
Password - 'hacksg2022'

The above volunteer user does not have much data associated with it.

3.2 - <b>Administrator Role - Sample User Credentials </b>:

Username - 'khatrimahesh@gmail.com'
Password - 'omsairam'

Username - 'naraindaskkhatri@gmail.com'
Password - 'hacksg2022'

3.3 - <b>Important</b> - When a volunteer user signs up, his or her email address is automatically registered as a volunteer in the system. When the volunteer logs into the system, it is suggested that she or he update her basic details such as Full Name as per NRIC / FIN, phone number. The user's email address is the unique key to the volunteer data in the system. 

3.4 - <b> Email addresses </b> - Avoid using Hotmail, Yahoo, OUtlook and Live email addresses for credentials as users have reported these email addresses as not being able to deliver by Sendgrid which is the service used by Bubble.

4.0 - <b>Known System Issues / Limitations / Points</b>
  
4.1 - Currently, the system has facilities for adding & viewing data only in the modules. For the volunteer data, it is possible to change the non-key details. (ie.details other than email address). A delete faclity has not been provided in the absence of clarity of business rules for retention of stakeholder data as well as the hackathon time constraints.
  
4.2 - The future modules section in the Administrative module gives details on those modules which we felt after discussions with Food Bank to keep pending for the hackathon phase. For some of these modules as mentioned, the 'Add' / 'Create' and 'View' facilities are working. Some modules like Warehouse, Bank Box were subsumed into the Location module. 
  
4.3 - Currently, our system is not checking as to whether a newly signed user has clicked on the confirmation link sent by the VTMS module. Future system operations will check for 'User's Confirmed Email status'. In this hackathon phase, we found it prudent to focus on the functional requirements of the Volunteer Task acivities.
  
4.4 - There is a check in the system of a volunteer user trying to log into the administration module or vice versa. An Error message is displayed and the user is logged out of the system.
  
4.5 - The Radio Button / Check Box viewing facility is not working for the volunteer data module. Due to lack of time, the same was not pursued.  
  
4.6 - VTMS functionality of sending Email confirmations to volunteers for task application as well as task approvals is functioning.
  
4.7 - We had planned to incorporate User Login / Signup via Facebook & Google but could not do so due to time limitation.
  
4.8 - It is recommended to listen to the video pitch using a microphone for a better experience.
  
4.9 - We apologize in advance for any software defects / bugs in the system due to the time constraint of the hackathon. You are kindly requested to bring this to our immediate attention at our email address.

  <b>Summary</b> - We sincerely thank you for the opportunity to enable us to participate in this project and also thanking you for your valued time in reviewing our submission.

(c) Hack Singapore, Food Bank Singapore, Mahesh Khatri 2022 onwards.





