# Static Website Hosting Through Google Cloud Storage on GCP 
## Here are the steps to follow 

### Step1: Open and login to GCP console
This is how it looks like 

<img width="1707" height="801" alt="image" src="https://github.com/user-attachments/assets/4d48a258-ee0c-4a05-a823-401c5acaaf2c" />

### Step2: Search Google Cloud Storage 
Here is the dashboard of GCS

<img width="1707" height="801" alt="image" src="https://github.com/user-attachments/assets/64e4b0b8-716a-43d6-8deb-d05f2902835b" />

### Step3: Click on create bucket
The following screen will appear

<img width="1698" height="802" alt="image" src="https://github.com/user-attachments/assets/94ec0a6f-4612-4276-8d1c-786578e32e0b" />

### Step4: Enter name of bucket
Enter name of bucket. As we are hosting our website we can even put domain name as name of bucket. You need to verify the domain.

<img width="673" height="343" alt="image" src="https://github.com/user-attachments/assets/4186ef7a-baf2-47a8-a2bc-01ff48d0a44f" />

### Step5: Select the region
Select the location in which you want to make your bucket

<img width="715" height="673" alt="image" src="https://github.com/user-attachments/assets/fabe6ee1-2f36-416a-aab5-1d807b6b7e1d" />

### Step6: Choose how to store your data
<img width="715" height="673" alt="image" src="https://github.com/user-attachments/assets/5c59f528-640a-495a-a268-809ef5d250b8" />

### Step7: Access Control
Uncheck Enforce public access preventition on this bucket so the site can be publicly accessible. 

<img width="715" height="673" alt="image" src="https://github.com/user-attachments/assets/ff374aff-ca00-47b6-ad97-eadc8378b163" />

### Step8: Data protect 
In order to protect your data from huge blunders and mistakes you can use the following. After this click create button.

<img width="715" height="673" alt="Screenshot from 2026-10-07 12-47-05" src="https://github.com/user-attachments/assets/5aba1dc3-8015-490d-b5c8-a384b91e139e" />

### Step 9: The below screen will appear once the bucket is created
<img width="1678" height="723" alt="image" src="https://github.com/user-attachments/assets/f614b0bc-6056-4c6d-a086-436b7f3465e5" />

### Step10: Configure the bucket for website hosting
Open the bucket list page, find your bucket, click the three-dot menu icon on the right, and select Edit website configuration.

<img width="1678" height="723" alt="Screenshot from 2026-10-07 13-07-13" src="https://github.com/user-attachments/assets/9d043bf8-ec7c-49ce-acb4-74a5bbff2d87" />

### Step 11: Set the index page.
<img width="708" height="536" alt="Screenshot from 2026-10-07 13-11-02" src="https://github.com/user-attachments/assets/acd70665-8611-4a40-b3f0-9987794417a8" />

### Step12: Make Bucket Publicaly Readable
  - Click into your bucket and go to the permissions tab
  - Click Grant Access
  - In New principals, type allUsers
  - In Select a role, select Cloud Storage > Storage Object Viewer.
  - Click Save and then Allow Public Access to confirm.
    
<img width="695" height="721" alt="image" src="https://github.com/user-attachments/assets/42f9d696-22c4-4118-9d25-02271923874b" />

### Step13: To verify
Click on three dots of index.html file. Click on the option copy public url.

<img width="996" height="827" alt="image" src="https://github.com/user-attachments/assets/1566f191-3275-4210-9297-7a64af73964f" />

### Step14: Run it in browser
<img width="1693" height="467" alt="image" src="https://github.com/user-attachments/assets/3beab61d-f070-42fd-9872-3197258003a7" />
