# awsmigration
### 1. Sync Local Folder to an S3 Bucket (Upload)
`aws s3 sync directory_name s3://my-bucket-name `
### 2. Sync Bucket to Bucket
`aws s3 sync s3://source-bucket-name s3://destination-bucket-name `
##wget -O ./aws-replication-installer-init.py https://aws-application-migration-service-<REGION>.s3.<REGION>.amazonaws.com/latest/linux/aws-replication-installer-init.py
##sudo python3 aws-replication-installer-init.py'
