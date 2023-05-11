| Layer | AWS Services | Features | Applied Security |
| --- | --- | --- | --- |
| Frontend | Amazon CloudFront | Global CDN, caching, fast content delivery | HTTPS/TLS encryption, WAF integration, signed URLs |
| API Layer | Amazon API Gateway | API creation, publishing, maintenance | Authentication (Cognito, IAM), caching, rate limiting, WAF integration |
|     | AWS Lambda | Serverless compute, event-driven processing | IAM roles, VPC isolation, encryption of environment variables |
| Compute Layer | Amazon EC2 | Virtual servers, flexible compute | Security groups, network ACLs, IAM roles, patch management, antivirus/antimalware |
|     | Amazon EKS | Managed Kubernetes, container orchestration | Kubernetes RBAC, network policies, pod security policies, container image scanning |
| Data Layer | Amazon RDS | Managed relational databases | Encryption at rest (KMS), in transit (TLS), IAM authentication, database firewall |
|     | Amazon DynamoDB | Managed NoSQL databases | Encryption at rest (KMS), fine-grained access (IAM), VPC endpoints, attribute-based access control |
|     | Amazon S3 | Object storage, scalable, durable | Server-side encryption (SSE-S3, SSE-KMS), bucket policies, ACLs, S3 object lock, VPC endpoints |
| Networking & Content Delivery | Amazon VPC | Isolated virtual networks | VPC security groups, network ACLs, VPC flow logs, private subnets, bastion hosts |
|     | AWS Direct Connect | Dedicated network connections | Secure, low-latency data transfer, dedicated connections, VPN as a backup |
|     | AWS Certificate Manager | SSL/TLS certificate management | Automatic certificate renewal, integration with CloudFront, API Gateway, and load balancers |
| Security & Compliance | AWS WAF | Web application firewall | Custom rules, OWASP Top 10 protection, rate-based rules, IP blocking |
|     | AWS Shield | Managed DDoS protection | Automatic protection (Standard), advanced protection (Advanced) |
|     | Amazon GuardDuty | Continuous security monitoring, threat detection | Threat analysis, anomaly detection, machine learning-based insights |
|     | AWS Secrets Manager | Secrets management | Secure storage, rotation, and access of secrets, IAM policies, KMS encryption |
|     | AWS Systems Manager(SSM) | Automation, compliance enforcement, patch management | Compliance automation, patching, inventory, Parameter Store, Session Manager |
| Monitoring & Logging | Amazon CloudWatch | Monitoring, metrics, alarms, logs | Resource and application monitoring, anomaly detection, CloudWatch Logs Insights |
|     | AWS CloudTrail | AWS API call recording, log file delivery | Audit, compliance, anomaly detection, data event logging, encryption with KMS |
