# 🌐 AWS CI/CD Pipeline for Static Website

## 🚀 Project Overview  
This project demonstrates a complete CI/CD pipeline for deploying a static website using AWS cloud services.

The website source code is stored in GitHub. Whenever changes are pushed, AWS CodePipeline automatically triggers a workflow that builds the project using CodeBuild and deploys it to an S3 bucket.

---

## 🧰 Tech Stack  
- GitHub  
- AWS CodePipeline  
- AWS CodeBuild  
- Amazon S3  
- HTML, CSS, JavaScript  

---

## 🏗️ Architecture  
GitHub → CodePipeline → CodeBuild → S3  

GitHub stores the source code, CodePipeline automates the workflow, CodeBuild processes the build, and S3 hosts the deployed website.

---

## ✨ Features  
- Fully automated CI/CD pipeline  
- Continuous deployment on every Git push  
- Static website hosting on S3  
- No manual deployment required  
- Scalable and efficient workflow  

---

## 📸 Screenshots  
<img width="1918" height="1040" alt="4" src="https://github.com/user-attachments/assets/f8f210a4-a125-4106-8344-750f4871ecd0" />
<img width="1920" height="1041" alt="1" src="https://github.com/user-attachments/assets/3ed4f760-f221-46fe-815c-82144e949148" />
<img width="1928" height="986" alt="2" src="https://github.com/user-attachments/assets/b40e540d-c9a2-42e4-a662-787200eb4875" />
<img width="1922" height="917" alt="3" src="https://github.com/user-attachments/assets/f3f1c309-d20f-4368-85b3-54c76288ef35" />
<img width="1920" height="1040" alt="5" src="https://github.com/user-attachments/assets/8502e07c-8e20-461d-99b9-78eed5e6a4a3" />

---

## 🧠 What I Learned  
- Setting up CI/CD pipelines using AWS  
- Integrating GitHub with AWS services  
- Automating deployments using CodePipeline  
- Using CodeBuild for build automation  
- Managing static website hosting with S3  

---

## ⚙️ Deployment Steps  
- Create a GitHub repository for website code  
- Add `buildspec.yml` file to define build steps  
- Create an S3 bucket for deployment  
- Set up AWS CodePipeline  
- Connect GitHub repository as source  
- Configure CodeBuild project  
- Add S3 as deployment stage  
- Push code changes and verify auto deployment  

---
## ⚠️ Note
AWS resources should be monitored to avoid unnecessary billing.  
Browser caching may require manual refresh to see updates

---

## 💼 Resume Highlight
Implemented a CI/CD pipeline using GitHub, AWS CodePipeline, and CodeBuild to automate deployment of a static website to S3, enabling continuous delivery with zero manual intervention.
