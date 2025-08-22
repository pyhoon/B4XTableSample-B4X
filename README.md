# B4XTableSample-B4X
A sample project to demonstrate loading SQLite data into B4XTable

## Features:
- Use OkHttpUtils to download json file from a URL
- Parse the JSON as List and extract each item as Map
- Store the data into SQLite database
- Perform CRUD functions like add, retrieve, edit, delete rows
- Use B4XPreferencesDialog to show the panel for input
- Jump to an Id of row in SQLite

## Why I created this sample project
B4X developers often confuse or don't understand how to load and save data between an SQL database and use B4XTable to display the data. 
B4XTable uses a in-memory database for it's internal operation. It has a single table name "data" with columns start with c0, c1, c2 and so on.
Developers should not mix the internal db with their actual database. 
This sample shows how we can interact and work with B4XTable by connecting it to a SQLite database.
In fact, B4XTable is so powerful that it actually can work with CSV files or non SQL database.
