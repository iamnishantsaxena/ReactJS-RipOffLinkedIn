# LinkedIn Clone using Vanilla JS

RipOffLinkedIn is a frontend website built in Vanilla JS that serves as a rip-off version of the popular professional social networking tool LinkedIn. It interacts with a RESTful API HTTP backend built in JavaScript (NodeJS express server).

## Features

### Registration & Login
- Users can register and log in to the site.
- Login form with email and password fields.
- Registration form with email, name, password, and confirm password fields.

### Error Handling
- Error popups are displayed when there are frontend or backend errors.
- Popups can be closed by pressing an "x" or "close" button.

### Basic Feed
- Displays a feed of user content on the home page.
- Fetches feed data from the API using the `GET /job/feed` endpoint.
- Jobs are displayed in reverse chronological order.
- Each job displays the user who made the post, posting time, job content, likes count, and comments count.

### Advanced Feed
- Users can see a list of users who have liked a job.
- Users can see a list of comments on a job.
- Users can like a job and trigger an API request using `PUT /job/like`.
- Users can paginate through the feed using the position token with `GET /job/feed`.

### User Profiles
- Users can view other users' profiles.
- Profiles display information about the user and all jobs made by that user.
- Profiles also display the list of users watching that profile.

### Updating User Profile
- Users can update their own personal profile using `PUT /user`.
- Users can update their email address, password, name, and image.

### Watching/Unwatching
- Users can watch/unwatch other users' profiles.
- A button is provided to watch/unwatch a user on their profile page.
- Users can also enter an email address to watch a particular user from the feed screen.

### Adding & Updating Content
- Users can add new jobs using `POST /job`.
- Users can update/delete their own jobs using `PUT /job` and `DELETE /job`.
- Users can leave comments on jobs using `POST /job/comment`.

### Challenge Components
- Infinite Scroll: Users can infinitely scroll through results in the feed.
- Live Update: Job likes and comments update without page refresh.
- Push Notifications: Users receive push notifications when a watched user posts a job.

### Bonus Marks
- Extra features that make the web app stand out.
- Additional frontend form validations or other enhancements.

## Getting Started

1. Clone the repository.
2. Install dependencies for the frontend and backend.
3. Start the backend server.
4. Start the frontend server.
5. Access the web app in your browser.

## Constraints & Assumptions

- The project is implemented in ES6-compliant Vanilla JavaScript.
- External JavaScript libraries are not allowed, except for small amounts of general-purpose code with proper attribution.
- The project should be mobile-responsive and follow standard accessibility guidelines.
- The code should be clean, well-commented, and well-organized.
- The web app must be a single page app, with all dynamic changes made through JavaScript DOM manipulation.
