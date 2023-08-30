# EC2Backup

Consider your jenkins server is running on EC2 instance and the job configurations are stored on the jenkins server. You are assigned a task to do periodic configuraiton backup so that we do not loose anything if there is some issue with the server and you might have to terminate the current server and provision a new one. 

Please keep following points while implementing:
- Store the backup files on S3.
- The S3 bucket should be created by the script if it doesn't exist.
- Increamental backup should be captured.
- Make sure the backup is successful.
