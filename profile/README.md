# Pick It Up

## Overview
**Pick It Up** is an innovative application designed to empower households to manage waste responsibly and sustainably. Aligning with **Sustainable Development Goals (SDGs)** #11 (Sustainable Cities and Communities) and #12 (Responsible Consumption and Production), this platform simplifies waste segregation, disposal, and management through technology-driven features like object detection, interactive education, and chatbot recommendations. With a rewards program for eco-friendly actions, Pick It Up transforms waste management into a modern, engaging, and profitable activity.

---

## Background
Waste management is a growing global challenge. According to **The World Bank (2022)**:
- **2.01 billion tons** of solid waste is generated globally each year, projected to rise to **3.40 billion tons by 2050**.
- Only **19%** of waste is recycled; the rest ends up in landfills or pollutes the environment.

In **Indonesia**, the Ministry of Environment and Forestry reported:
- **67.8 million tons** of waste generated in 2023, with **16% being hard-to-decompose plastic**.
- **40-50%** of waste comes from households, largely due to the lack of education and facilities for proper segregation.

By addressing these issues, Pick It Up seeks to unlock the untapped economic potential of waste recycling, which the World Bank estimates could generate **USD 87 billion annually**.

---

## Key Features
1. **Services**: 
   - **Drop-off (Free)**: Locate nearby drop-off points.
   - **Pick-up (Paid)**: Schedule regular or urgent waste pick-up.
   - **Real-Time Tracking**: Monitor pick-up status.
2. **Technology**: 
   - **Object Detection**: Identify waste types.
   - **Chatbot Recommendations**: Manage special waste (e.g., medical waste, oil).
3. **Interactive Education**: 
   - Access videos, articles, and mini-games on waste management.
4. **Rewards Program**: 
   - Earn points for eco-friendly actions, redeemable for exclusive merchandise.

---

## Stakeholders
### 1. **Households (End-Users)**
   - Primary users managing household waste.
### 2. **PiU Drivers**
   - Handle waste collection and processing.
### 3. **Admin Team**
   - Oversee application operations, user data, content, and reporting.

---

## User Requirements
### Households
- Register/login using email or phone.
- Select and track waste management services.
- Access educational content and mini-games.
- Utilize object detection and chatbot features.
- Earn and redeem reward points.

### PiU Drivers
- Register/login with verified company IDs.
- View schedules and update service statuses.
- Report issues and handle urgent pick-up requests.

### Admin
- Manage user accounts and service schedules.
- Monitor operations and generate reports.
- Update educational content and reward catalogs.

---

## System Requirements
### Functional Requirements
1. **User Registration and Authentication**:
   - Support registration via email/phone.
   - Verify company IDs for operators.
2. **Service Management**:
   - Provide drop-off point locations.
   - Enable scheduling and tracking of pick-up services.
3. **Waste Identification**:
   - Use object detection to classify waste.
4. **Reward System**:
   - Automatically calculate points based on waste weight.
   - Enable point redemption for merchandise.

### Non-Functional Requirements
- **Usability**: Intuitive and user-friendly interfaces.
- **Performance**: Handle concurrent requests with minimal latency.
- **Scalability**: Support growing user bases and data loads.
- **Security**: Protect user data and transactions.

---

## User Goals
### Households
- Access fast and easy waste management services.
- Learn proper waste segregation techniques.
- Gain rewards for eco-friendly practices.

### PiU Drivers
- Efficiently complete pick-up tasks.
- Access clear schedules and user locations.

### Admin
- Ensure smooth application operations.
- Provide accurate and relevant information to all stakeholders.

---

## Inputs and Outputs
| **Role**         | **Input**                                                                                              | **Output**                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Households**    | Account data, service selection, scanned waste images, chatbot queries, mini-game actions             | Notifications, service status, educational content, chatbot recommendations, reward points updates  |
| **PiU Driver** | Login credentials, service status updates, issue reports                                            | Task notifications, detailed service information, urgent pick-up requests                          |
| **Admin**         | User data, schedules, educational content, reward catalog updates, waste weight data                  | User management tools, updated schedules and content, transaction records, statistical reports      |

---

## How to Use
1. **Build the App**: Build the apps using Flutter SDK.
2. **Register/Login**: Create an account using email or phone.
3. **Select Services**: Choose from drop-off, pick-up, or urgent pick-up options.
4. **Engage with Features**: Use object detection, chatbot recommendations, or mini-games.
5. **Earn Rewards**: Collect points and redeem them for exciting merchandise.

---

## Credits  
This application was developed through the teamwork and dedication of Group 4 from the Software Engineering class:  

- **Putu Nirvana Putri Arta** (2702363872)  
- **Felix Febryan Wana** (2702363626)  
- **Helena Viveca Handoyo** (2702363670)  
- **Jonathan Fortino Chandra** (2702363784)  
- **Delbert Sugihoentoro** (2702364156)  

We sincerely thank our lecturer, Kenny Jingga, S.Kom., M.T., for his invaluable support and guidance throughout the project.

---

## License
Pick It Up is licensed under the [MIT License](LICENSE).

---
