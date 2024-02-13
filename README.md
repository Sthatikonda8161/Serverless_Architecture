# Serverless_Architecture
## Assignment question 1

1. Create a new lambda function
   ![image](https://github.com/Sthatikonda8161/Serverless_Architecture/assets/136583514/410367dc-8df8-4936-8d85-4fdb9ad1dfab)

2. Add code into the lambda function from the lambda_function.py file
![image](https://github.com/Sthatikonda8161/Serverless_Architecture/assets/136583514/22b1e33f-7de4-4b65-9391-302bb6b83cff)

3. Create two ec2 instances and tag the "Action" key accordingly. i.e. one with "Auto-Start" & "Auto-Stop. start the ec2 manually with Auto-Stop as a tag. Example image is given below
![image](https://github.com/Sthatikonda8161/Serverless_Architecture/assets/136583514/09fdc31a-70c4-47fd-9b75-8718b65b8d85)



4. Run the Lambda Function and check the response
![image](https://github.com/Sthatikonda8161/Serverless_Architecture/assets/136583514/5e036b74-83ac-4d3d-835d-f7dbee0dab0d)


5. Check in the ec2 console if servers are started and stopped
![image](https://github.com/Sthatikonda8161/Serverless_Architecture/assets/136583514/25d152fa-b94b-46b7-b510-920231d0e38e)

## Assignment - 2
Assignment 2: Automated S3 Bucket Cleanup Using AWS Lambda and Boto3

1. Navigate to the S3 dashboard and create a new bucket.

   Upload multiple files to this bucket, ensuring that some files are older than 30 days (you may need to adjust your system's date temporarily for this or use old files).
2. Lambda IAM Role:

   In the IAM dashboard, create a new role for Lambda.

   Attach the AmazonS3FullAccess policy to this role. (Note: For enhanced security in real-world scenarios, use more restrictive permissions.)

3. Lambda Function:

   Navigate to the Lambda dashboard and create a new function.

   Choose Python 3.x as the runtime.

   Assign the IAM role created in the previous step.

   Write the Boto3 Python script from lambda-q2.py:

   a. Initialize a boto3 S3 client.
   b. List objects in the specified bucket.
   c. Delete objects older than 30 days. d. Print the names of deleted objects for logging purposes.

![image](https://github.com/Sthatikonda8161/Serverless_Architecture/assets/136583514/22c0b8f5-98d6-4823-9bc9-57c8feea1bf3)


