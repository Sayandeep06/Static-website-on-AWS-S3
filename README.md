# Hosting a Static Website on AWS S3 - 

AWS S3 is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. I deployed a static website to AWS S3 storage service in this project. An S3 bucket was created and configured  for website hosting, secured using IAM policies. Next, I uploaded the website files to your bucket. Lastly, accessed the website in a browser using the unique S3 endpoint.

## Why Use AWS S3 for Hosting?

Many companies and individuals require a website, and most of these websites don't necessitate intricate server setups or databases. AWS S3 is an excellent choice for hosting static websites due to its simplicity and cost-effectiveness. With this project, you can harness the full potential of AWS S3 for web hosting.

## Project Overview:

1. Create an AWS account if you don't already have one. 

2. Set up an S3 bucket to store your static website files.

3. Configure the S3 bucket for static website hosting, including specifying the default index and error documents.

4. Secure access to the S3 bucket using AWS Identity and Access Management (IAM).

5. Upload your website's HTML, CSS, and JavaScript files to the S3 bucket.

6. Optionally, configure a custom domain and DNS settings using AWS Route 53.

7. Access your static website via the S3 bucket's URL or your custom domain.


## Getting Started

Steps to host the static website on AWS S3:

1. **Created an AWS Account**: If you don't have one, sign up for an AWS account at [AWS Management Console](https://aws.amazon.com/).

2. **Set Up Your S3 Bucket**: Created an S3 bucket to store the website files. Then unchecked all the options in the Block public access element of the bucket settings. Enabled all public access
 ![Screenshot from 2023-10-30 01-34-59](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/174cd3e7-1140-4cc1-a1bf-a38da7d28cbf)


3. **Configure Static Website Hosting**: Enabled static website hosting on your S3 bucket from properties and set the default index as index.html and error document as error.html.![Screenshot from 2023-10-30 01-33-16](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/c9274945-9e0b-4a54-a7de-65a987b93f1c)


4. **Manage Access**: Use AWS IAM to secure access to your S3 bucket. 

5. **Upload Your Website**: Upload your website files to the S3 bucket using the AWS CLI or the AWS Management Console.![Screenshot from 2023-10-30 02-00-21](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/ca7a23fa-0a0b-4556-ae96-a8fe3769187a)


6. **Make your website files public**: Select all the files on S3 bucket created and click on actions. Then make them public![Screenshot from 2023-10-30 01-54-56](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/fcd0d394-468f-479f-beab-3f748470c8af)


7. **Access Your Website**: Your website will be available via the S3 bucket's endpoint URL or your custom domain. This is the link to my website setup on S3 http://staticnewwebsite.s3-website.ap-south-1.amazonaws.com/ (the bucket is probably deleted now and won't be able to access)![Screenshot from 2023-10-30 01-41-08](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/1a642ba1-bce5-43c2-a8f3-33fc9f787e5b) ![Screenshot from 2023-10-30 01-41-15](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/f0c93d68-abd0-4d23-b704-f11e05e82e5f)
  
8. **Enable versioning**: From the properties tab enable versioning to make any changes to the website. The new file uploaded as an update must be made public explicitly and if you wanna revert back to the previous version, just delete the update file.![Screenshot from 2023-10-30 01-47-57](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/0ad71f77-2e6f-4707-8344-9613396d4de2)

## Key takeaways 
I was able to understand how AWS S3's main components work and how to use them to create and upload our static website.

Learned how to configure AWS S3 to host a static website, configure main pages, and error pages, and see website endpoint, in any region around the world.

Was able to set the right permissions and security configurations to make our static website public and available for all internet users.

Configured versioning for our static website, made updates, and rolled back updates.



