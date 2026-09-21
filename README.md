# Chronos: The Digital Legacy & Dead Man Switch

**Chronos** is a secure digital legacy management system designed to ensure that your sensitive information, digital assets, and final messages are safely delivered to designated beneficiaries in the event of your absence. Utilizing a **Dead Man Switch** mechanism, the system monitors user activity and triggers automated data release only when predefined conditions are met.

---

## 🚀 Features

*   **Dead Man Switch Mechanism:** Automated monitoring of user "check-ins." If the timer expires without user intervention, the legacy protocol initiates.
*   **Secure Asset Vault:** Store encrypted messages, credentials, and digital documents.
*   **Beneficiary Management:** Assign specific assets to different individuals with verified contact details.
*   **Multi-Stage Notifications:** Sends warnings via email before the final execution to prevent false triggers.
*   **Modern UI/UX:** A sleek, motion-enhanced interface featuring a dark-mode aesthetic and sliding overlays.

---

## 🛠 Tech Stack

*   **Backend:** Java, Spring Boot (Spring Security, Spring Data JPA)
*   **Frontend:** HTML5, CSS3, JavaScript
*   **Database:** MySQL
*   **Project Management:** Maven

---

## 🏗 System Architecture

The application follows a modular architecture to ensure security and reliability:
1.  **Check-in Module:** Tracks the "Last Seen" timestamp of the user.
2.  **Trigger Engine:** A background scheduling service that compares current time against the user's inactivity threshold.
3.  **Delivery Service:** Handles the automated dispatch of stored data to beneficiaries.

---

## 🔧 Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aravinthsenthil23/ChronosTheDigitalLegacyAndDeadManSwitch.git]
    ```
2.  **Database Configuration:**
    *   Create a MySQL database named `chronos_db`.
    *   Update `src/main/resources/application.properties` with your MySQL credentials.
3.  **Build the project:**
    ```bash
    mvn clean install
    ```
4.  **Run the application:**
    ```bash
    mvn spring-boot:run
    ```

---

## 📸 Screenshots

| Dashboard |
| :--- 
| Dashboard - <img width="1917" height="949" alt="Dashboard ScreenShot" src="https://github.com/user-attachments/assets/9d45e580-acbb-4d01-9fdc-cdee705200f2" />
| Index     - <img width="1897" height="944" alt="index page screenshot" src="https://github.com/user-attachments/assets/079f7425-1de3-4894-bacf-81711600ddb6" />
| Log in    - <img width="1917" height="940" alt="Log in page screenshot" src="https://github.com/user-attachments/assets/afc0c5e0-5ebd-46ad-a1cb-043ab9915b40" />
| Sign up   - <img width="1919" height="945" alt="Sign up page screenShot" src="https://github.com/user-attachments/assets/fa237b57-013b-4497-8506-56ca93500d25" />

---

## 🛡 Security Considerations

*   **Encryption:** Implementation of industry-standard encryption for sensitive stored data.
*   **Verification:** Beneficiaries must undergo a verification process before accessing released legacy data.

---

## 👨‍💻 Author

**Aravinth Senthil**
*   B.Tech Information Technology
*   [GitHub](https://github.com/aravinthsenthil23) | [LinkedIn](https://linkedin.com/in/senthilaravinth)
