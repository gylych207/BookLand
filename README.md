

## Overview
**BookRental** is a web application in which you can find books and articles for rent.

## MVP
- Creating Landing Screen.
- Getting all books in listing Screen with proper table relations.
- Editing the Book through Customize screen.
- Creating Book info screen with functional Edit and Delete buttons.
- Creating Sell your book Screen.

### Libraries and Dependencies
|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | for front end Development.                 |
|   React Router   | to set up react routes |
|     axios        | as a api call tool|
|     bcrypt       | for the the authenctication |
|     cors         | to serve frond end and backend|

<br>

### Client (Front End)

#### Wireframes
https://xd.adobe.com/view/8c170485-3b4b-43ec-ada1-30c897aaf7d0-d944/ (url)

#### Component Tree
https://www.figma.com/file/ZrpzgNjpGQiZTD1yN2LlCh/Untitled?node-id=0%3A1

#### Component Hierarchy
src
|__ containers/
      |__ MainContainer.jsx
|__ layouts/
      |__Layout.jsx
|__ Screens/
      |__Landing.jsx
      |__BookInfo.jsx
      |__Login.jsx
      |__Register.jsx
      |__BookInfo.jsx
      |__Sell your Book.jsx
      |__ShoppingCard.jsx
      |__Customize Book.jsx
      |__Extension Reqest.jsx
|__ services/
      |__api-config.js
      |__auth.js
      |__books.js
      |__authors.js
      |__users.js

#### Time Estimates
| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| set up models.      |    H     |     3 hrs      |     0 hrs     |    N/A      |
| Set up tables.      |    H     |     2 hrs      |     0 hrs     |    N/A      |
| Set up relations    |    H     |     3 hrs      |     0 hrs     |    N/A      |
| Set up routes       |    H     |     3 hrs      |     0 hrs     |    N/A      |
| Backend Debugging.  |    H     |     5 hrs      |     0 hrs     |    N/A      |
| React Structure.    |    H     |     2 hrs      |     0 hrs     |    N/A      |
| Landign Screen.     |    H     |     2 hrs      |     0 hrs     |    N/A      |
| Landing S   Styling |    M     |     3 hrs      |     0 hrs     |    N/A      |
| Catalog Screen.     |    H     |     2 hrs      |     0 hrs     |    N/A      |
| Delete Button       |    H     |     1 hrs      |     0 hrs     |    N/A      |
| Update Button       |    H     |     3 hrs      |     0 hrs     |    N/A      |
| Cata-Screen styling |    M     |     5 hrs      |     0 hrs     |    N/A      |
| Info Screen         |    H     |     1 hrs      |     0 hrs     |    N/A      |
| Info Screen styling |    M     |     1 hrs      |     0 hrs     |    N/A      |
| Shopping Card       |    H     |     5 hrs      |     0 hrs     |    N/A      |
| ShoppingCard styling|    M     |     3 hrs      |     0 hrs     |    N/A      |
| Sell your Book.     |    H     |     2 hrs      |     0 hrs     |    N/A      |
| SellYourBook styling|    M     |     2 hrs      |     0 hrs     |    N/A      |
| Login Screen        |    H     |     2 hrs      |     0 hrs     |    N/A      |
| Login Screen Styling|    M     |     2 hrs      |     0 hrs     |    N/A      |
| register            |    H     |     2 hrs      |     0 hrs     |    N/A      |
| register  Styling   |    M     |     2 hrs      |     0 hrs     |    N/A      |
| Extend setup        |    L     |     2 hrs      |     0 hrs     |    N/A      |
| Login Screen Styling|    L     |     2 hrs      |     0 hrs     |    N/A      |
| Update Form         |    H     |     2 hrs      |     0 hrs     |    N/A      |
| Update Form  styling|    M     |     2 hrs      |     0 hrs     |    N/A      |
| TOTAL               |          |     64 hrs     |     N/A       |    N/A      |

#### ERD Model
https://lucid.app/lucidchart/invitations/accept/a2b48a76-10f5-464d-8e88-b564fc379c1e
https://lucid.app/lucidchart/invitations/accept/2ff99da0-249f-4425-9c1a-f89b5a37a55c

## Post-MVP
- Implementing Sort and Filter
- Creating Search
- Ask extension Section
- Customizing shopping card 
- Creating Sell your book Screen.


