# B2B EdTech Platform

This is a B2B e-learning platform similar to Udemy and Coursera, developed with a comprehensive feature set for creators and learners. The platform allows creators to upload, manage, and analyze their courses, while learners can browse, enroll, and track their progress through their dashboard.

(Due to Company's policies code cant be shared in public)

## Demo Video Link
https://drive.google.com/file/d/1qkQtHCuZ3VWsMDmBpcbviK3TCDLgz9WA/view?usp=sharing

## FlowCharts
![flowchart2 b2b](https://github.com/user-attachments/assets/37bd4949-a6f0-43e2-9f79-1c0444de2d72)

![flowchart b2b](https://github.com/user-attachments/assets/58727d61-2aa8-4b5c-8493-f3a802e93362)

## Hosted Link
https://imaginaryhubb2b.onrender.com (currenlty my AWS Services is down due to free plan Expiration,So platform may not work properly)


## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [Deployment](#deployment)
- [License](#license)

## Features

### For Creators
- **Profile Creation**: Creators can create profiles to showcase their courses.
- **Course Upload**: Creators can upload a `.zip` file containing their course content.
- **Publishing**: Once a course is published, it appears on the All Courses page, categorized appropriately.
- **Analytics**: Real-time monthly analytics for watch time, views, and student enrollments, similar to YouTube analytics.
- **Course Management**: Edit courses at any time by adding or removing videos.

### For Learners
- **Profile Creation**: Learners can create profiles to personalize their learning experience.
- **Course Browsing**: Browse courses by category, view all available courses, and explore creator profiles.
- **Enrollment and Tracking**: Enroll in courses, access a personalized dashboard, and track progress and completion in each course.

### General Platform Features
- **Secure User Authentication**: Managed with Passport.js, including password reset functionality.
- **AWS Integration**:
  - **S3**: Storage for course content.
  - **CloudFront**: Content delivery for optimized video streaming.
- **Zip Handling**: Course uploads managed with `adm-zip` for unzipping and storing course content.
- **Deployment**: Platform deployed on Render and Elastic Beanstalk for scalability and performance.

## Tech Stack

### Frontend
- **EJS**: Template engine for dynamic content rendering.
- **Bootstrap & Tailwind CSS**: Responsive and modern UI design.

### Backend
- **Node.js & Express.js**: Server and routing management.
- **MongoDB**: Database for managing user profiles, courses, and analytics.
- **Passport.js**: User authentication and session management.
- **NPM Packages**: Various utilities for handling zip files, AWS SDK, and other functionalities.

### Cloud Services
- **AWS S3**: Secure storage for course content.
- **AWS CloudFront**: For efficient video streaming and content delivery.
- **Elastic Beanstalk**: Deployed for web server management and scalability.
- **Render**: Alternative deployment platform.

## Usage

- **Creators**: Can log in, upload and manage courses, view analytics, and edit content.
- **Learners**: Can create profiles, browse courses, enroll, and monitor learning progress on their dashboard.

## Deployment

### AWS Elastic Beanstalk
- Deploy the application by creating an Elastic Beanstalk environment and configuring the environment variables on AWS.

### Render
- Alternatively, deploy the platform on Render for continuous integration and ease of scaling.


