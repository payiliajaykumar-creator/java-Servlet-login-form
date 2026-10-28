Java Servlet Login Form

A simple web application built with Java Servlets and HTML that shows a login form and handles the submitted details on the server side using Apache Tomcat.

Features
HTML login form (login.html) for entering user details
Java Servlet (helloServelet.java) that receives and processes the form request
Servlet mapping configured through web.xml
Runs on Apache Tomcat 10.1
Tech Stack
Technology	Purpose
Java	Backend logic
Servlets (Jakarta Servlet API)	Handling HTTP requests and responses
HTML	Login page (frontend)
Apache Tomcat v10.1	Web server / servlet container
Eclipse IDE for Enterprise Java and Web Developers	Development environment
Project Structure
java-Servlet-login-form
└── src
    └── main
        ├── java
        │   └── co/pack1
        │       └── helloServelet.java
        └── webapp
            ├── login.html
            ├── META-INF
            │   └── MANIFEST.MF
            └── WEB-INF
                └── web.xml
How to Run
Clone or download this repository.
Open Eclipse IDE and import it as an existing project (File → Import → Existing Projects into Workspace), or create a Dynamic Web Project and copy the files in.
Make sure Apache Tomcat v10.1 is added under Window → Preferences → Server → Runtime Environments.
Right-click the project and choose Run As → Run on Server, then select Tomcat v10.1.


(Change helloserveletapp to match your project's context path if it is different.)

What I Learned
How the servlet lifecycle works (init, service, destroy)
Handling form data with HttpServletRequest and HttpServletResponse
Mapping a servlet to a URL using web.xml
Deploying and running a Java web application on Tomcat
Future Improvements
Connect to a MySQL database using JDBC to validate users
Add session management
Add a registration page and password hashing
Improve the UI with CSS
Author

Payili Ajay Kumar B.Tech CSE (AI & ML), Bharat Institute of Engineering and Technology GitHub: payiliajaykumar-creator
