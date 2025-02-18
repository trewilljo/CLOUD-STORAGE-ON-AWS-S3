# Cloud_Storage_Setup

*COMPANY*: CODTECH IT SOLUTIONS 

*NAME*: Aastha Joshi

*INTERN ID*: CT08OHH

*DOMAIN*: CLOUD COMPUTING

*BATCH DURATION*: JANUARY 20,2025 to FEBRUARY 20,2025

*MENTOR NAME*: NEELA SANTOSH

# Description
*AWS S3 (Simple Storage Service)*
Amazon Simple Storage Service (Amazon S3) is a leading object storage service that provides exceptional scalability, data availability, security, and performance. This versatile solution is applicable across various scenarios, including data lakes, websites, mobile applications, backup and restore operations, archiving, corporate applications, Internet of Things (IoT) devices, and big data analytics. Amazon S3 is designed to accommodate users from diverse sectors, allowing them to store and protect virtually any volume of data securely.

*TASK 1*
1. CREATE AND CONFIGURE CLOUD STORAGE ON AWS S3 OR GOOGLE CLOUD STORAGE.
2. DELIVERABLE: A BUCKET SETUP WITH EXAMPLE FILES UPLOADED AND ACCESS PERMISSIONS CONFIGURED.

# Procedure:

*Step 1: Logging in to the AWS Console*
- Go to the AWS Console and sign in with our credentials.
-  We need to navigate to the S3 service by searching for "S3" in the AWS Management Console.

*Step 2: Creating an S3 Bucket*
- We'll click on “Create Bucket” in the S3 dashboard.
- Now, we need to enter a unique bucket name (remember, bucket names must be globally unique). For example, let’s name our bucket "bbright."
- By default, all new S3 buckets are set to General Purpose, which is the recommended bucket type  and supports a wide range of use cases with no specific restrictions on storage class or data access.


<img src="create s3.png">

*step 3: Enabling ACLs and Configuring Public Access*

1. **Enable ACLs**:
   - we should opt for the option for **Object Ownership** and select **ACLs enabled**. This will allow objects in our bucket to be owned by other AWS accounts.

3. **Turn Off Block Public Access**:
   - Still in the **Permissions** section, we look for the **Block Public Access settings for this bucket**.
   - We will uncheck the box for **Block all public access**. This will make the bucket and its objects publicly accessible.

4. **Acknowledge the Warning**:
   - After unchecking the public access settings, a warning message will appear, stating the implications of making the bucket public.
   - We need to click the checkbox to acknowledge that we understand the risks involved with enabling public access.

5. **Final Review and Create Bucket**:
   - We should review all the settings we've configured for accuracy.
   - Finally, we click **Create Bucket** to complete the setup.

<img src="Public access settings for bucket.png">

*step 4:  Upload Objects to S3 Bucket*

1. **Now we Navigate to S3**  
   - Find the S3 service we made searching for "S3" in the AWS Management Console.  

2. **Open the Bucket we create**  
   - Click on the bucket we created earlier ("bbright").  

3. **Click "Upload"**  
   - In the bucket dashboard, click on the **Upload** button.  

4. **Select Files or Folder**  
   - Choose **Add files** or **Add folder** to upload multiple files at once.  

5. **Complete the Upload**  
   - Follow any prompts to finish uploading your selected files or folder.  
 
