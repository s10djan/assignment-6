# Assignment 6 - RDS and MySQL Practice

## 📚 Objective
The goal of this assignment was to launch an Amazon RDS instance, connect to it using MySQL, create a database and table, insert data, and verify everything works as expected.

---

## ✅ Steps Completed

1. **Created an RDS MySQL instance** via the AWS Console.
2. **Configured security group** to allow MySQL connections (port 3306) from my IP address.
3. **Connected to RDS using MySQL** from my terminal.
4. **Created two databases**: `students` and `StudentData`.
5. **Created a table** called `Assignments` in `StudentData`.
6. **Inserted sample records** into the table.
7. **Queried the table** using `SELECT * FROM Assignments` to verify data insertion.

---

## 🛠 SQL Commands Used

See the file [`sql-commands.txt`](./sql-commands.txt) for all the SQL queries used.

---

## 🖼️ Screenshots

All screenshots are in the `screenshots/` folder:

- `rds-dashboard.png` – RDS instance running
- `terminal-sql-commands.png` – SQL queries and output
- `security-group.png` – MySQL port open for my IP

---

## 🙋‍♂️ What I Learned

- How to launch and configure RDS
- How to connect using MySQL
- Creating and interacting with databases and tables
- Importance of security groups for remote access

---

## 💡 Challenges Faced

- My terminal froze during the process — had to reopen it.
- Ensured the correct IP and port were set in the security group.
# Assignment 6
