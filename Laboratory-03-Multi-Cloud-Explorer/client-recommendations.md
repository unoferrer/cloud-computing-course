# Cloud Platform Recommendation Challenge

## Client A – Startup Company

### Recommended Platform: Amazon Web Services (AWS)

AWS is a suitable choice for the startup because it provides a broad range of cloud services that can support a mobile application as it grows. The startup can begin with a small amount of infrastructure and increase its resources as the number of users increases. AWS also provides services that can help the company develop, deploy, store data, and monitor its application. This flexibility can help the startup avoid investing heavily in physical infrastructure at the beginning.

### Recommended Services

* **Amazon EC2** – Provides virtual servers for running application workloads.
* **Amazon S3** – Provides scalable object storage for application files and data.
* **Amazon RDS** – Provides managed relational database services.
* **Amazon CloudWatch** – Provides monitoring and observability for AWS resources and applications.

---

## Client B – University

### Recommended Platform: Microsoft Azure

Microsoft Azure is the most appropriate choice for the university because it already uses Windows Server, Microsoft 365, and Active Directory. Azure integrates closely with Microsoft's identity and productivity ecosystem, including Microsoft Entra ID and Microsoft 365. The university can use Azure to extend its existing infrastructure into the cloud while maintaining connections with its current Microsoft environment. This can make migration and identity management more convenient for the university.

### Recommended Services

* **Azure Virtual Machines** – Provides cloud-based Windows and Linux virtual machines.
* **Microsoft Entra ID** – Provides cloud identity and access management.
* **Azure Virtual Network** – Provides private networking for Azure resources and connections to existing infrastructure.
* **Azure Blob Storage** – Provides scalable object storage for files, backups, and other data.

---

## Client C – AI Research Company

### Recommended Platform: Google Cloud Platform (GCP)

Google Cloud is a strong choice for an AI research company because it provides infrastructure and services specifically suited for artificial intelligence and machine learning workloads. Google Cloud supports GPUs and TPUs for demanding AI workloads, while Google Kubernetes Engine provides a managed Kubernetes platform for scalable AI/ML applications. The company can use these capabilities for model training, experimentation, and inference. GCP also provides services for managing data and deploying machine learning applications.

### Recommended Services

* **Compute Engine** – Provides scalable virtual machines for computing workloads.
* **Vertex AI** – Provides tools and services for developing, training, and deploying machine learning models.
* **Google Kubernetes Engine (GKE)** – Provides managed Kubernetes for containerized AI/ML workloads.
* **Cloud Storage** – Provides scalable storage for datasets, models, and other research files.

---

## Client D – Global E-Commerce Company

### Recommended Platform: Amazon Web Services (AWS)

AWS is a strong choice for a global e-commerce company because it provides extensive global infrastructure and services designed for scalable and highly available applications. The company can distribute its workloads across multiple AWS Regions and Availability Zones to improve availability and resilience. AWS also provides services for computing, databases, storage, networking, and monitoring that can support an international online shopping platform. These capabilities allow infrastructure to scale as customer traffic changes.

### Recommended Services

* **Amazon EC2** – Provides scalable compute resources for application servers.
* **Amazon RDS** – Provides managed relational databases for transactional workloads.
* **Amazon S3** – Provides durable object storage for images, files, backups, and other data.
* **Elastic Load Balancing** – Distributes incoming application traffic across available resources.
* **Amazon CloudFront** – Provides content delivery to users around the world.

---

# Multi-Cloud Decision Matrix

| Business Requirement        | Recommended Platform  | Justification                                                                                                                                       |
| --------------------------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Startup Company**         | AWS                   | AWS provides a broad range of services and scalable infrastructure suitable for startups that may experience rapid growth.                          |
| **Enterprise Organization** | AWS                   | AWS provides a broad selection of enterprise services covering computing, storage, databases, networking, security, analytics, and other workloads. |
| **Microsoft Environment**   | Microsoft Azure       | Azure integrates closely with Windows Server, Microsoft 365, Microsoft Entra ID, and other Microsoft technologies.                                  |
| **AI / Machine Learning**   | Google Cloud Platform | Google Cloud provides AI/ML infrastructure, specialized accelerators, Vertex AI, and other services designed for machine learning workloads.        |
| **Kubernetes Deployment**   | Google Cloud Platform | Google Kubernetes Engine provides a managed Kubernetes platform with strong scalability and support for containerized workloads.                    |
| **Global Web Application**  | AWS                   | AWS provides extensive global infrastructure and scalable services suitable for applications serving users across different regions.                |

## Overall Recommendation

There is no single cloud provider that is automatically the best for every organization. AWS is a strong general-purpose choice because of its broad service portfolio and global infrastructure, Azure is particularly appropriate for organizations built around Microsoft technologies, and Google Cloud is especially attractive for AI, machine learning, data analytics, and Kubernetes workloads. The final decision should be based on the client's technical requirements, existing infrastructure, budget, security requirements, scalability needs, and business objectives.

## Sources

* Amazon Web Services. AWS Decision Guides.
* Amazon Web Services. AWS Cloud Comparisons.
* Microsoft Learn. Azure integration with Microsoft 365.
* Microsoft Learn. Microsoft Entra ID.
* Google Cloud. AI and Machine Learning.
* Google Cloud Documentation. AI/ML workloads on Google Kubernetes Engine.
