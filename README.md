# 🚀 NASA API Data Extraction and Display Using AWS & Django 🌌

I’m excited to share a project I’ve been working on! In this project, I combined multiple technologies to build a system that automatically fetches data from the NASA API and displays it on a Django-powered web page. Here’s a quick overview:


🛠️ Tech Stack:

AWS Lambda: Automatically fetches the latest data (e.g., Astronomy Picture of the Day) from the NASA API.

Amazon S3: Stores the fetched JSON data.

S3LINK ==> s3://nasa-project-bucket/Mars_Rover_Photos.json

AWS EventBridge: Triggers the Lambda function at scheduled intervals (e.g., once a day).

Django: A Python web framework to display the data on a beautiful webpage.

boto3: Used to interact with AWS services (Lambda, S3) from the Django app.

📈 How It Works:

Lambda function fetches the data from the NASA API and stores it in an S3 bucket.

EventBridge automatically triggers the Lambda function on a daily schedule.

The Django app retrieves the data from S3 and renders it in a simple HTML page, displaying the title, description, and image

mars rovers webpage ==>https://lnkd.in/gqMr5FC3

☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️☝️

![architecture](https://github.com/user-attachments/assets/79ffffd4-57c4-42c2-9ef3-43951f507a22)
