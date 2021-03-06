
 ## Deployed Static Website on Amazon web services (AWS)S3 bucket
    This project deploys static web page using AWS s3 bucket. The bucket is secured with IAM read only policy. Content distribution service, `CloudFront` is used to speed up the distribution of web page in the browser. 

### Prerequisite
    1. AWS account. Create group and user.
    2. Knowledge of IAM, S3, CloudFront.

### Summary of working of project
    
    1. I hosted static website named Vacation Spots, using Amazon web services (AWS) S3 bucket.
    2. I secured bucket with IAM read only policy. I configured bucket for website hosting.
    3. I used AWS content distribution network service, CloudFront, to speed up the content delivery.
    4. My website could be accessed in a browser with s3 endpoint.

### Steps
    1. I created S3 bucket. Uploaded files such as index.html which contains my website content, image-background image used in html, css, bootstrap, font-awesome.
    2. I secured bucket with IAM read only policy. For this, I changed bucket policy to getObject action.
    3. I configured bucket for static website hosting. For this, I went to properties tab and enabled static website hosting.
    4. I configured CloudFront with s3 url. 

### Files included are
    1) index.html- Displays content of web application
    2) \css
    3) \Screen Shots- Screen Shots of different steps while deploying website
    4) \vendor- Contains bootstrap

### Instruction to deploy
    Click on the url that is displayed after the CloudFront is deployed. 





