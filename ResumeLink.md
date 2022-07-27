# RESUME CHALLENGE #

[Cristian's Resume](https://cmresume.cr1st1anlinux.net/)

<!-- 
## **1. Certification** ##
- Your resume needs to have at least AWS Cloud Practitioner certification on it.
- This is an introductory certification that orients you on the industry-leading AWS cloud – if you have a more advanced AWS cert.
  
## **2. HTML** ##
- Your resume needs to be written in `HTML`. Not a Word doc, not a PDF.

## **3. CSS** ##
- Your resume needs to be styled with `CSS`.
- It doesn’t have to be fancy. But we need to see something other than raw HTML when we open the webpage.

## **4. Static Website** ##
- Your `HTML` resume should be deployed online as an Amazon `S3` static website.

## **5. HTTPS** ## 
- The `S3` website URL should use HTTPS for security.
- You will need to use Amazon `CloudFront` to help with this.

## **6. DNS** ## 
- Point a custom DNS domain name to the CloudFront distribution, so your resume can be accessed at something like my-c00l-resume-website.com.
- You can use Amazon `Route53` or any other DNS provider for this.
- A domain name usually costs about ten bucks to register.

## **7. Create a Counter (use `Javascript` or `Python`)** ##
- Your resume webpage should include a visitor counter that displays how many people have accessed the site.
- You will need to write a bit of `Javascript` to make this happen.

## **8. Database** ##
- The visitor counter will need to retrieve and update its count in a database somewhere.
- I suggest you use `DynamoDB` for this.
- (Use on-demand pricing for the database and you’ll pay essentially nothing, unless you store or retrieve much more data than this project requires.)

## **9. `API`** ##
- Do not communicate directly with `DynamoDB` from your `Javascript` code.
- Instead, you will need to create an `API` that accepts requests from your web app and communicates with the database.
- I suggest using `AWS API Gateway` and `AWS Lambda` services for this.

## **10. Python** ##
- You will need to write a bit of code in the Lambda function;
- you could use more `Javascript`, but it would be better for our purposes to explore `Python` – a common language used in back-end programs and scripts – and its `Boto3` library for `AWS`.

## **11. Tests** ##
- You should also include some tests for your Python code.

## **12. Infrastructure as Code (IaC)** ##
- You should not be configuring your `API` resources – the `DynamoDB` table, the `API Gateway`, the Lambda function – manually, by clicking around in the AWS console.
- Instead, define them in an AWS Serverless Application Model (`SAM`) template and deploy them using the `AWS SAM CLI`.

## **13. Source Control/Mangement Configuration** ##
- You do not want to be updating either your back-end API or your front-end website by making calls from your laptop, though.
- You want them to update automatically whenever you make a change to the code.
- Create a `GitHub` repository for your backend code.

## **14. CI/CD (Back end)** ##
- Set up `GitHub Actions` such that when you push an update to your Serverless Application Model template or `Python` code, your `Python` tests get run.
- If the tests pass, the `SAM` application should get packaged and deployed to `AWS`.

## **15. CI/CD (Front end)** ##
- Create a second `GitHub` repository for your website code. Create `GitHub Actions` such that when you push new website code, the `S3` bucket automatically gets updated
- (You may need to invalidate your `CloudFront` cache/distrubution in the code as well.)
- **Important note:** _DO NOT commit AWS credentials!_

## **16. Blog Post** ##
 + Finally, in the text of your resume, you should link a short blog post describing some things you learned while working on this project. `Dev.to` or `Hashnode` are great places to publish if you don’t have your own blog.
 -->
