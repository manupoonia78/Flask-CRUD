# Flask-CRUD

boto3: AWS SDK for Python
moto: Mock AWS Services
Pytest: Test framework for Python


#To unit test using moto
```
Run pytest test_s3.py
```

The /storage endpoint will be the landing page where we will display the current files in our S3 bucket for download, and also an input for users to upload a file to our S3 bucket,
The /upload endpoint will be used to receive a file and then call the upload_file() method that uploads a file to an S3 bucket
The /download endpoint will receive a file name and use the download_file() method to download the file to the user's device
