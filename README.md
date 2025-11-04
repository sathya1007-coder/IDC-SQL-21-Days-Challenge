# IDC-SQL-21-Days-Challenge

🚀 IDC 21-Day SQL Challenge Journey
Welcome! This repository tracks my daily progress as I take on the IDC 21-Day SQL Challenge—a campaign to build up my SQL skills and deepen my understanding of data analysis. Sponsored by DPDzero and organised by Indian Data Club, this challenge is all about learning by doing, one day (and one query) at a time!

Challenge Overview
Over the next 21 days, I’ll be working through guided tasks designed to take me from SQL basics to advanced querying skills. Each day comes with a fresh challenge, hands-on exercises, and a chance to uncover insights from real-world hospital data. My goal: master SQL, reflect on my learning, and showcase results right here in my GitHub repo.

What I’ll Be Doing
Practicing SQL every day with structured tasks

Solving data challenges based on hospital datasets

Sharing sample queries, results, and reflections

Tracking progress as I learn SELECT, DISTINCT, WHERE, JOIN, GROUP BY, and more!

📅 Day 1 of the IDC 21-Day SQL Challenge — Getting Started!
Sponsored by DPDzero and organised by Indian Data Club

Every journey begins with a first step, and today mine was all about understanding the basics of SQL and learning how to look at the data.

Today’s focus:
Getting comfortable with the SELECT and DISTINCT statements — the tools for exploring and finding unique insights.

💡 What I explored today:

Used SELECT to view the entire table and specific columns

Checked how information is structured in the database

Practiced with DISTINCT to find all unique hospital services

🎯 Challenge:
List all unique hospital services available in the hospital.

⚙️ Query I wrote:

sql
SELECT DISTINCT service AS hospital_services FROM patients;
🧠 Reflection:
The simplest queries are often the most powerful. Seeing how easy it is to find unique values gives me confidence to ask bigger questions next!

📅 Day 2 of the IDC 21-Day SQL Challenge — Leveling Up!
Sponsored by DPDzero and organised by Indian Data Club

Diving deeper into the world of SQL today! I learned how to ask targeted questions and filter out just the data I need.

Today’s focus:
Using the WHERE clause and comparison operators to narrow down the results and extract meaningful patterns.

💡 What I explored today:

Filtered rows with WHERE and comparison operators (>, <, =)

Combined conditions using AND, OR, and other logical operators

Practiced on hospital datasets to find important trends

🎯 Challenge:
List all weeks where more than 100 patients requested admission in any service.

⚙️ Query I wrote:

sql
SELECT week, service FROM services_weekly WHERE patients_request > 100;
🧠 Reflection:
Learning to filter with WHERE instantly sharpens your insights! Now I can spot busy weeks and highlight data that matters most. Excited for new challenges ahead!

