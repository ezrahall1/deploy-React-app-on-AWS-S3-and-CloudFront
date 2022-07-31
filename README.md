<h1>How to Deploy React App on AWS S3 and CloudFront</h1>

<h2>Description</h2>
In this project I will demonstrate I how deploy a react app to AWS using S3, CloudFront, ACM and Route53.
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
<H3>Step 1 - Creating EC2 instance</H3>

Once I logged into my AWS account, I clicked on services and navigated to EC2. From there I entered the name of the EC2 instance and select Amazon Linux.
In the network settings section I left "allow SSH traffic from" ticked as well as leaving the rest of the settings as defualt and clicking launch instance.

<img src="https://i.imgur.com/fdVAGzB.png" height="80%" width="80%" alt="Image 1"/>


<H3>Step 2 – Connecting to EC2 instance </H3>
Once the EC2 instance was in a running state I connected to it, by right clicking and selecting connect.

<img src="https://i.imgur.com/kaoMGqH.png" height="80%" width="80%" alt="Image 2"/>

<img src="https://i.imgur.com/WQEebAw.png" height="80%" width="80%" alt="Image 3"/>



There are many applications you can use to connect to your EC2 instance, for this project I used [Putty](https://www.putty.org).
This screenshot shows that I successfully connected to my EC2 instance using Putty:
<img src="https://i.imgur.com/wsd36ox.png" height="80%" width="80%" alt="Image 4"/>

<H3>Step 3 – Creating bash script and variables</H3>
The final step is creating the the bash script name for example testscript.sh and creating the variables in a text editor using this command <b>nano testscript.sh</b>.

<img src="https://i.imgur.com/nb0aNT5.png" height="80%" width="80%" alt="Image 5"/>

Once I had entered my script I would need to save it and make sure the bash script is executable by running this command <b>chmod +x testscript.sh</b>. 
Now I am able to run the bash script using the command <b>./testscript.sh</b>

<img src="https://i.imgur.com/WtDE4tp.png" height="80%" width="80%" alt="Image 6"/>


