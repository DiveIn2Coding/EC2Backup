# EC2Backup

Consider your Jenkins server is running on an EC2 instance and the job configurations are stored on the Jenkins server. You are assigned a task to do periodic backups of configuration files so that we do not lose anything if there is some issue with the Jenkins server and you might have to terminate the current server and provision a new one. 

Please keep following points while implementing:
- Store the backup files on S3.
- The S3 bucket should be created by the script if it doesn't exist.
- Increamental backup should be captured.
- Make sure the backup is successful.
