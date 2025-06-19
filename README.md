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

