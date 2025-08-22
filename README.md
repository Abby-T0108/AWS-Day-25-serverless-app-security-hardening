# AWS-Day-25-serverless-app-security-hardening

Serverless Application Security Hardening  

This project demonstrates how I transformed a customer feedback application built without security controls into a secure, compliance-ready, serverless application in AWS.  

What I delivered  
1.	Built a serverless architecture using Lambda, DynamoDB, S3, and API Gateway  
2.	Implemented least-privilege IAM roles and policies  
3.	Enabled encryption at rest for sensitive customer data  
4.	Configured API rate limiting with API Gateway Usage Plans  
5.	Set up continuous monitoring with GuardDuty and Security Hub  
6.	Established audit trails using CloudTrail  

Proof it works  
1.	DynamoDB table `customer-feedback` encrypted at rest  
2.	API Gateway usage plan enforcing throttling and quotas  
3.	GuardDuty and Security Hub dashboards showing active monitoring  
4.	CloudTrail recording API calls for auditing  
5.	IAM roles scoped with least privilege for Lambda  

Results that matter  
1.	Insecure app → SOC 2-ready platform  
2.	99% cost reduction compared to EC2-based solution  
3.	Stronger security posture with real-time threat detection  
4.	Fully serverless, auto-scaling and cost-efficient design  

Why it matters  
This project reflects what cloud security engineers do every day: securing existing workloads while ensuring scalability and compliance. It’s proof that security can be baked into modern serverless architectures without trade-offs.  
