# Python Code Review Assistant


The Python Code Review Assistant is a web application built using Streamlit and Google’s Gemini API. It provides an interface for users to submit Python code and receive instant feedback, including bug detection and suggested fixes.

The application uses Streamlit for creating a simple and interactive frontend, featuring a text area for code input, a button to trigger the review process, and a responsive layout with custom styling. The backend integrates Google’s Gemini LLM (gemini-1.5-flash) through the GenerativeModel API, configured to function as a Python tutor. The model analyzes the submitted code and generates detailed feedback for users.
