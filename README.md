# Cloud-Resume-Challenge---Azure

  In the ever-changing world of IT, you need to keep swimming to keep current (Pun intended). Here we will document my progress as I launch into the world of the Cloud. As a Tier 2 IT Support Professional for a Cloud-Oriented MSP, I work adjacent to the cloud regularly, but not as directly as I would like; this challenge will enable me to get first-hand experience planning, building, configuring and securing Cloud-based resources. 

My duties currently take me into Microsoft's cloud-based Identity and Access Management tools regularly via EntraID (formerly AzureAD). These duties also require me to understand the different server environments to administer changes regardless of whether the client has a Cloud-only, Hybrid-Cloud, or Fully On-Premise environment. For me to improve my skills and achieve my goals though, it is important to take the time outside of work to understand and explore what I believe is the next generation of computing, which brings to here:

# OverView - What is the Cloud Resume Challenge?
  The Cloud Resume Challenge is a project designed to challenge and expose IT professionals to the basics and core services of Cloud computing. This opportunity will give additional experience and context to why cloud-based infrastructure has been a disruptive force in today's industry. This general project outline guides professionals to interact with the 3 main elements of Azure-based infrastructure: Compute, Networking, and Storage at an entry level. Each of these sections can certainly be expanded on and made more complex, however, it serves as a good, near-free option (Using a free Azure subscription) for beginners in this technology to get their feet wet. 

At the free tier, three of the services we will be using will be free of charge, assuming the website doesn't get DDOSed or somehow starts receiving thousands of requests (At which point, I would be honoured if so many people visited). 

![Azure Free Account Resources](https://github.com/MellowFelllow/Cloud-Resume-Challenge---Azure/assets/26839153/d4d4aea0-7f93-4dd0-af14-80a742db2806)

  During this project, we will use Azure Blog Storage to host our static website, CosmosDB to store our website visit counter database, and lastly, Azure functions, which will be called on with an API to utilize the Azure Functions with an HTTP trigger. Using the HTTP trigger Function, and configuring the serverless capacity mode is going to ensure that after the 12-month free tier bonuses expire, this project will remain affordable and practical for ongoing use. This is another aspect of the Cloud Resume Challenge that seems to be very underappreciated, it also offers suggestions to minimize costs which is a notable skill set expected of Cloud Professionals.

The roadmap for this project will ultimately include working with key Azure services such as:

- Hosting the resume on Azure Static Website via Azure Storage - Storage
- Securing my resume using Azure CDN for HTTPS - Security
- Making the website publicly accessible with a domain from Azure DNS - Networking (Arguably, as we will have to point the DNS to our CDN)
- Creating a database to track website visits using CosmosDB - Storage
- Updating the website tracker count with Azure Functions - Automation
- Utilizing ARM to run these tasks as IaC - Scripting

### In more detail

  The first step that involves Cloud services will be hosting the website on Azure Storage as a static website. There is also the option to use an Azure Web app, however, this will include features beyond the need or scope of this project.

# Where are we now?
May 24, 2024

Today I wrapped up the resume portion of the project. I used HTML5 boilerplate, added a little sprinkle of styling with CSS, and spent more time than I would like to admit fussing with the CSS to line up the text. The CSS jokes I see online make much more sense to me now!

The next step will be to host it in an Azure Storage blob as a Static Website.

May 25, 2024

Today I created an Azure subscription and began making resources! I created a storage account which was very straightforward. From there, I enabled the Static website option which created a $web container. from there, uploading the index.html, my CSS and images was very easy and the site is now officially hosted online at: https://jamescooperresume.z13.web.core.windows.net/

While this is all very nice, it could load faster and be more secure, the next step will be enabling a Content Delivery Network. It will also be nice to have a custom domain that better suits my needs, which will also follow. 

---------------------------------------------------------------------------------
