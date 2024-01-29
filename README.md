<h1>How to Deploy React App on AWS S3 and CloudFront</h1>

<h2>Description</h2>
In this project, I will showcase the deployment process of a React app on AWS, utilizing key services such as S3 for object storage, CloudFront for content delivery, ACM (AWS Certificate Manager) for managing SSL/TLS certificates, and Route 53 for domain registration and routing. The demonstration will encompass the step-by-step deployment workflow, ensuring the seamless integration of these AWS services to host the React app. This practical guide provides insights into best practices for deploying web applications on AWS, offering a comprehensive overview of the configuration and coordination of these services to achieve a robust and scalable deployment.
<br />


<h2>Services Used</h2>

- <b>S3</b> 
- <b>CloudFront</b> 
- <b>ACM</b> 
- <b>Route53</b> 

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>YouTube Demonstration </h2>

[How to Deploy React App on AWS S3 and CloudFront - video walk-through guide](https://youtu.be/hI2sZZBVLs0)

<h2>Program walk-through:</h2> 
<H3>Step 1 – Create S3 bucket</H3>
Once I had created my react app using PowerShell, I created two S3 buckets and uploads files.

<img src="https://i.imgur.com/BiBC58y.png" height="80%" width="80%" alt="Image 1"/>

<H3>Step 2 – Route 53</H3>
In this step I created two A records.

<img src="https://i.imgur.com/Cu4q4Aw.png" height="80%" width="80%" alt="Image 2.1"/>

<img src="https://i.imgur.com/6MIRiNX.png" height="80%" width="80%" alt="Image 2.2"/>

<H3>Step 3 – Certificate Manager</H3>
In this step I provision the required certificates.


<img src="https://i.imgur.com/pNUTl71.png" height="80%" width="80%" alt="Image 3.1"/>

<img src="https://i.imgur.com/NdoMnZL.png" height="80%" width="80%" alt="Image 3.2"/>


<H3>Step 4 – Cloudfront</H3>
In this final step I setup regional distribution and enabled HTTPS.

<img src="https://i.imgur.com/StjHhoG.png" height="80%" width="80%" alt="Image 4.1"/>

<img src="https://i.imgur.com/V9mnn1M.png" height="80%" width="80%" alt="Image 4.2"/>
