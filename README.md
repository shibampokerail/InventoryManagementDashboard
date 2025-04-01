# Inventory Management System For Union & Involvement Services Truman

## Overview
The **Inventory Management System** is a three-tier application designed to streamline inventory tracking and management. It integrates a **Slack bot** for seamless communication and tracking, along with an **Admin Management Portal** for detailed manual oversight, reporting, and vendor notifications. The system ensures efficient inventory control, staff tracking, and shift management while maintaining an organized and user-friendly interface.

# Repository Structure
![git branch overview](https://github.com/user-attachments/assets/55b3f34c-3d4d-4590-84ab-3df8bc1dbf57)
```
backend-dev     → Development branch for backend changes
backend-main    → Stable production-ready backend branch
frontend-dev    → Development branch for frontend changes
frontend-main   → Stable production-ready frontend branch
slackbot-dev     → Development branch for changes in slackbot
slackbot-main   → Stable production-ready Slackbot branch
```



## Architecture
The system follows a three-tier architecture:
1. **Frontend (Presentation Layer):** Next.js + React
2. **Backend (Application Layer):** Flask (Python)
3. **Database (Data Layer):** MongoDB

![image](https://github.com/user-attachments/assets/1bffd53b-645a-4597-9334-1484405b13fc)


## Features
### Slack Bot (Python + Slack API)
The Slack bot provides an interactive way for users and managers to interact with the inventory system directly from Slack. It enables:
- **Inventory Management:** Users can add, modify, and track inventory items.
- **Shift & Staff Tracking:** Managers can monitor and update staff schedules.
- **Real-time Notifications:** Alerts for low-stock items, schedule changes, and important inventory updates.

### Admin Management Portal(React + NextJs)
The Admin Portal offers a more detail
led and manual way to manage inventory and staff operations. It includes:
- **Inventory Control:** Manual addition, modification, and deletion of inventory items.
- **Report Generation:** Automated reports providing insights into inventory trends.
- **Vendor Notifications:** Sends notifications and restock requests via email.
- **User Access Control:** Secure authentication and role-based access for different users.

## License
This project is licensed under the GPLv3 License. Feel free to use and modify it as per your needs.


