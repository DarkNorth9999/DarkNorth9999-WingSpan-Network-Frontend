![text](https://github.com/DarkNorth9999/DarkNorth9999-WingSpan-Network-Frontend/blob/0e997518f5c2c53cc2d5ef41b0839fba5480c48f/WingSpan.gif)

WingSpan - Flight Tracking Application
WingSpan is a robust flight tracking application designed to provide real-time flight status updates and detailed flight information. Developed as part of a software engineering assignment, this application showcases advanced web development techniques and modern software architecture principles.

Features
Real-time Flight Tracking: Allows users to search and track flight status in real time, including departure and arrival times, gate information, and any delays or cancellations.
Advanced Search with Debounce: Implements a debounce mechanism to optimize search responsiveness and minimize server load, enhancing the overall user experience.
Dynamic Data Rendering: Flight data is rendered dynamically, enabling real-time updates without the need for page reloads.
Auto-complete Functionality: Integrates an auto-complete feature for airport searches, powered by backend data fetching for efficient user input handling.
Responsive Web Design: Ensures that the application is accessible across various devices and screen sizes, from desktops to mobile phones.
Accessibility Features: Includes comprehensive accessibility features like keyboard navigability and screen reader support to cater to all users.
Technology Stack
Frontend
React: Utilized for building the user interface with a component-based architecture, facilitating reusable UI components.
Tailwind CSS: Employed for styling, leveraging its utility-first classes to speed up development time and enhance design consistency.
Debounce Technique: Implemented using custom hooks to manage state and API calls efficiently, reducing the number of requests made to the server.
Backend
FastAPI: Chosen for its high performance and ease of use, FastAPI handles incoming requests and serves data from the server.
PostgreSQL: Acts as the primary database, storing flight and airport data reliably with robust transaction support.
SQLAlchemy: Used for database interaction, abstracting database commands into Python code and providing ORM capabilities.
Architecture
MVC Architecture: The application follows the Model-View-Controller (MVC) architecture, enhancing code maintainability and scalability.
RESTful API: Develops a RESTful API design for effective communication between the client and server using HTTP methods.
Service Layer: Incorporates a service layer for business logic, reducing the complexity in the API endpoint functions.
Deployment
Docker: Utilizes Docker containers to encapsulate the application environment, ensuring consistency across different deployment platforms.
GitHub Actions: Implements CI/CD pipelines using GitHub Actions for automated testing and deployment.
Getting Started
To set up and run WingSpan locally, follow these steps:

bash
Copy code

# Clone the repository

git clone https://github.com/yourgithubusername/wingspan.git

# Navigate to the project directory

cd wingspan

# Install dependencies

npm install

# Start the application

npm start

# In a new terminal, navigate to the backend directory

cd backend

# Set up and activate a virtual environment

python -m venv env
source env/bin/activate

# Install Python dependencies

pip install -r requirements.txt

# Run the FastAPI server

uvicorn app.main:app --reload
Contributing
Contributions are welcome! If you have suggestions for improvements or bug fixes, please fork the repository and submit a pull request.

License
Distributed under the MIT License. See LICENSE for more information.
