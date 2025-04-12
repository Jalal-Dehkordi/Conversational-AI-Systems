# Conversational-AI-Systems
This repository contains two tutorial scripts for understanding the creation and operation of chabot  systems.

---

## 1. BaristaBot - Cafe Ordering System

A conversational chatbot for placing café orders, built using **LangGraph** and **Gemini API**.

### Overview:
This script creates an interactive café ordering system called **BaristaBot**. It allows users to place orders for café items through a natural language conversation interface.

### Features:
- **Natural Language Interaction**: Engage in a human-like conversation to browse the menu and place orders.
- **Dynamic Menu Management**: Simulates a live menu system that can be updated dynamically.
- **Order Management**: Add, modify, or clear items from the order before finalizing.
- **Order Confirmation**: Ensures the user confirms their order before final submission.
- **Conditional Flow**: Handles complex conversational flows, including conditional transitions and looping.

### Learning Outcomes:
- Building graph-based applications using **LangGraph**.
- Managing state in a conversational system.
- Integrating **Gemini API** for natural language processing.
- Creating tools for menu management and order handling.

---

## 2. Database Chatbot: SQL Query Interface

The second script demonstrates how to create a chatbot that interacts with an **SQLite database**. This system allows users to ask questions about the data and receive answers by executing SQL queries.

### Key Features:
- **Database Interaction**: Users can query the database through natural language questions.
- **Schema Exploration**: The bot can list tables, describe table schemas, and execute custom SQL queries.
- **Compositional Function Calling**: The bot can compose multiple functions to handle complex tasks, such as generating charts or inserting new data.

### Learning Outcomes:
- Connecting to and querying an SQLite database.
- Using **Gemini API** to convert user questions into SQL queries.
- Defining Python functions for database operations.
- Implementing compositional function calls for advanced workflows.
