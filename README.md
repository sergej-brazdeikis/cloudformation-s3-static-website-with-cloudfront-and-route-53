## Cloudformation template for creating static website

It creates the infrastructure for static website in AWS from scratch in minutes.

Building parts:
- AWS S3
- AWS Cloudfront
- AWS Route53
- AWS Cloudformation

## How to

- Apply `route53-zone.template` for the domain.
- Apply `s3-static-website-with-cloudfront-and-route-53.template` for each subdomain need:
    - www.jevsejev.io
    - perfect-blog.jevsejev.io
- Upload your `index.html` to the S3 bucket

Your website is provisioned.

### Links

In order to apply the template you need to upload it to AWS Cloudformation: [How to upload the Cloudformation template](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-using-console-create-stack-template.html)
