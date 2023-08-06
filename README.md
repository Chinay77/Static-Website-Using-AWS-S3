# AWS Static Website Hosting

Title: Easy Steps to Host Your Website on AWS S3

# Step 1: Get Started with AWS

If you don't have an AWS account, don't worry. Sign up is for a free tier. Once you're in, head to the AWS Management Console, where you'll find a treasure trove of services, including S3.

# Step 2: Create Your S3 Home

Inside the AWS Management Console, go to S3.
Hit "Create bucket" and give it a name – something unique like "your-website-bucket."
Choose a region that's closer to your audience for speedy loading.
Follow the prompts and create your bucket.

# Step 3: Set the Stage for Your Website

With your bucket selected, head to "Properties" and click "Static website hosting".
Opt for "Use this bucket to host a website".
Name your main page (e.g., "index.html") and an optional error page (e.g., "404.html").
Save your changes.

# Step 4: Drop Your Website In

Back on your bucket's main page, hit "Upload".
Toss in your website files – think HTML, CSS, JS, and images – using the drag-and-drop magic.
Make sure they're public by selecting them, clicking "Actions", and choosing "Make public".

# Step 5: Permissions 

Edit Bucket Policy:
Policy type - S3 Bucket Policy
Principal - write '*'
Actions - getobject

Click on Add statement and generate policy.
![image](https://github.com/Chinay77/Static-Website-Using-AWS-S3/assets/105514247/2f555972-6f34-4378-a205-d23ce582f06c)


# Step 6: The Big Reveal

Spot the "Endpoint" URL under "Static website hosting".
Copy this unique URL (e.g., http://your-website-bucket.s3-website-region.amazonaws.com).
Pop it into your browser's address bar and voilà – your website is live and kicking!

![image](https://github.com/Chinay77/Static-Website-Using-AWS-S3/assets/105514247/5f6e2757-80c7-4e07-a920-ac1b5caee66f)

MY Static WebPage Link - http://chinay-static-webpage.s3-website-us-east-1.amazonaws.com/

