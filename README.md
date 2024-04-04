# SESCloudEngineering
SES Cloud Engineering homework

Deployed website URL: https://ses-ce.storage.googleapis.com/index.html

Architecture Diagram: 

![image](https://github.com/nictkw/SESCloudEngineering/assets/57402933/c4834e7a-719f-4c2f-8a51-52d376fe5d13)


1. Operational Excellence
   - Google Cloud monitoring and logging is added to track the application health, performance metrics, and logs
   - Postbase database should be configured to have automated backups and disaster recovery procedures using Google Cloud SQL

3. Security
   - Utilizing the Google Cloud IAM to control access to the Google Cloud Platform resources
   - Implemented Google Cloud Armor to protect against DDOS attacks and any web vulnerabilities
  
4. Reliability
   - Make use of Google Kubernetes Engine to set up high availability for the frontend and backend services
   - Health checks were also implemented using Google Cloud monitoring to ensure that the service remains available even when there are failures
     
6. Performance Efficiency
   - Able to optimize database performance by adjusting some configurations in the PostgreSQL and indexing strategies
   - Utilizing caching mechanisms such as Google Cloud memory store to access data from there to reduce any database load
   - Make use of Google Cloud monitoring to optimize resources based on the metrics
  
8. Cost Optimization
   - Analyze the resource usage and optimization cost using Google Cloud's cost management tools
     
10. Sustainability
    - resources are optimized to reduce energy consumption and waste
    - The architecture above uses serverless offerings eg. Cloud Functions to scale the resources based on the demand, reducing idle capacity and energy usage.

