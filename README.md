# ⭐ Salesforce Mini CRM – Customer Premium Automation

A practical Salesforce Admin project that demonstrates **data modelling, custom UI design, automation, and email workflows** inside a Salesforce Developer Edition org.  
This system manages customers, tracks their status, and automatically sends a notification when someone becomes **Premium**.

---

## 🔹 Project Summary

This Mini CRM is built around a custom object called **Customer Profile**.  
It captures important customer attributes, provides clean list views for filtering, and includes a working **Record-Triggered Flow** that fires an email alert whenever a customer becomes Premium.

It reflects real workplace Salesforce admin responsibilities:  
customising objects, building automation, designing clean layouts, and testing flows.

---

## 🔹 Features

### **1. Custom Object – Customer Profile**
Includes fields for:
- Customer Full Name  
- Customer Type  
- Email  
- Phone  
- Status  
- Notes  

### **2. Clean Page Layout**
- Organised into a single “Customer Details” section  
- Grouped fields logically  
- Removed unused default fields  
- Optimised for quick reading and data entry  

### **3. Custom List Views**
- **All Customers**  
- **Premium Customers**  
- **Recent Customers** (sorted by Created Date)

Each list view includes only relevant fields for easy scanning.

### **4. Automation – Premium Notification Flow**
Record-Triggered Flow that:
- Detects when **Status** changes to *Premium*  
- Sends a personalised **Email Alert** to the admin  
- Uses merge fields (Name, Email, Phone, Type)

Flow is fully tested and functional.

### **5. Email Template + Email Alert**
- Classic email template with merge fields  
- Email alert configured and connected to the flow  
- Uses the Salesforce org email system  

---

## 🛠 Tools & Platform

- Salesforce Lightning Experience  
- Object Manager  
- Flow Builder  
- Email Alerts  
- Classic Email Templates  
- List Views  

---

## 📘 Trailhead Modules Completed

- Salesforce Platform Basics  
- Reports & Dashboards for Lightning Experience  

---

## 🧠 Skills Demonstrated

- Data Modelling  
- Custom Object + Field Creation  
- Page Layout & UI Design  
- List View Configuration  
- Record-Triggered Flow Automation  
- Email Templates & Alerts  
- Testing & Debugging  
- Admin Best Practices  

---

## 🚀 Next Steps

- Add Lead → Customer conversion  
- Add Case Management  
- Add Opportunity tracking  
- Add Validation Rules  
- Create dashboards (CRM Analytics)  

---

## Screenshots

### Custom Object
![Object Setup](assets/customer_home.png)

### Fields
![Fields](assets/customer_profile_fields.png)

### Page Layout
![Page Layout](assets/customer_profile_page_layout.png)

### List Views
![List Views](assets/high_value_customers.png)

### Flow Trigger
![Flow Trigger](assets/flow_trigger_setup.png)

### Flow Email Alert Action
![Email Alert](assets/email_alert_element.png)

### Email Template
![Email Template](assets/email_template.png)

### Email Received
![Premium Email](assets/email_recieved.png)


