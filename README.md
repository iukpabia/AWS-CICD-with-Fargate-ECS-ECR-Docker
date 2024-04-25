# AWS-CICD-with-Fargate-ECS-ECR-Docker



<h2>Description</h2>
Amazon Elastic Container Service (Amazon ECS) is a fully managed container orchestration service provided by Amazon Web Services (AWS). 
It allows you to easily run, stop, and manage Docker containers on a cluster. Amazon ECS eliminates the need for you to install, operate, 
and scale your own cluster management infrastructure. In this project, I deployed an application on AWS using Fargate mode, Docker image,
Amazon Elastic container registry (ECR), Code Pipeline & Load balancers.

<br />


<h2>Tools</h2>

- <b>Git</b> 
- <b>Codecommit</b>
- <b>Code deploy</b>    
- <b>Elastic Container Service (ECS)</b>
- <b>Elastic Container registry (ECS)</b>
- <b>AWS Code Pipeline</b>
  
<p align="center">

create a new repo in Codecommit <br/>

<img width="450" alt="Picture1" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/6a6b965e-3421-4051-8cb8-8479f3c5354f">


<br />
<br />

Clone repo and push code to Code Commit <br/>

<img width="450" alt="Picture2" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/0006d7dd-9a98-447f-a6a9-a562f05a7d4e">
<br />
<br />

Code Successfully push to Code Commit repo <br/>

<img width="409" alt="Picture3" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/a70f6b47-be7a-47e9-a095-04ca4fb1ac48">


<br />
<br />

Create a new project <br/>

<img width="450" alt="Picture4" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/e1dd4d3e-98f8-4b10-a497-730e9eb6294e">
<br />
<br />

Create a project on code build (enable the privileged flag for building docker images and modifying the build 
role to access ECR)
 <br/>

<img width="450" alt="Picture5" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/cbaf049a-59ce-4f37-911b-ecd6ad41fb1b">


<br />
<br />

Project creation successful <br/>

<img width="450" alt="Picture5" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/9867deeb-d8d5-4834-b297-8c0ce353a5f3">


<br />
<br />

Create a Cluster on ECS <br/>

<img width="450" alt="Picture6" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/9827504f-0b00-4ed2-b01f-56d9ddfbea10">

<br />
<br />

Cluster Created <br/>

<img width="450" alt="Picture7" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/0356d9d6-4a06-43f5-8332-a5681fca22fc">

<br />
<br />

Create a task definition <br/>

<img width="450" alt="Picture8" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/de5a5c9d-e7ec-4139-9a3c-6a0f64c6eb7f">


<br />
<br />


Create a Service <br/>

<img width="450" alt="Picture9" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/f41461d6-fda2-4391-ad4d-a1049fcaa8e0">

<br />
<br />

 Service Created <br/>

<img width="450" alt="Picture10" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/32615281-a4cf-40c3-ad92-ec992ce87459">



<br />
<br />

Tasks Created <br/>

<img width="450" alt="Picture11" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/891e2a57-08aa-402d-9e53-b3a90139f1b5">


<br />
<br />

Create a Code Pipeline to automate the entire process <br/>

<img width="468" alt="Picture12" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/ed21f0e8-a765-4891-a049-823b8b7f64fa">


<br />
<br />

Code build successful <br/>

<img width="472" alt="Picture13" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/dd5a688c-d7e9-4587-96d6-ad8d7ea19876">



<br />
<br />

Code deploy successful <br/>

<img width="459" alt="Picture14" src="https://github.com/iukpabia/AWS-CI-CD-Website-Deployment/assets/127888235/49b2bc6c-80fe-4b73-b3fe-83c8f731ab85">



<!--
