# work-intergrated-poe


Empowering the Nation - App
This is a mobile application designed to help empower domestic workers and gardeners by providing them with access to various upskilling courses and additional resources. The app offers features for course viewing, fee calculation, user registration, login, and more.

Features
1. Home Screen
Logo and Title: Displays the logo and a description of the project.
Hamburger Menu: A hamburger menu icon at the top-left of the screen that, when tapped, shows additional course-related options.
Navigation Links:
Apply: Navigates to a screen for applying to the courses.
Login: Navigates to the login screen for registered users.
Visit Our Website: Opens an external URL to view the organization’s website.
Course Viewing: Links to various courses, such as Six-Week Courses, Six-Month Courses, and All Courses Details.
Course Specifics: Links to specific courses like Child Minding, Cooking, and First Aid, which navigate to the course details screen.
Calculate Fees: Navigates to a screen where users can calculate fees for the courses they wish to take.
2. WebView Integration
When the user taps the "Visit Our Website" link, a WebView component is used to open a local HTML file or an online URL. This is used to display additional resources like course information, terms, and conditions, or other helpful resources.
Local HTML File: The app can load local HTML files from the device and display them within the app.
External URLs: The app can open external links directly in the WebView, allowing users to access websites without leaving the app.
3. Hamburger Menu
The hamburger menu provides a collapsible list of links that are conditionally rendered based on whether the menu is open or closed.
Links in Menu:
View Six-Week Courses
View Six-Month Courses
View All Courses Details
Course Links: Links to specific courses like "Child Minding", "Cooking", and "First Aid".
Fees Calculator: Opens the fees calculator screen where users can calculate how much they need to pay for specific courses.
4. Navigation
The app uses React Navigation to navigate between screens, allowing for a smooth flow between different sections such as course details, application forms, login, and more.
Screens are easily accessible via tapping buttons or links that route to specific components.
5. Courses
Six-Week Courses: Displays the list of six-week courses offered by the organization.
Six-Month Courses: Displays the list of six-month courses.
All Courses Details: Displays the details of all available courses.
Course Details: Each course has a dedicated screen that provides more detailed information about what the course includes, duration, fees, etc.
6. User Registration and Login
Apply: Allows users to apply for courses by submitting their details.
Login: Allows registered users to log in to the system to manage their courses, track progress, and more.
7. Fee Calculator
A calculator where users can input their details and course choices to calculate the fees for the courses.
8. Styling and Layout
The app uses modern design patterns to create a user-friendly and visually appealing interface.
Color Scheme: Predominantly pink background with green titles for a vibrant and professional look.
Responsive Design: Layout is adaptable to different screen sizes for a seamless experience on various devices.
Installation
Prerequisites
Before you begin, ensure that you have the following installed on your machine:

Node.js (version 14.x or above)
npm or yarn (for package management)
Expo CLI (if you are using Expo)
1. Clone the repository
bash
Copy code
git clone https://github.com/your-repository/empowering-the-nation-app.git
cd empowering-the-nation-app
2. Install dependencies
If you're using npm:

bash
Copy code
npm install
If you're using yarn:

bash
Copy code
yarn install
3. Start the development server
To run the app in development mode:

If using Expo:

bash
Copy code
expo start
If using React Native CLI (ensure you have Android/iOS setup):

bash
Copy code
npx react-native run-android
npx react-native run-ios
4. Running on Device
To run the app on a physical or virtual device, scan the QR code (if using Expo) or run the respective commands above.

Future Enhancements
Push Notifications: Integrating push notifications to alert users about upcoming courses and new content.
Payment Integration: Implementing payment gateways for course payments.
User Profile: Allowing users to manage and update their profiles.
Admin Panel: For course management, fee calculations, and student registrations.
Technologies Used
React Native: Framework for building the app.
React Navigation: For handling navigation between different screens.
React Native WebView: For displaying local HTML files and external websites within the app.
Expo: For easy development and management of the React Native app (if applicable).
