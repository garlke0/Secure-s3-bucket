# Secure-s3-bucket
I've tried the same process (securing an S3 bucket) on AWS CLI, and it was easier because of the CLI and the simple GUI
# Secure S3 Bucket Project

## Description
Configuring MinIO S3 bucket with user aliases and permissions.

## Tools
- MinIO
- mc (MinIO Client)
- Windows 10

## Steps
1. Created bucket and user aliases
2. Set permissions for admin and readonly users
3. Tested file upload and delete access

## Results
- Admin can upload/delete files
- Readonly cannot delete files (access denied)

## Recommendations
- Regularly review user permissions
- Enable logging and monitoring
