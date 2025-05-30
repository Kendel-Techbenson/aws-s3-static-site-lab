# AWS S3 Static Website Hosting Lab

## 📄 Summary
This project demonstrates how to host a static website using Amazon S3. The lab walks through creating a bucket, configuring it for static hosting, uploading a sample HTML file, managing permissions with IAM, and verifying access control using read-only roles.

---

## 🛠️ What I Did (Step-by-Step)

1. **Created an S3 Bucket**
2. **Enabled Static Website Hosting**
3. **Uploaded `index.html` to the bucket**
4. **Set a Bucket Policy for Public Access**
5. **Verified the Website was Live**
6. **Simulated Upload Denied using IAM ReadOnlyUser**
7. **Updated IAM Group Permissions to Allow Upload**
8. **Verified Upload Succeeds with Correct Policy**
9. **Created IAM Group and User with Read-Only Permissions**
10. **Tested Access and Verified Results**

---

## 🖼️ Screenshots and Descriptions

| Step | Screenshot | Description |
|------|------------|-------------|
| 1 | ![s3-bucket-created](screenshots/s3-bucket-created.png) | S3 bucket created |
| 2 | ![s3-enable-static-hosting](screenshots/s3-enable-static-hosting.png) | Enabled static website hosting |
| 3 | ![s3-html-upload-success](screenshots/s3-html-upload-success.png) | Uploaded HTML file |
| 4 | ![s3-bucket-policy](screenshots/s3-bucket-policy.png) | Configured bucket policy for public access |
| 5 | ![website-live](screenshots/website-live.png) | Verified site is publicly accessible |
| 6 | ![s3-upload-denied](screenshots/s3-upload-denied.png) | Upload denied without write permissions |
| 7 | ![s3-upload-allowed](screenshots/s3-upload-allowed.png) | Upload succeeded after fixing permissions |
| 8 | ![iam-group-s3readonly](screenshots/iam-group-s3readonly.png) | IAM group with read-only policy |
| 9 | ![iam-user-created](screenshots/iam-user-created.png) | IAM user created |
| 10 | ![s3-file-uploaded](screenshots/s3-file-uploaded.png) | Verified file uploaded by IAM user |

---

## 🧠 Skills Demonstrated

- S3 bucket setup & static hosting configuration
- Writing bucket policies for public access
- IAM group & user creation
- IAM permission testing (read-only vs write access)
- AWS CLI for access simulation
- HTML deployment in the cloud

---

## 🔔 Notifications

- Bucket names must be **globally unique**
- Public access requires correctly configured policies
- IAM role testing ensures security best practices

---

## 🔗 S3 Website URL

**[*](https://kendel-access-lab-bucket.s3.us-east-1.amazonaws.com/index.html)*
