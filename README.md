# ☁️ AWS S3 Static Website Hosting

This project demonstrates how to **host a static website using Amazon S3**.  
It includes setup steps, bucket policies, and AWS CLI commands — perfect for learning how to deploy a simple static website on the cloud.

---

## 🌐 Overview

AWS **Simple Storage Service (S3)** allows you to host static websites (HTML, CSS, JS, images) without needing any servers.  
It’s **fast**, **scalable**, and **cost-efficient** for small to large projects.


---
## 🚀 Steps to Host Website
### Step1: Create your S3 bucket
- Name
- Disable Public Access Block

![](./IMG/S3%20bucket.png)

---

### Step2: Give Permissions 
- Enable Static Website Hosting

![](./IMG/Screenshot%20(386).png)

---
 ### Step3: Generate Poicies
- Choose S3 bucket
- Getobject, Principle=*, ARN, Add statement
- Create a Bucket Policy

![](./IMG/Screenshot%20(387).png)

---
### Step4: Upload website files
- index.html
- error.html
- images/
---

### Step5: Check on browser
- Copy the bucket website endpoint
- Paste on browser

![](./IMG/Screenshot%20(388).png)

---


## 🧠 What You’ll Learn

<table border="6" cellspacing="0" cellpadding="6">
  <tr>
    <th>Step</th>
    <th>Topic</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1️⃣</td>
    <td><b>Create Bucket</b></td>
    <td>Make a new S3 bucket for hosting your website</td>
  </tr>
  <tr>
    <td>2️⃣</td>
    <td><b>Enable Hosting</b></td>
    <td>Turn on static website hosting in S3</td>
  </tr>
  <tr>
    <td>3️⃣</td>
    <td><b>Set Policy</b></td>
    <td>Allow public read access</td>
  </tr>
  <tr>
    <td>4️⃣</td>
    <td><b>Upload Files</b></td>
    <td>Use AWS CLI to sync website files</td>
  </tr>
  <tr>
    <td>5️⃣</td>
    <td><b>Access Site</b></td>
    <td>Use the S3 endpoint URL to visit your hosted site</td>
  </tr>
</table>

---


## 🛠️ Prerequisites

<table border="3" cellspacing="0" cellpadding="6">
  <tr>
    <th>Requirement</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>🧑‍💻 <b>AWS Account</b></td>
    <td>To access S3 and create buckets</td>
  </tr>
  <tr>
    <td>⚙️ <b>AWS CLI Installed</b></td>
    <td>To run commands in your terminal</td>
  </tr>
  <tr>
    <td>💻 <b>Website Files</b></td>
    <td>Example: <code>index.html</code>, <code>error.html</code>, <code>styles.css</code></td>
  </tr>
</table>

---

##  🏁 Conclusion

Hosting a static website on Amazon S3 is one of the simplest and most efficient ways to make your project live on the internet.
It provides high availability, scalability, and cost-effectiveness without managing any servers.
