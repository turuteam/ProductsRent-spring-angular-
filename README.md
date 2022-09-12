# ProductsRent-spring-angular-

Need a full stack developer to create an Ecommerce app with SpringBoot, Angular, and MySql

DELIVERABLES
MVP Due 9/8
MVP includes working login/signup page with auth for Owners, Borrowers, Admin
Owners can post and delete items, with picture and description
Borrowers can borrow and return items, with picture and description

Complete web app due: 9/12

ADDITIONAL INFORMATION
Deadlines:
MVP - Due September 8th by Midnight EST
Completed web app and presentation due: September 12th by Midnight EST
MVP includes working login/signup page with auth for Owners, Borrowers, Admin
Owners can post and delete items, with picture and description
Borrowers can borrow and return items, with picture and description
Problem:
○ Do you have random items around the house that’s not in use?
○ Having a hard time keeping track of who borrows those items?
Solution:
I propose a solution in building a web app to keep track of items that you have in the
house. With this app, you can add a photo and short description of your items such as
books, lawn tools, DVDs, etc. Your friends and family can sign up to the app, view the
items to borrow and return.
(Approved) Capstone Proposal
Sunday, September 4, 2022 4:32 PM

Setup Springboot and angular project
Setup database - My SQL
Separate Git Repo for Springboot/Angular
Install dependencies (Define dependencies)
Tech stack:
Springboot
Angular
H2 embedded database or MySQL
Vscode/intellij
Postman
Git/Github
Java 8 or later
Front-End Routes
/signup
-To create an account
/signin
-To get a JWT
/home
-See available items to borrow
/owner
-Can add and remove post of items
/borrower
-Can view, borrow, and return items
/admin
-Can view data from both owner and borrower
What entities are needed?
Admin = firstName, lastName, username, email, password = Owner
firstName, lastName, username, email, password = Borrower
Admin has master list of all data
Owner =
ID
firstName,
lastName,
userName,
email,
password,
items_to_post,
items_available,
items_returned
Borrower = firstName,
lastName,
userName,
email,
password,
items_borrowed,
items_returned
Items = Title,
Photo,
Description,
Availablity
What are the tables needed?
Admin - Full CRUD, Add/Remove/List Items
Owner - Add/Remove/List/Post Items
Borrower - Review items/ borrow and return items
Items- Listed/Added/Removed
What are the relationships?
Owner to Borrower - One to Many
Borrow to Owner - Many to One
Borrower to Items - One to Many
Items to Borrower - Many to One
Owner to Items - One to Many
Items to Owner - Many to One
Authentication
JWT authentication
-JWT will contain the user id
-Properly encoded password
App Non-Final Features:
• Simple Sign Up & Sign In Login Screen
• Implement token and role base auth using spring boot (JWT)
• Implement token and role base auth using angular (JWT)
• Setup Springboot/Angular for Borrower App
• Rename Spring Boot Project (if needed)
• Rename Angular Project (if needed)
• Designing Login Form Using Angular Material UI Library
• Create API to Add Product Details
• Create Form to Save/Add Product Details (For admin/owner)
• Create API to Upload Images to Spring Boot
• Upload Images in Angular (Using Spring Boot API)
• Showing the Selected Image Preview (Uploading Images in Angular)
How to upload images and display in Angular (How to drag and
drop)
•
• Finalizing Add new product component (Adding Security)
• Creating API to Get all Product Details
• Showing All Product Details using Angular Material Table (To Admin)
• Creating API to Delete Product Details
• Deleting Product Details (UI Work)
• How to Show Images to User? (Image Bytes to File)
• Validation/Tests
Nice to Have (But not required):
Message capability between Owner/Borrower
Due date for return items
Upload feature with the camera for mobile devices
Reviews & Ratings
Social Media Sharing
Built In Camera
Chat
Call
Activity records: pending orders, sales, returns, etc
