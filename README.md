## SkillStream - Free Educational Platform

## Project Overview

SkillStream is a full-stack web application designed to democratize education by providing free access to valuable skills and knowledge. The platform leverages volunteer contributions to offer educational content to learners who may not have the financial means for traditional education.

## Features

- React-based single-page application with Vite
- Node.js and Express backend with MongoDB integration
- YouTube video integration for course content
- Admin dashboard for platform management
- User authentication and session handling
CRUD operations for student management
- Responsive design for various screen sizes

## Technology Stack

## Frontend

- React
- Vite
- React Router
- Custom CSS
- Fetch API

## Backend

- Node.js
- Express.js
- MongoDB with Mongoose
- YouTube Data API v3
- express-session
- dotenv
- cors

## API Endpoints

- **GET /api/contributors**: Fetch contributors
- **GET /api/youtube/videos**: Fetch YouTube videos
- **POST /api/login**: User login
- **GET /api/students**: Fetch students
- **POST /api/students**: Add student
- **PUT /api/students/:id**: Update student
- **DELETE /api/students/:id**: Delete student
- **POST /api/logout**: User logout

## Page-by-Page Breakdown

### Home Page
- Purpose: Welcome users and showcase platform features
- Elements:
  - Static: Logo, navigation, welcome message, hero image
  - Dynamic: Reviews section
- **Technologies**: React components, CSS Grid, custom animations

### About Page

- **Purpose**: Share mission and team information
- **Elements**:
  - Static: Mission statement, impact statistics
  - Dynamic: Team member profiles
- **Technologies**: React hooks, API integration, CSS Flexbox

### Courses Page

- **Purpose**: Provide access to educational content
- **Elements**:
  - Static: Page layout
  - Dynamic: Video list, search functionality
- **Technologies**: YouTube API integration, React state management

### Admin Section

- **Login Page**:
  - Secure authentication
  - Session management
- **Dashboard**:
  - Statistics display
  - Activity tracking
- **Work Space**:
  - CRUD operations for student management
  - Real-time updates

## Key Features Implementation

- **Authentication System**:
  - Express-session for secure login/logout
  - Protected routes for admin access
- **YouTube Integration**:
  - Dynamic video fetching and search
- **CRUD Operations**:
  - Student management system
  - Modal-based editing interface
- **Responsive Design**:
  - Custom CSS with Grid and Flexbox

## Future Enhancements

- User registration for students
- Course creation interface for admins
- Enhanced search functionality
- More robust state management
- Original video content creation
- Advanced authentication methods

## Resources

**Backend**

- [MERN Stack Tutorial with Deployment – Beginner's Course](https://www.youtube.com/watch?v=O3BUHwfHf84)
- [Fetching All Videos of a channel | Youtube Data API V3](https://www.youtube.com/watch?v=DuudSp4sHmg)
- [How to Get YouTube API Key 2024](https://www.youtube.com/watch?v=LLAZUTbc97I)
- [Add YouTube functionality to your app](https://developers.google.com/youtube/v3)
- [YouTube Data API Tutorial - Search for Videos](https://www.youtube.com/watch?app=desktop&v=QY8dhl1EQfI)
- [Register and Login Tutorial | ReactJS, NodeJS, MySQL - Cookies, Sessions, Hashing](https://www.youtube.com/watch?v=sTHWNPVNvm8&t=381s)
- [Cookie and Session (II): How session works in express-session](https://medium.com/@alysachan830/cookie-and-session-ii-how-session-works-in-express-session-7e08d102deb8)
- [Session Secret Value Error](https://forum.freecodecamp.org/t/session-secret-value-error/457249)
- [Learn w/ Leon & Friends] (Discord Channel)

**Frontend**

- https://www.geeksforgeeks.org/link-and-navlink-components-in-react-router-dom/
- https://dev.to/salehmubashar/create-active-links-using-react-router-v6-2gle
- https://www.pexels.com/photos/
- https://commentpicker.com/youtube-channel-id.php#google_vignette
- https://developer.mozilla.org/en-US/docs/Learn/CSS/Howto/Create_fancy_boxes (Used for styling content boxes and cards)

**CSS Resources**

- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout (For your grid layouts in courses, about, and home pages)
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/ (For your flexible layouts in sidebar and content sections)
- https://developer.mozilla.org/en-US/docs/Web/CSS/gradient (For your gradient backgrounds)
- https://css-tricks.com/almanac/properties/b/box-shadow/ (For your box shadow effects across components)
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions (For your hover transitions and animations)
- https://css-tricks.com/custom-scrollbars-in-webkit/ (For your custom scrollbar styling in sidebar)
- https://developer.mozilla.org/en-US/docs/Web/CSS/position (For fixed positioning of logo and sidebar)
- https://css-tricks.com/almanac/properties/t/transform/ (For your hover transform effects)
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout (For your stats and contributors grid layouts)
- https://css-tricks.com/almanac/properties/b/border-radius/ (For rounded corners across components)
- https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals (For text styling and shadows)
- https://css-tricks.com/styling-form-input-buttons/ (For your form input and button styling)
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders (For background effects and borders)
- https://css-tricks.com/modal-dialog-styling/ (For your modal styling in WorkSpace)

## Thanks

I would like to express my deepest gratitude to:

Per Scholas for providing me with this incredible opportunity to learn and grow as a developer. This transformative experience has opened new doors and possibilities in my tech career.

Kevin Dang, my classmate and friend, for his constant support and assistance throughout this project and many other projects. Your willingness to help whenever needed made a huge difference.

My instructors Colton and Abraham, whose expertise, patience, and dedication to teaching have been instrumental in my growth as a developer. Thank you for sharing your knowledge and guiding me through this journey.

All my classmates who have been an incredible source of support, inspiration, and collaboration throughout this program. Your camaraderie and willingness to help one another has created a truly enriching learning environment.

And special thanks to my dear friend of 28 years overseas, whose encouragement and help throughout my learning journey and especially with this project has been invaluable.

Your support made this possible. Thank you!