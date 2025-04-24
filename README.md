mars rovers webpage ==>https://lnkd.in/gqMr5FC3
☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️
# 🚀 NASA API Data Extraction and Display Using AWS & Django 🌌
I’m excited to share a project I’ve been working on! In this project, I combined multiple technologies to build a system that automatically fetches data from the NASA API and displays it on a Django-powered web page. Here’s a quick overview:
🛠️ Tech Stack:
AWS Lambda: Automatically fetches the latest data (e.g., Astronomy Picture of the Day) from the NASA API.
Amazon S3: Stores the fetched JSON data.
AWS EventBridge: Triggers the Lambda function at scheduled intervals (e.g., once a day).
Django: A Python web framework to display the data on a beautiful webpage.
boto3: Used to interact with AWS services (Lambda, S3) from the Django app.
📈 How It Works:
Lambda function fetches the data from the NASA API and stores it in an S3 bucket.
EventBridge automatically triggers the Lambda function on a daily schedule.
The Django app retrieves the data from S3 and renders it in a simple HTML page, displaying the title, description, and image
![Capture](https://github.com/user-attachments/assets/c6e716d4-b700-4dc8-ac4c-b73abc83c615)
