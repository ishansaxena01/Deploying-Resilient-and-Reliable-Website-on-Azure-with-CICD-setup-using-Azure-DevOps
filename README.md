# Deploying-Resilient-and-Reliable-Website-on-Azure-with-CICD-setup-using-Azure-DevOps

To deploy the changes of the code or website manually is troublesome as one have to again and again save the changes and then push the code to the platform and then configure changes accordingly, with help of CICD which is continuous integration and deployment one can save the changes and the changes would be automatically deployed over the production or website with the manual intervention hence saving time and manual efforts of doing so. With Azure DevOps we can push our code to azure repos once and then have to manually trigger the build and release pipeline of the code and then once deployed we can enable CICD triggers which will automatically run whenever there is a change marked or observed. To check the status and state of the website, metric and monitoring can be enabled to see how it works.

Through this project we can automatically build and deploy the code to the production without any human intervention and thus enabling the efficiency and increases the affectability of work. Whenever any changes in code are performed they will be automatically reflected in website. By by effective metrics and log monitoring we can se how our Webapp is performing, CPU, downtimes, failures, etc. Ensuring no single point of failure we enabled backups according to our backup policy and also replicated the web app to another region to ensure reliability and resiliency of the web app even at times of disaster. To ensure security and denying the public access of web app we configured Private Endpoints which only allows the IP’s in the range of Virtual Network thus enabling security.

Project steps - 
1 Importing and Developing code in Visual Studio 
2 Pushing the code using VSC terminal to Azure Repos
3 Accessing code in azure repos and creating build pipeline
4 Creating Release Pipeline 
5 Configuring CICD triggers for build and release
6 Perform changes in code
7 Enabling logs and metrics
8 Enabling Disaster Recovery and Business Continuity
9 Enhancing Security by Enabling Private Endpoints

Use Cases - 
To ensure that the website is always up-to-date and provides a seamless user experience, the hospital has chosen to use Azure Web App as their hosting platform. They have also implemented a CI/CD pipeline using Azure DevOps to automate the deployment process and ensure that any updates to the website are deployed quickly and consistently. 
To monitor the performance and usage of the website, the hospital has integrated Application Insights into their Azure Web App. This provides them with real-time telemetry data, such as page load times, error rates, and user behavior, which they can use to optimize the website and improve the user experience
To ensure the website is secure and protected against threats, the hospital website is enabled with private endpoints through which only those in the CIDR block range of Vnet can access.
To protect against data loss in the event of a disaster, the hospital has implemented disaster recovery. This involves replicating their website and database to a secondary Azure region, which can be activated in the event of a major outage or disaster in the primary region
![image](https://github.com/ishansaxena01/Deploying-Resilient-and-Reliable-Website-on-Azure-with-CICD-setup-using-Azure-DevOps/assets/123859836/76e19148-d8b4-4cdf-bebb-78442e6b6f21)

![image](https://github.com/ishansaxena01/Deploying-Resilient-and-Reliable-Website-on-Azure-with-CICD-setup-using-Azure-DevOps/assets/123859836/46290f6e-5435-42b9-9a15-efc927aec89b)

![image](https://github.com/ishansaxena01/Deploying-Resilient-and-Reliable-Website-on-Azure-with-CICD-setup-using-Azure-DevOps/assets/123859836/cd23bb40-67ae-425a-845c-ee5c73518333)

![image](https://github.com/ishansaxena01/Deploying-Resilient-and-Reliable-Website-on-Azure-with-CICD-setup-using-Azure-DevOps/assets/123859836/26e2f6ba-d5dc-447b-9bb0-1953d59f0dfb)
