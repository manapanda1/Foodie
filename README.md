
# Project Title

# Foodie - Ultimate Restaurant Table Reservation Website

Foodie is the ultimate restaurant table reservation website for food enthusiasts. This project leverages Java technology to provide a seamless experience for reserving tables at your favorite restaurants.

## Features

- User-friendly interface for table reservations
- Secure user sessions and data management
- Responsive design with CSS
- Dynamic content rendering with JSP
- Reliable data storage with MySQL

## Technologies Used

- **Java**: Core backend logic
- **JSP**: JavaServer Pages for dynamic web content
- **MySQL**: Database management
- **Tomcat Server**: Web server
- **Cookies and Sessions**: For user data storage and session management
- **CSS**: Styling the website
- **JavaScript**: Basic interactivity and functionality


## Project Structure
```sh
Foodie/
│
├── Web Pages/
│   ├── META-INF/
│   │   └── context.xml
│   │
│   ├── WEB-INF/
│   │   ├── addReservation.jsp
│   │   ├── addUser.jsp
│   │   ├── checkLogin.jsp
│   │   ├── dashboard.jsp
│   │   ├── delete.jsp
│   │   ├── index.jsp
│   │   ├── logout.jsp
│   │   ├── reservation.jsp
│   │   ├── signup.jsp
│   │   ├── style.css
│   │   ├── style1.css
│   │   └── style2.css
│
├── Remote Files/
│   ├── all.min.css
│   └── all.min.css (duplicate or different path)
│
├── Source Packages/
│   └── <default package>
│
├── Libraries/
│   ├── mysql-connector-j-9.2.0.jar
│   ├── JDK 17 (Default)
│   └── Apache Tomcat or TomEE
│
├── Configuration Files/
│   ├── MANIFEST.MF
│   ├── context.xml
│   ├── web-fragment.xml
│   └── web-fragment.xml (another instance, likely auto-generated)
```
## Setup and Installation
1. Clone the Repository
```sh
git clone https://github.com/your-username/Foodie.git
cd Foodie
```
2. Open the Project in Your IDE
Use NetBeans, Eclipse, or any IDE that supports Java EE.

Make sure the folder structure is recognized correctly.

Import as a web application project if needed.

3. Configure the Tomcat Server
Add Apache Tomcat (v9 or above) to your IDE.

Set it as the default server for this project.

Ensure your deployment folder is correctly set (usually webapps/Foodie).

4. Set Up the MySQL Database
sql
```sh
CREATE DATABASE foodie_db;

-- Create the required tables:
CREATE TABLE login (
    Username VARCHAR(50),
    Password VARCHAR(50),
    Fullname VARCHAR(100),
    mobile VARCHAR(15)
);

CREATE TABLE reservation (
    Username VARCHAR(50),
    Location VARCHAR(100),
    Plan DATE,
    Time VARCHAR(10)
);
```


5. Deploy the Project on Tomcat
Right-click the project > Run or Deploy on Tomcat.

Or access via browser:
http://localhost:8765/Foodie

6. Usage Instructions
On the login page, enter your username and password.

If you are a new user, click "Sign Up" and fill in the required details.

After login, you can:
Make reservations,
View dashboard,
Logout securely


## Screenshots

![login](https://github.com/manapanda1/Foodie/blob/main/web/login.png?raw=true)

![signup](https://github.com/manapanda1/Foodie/blob/main/web/signup.png?raw=true)

![home](https://github.com/manapanda1/Foodie/blob/main/web/home.png?raw=true)

### DATABASE

![db_table](https://github.com/manapanda1/Foodie/blob/main/web/db_tables.png?raw=true)

![login_table](https://github.com/manapanda1/Foodie/blob/main/web/login_table.png?raw=true)


## Authors

For any questions or feedback, feel free to reach out:

📧 Email: pandamana2004@gmail.com

📞 Phone: +91 9339259627

🔗 LinkedIn: linkedin.com/in/manapanda

💻 GitHub: github.com/manapanda1

