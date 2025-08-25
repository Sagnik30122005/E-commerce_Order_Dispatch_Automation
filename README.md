# E-commerce Order & Dispatch Automation

## 📌 Project Overview
This project automates the end-to-end process of handling e-commerce orders, from receiving customer details to dispatch confirmation. It streamlines order management, reduces manual intervention, and ensures timely updates to customers.

## 🚀 Features
- Automated order intake from daily Excel sheets
- Filtering and processing based on **delivery dates**
- Order dispatch status tracking
- Automatic email notifications to customers
- Error handling and logging
- Role-based automation (Admin, Dispatch Manager, Customer)

## 🛠️ Tech Stack
- **UiPath Studio** – Workflow automation
- **Excel** – Order data management
- **SMTP/Outlook** – Email notifications
- **File System Activities** – Data storage and handling

## 🔄 Workflow
1. **Order Intake** – Reads the daily order Excel file.  
2. **Filtering** – Identifies orders scheduled for today’s dispatch.  
3. **Processing** – Updates dispatch status (Dispatched / Pending).  
4. **Notifications** – Sends email confirmation to respective customers.  
5. **Logging** – Saves execution logs for admin tracking.  

