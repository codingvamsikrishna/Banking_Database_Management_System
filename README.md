# 🏦 Banking Data Management and Analysis System  

## 📘 Overview  
This project focuses on designing a **relational banking database system** that efficiently manages and analyzes customer, account, and transaction data.  
The goal is to simulate real-world banking operations and perform **data-driven analysis** using SQL and Python for insights such as **average balances, active accounts, and transaction summaries.**  

---

## 🧾 Database Overview  
The database consists of multiple interrelated tables representing essential banking entities and their relationships.  

**Tables used in this project:**    

- 👤 **Bank_Customer_Info:** Holds essential customer details like ID, name, and address.  
- 🧮 **Bank_Customer_InfoExport:** Stores summarized customer account information for reports.  
- 💳 **Bank_Account_Data:** Contains account details such as type, balance, and transaction status.  
- 🔗 **Bank_Account_Mapping:** Maps customer accounts and links primary with secondary accounts.  
- 📊 **Bank_Transaction_Log:** Records transaction details including amount, date, and channel.  
- 📁 **Bank_Customer_Alerts:** Manages notifications and alerts for customer activities.  
- 🧠 **Bank_Interest_Info:** Maintains information on interest types and linked account relationships.  
  

---

## 🧠 Project Workflow  
1️⃣ **Database Design:** Created normalized tables and defined relationships using primary and foreign keys.  
2️⃣ **Data Insertion:** Used Python (sqlite3) functions for automated record entry.  
3️⃣ **Data Retrieval:** Queried data using SQL `SELECT`, `WHERE`, `JOIN`, and `GROUP BY` clauses.  
4️⃣ **Data Analysis:** Generated insights such as average balances per customer, total transactions, and inactive accounts.  
5️⃣ **Visualization:** Displayed outputs using **Pandas DataFrames** and **Tabulate** for readable table formatting.  

---

## ⚙️ Tech Stack  
- 🐍 **Programming Language:** Python  
- 🗃️ **Database:** SQLite (via sqlite3 library)  
- 📚 **Libraries:** Pandas, Tabulate, OS  
- 💻 **Tools:** Google Colab, SQL, DataFrames  

---

## 📈 Results  
✅ Efficiently managed and analyzed **customer–account–transaction** relationships.  
✅ Simplified complex SQL operations through **Python automation.**  
✅ Derived insights such as **average account balances** and **linked account reports** to support banking decisions.  

---

## 💡 Key Features  
✨ Automated data creation, retrieval, and reporting using Python functions.  
✨ Real-time insights through SQL aggregate and join queries.  
✨ Structured data visualization using Pandas and Tabulate.  
✨ Database securely stored in Google Drive for persistent access.  

---
  
**Tools Used:** Python, SQLite, Pandas, Google Colab


