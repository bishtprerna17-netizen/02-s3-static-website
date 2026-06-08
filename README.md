
# 02-s3-static-website
> A simple project showing how to host a static website using Amazon S3.

💡 **Note:** I deleted the S3 bucket after completing the project to save costs and avoid any accidental AWS bills. You can see all the step-by-step screenshots below!

---

## 📂 Project Structure
* 'index.html` - The basic webpage file.
* 'screenshots/` - Folder containing step-by-step proofs from the AWS Console.

---

## 🛠️ Step-by-Step Guide & Screenshots

### 1. Created the S3 Bucket
First, I created a new S3 bucket on the AWS Console.
![S3 Bucket Created](./screenshots/01-bucket-created)


### 2. Uploaded the Website Files
Next, I uploaded my `index.html` file into the bucket.
![Files Uploaded](./screenshots/02-files-uploaded)


### 3. Enabled Static Website Hosting
I turned on the "Static website hosting" feature in the bucket properties to get a public link for the website.
![Static Hosting Enabled](./screenshots/03-static-hosting-enabled)


### 4. Turned Off "Block Public Access"
By default, AWS blocks public access for safety. Since this is a public website, I turned off this block so people can visit it.
![Block Public Access Disabled](./screenshots/04-block-public-access-disabled)


### 5. Added the Bucket Policy
I added a simple JSON bucket policy to allow anyone on the internet to view the website files (`GetObject` permission).
![Bucket Policy Added](./screenshots/05-bucket-policy-added) 


### 6. Website is Live!
Finally, I opened the AWS S3 endpoint link, and the website loaded perfectly!
![Website Live](./screenshots/06-website-live)<




---
*Learning and building step-by-step!*
