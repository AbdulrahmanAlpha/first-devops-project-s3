# 🌐 First DevOps Project: Deploy a Static Website to AWS S3

Welcome to your **first hands-on DevOps project**!  
In this simple guide + repo, we’ll show you how to deploy a static HTML/CSS website to **Amazon S3** — manually, step-by-step.

> 💡 This is part of my beginner DevOps series: [Read the full article here](https://abdulrahmanalpha.hashnode.dev/your-first-devops-project-deploy-a-static-website-to-aws-s3-step-by-step-guide)

---

## 🚀 What You'll Learn

- How to structure and build a static website (HTML + CSS)
- How to create and configure an AWS S3 bucket
- How to host your site publicly using S3
- How to upload files via **AWS CLI**
- Bonus: how to prepare for future CI/CD automation

---

## 🗂️ Project Structure

```

/first-devops-project
├── index.html
└── styles.css

````

✅ You can open `index.html` in your browser to preview it locally.

---

## ☁️ Hosting on AWS S3 (Summary)

> For the full step-by-step guide, [read the tutorial here](https://abdulrahmanalpha.hashnode.dev/your-first-devops-project-deploy-a-static-website-to-aws-s3-step-by-step-guide)

1. Create an S3 bucket  
2. Enable static website hosting in the bucket properties  
3. Make the bucket publicly readable via a bucket policy  
4. Upload files using the AWS CLI:

```bash
aws s3 cp ./first-devops-project s3://your-bucket-name/ --recursive
````

5. Visit the **S3 website endpoint** to view your live site 🎉

---

## 📥 Download This Project

Click the green **Code** button and choose **Download ZIP**, or clone the repo:

```bash
git clone https://github.com/AbdulrahmanAlpha/first-devops-project-s3.git
```

---

## 🔗 Stay Connected

* 🧠 Blog: [abdulrahmanalpha.hashnode.dev](https://abdulrahmanalpha.hashnode.dev)
* 💻 GitHub: [@AbdulrahmanAlpha](https://github.com/AbdulrahmanAlpha)
* 🌐 Portfolio: [abdulrahman-alpha.web.app](https://abdulrahman-alpha.web.app)
* 📺 YouTube: [AlphaOpsCraft](https://www.youtube.com/@alphaopscraft)

---

## 🧪 What's Next?

This repo is part of a multi-step DevOps journey.
Next, we’ll learn how to automate deployment using **GitHub Actions**. Stay tuned!

---

### 👨‍💻 Made with 💙 by Abdulrahman A. Muhamad
