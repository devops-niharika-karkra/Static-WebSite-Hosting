# STATIC WEBSITE HOSTING THROUGH AWS S3

**_S3_** stands for  Simple Storage Service. Amazon S3 is an object storage service and every object in S3 is stored in a bucket
that offers industry-leading scalability, data availability, security, and performance.

## Steps to host static website

### Step1: Search and open dashboard of S3 service on AWS 
<img width="1691" height="751" alt="image" src="https://github.com/user-attachments/assets/e24c8f56-a26b-456a-b709-3c53a0af3669" />

### Step2: Click on create the bucket
<img width="1100" height="422" alt="image" src="https://github.com/user-attachments/assets/e0890313-0268-4ffd-ad1d-9663e24fd712" />

### Step3: The region of bucket
This is selected by the the region of aws you are currently working in. It can be changed from the drop-down you can get by clicking the 
arrow given on top right corner with te region name you are currently working in.

<img width="645" height="218" alt="image" src="https://github.com/user-attachments/assets/e5d3f7ce-6675-490e-87be-1f8e55ec75fb" />

### Step4: Select type of bucket
In this we will select the type of bucket. To host website we will go with general one.

<img width="1601" height="327" alt="image" src="https://github.com/user-attachments/assets/86cd5184-eb2e-4d39-8ac6-cd37cbe201db" />

### Step5: Define bucket name 

<img width="1531" height="116" alt="image" src="https://github.com/user-attachments/assets/58c5c68b-87db-401d-be56-54c7acd52aac" />

### Step6: Set the object ownership
This option is useful when you work in team and you need that each teammate who is putting any object in s3 should have the ownership of that.

<img width="1481" height="283" alt="image" src="https://github.com/user-attachments/assets/c004c669-0a46-402e-a83b-23805b0f9aad" />

### Step7: Remove block public access 
We have to remve the block poblic access to host a static website.

<img width="1591" height="447" alt="image" src="https://github.com/user-attachments/assets/e91760fa-dfa7-4d69-a2a3-438672395da9" />

### Step8: After finishing the settings you have to click on create bucket button to create a bucket
<img width="1660" height="185" alt="image" src="https://github.com/user-attachments/assets/33f0103f-fff9-46e5-ae1d-bff767c945be" />

### Step9: Upload the website files.
<img width="1673" height="507" alt="image" src="https://github.com/user-attachments/assets/35174964-48ce-42cd-a53b-3829a72e49a6" />

Check upload status

<img width="1687" height="443" alt="Screenshot from 2026-10-05 15-35-30" src="https://github.com/user-attachments/assets/c9f00cc5-6e3d-4298-82b2-ea60ae0eb8c1" />

### Step10: Enable Static Website Hosting
Click on properties and scroll down to static website hosting

<img width="1650" height="328" alt="Screenshot from 2026-10-05 15-36-04" src="https://github.com/user-attachments/assets/ee250941-71f8-4205-8ad6-b7b25e28f631" />

Click enable and write the name of default page in the given space
<img width="1658" height="592" alt="Screenshot from 2026-10-05 15-36-29" src="https://github.com/user-attachments/assets/e73a78fe-336c-47aa-b102-2a3a3e5b8b7f" />

### Step11: Create an IAM policy to give read access to objects in s3
Go to permissions and scroll down to bucket policy and then click on edit

<img width="1653" height="697" alt="Screenshot from 2026-10-05 15-39-16" src="https://github.com/user-attachments/assets/b649a7e4-8c7b-4f3d-ab01-ac816799be7c" />

write this policy in it 

<img width="1166" height="337" alt="Screenshot from 2026-10-05 15-42-59" src="https://github.com/user-attachments/assets/5d93893e-8731-4360-9ca4-1acefbd7cbbb" />

### Step12: Get the endpoint and paste it on browser
<img width="1673" height="507" alt="image" src="https://github.com/user-attachments/assets/d4b20fde-5c8b-40da-8097-b5998793e0e9" />

<img width="1673" height="507" alt="image" src="https://github.com/user-attachments/assets/4710c4d8-89a0-4291-935f-b081be449887" />

### Step13: Add DNS records
Copy your endpoint and add reord in CNAME

<img width="1137" height="495" alt="image" src="https://github.com/user-attachments/assets/3dbf2ec1-f3a3-4845-af2c-f6c08a2e9418" />
