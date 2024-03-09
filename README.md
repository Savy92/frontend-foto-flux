# Foto Flux

Foto Flux is a social media platform built using React where users can post and share pictures with others. It provides a user-friendly interface for browsing, uploading, and interacting with images in a social context.
<br>
The live link can be found here: [Live Site - Foto Flux](https://frontend-foto-flux-42b405ca1597.herokuapp.com/)
<br>

![Mockup](/static/images/i-am-responsive.png)

## The Strategy Plane

## Site Goals

My social media platform, Foto Flux, is dedicated to fostering a vibrant online community where users can connect, share, and engage with visually inspiring content. The primary goal is to provide users with an intuitive and enjoyable experience, encouraging regular interaction and exploration of the platform's features.
<hr>

## Agile Planning

The development process follows Agile principles, with a focus on transparency, collaboration, and iterative improvement. I utilized a Kanban board within GitHub Projects to manage the user stories and tasks efficiently. Each user story represents a specific feature or functionality from the user's perspective, organized into our Kanban board backlog. With clear workflow columns such as 'To Do,' 'In Progress' and 'Done,' to track the progress of each task as it moves through our development pipeline.

![Kanban](/static/images/user-stories.png)

<hr>
<br>

## Features:

### Favicon: 
The favicon feature ensures your website has a recognizable icon displayed in the browser tab, enhancing brand visibility and user experience.

![Favicon](/static/images/favicon.png)

### Navbar: 
The responsive navigation bar adapts seamlessly to different screen sizes, providing intuitive navigation for both desktop and mobile users. It includes a hamburger menu for mobile devices, optimizing space and accessibility on smaller screens.

![Navbar](/static/images/navbar.png)

### Authentication: 
Authentication functionality allows users to securely register, log in, and access personalized features. It ensures that only authorized users can interact with the platform's content and functionality.


### Homepage: 
The homepage displays a curated feed of all users' posts, providing a centralized hub for users to discover and engage with content uploaded by the community.

![Homepage](/static/images/homepage.png)

### Create Post Page:
The create post page offers users a streamlined interface to upload and share their own content, encouraging active participation and contribution to the platform.

![Createpost](/static/images/create-post.png)

### Feed Page: 
The feed page presents users with a personalized feed of posts tailored to their interests and interactions, facilitating engagement and discovery of relevant content.

![Feed](/static/images/feed.png)

### Liked Page: 
The liked page showcases posts that the user has liked, enabling them to revisit and interact with their favorite content easily.

![Liked](/static/images/liked.png)

### Contact Page: 
The contact page offers a dedicated space for users to reach out with any issues, feedback, or inquiries, fostering communication and addressing user concerns promptly.

![Contact](/static/images/contact.png)

### Profile Page: 
The profile page provides users with a customizable space to showcase their information, activity, and preferences. It serves as a hub for managing personal settings and interactions within the platform.

![Profile](/static/images/profile.png)

### Sign Out Option: 
Logged-in users have the convenience of signing out securely from their accounts, ensuring privacy and security when accessing the platform from shared or public devices.

![Signout](/static/images/sign-out.png)

### Sign In/Sign Up Options:
Logged-out users are presented with clear sign-in and sign-up options, streamlining the process of accessing the platform and encouraging new user registrations.

![Signin](/static/images/sign-in.png)

![Signup](/static/images/sign-up.png)
### Search Bar: 
The search bar functionality allows users to search for posts by keywords used in the title or content, facilitating content discovery and navigation within the platform.

![Search](/static/images/search.png)

### Like/Unlike Feature: 
The like/unlike feature enables users to express their appreciation for posts by liking or unliking them, fostering engagement and interaction within the community.

![Like](/static/images/like.png)

### Comment Feature: 
The comment feature allows users to create, view, edit, or delete comments on posts, facilitating discussion, feedback, and interaction among users.

![Comment](/static/images/comment.png)

### Future Features

As a future feature, a bookmark component will be implemented to allow users save posts in which they would like to view at a later date.

<hr>
<br>


## Design

### Colour-Scheme
The platform adopts a carefully curated color scheme designed to enhance user experience and aesthetics. Following the 60-30-10 rule of color balance, i've opted for a clean and minimalist approach with a white background providing a sense of spaciousness and clarity. Dark blue hues dominate our components, offering a visually appealing contrast against the background and ensuring readability and focus. Light green accents punctuate the interface, particularly for buttons, injecting a touch of vibrancy and signaling actionable elements for users.


### Typography

The main font used on the website is "DM Sans".
<hr>
<br>

## Technologies

* React
    * Main framework used to create the user interface
* Node
    * Package manager used to install dependencies
* Eslint
    * Linting tool used in order to check best practice coding standards
* Heroku
    * Used for application hosting
* Git
    * Version control software
* Github
    * Repository used to store base code and docs

<hr>
<br>

## Testing

Feature            | Testing Performed                                      | Test Results                    |
|--------------------|--------------------------------------------------------|---------------------------------|
| Favicon            | Verified favicon displays correctly in supported browsers. | Passed                         |
| Navbar             | Tested navigation bar functionality on desktop and mobile devices. | Passed                     |
| Authentication     | Conducted user registration, login, and logout tests.  | Passed                         |
| Homepage           | Verified all users' posts are displayed correctly on the homepage. | Passed                    |
| Create Post Page   | Tested uploading, editing, and deleting posts.        | Passed                         |
| Feed Page          | Ensured personalized feed displays correctly based on user preferences. | Passed                     |
| Liked Page         | Tested display of liked posts for logged-in users.    | Passed                         |
| Contact Page       | Checked functionality to submit queries and issues.    | Passed                         |
| Profile Page       | Verified display of user information and settings.    | Passed                         |
| Sign Out Option    | Tested signing out functionality for logged-in users. | Passed                         |
| Sign In/Sign Up    | Checked usability of sign-in and sign-up processes.   | Passed                         |
| Search Bar         | Verified search functionality for posts by keywords.  | Passed                         |
| Like/Unlike Feature| Tested liking and unliking posts.                     | Passed                         |
| Comment Feature    | Ensured creation, viewing, editing, and deletion of comments. | Passed 

## Lighthouse Testing

![lighthouse](/static/images/light-house.png)

<hr>
<br>

## Deployment
### Heroku Deployment

The site was deployed to Heroku. The steps to deploy are as follows:

* Navigate to heroku and create an account
* Click the new button in the top right corner
* Select create new app
* Enter app name
* Select region and click create app
* Click the resources tab and search for Heroku Postgres
* Select hobby dev and continue

* Click the deploy tab
* Scroll down to Connect to GitHub and sign in / authorize when prompted
* In the search box, find the repositoy you want to deploy and click connect
* Scroll down to Manual deploy and choose the main branch
* Click deploy

<br>

### Run Locally

Navigate to the GitHub Repository you want to clone to use locally:

- Click on the code drop down button
- Click on HTTPS
- Copy the repository link to the clipboard
- Open your IDE of choice (git must be installed for the next steps)
- Type git clone copied-git-url into the IDE terminal

The project will now have been cloned on your local machine for use.

Install Dependencies:

```npm install```

Run Application:

```npm start```
<br>

### Forking

Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

- Navigate to the GitHub Repository you want to fork.

- On the top right of the page under the header, click the fork button.

- This will create a duplicate of the full project in your GitHub Repository.
<hr>
<br>

## Credits

-   [React Bootstrap documentation:](https://react-bootstrap.netlify.app/)  - Documentation used for styling and to build responsive web pages
-   [Code Institute:](https://codeinstitute.net/)  Walkthrough modules for the Moments app
-   [Code Institute Slack Community:](https://app.slack.com/)  Slack community for troubleshooting and FAQ.
-   [Code Institute Tutor Support:](https://app.slack.com/)  For help and support
-   [React documentation:](https://legacy.reactjs.org/docs/getting-started.html)  Everything you need to know about React
-   [Stack Overflow:](https://stackoverflow.com/)  For troubleshooting and FAQ
-   [W3Schools:](https://www.w3schools.com/)  Online Web Tutorials


