# Static Website Hosting On Azure Using Blob Storage

## Steps for hosting website 
### Step1: Sign in to azure portal
<img width="1687" height="596" alt="image" src="https://github.com/user-attachments/assets/c4784b22-e7c4-42f6-bc4a-f912e67e5c22" />

### Step2: Create storage account
  - search for storage account
    <img width="521" height="342" alt="image" src="https://github.com/user-attachments/assets/478a0d19-36b9-44de-94b7-57d82e732361" />
  - create a storage account
      - Subscription: Choose your subscription.
      - Resource group: Select an existing group or create a new one.
      - Storage account name: Enter a unique name for your storage account.
      - Region: Choose a region close to your users.
      - Performance: Choose Standard.
      - Replication: Choose the replication option that suits your needs (e.g., LRS, GRS).
      - Click “Review + Create”. 
        <img width="967" height="788" alt="Screenshot from 2026-10-06 14-16-18" src="https://github.com/user-attachments/assets/6a719526-56b6-4c68-9f2e-9aad7b608104" />

### Step3: Preview and create
After clicking "Review and create", you'll get to preview the details you filled 

<img width="908" height="783" alt="image" src="https://github.com/user-attachments/assets/fe0d6e5d-388f-4392-b069-490c45c217c8" />

### Step4: Then you'll get to see this 
Here, you have to click go to resources 
<img width="771" height="776" alt="image" src="https://github.com/user-attachments/assets/5e0387af-7d51-487a-aa1c-34c049abd0da" />

### Step5: Then you'll upto this page
<img width="1663" height="766" alt="image" src="https://github.com/user-attachments/assets/433cdf17-fa4a-447b-a7d8-a860b3c41503" />

### Step6: Navigate to static website 
Scroll down to data management. Open the drop down and select static website.

<img width="390" height="702" alt="image" src="https://github.com/user-attachments/assets/a9c800bc-5461-4d0d-b86a-b4942f25e153" />

### Step7: Enable static website hosting
  - Click the toggle button to enable
  - Enter the default page
  - Click on save 
<img width="1688" height="667" alt="image" src="https://github.com/user-attachments/assets/575c585d-642e-4bd9-b2f1-825a145c6903" />

### Step8: Once the file is successfully saved you'll get the endpoint

<img width="1347" height="96" alt="image" src="https://github.com/user-attachments/assets/5fc62aad-d204-4be2-86e4-7104a3ba5873" />

### Step9: Now look for data storage on left side menu and open containers
<img width="1682" height="471" alt="image" src="https://github.com/user-attachments/assets/b544d67d-8aa5-4f15-b164-c470c0605d08" />

### Step10: Now open $web container and upload your code files in that
<img width="1691" height="572" alt="image" src="https://github.com/user-attachments/assets/6f5fc7c7-f04d-4bf8-a419-6cc8814283b6" />

### Step11: uploaded files and folder
Files can be uploaded normally with upload button 
Folders are first created in azure and then the files in it are uploaded through same way it was uploaded before.
<img width="1360" height="603" alt="image" src="https://github.com/user-attachments/assets/7bc31f45-0f48-4e1f-adef-a94b7ea7c569" />

### Step12: To verify
Paste the end point we got it above in browser.
<img width="1367" height="700" alt="image" src="https://github.com/user-attachments/assets/8b4ea384-2963-44e3-b74e-ebccb6fec13f" />

