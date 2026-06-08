
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
![S3 Bucket Created]<img width="1600" height="756" alt="image" src="https://github.com/user-attachments/assets/b7ea4131-b2d9-402e-b77d-549f79df2458" />


### 2. Uploaded the Website Files
Next, I uploaded my `index.html` file into the bucket.
![Files Uploaded]<img width="1600" height="756" alt="image" src="https://github.com/user-attachments/assets/21ac5bae-a443-4455-9f0d-a168c45245c7" />


### 3. Enabled Static Website Hosting
I turned on the "Static website hosting" feature in the bucket properties to get a public link for the website.
![Static Hosting Enabled]<img width="1600" height="756" alt="image" src="https://github.com/user-attachments/assets/c3324377-9136-465c-8412-1fc7098c9990" />


### 4. Turned Off "Block Public Access"
By default, AWS blocks public access for safety. Since this is a public website, I turned off this block so people can visit it.
![Block Public Access Disabled] <img width="1600" height="756" alt="image" src="https://github.com/user-attachments/assets/c44898fc-1ed2-417a-86f0-9ea68a5330b2" />


### 5. Added the Bucket Policy
I added a simple JSON bucket policy to allow anyone on the internet to view the website files (`GetObject` permission).
![Bucket Policy Added] <img width="1600" height="756" alt="image" src="https://github.com/user-attachments/assets/59b5d5aa-1d12-4715-bea6-ee5f518f2218" />


### 6. Website is Live!
Finally, I opened the AWS S3 endpoint link, and the website loaded perfectly!
![Website Live]<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/2af33968-a0dd-4565-b96b-64a5f4dcffcf" />


---
*Learning and building step-by-step!*
