# Static-Website
The "Secure Static Website Deployment to AWS S3 with HTTPS using CloudFront" 
project focuses on deploying a secure static website on Amazon S3 
while leveraging CloudFront for enhanced security and global availability.
It includes  with setting up and configuring a new S3 bucket and 
implementing robust security measures through generating new bucket policies and lifecycle configurations for cost optimization. 
An SSL certificate, obtained through AWS Certificate Manager by configuring the CName records in DNS settings, and is utilized to encrypt traffic, 
ensuring secure communication between users and the website. A CloudFront Distribution is created for the static website  to enhance performance, 
with the SSL certificate attached to it and Setup HTTP to HTTPS redirection and alias configuration for the specific domain name. 
DNS settings are configured to point to our specific domain name into the DNS management provider. This helps in serving traffic globally, 
implement security practices, and cost optimization techniques, ensuring a secure, scalable, and globally available static website deployment.
