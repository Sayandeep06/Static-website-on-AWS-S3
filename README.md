# Hosting a Static Website on AWS S3 - 

Welcome to the "One Hour Project" where you'll learn how to host a static website using Amazon Web Services (AWS) Simple Storage Service (S3). In just one hour, you'll be able to deploy a website without the need for complex databases or backends. AWS S3's Free Tier offers an excellent solution for this purpose, providing scalability and high availability.

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

## Prerequisites

Before you begin, ensure you have the following:

- An AWS account (or you can sign up for one).

- Your website files in HTML, CSS, and JavaScript.

## Getting Started

Follow these steps to host your static website on AWS S3:

1. **Create an AWS Account**: If you don't have one, sign up for an AWS account at [AWS Management Console](https://aws.amazon.com/).

2. **Set Up Your S3 Bucket**: Create an S3 bucket to store your website files. Then uncheck all the options in the Block public access element of the bucket settings. Enable all public access
 ![Screenshot from 2023-10-30 01-34-59](https://github.com/Sayandeep06/Static-website-on-AWS-S3/assets/100061797/174cd3e7-1140-4cc1-a1bf-a38da7d28cbf)


3. **Configure Static Website Hosting**: Enable static website hosting on your S3 bucket and set the default index and error documents.

4. **Manage Access**: Use AWS IAM to secure access to your S3 bucket.

5. **Upload Your Website**: Upload your website files to the S3 bucket using the AWS CLI or the AWS Management Console.

6. **Custom Domain (Optional)**: If you want a custom domain, configure it using AWS Route 53.

7. **Access Your Website**: Your website will be available via the S3 bucket's URL or your custom domain (if set up).

## Project Structure

This repository includes:

- `README.md`: This README file.

Start hosting your static website on AWS S3 in just one hour and take advantage of AWS's scalability and availability!

Happy hosting!
