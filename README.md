SMART INVENTORY MANAGER (JAVA EDITION)
======================================

Crafted by Yashwant Sharma
MCA Student & AI Enthusiast | Himachal Pradesh, India

WHY THIS PROJECT?
-----------------
- Showcases Java, Swing GUI, and MySQL skills
- Demonstrates full-stack capabilities
- Real-world inventory management application

TECH STACK
----------
Core Technologies:
- Java 11+
- MySQL 8+
- Swing GUI

Tools:
- XAMPP
- MySQL Workbench

GETTING STARTED
---------------

PREREQUISITES
1. JDK 11+ (https://adoptium.net/)
2. XAMPP (https://www.apachefriends.org/)
3. MySQL Connector/J 8.0+

DATABASE SETUP
--------------
1. Start XAMPP MySQL:
   sudo /opt/lampp/lampp start  # Linux/Mac
   (Windows: Launch XAMPP Control Panel)

2. Create database:
   mysql -u root -p
   CREATE DATABASE inventory;
   USE inventory;
   SOURCE resources/database/schema.sql;

CONFIGURATION
-------------
Create config.properties in project root:

db.url=jdbc:mysql://localhost:3306/inventory
db.user=root
db.password=

BUILD & RUN
-----------
Command Line:
# Compile
javac -cp "lib/*" -d bin src/com/inventory/main/*.java

# Execute
java -cp "bin:lib/mysql-connector-j-8.0.30.jar" com.inventory.main.App

IDE Setup:
1. Import as Java project
2. Add MySQL connector to classpath
3. Run App.java

TROUBLESHOOTING
---------------
| Issue            | Solution                 |
|------------------|--------------------------|
| Connection Error | Verify XAMPP MySQL status|
| Driver Not Found | Check lib/ JAR file      |
| Access Denied    | Reset MySQL credentials  |

LEARNING EXTENSIONS
-------------------
1. Add AI-powered stock predictions
2. Implement user activity analytics
3. Create REST API interface

CONTRIBUTE
----------
1. Fork repository
2. Create feature branch
3. Submit PR with description

CONTACT
-------
For collaborations or queries:
- Email: [your_email@domain]
- LinkedIn: [linkedin_profile_link]

Last Updated: April 2025 | Himachal Pradesh, India
