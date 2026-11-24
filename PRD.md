CAMPUS LOST AND FOUND SYSTEM
1. Introduction
The Campus Lost and Found System is a web application designed to help students and staff report and recover items lost or found within the school environment. Students often lose personal belongings such as phones, bags, laptops, identity cards, textbooks, chargers and keys. When this happens, they usually depend on WhatsApp groups, social media platforms or asking people around the school. However, these methods are not always reliable because messages can get buried, and some students may not belong to the same groups. This system will provide one central platform where users can report missing items, report items they have found, search for items and make claims when they identify their belongings.
2. Problem Statement
The current process of finding lost items on campus is not well organised. Students may spend a lot of time asking questions or checking different platforms before finding useful information.Some of the major problems include:
•	There is no central platform for reporting lost and found items.
•	Messages shared on social media can easily get buried.
•	Students may not receive information about items found by other people.
•	It can be difficult to confirm whether an item belongs to someone claiming it.
•	There is no proper record of reported and recovered items.
These problems can lead to financial loss, wasted time and unnecessary stress for students.
3. Proposed Solution
The proposed solution is a web-based Lost and Found System that allows students and staff to report and search for missing or found items.
Users will be able to create an account, log in, submit reports and search for items. Anyone who finds an item can upload its details, while someone who has lost an item can check the platform to see whether it has been reported.
The system will also include a claiming process to help confirm ownership before an item is returned.
The main sections of the system will include:
Home: Displays general information and recently reported items.
Report Lost Item: Allows users to submit details about items they have lost.
Report Found Item: Allows users to provide information about items they have found.
Search Items: Allows users to search for items using names, categories or locations.
My Reports: Allows users to view and manage the reports they have submitted.
4. Target Users
The system will mainly serve three groups of users.
Students: Students can report lost items, report found items and search for their missing belongings.
Finders: Students or staff members who find items can submit reports so the rightful owners can identify them.
Administrators: Administrators will manage reports, review claims and help ensure that the platform is used properly.
5. Main Features and Requirements
The first version of the system will focus on the most important features needed to make it useful.
•	User Registration: Users can create accounts by providing their details.
•	User Login: Registered users can securely access their accounts.
•	Report Lost Items: Users can provide the name, category, description, location and date an item was lost. They may also upload an image.
•	Report Found Items: Users can provide information about items they have found.
•	View Reports: Users can see available lost and found item reports.
•	Search and Filter: Users can search for items by name, category, location or status.
•	Claim Items: Users can submit a claim when they recognise an item as theirs.
•	Ownership Verification: The system will allow the necessary details to be checked before an item is returned.
•	Update Item Status: Item statuses can be changed as the recovery process continues.
•	Admin Management: Administrators can review reports and manage inappropriate or incorrect submissions.
6. Non-Functional Requirements
The system should be easy to use, even for people who are not very familiar with technology. Its pages should load within a reasonable time, and users' personal information should be protected. It should also work properly on mobile phones, tablets and computers. The system should be reliable, easy to maintain and available whenever users need it, provided they have an internet connection.
7. Technology Requirements
The following technologies are proposed for developing the system:
•	HTML: To create the structure of the web pages.
•	CSS: To handle the design and appearance of the website.
•	JavaScript: To add interaction and improve the user experience.
•	MySQL: To store user details, item reports and claims.
•	Backend Technology: The team will decide on the backend technology to connect the website to the database and handle server-side operations.
8. Database Design
The system will use a MySQL database to store and manage its information. The main database tables will include:
Users Table
This table will store information about registered users. Fields: user_id, full_name, matric_number, email, password and role.
Items Table
This table will store details of lost and found items.Fields: item_id, user_id, item_name, category, description, report_type, location, date_reported, image and status.
Claims Table
This table will store information about users who claim reported items. Fields: claim_id, item_id, claimant_id, claim_description, verification_answer, claim_status and date_claimed.
Categories Table
This table will contain the different categories of items, such as electronics, documents, clothing, books and accessories. Fields: category_id and category_name. The tables will be connected through their IDs. For example, one user can report several items, and an item can receive more than one claim.
9. System Workflow
The system will follow a simple process.
Reporting a Lost Item: A user logs in, opens the Report Lost Item section, enters the required details and submits the report. The information is then saved in the database.
Reporting a Found Item: A user who finds an item logs in and submits its details. Other users can then view the report and search for it.
Claiming an Item: A user who recognises an item submits a claim and provides information to show that the item belongs to them.
Verification and Collection: The administrator or responsible person reviews the claim and checks the ownership information. If the claim is approved, arrangements can be made for the item to be returned. Its status is then updated to Returned.
10. Project Scope and Limitations
The first version of the system will focus on helping members of the university community report, search for and recover lost items.It will include account registration, login, lost and found reports, searching, claiming and basic administrative management.However, the first version will not include advanced features such as automatic image recognition, live chat or complex item-matching technology. These features may be considered for future improvements.The system will also require an internet connection. In addition, the successful return of an item will depend on proper ownership verification.
11. Research and User Feedback
The team plans to gather information from students through surveys, interviews and observation. This will help us understand how students currently report lost items and what features they would find useful.The feedback collected will guide the development of the system and help the team make improvements based on users' actual needs.
12. Future Improvements
After completing the first version, the team may introduce additional features such as email notifications, improved matching between lost and found reports, direct messaging between users, image recognition and a more advanced administrator dashboard.These improvements will make the system more useful and convenient.
13. Conclusion
The Campus Lost and Found System is designed to make reporting and recovering lost items easier within the university. Instead of depending only on social media groups and informal announcements, students and staff will have one organised platform to report and search for missing belongings.By providing features such as item reporting, searching, claiming and ownership verification, the system will help reduce the difficulties associated with finding lost items and make the process more organised and reliable.

