# Cloud Portfolio on AWS

A responsive static portfolio website hosted on Amazon S3 and delivered globally using Amazon CloudFront with HTTPS.

## 🚀 Live Demo

**[View Live Portfolio](https://d5fz0wy8dnzo2.cloudfront.net/)**

## 📌 Project Overview

This project was completed as part of the **ProStackHub Cloud Computing Internship**.

### Task 1: Cloud Foundations — Host a Static Website with Global Delivery

The portfolio website is hosted using **Amazon S3** and delivered to users through **Amazon CloudFront**. CloudFront provides global content delivery and HTTPS access to the website.

## ☁️ AWS Architecture

```text
                    User / Browser
                         |
                         | HTTPS
                         ↓
              Amazon CloudFront
                  CDN / HTTPS
                         |
                         | OAC
                         ↓
                 Amazon S3 Bucket
                  Private Origin
                         |
              ┌──────────┼──────────┐
              ↓          ↓          ↓
          index.html  style.css  script.js
