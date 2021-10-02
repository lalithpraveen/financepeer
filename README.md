# Financepeer React App

In this project I created a web app that uses reactjs to **Financepeer**

As a demonstration of my skills, I built an app that utilizes components to fetch data from an internal server, displays that data,introduces **routing** concepts, **authenticates** and **authorizes** users, and adds responsiveness to the website.

### Refer to image below:

<br/>
<div style="text-align: center;">
    <img src="https://res.cloudinary.com/strawhat/image/upload/v1633161344/currency%20codes/finance_i9ci0n.gif" alt="currency-converter-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Project Details

<details>
<summary>Click to view the Functionality that are added</summary>

#### Project Functionality

The app have the following functionalities

- Signup Route

  - To create an account, users will need to provide their email address and password.
  - There will be an error message if the password and confirmation password don't match.

- Login Route

  - Signing up is easy with a valid username and password. Users will be able to
    access their accounts once they've registered.
  - Navigation links are provided in the Navbar for users to access Home, Login, and Signup.
  - Users will be able to view the website responsively in mobile view, tablet view as well

- Home Route

  - JSON files can only be uploaded via this panel. I used the local storage after I've submitted the selected file to save the data.
  - After clicking the logout link, users will be able to navigate to the login page.
  - A page dedicated to data will be accessed as soon as you click Data on the navbar.
  - A navbar button will be displayed only when the user submits a json file or local storage already stores json data.

- Forget Password Route

  - In case a user forgets his password, he can update it by using the forget password feature

- DisplayData Route
  - Users will be able to view their individual details from JSON files retrieved from local storage.

#### Project Details

- In order to focus my efforts on the functionality of this app rather than styling it, I used Bootstrap for quick styling for most of the components.
- I built a signup page to store user information in local storage, and then I built a login page to cross-check user input with the data in local storage, and if they do not exist, it will show the user an error.
- Upon successfully entering user details and pressing login, the user will be redirected to the home page.
- A flag is saved in local storage when a user enters the home page after clicking login so that I can communicate with the app. The flag is changed to false when the user clicks logout.Only authorized users will be able to access the home page. Everyone else will be redirected to the login page.
- All records were displayed on one page.

### Improvements to come

- There will be the ability to store emails and passwords for multiple users.
- A pagination was needed to limit the number of details displayed on each page to ten.
- Clicking a particular post will redirect the user to the posts by that particular user of that particular post
- A user interface and user experience needs to be improved to be attractive.
- Had to make components DRY by eliminating code lines re-used more than once.

</details>
