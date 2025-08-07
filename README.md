<h1>IaC AWS CDK Project</h1>

<h2>Description</h2>
This Project creates a serverless web application deployment using AWS CDK (Cloud Development Kit). It sets up an S3 Bucket for storage, a Lambda Function that returns a 'Hello World' HTML page and an API Gateway that exposes the Lambda function as a web endpoint.
<br />


<h2>Resources and Utilities Used</h2>

- <b>GenAI</b>
- <b>AWS CDK - IaC</b>
- <b>AWS CloudShell</b>
- <b>CloudFormation</b>
- <b>AWS Lambda - Lambda Function</b>
- <b>API Gateway</b>

<h2>Environments Used </h2>

- <b>AWS CloudShell</b>

<h2>Project Walk-Through:</h2>

<p align="center">
Poject Diagram: <br/>
<img src="https://i.imgur.com/gXPYKab.png"/>
<br />
<br />
Creating a directory:  <br/>
<img src="https://i.imgur.com/PvnuJUL.png"/>
<br />
<br />
Initializing a new CDK Project with Python: <br/>
<img src="https://i.imgur.com/m4ZU5Th.png"/>
<br />
<br />
Activating a virtual environmeent:  <br/>
<img src="https://i.imgur.com/n2vKHTO.png"/>
<br />
<br />
Adding Dependencies:  <br/>
<img src="https://i.imgur.com/dpLR15d.png"/>
<br />
<br />
Creating a Lambda function directory and adding code:  <br/>
<img src="https://i.imgur.com/7oMtQaG.png"/>
<img src="https://i.imgur.com/lv4Pc3P.png"/>
<br />
<br />
S3 Bucket Creation and Lambda Function Setup:  <br/>
<img src="https://i.imgur.com/rSs1NfL.png"/>
<br />
<br />
API Gateway Configuration and Stack Output:  <br/>
<img src="https://i.imgur.com/DWH4dpR.png"/>
<br />
<br />
Stack Deployed and API URL:  <br/>
<img src="https://i.imgur.com/Zr7vYAP.png"/>
<br />
<br />
CloudFormation - Project1Stack and Resources:  <br/>
<img src="https://i.imgur.com/4NzwJAH.png"/>
<img src="https://i.imgur.com/NTmGfvc.png"/>
<br />
<br />
API URL Successfully triggers the Lambda Functions🎉:  <br/>
<img src="https://i.imgur.com/37HOrcd.png"/>
<br />
<br />
Done - Clean Up to remove all the resources:  <br/>
<img src="https://i.imgur.com/fwfOwmn.png"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
