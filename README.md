## AI Agent with PDF Integration and Note-Taking Functionality

# Overview
This project creates an AI-powered agent that interacts with a DataFrame and integrates with PDF documents. Additionally, it includes a note-taking feature that generates notes based on user queries. The solution is built using Python and leverages various tools and packages to handle PDF reading, data manipulation, and AI-based operations.

# Features
 - AI Agent: A flexible AI-based system that interacts with user inputs and connected data sources to provide insights and answers.
 - PDF Integration: Parses and extracts information from PDF files to facilitate interaction and query resolution.
 - Note-Taking Functionality: Creates and organizes notes based on user queries, enabling efficient information retrieval and summaries.

# Project Structure
- pdf.py: Contains functions for reading and parsing PDF documents. Uses libraries such as PyPDF for extracting content and integrating it into the AI agent’s knowledge base.
- note_engine.py: Implements note-taking functionality, allowing users to input queries and receive summarized notes based on the information retrieved from data sources or user inputs.
- prompts.py: Stores and manages the predefined and dynamically generated prompts to interact with the AI agent, enhancing its response capabilities.
- main.py: The entry point of the application, orchestrating the connections between the PDF parser, note-taking engine, and the AI agent. Handles user queries and directs them to the appropriate processing modules.
- requirements.txt: Specifies the dependencies required to run the project.
