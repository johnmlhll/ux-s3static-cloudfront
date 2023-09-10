
# This Project

This project is focused on UX design and crafting old UX content (created by me in 2017) into a front end. It will also use AWS services to deploy a static website using Azure DevOps. Its UX focus makes it a content writing and web frontend project. It also has a DevOps project focus developing a static website in HTML, CSS, and Javascript (clientside). The CloudFormation template is customised for this project to firstly provision an s3 bucket, and then an AWS CLoudFront instance. Once done, the S3 bucket is bound via OAI policy to the CloudFront instance completing the templates automated provisioning of service infrastructure. The 2nd stage of the pipeline will deploy the app payload to the s3 bucket for rendering onto the cloudfront distribution. No custom domain was included in this project nor associated securing of its routing via TLS encryption over SSL. AWS's inbuilt securitizing of its DomainName will be used given this is a demo project for the promotion of good UX design by Maolte Technical Solutions.

# ux-s3static-cloudfront
Refined old project UX code and coded IaC for CloudFront S3 deployments to deploy under time pressure to the Sandbox AWS account.

# Maolte Technical Solutions Limited

This repo is the 4th in a series of demo deployments for the company I set up to pursue contracting. My intent for these repos is to demo my technological skills, mainly in infrastructure deployments over time. The idea is to show case reusable infrastructure as code (IaC) for cloud resources via Azure Devops and CloudFormation templating in AWS. I will, time permitting code up some fun apps for demo purposes and demo infrastructure as I go.

Maolte Technical Solutions Limited was set up provide specialist services in the Cloud Infrastructre, DevOps and Writing. More at https://maolte.ie. Any queries, drop me a long at john@maolte.ie.

Best Regards 
John

Founder | Engineer | Writer 
Maolte Technical Solutions Limited
