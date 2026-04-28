# 🚀 AWS Static Website Deployment using S3 + CloudFront

## 📌 Project Overview

This project demonstrates a real-world cloud deployment scenario where a company website was facing performance and availability issues. The solution was implemented using AWS services to build a fast, scalable, and globally accessible static website.

---

## Problem Statement

A startup company had its website hosted on a traditional server, which caused multiple issues:

- Slow website loading speed for users in different regions
- Frequent downtime due to server limitations
- High maintenance and infrastructure costs
- Poor scalability during traffic spikes
- No global content delivery optimization

These issues affected user experience and business growth.

---

## 💡 Proposed Cloud Solution

To solve these challenges, a serverless and scalable architecture was designed using AWS:

- Amazon S3 for static website hosting
- AWS CloudFront for global content delivery (CDN)
- Public access configuration for website availability

---

## Architecture

User → CloudFront CDN → Amazon S3 (Static Website Hosting)

---

## ⚙️ Implementation Steps

### 1. S3 Bucket Creation
- Created an S3 bucket for storing website files
- Enabled static website hosting

### 2. Website Deployment
- Uploaded `index.html` file to S3 bucket
- Configured public access permissions using bucket policy

### 3. CloudFront Configuration
- Created CloudFront distribution
- Connected S3 website endpoint as origin
- Enabled global content caching for faster performance
- Configured HTTPS redirection for security

---

## 📈 Results & Improvements

After deployment, the following improvements were achieved:

- ⚡ Significant improvement in website loading speed
- 🌍 Global accessibility with low latency via CloudFront CDN
- 💰 Reduced infrastructure cost (no traditional server required)
- 📊 Improved scalability for handling traffic spikes
- 🔐 Better security with HTTPS enabled via CloudFront

---

## 🎯 Key Learnings

- Understanding of AWS S3 static hosting
- CDN concept and real-world usage of CloudFront
- Importance of bucket policies and public access control
- Basic cloud architecture design principles

---

## 🔗 Live Project

CloudFront URL: d3r0421bh2cbif.cloudfront.net

---

## 🎥 Demo Videos

S3 Bucket- https://drive.google.com/file/d/10YCSDYth2DM_dgYy4lqDKkbAF61sq1V1/view?usp=sharing
CloudFront - https://drive.google.com/file/d/1bEjjJRaNbIBMWGknwGy5Zfi_7OuxbyEB/view?usp=sharing

---

## 👨‍💻 Author

Umar Ali  
Aspiring Cloud Engineer (AWS Focused)
