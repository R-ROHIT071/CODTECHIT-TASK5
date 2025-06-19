Task 4 – Cloud Security Implementation
1. IAM User + Policy
- Created IAM user: `s3-read-user`
- Gave it the AWS-managed policy: `AmazonS3ReadOnlyAccess`
- User can only **view objects in S3**, not write or delete

  
 2. S3 Encryption (Secure Storage)
- Enabled **default encryption** on my S3 bucket (`task-3-frontend`)
- Used: **SSE-S3 (Amazon S3 Managed Keys)**
- All future uploads to this bucket are encrypted automatically

3. Secure Access Policy (HTTPS-only)
- Added a **bucket policy** to block all insecure (HTTP) access
- Bucket now accepts only **HTTPS requests**

  🛠️ Tools Used

- AWS IAM (Identity & Access Management)
- Amazon S3
- AES-256 Encryption
- Bucket Policy (JSON)

ATTACHED IMAGES 1-4->
![Image](https://github.com/user-attachments/assets/b4cd9656-d004-4daa-a3d7-d20bffebebfb)

![Image](https://github.com/user-attachments/assets/b41ab6f0-bb4d-4e1b-8dee-307ced767bcd)

![Image](https://github.com/user-attachments/assets/35f1d6cc-7b8b-440c-8645-c8da6ce58dba)

![Image](https://github.com/user-attachments/assets/a8020f69-7f9b-4b98-9ba6-640f61d6cc3d)
