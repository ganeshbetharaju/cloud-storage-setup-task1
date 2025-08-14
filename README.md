# Codetech Cloud Computing Internship Project

This repository documents my work for the Codetech Cloud Computing Internship.

---

## Task 1: Cloud Storage Setup on AWS S3

**Objective:** To create and configure a cloud storage bucket using AWS S3, upload files, and set public access permissions[cite: 24, 25].

### Step 1: Creating the S3 Bucket

I began by setting up the storage container (a "bucket") in AWS.

1.  **Navigated to S3:** Logged into the AWS Management Console and selected the S3 (Simple Storage Service).
2.  **Initiated Creation:** Clicked the "Create bucket" button to start the configuration process.
3.  **Configured Bucket Details:**
    * **Bucket Name:** Assigned a globally unique name to the bucket.
    * **AWS Region:** Selected a geographical region to host the bucket.
4.  **Set Public Access Permissions:** In the "Block Public Access settings for this bucket" section, I un-checked **"Block all public access"** and acknowledged the warning. This step is necessary to allow for a public access policy later.
5.  **Created the Bucket:** Finalized the settings and clicked "Create bucket".

### Step 2: Uploading Files and Configuring Public Access

With the bucket created, the next step was to add content and make it accessible.

1.  **Uploaded Files:** Navigated inside my newly created bucket and used the "Upload" button to add several example files[cite: 25].
2.  **Configured Bucket Policy:**
    * Went to the **"Permissions"** tab of the bucket.
    * Clicked on "Bucket Policy" and used the policy editor to attach a JSON policy that grants read-only permission (`s3:GetObject`) to anonymous users.

### Deliverable: Final Configuration

The task result is a fully configured S3 bucket with files that are accessible publicly, as demonstrated by the screenshots below[cite: 25].

#### 1. Bucket with Uploaded Files
<img width="1920" height="1080" alt="Screenshot 2025-08-15 001259" src="https://github.com/user-attachments/assets/345908b8-0e90-488c-8e52-e690e7ed0b7e" />


#### 2. Public Access Permissions Confirmed
<img width="1920" height="1080" alt="Screenshot 2025-08-15 001426" src="https://github.com/user-attachments/assets/1f19c90f-4d33-40ae-bcd5-0e9e45985ef9" />


---
