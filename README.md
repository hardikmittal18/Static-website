# Static-website
Manually deploy static website into S3 bucket with HTTP hosting and CloudFront

Deploy a static website to AWS. Create a S3 bucket, configure the bucket for website hosting, and secure it using IAM policies. Upload the website files to your bucket and speed up content delivery using AWS’s content distribution network service, CloudFront. Lastly, access your website in a browser using the unique S3 endpoint.

## Files included:
- bucket.png - The S3 bucket is created
- websiteContent.png - All the website files uploaded to the newly created S3 bucket 
- website hosting.png - The S3 bucket is configured to support static website hosting
- bucket policy.png - The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.
- cloudfront.png - CloudFront has been configured to retrieve and distribute website files
- website.png - The website is accessible to anyone on the Internet via a web browser
