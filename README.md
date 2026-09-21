# The-Digital-Legacy-Dead-Man-Switch
Chronos is a secure digital legacy management system designed to ensure that your sensitive information, digital assets, and final messages are safely delivered to designated beneficiaries in the event of your absence. Utilizing a Dead Man Switch mechanism, the system monitors user activity and triggers automated data release only when predefined conditions are met.
🚀 Features
Dead Man Switch Mechanism: Automated monitoring of user "check-ins." If the timer expires without user intervention, the legacy protocol initiates.
Secure Asset Vault: Store encrypted messages, credentials, and digital documents.
Beneficiary Management: Assign specific assets to different individuals with verified contact details.
Multi-Stage Notifications: Sends warnings via email before the final execution to prevent false triggers.
Modern UI/UX: A sleek, motion-enhanced interface featuring a dark-mode aesthetic and sliding overlays.
🛠 Tech Stack
Backend: Java, Spring Boot (Spring Security, Spring Data JPA)
Frontend: HTML5, CSS3, JavaScript
Database: MySQL
Project Management: Maven
🏗 System Architecture
The application follows a modular architecture to ensure security and reliability:

Check-in Module: Tracks the "Last Seen" timestamp of the user.
Trigger Engine: A background scheduling service that compares current time against the user's inactivity threshold.
Delivery Service: Handles the automated dispatch of stored data to beneficiaries.
🔧 Installation & Setup
Clone the repository:
git clone [https://github.com/aravinthsenthil23/ChronosTheDigitalLegacyAndDeadManSwitch.git]
Database Configuration:
Create a MySQL database named chronos_db.
Update src/main/resources/application.properties with your MySQL credentials.
Build the project:
mvn clean install
Run the application:
mvn spring-boot:run
📸 Screenshots
Dashboard
Dashboard - Dashboard ScreenShot
Index - index page screenshot
Log in - Log in page screenshot
Sign up - Sign up page screenShot
🛡 Security Considerations
Encryption: Implementation of industry-standard encryption for sensitive stored data.
Verification: Beneficiaries must undergo a verification process before accessing released legacy data.
