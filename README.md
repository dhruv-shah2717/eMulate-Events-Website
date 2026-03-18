<h1>About the Project</h1>
<p>
This is a web-based <strong>Event Management Application</strong> developed using modern web technologies with the <strong>MERN Stack (MongoDB, Express.js, React.js, Node.js)</strong>.
The system supports different types of users such as <strong>Admin</strong>, <strong>Registered User (Student)</strong>, and <strong>First-Time Visitor</strong>.
Users can log in, manage their profiles, browse events, participate in events, and view event participants.
After the system sends an <strong>MU Pass (Event Pass)</strong> to the participant via email.
The <strong>Admin Panel</strong> allows complete control over events, categories, students, attendance management, and ranking assignment.
</p>

<h1>User Types</h1>
<ul>
    <li><strong>Admin:</strong> Manages the entire system including events, event categories, students, attendance, and event rankings.</li>
    <li><strong>Registered User (Student):</strong> Students who can  participate in events, view participants, and manage their profiles.</li>
    <li><strong>First-Time Visitor:</strong> New visitors who can browse available events and register to participate.</li>
</ul>

<h1>Project Functionality</h1>

<h2>User Features</h2>
<ul>
    <li>User Registration and Login</li>
    <li>Edit and Manage User Profile</li>
    <li>Browse and Search Events</li>
    <li>View Event Details</li>
    <li>Participate in Events</li>
    <li>View Event Participants</li>
    <li>Receive MU Pass via Email</li>
</ul>

<h2>Admin Panel Features</h2>
<ul>
    <li>Admin Login</li>
    <li>Dashboard Overview</li>
    <li>Add, Edit, and Delete Events</li>
    <li>Manage Event Categories</li>
    <li>Manage Students</li>
    <li>View Event Participants</li>
    <li>Update Event Details</li>
    <li>Mark Event Attendance</li>
    <li>Assign Event Rankings</li>
    <li>Send MU Pass to Participants via Email</li>
</ul>

<h1>Technologies Used</h1>
<ul>
    <li><strong>Frontend:</strong> HTML, CSS, JavaScript, React.js, Bootstrap</li>
    <li><strong>Backend:</strong> Node.js, Express.js</li>
    <li><strong>Database:</strong> MongoDB (MongoDB Atlas)</li>
    <li><strong>Tools:</strong> Node.js, NPM, MongoDB Atlas, Nodemailer</li>
</ul>

<h1>What Changes Have Been Made</h1>
<ul>
    <li>Integrated <strong>MongoDB Atlas</strong> as the cloud database.</li>
    <li>Added the MongoDB database. The database file is provided in the project folder as src/Backend/Database allcollection.json.</li>
    <li>Updated environment configuration for MongoDB connection.</li>
    <li>Rename <strong>.env.example</strong> to <strong>.env</strong> and update the environment variables.</li>
    <li>Installed all required project dependencies using <strong>npm install</strong>.</li>
</ul>

<h1>How to Run the Project</h1>
<ul>
    <li>Install <strong>Node.js</strong> and <strong>NPM</strong>.</li>
    <li>Download the project from the repository.</li>
    <li>Open the project folder in terminal.</li>
    <li>Start the development server using: <strong>npm run dev</strong></li>
    <li>Open browser and visit: <strong>http://localhost:5173</strong></li>
</ul>

<h1>Database Setup</h1>
<ul>
    <li>Open MongoDB compass.</li>
    <li>Create a new database (example: mufest).</li>
    <li>Import the all files allcollections.json.</li>
    <li>Ensure MongoDB service is running.</li>
    <li>Configure MongoDB connection details in the .env file.</li>
    <li>The database collections will be created automatically when the application runs.</li>
</ul>

<h1>Requirements</h1>
<ul>
    <li>Node.js</li>
    <li>NPM</li>
    <li>MongoDB Atlas Account</li>
    <li>React.js</li>
</ul>
