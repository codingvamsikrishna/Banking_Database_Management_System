# 🏦 Banking Data Management and Analysis System  

## 📘 Overview  
This project focuses on designing a **relational banking database system** that efficiently manages and analyzes customer, account, and transaction data.  
The goal is to simulate real-world banking operations and perform **data-driven analysis** using SQL and Python for insights such as **average balances, active accounts, and transaction summaries.**  

---

## 🧾 Database Overview  
The database consists of multiple interrelated tables representing essential banking entities and their relationships.  

**Tables used in this project:**  
- 👤 **Bank_Customer_Info:** Stores customer details such as ID, name, address, and state code.  
- 🧮 **Bank_Account_Data:** Contains account types, balances, and statuses.  
- 💳 **Bank_Transaction_Log:** Records customer transactions with date, amount, and channel.  
- 🔗 **Bank_Account_Mapping:** Links customers’ primary and secondary accounts.  
- 📊 **Bank_Account_Records:** Maintains account creation and performance details.  
- 📁 **Bank_Customer_InfoExport:** Used for exporting customer data summaries.  
- 🧠 **Bank_Account_Relationship:** Defines the mapping between linked or joint accounts.  

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



