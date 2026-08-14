# Client Recommendations

## Client A – Startup Company

**Recommended Cloud Platform: Amazon Web Services (AWS)**

For Client A, I would choose **AWS** because the company is a startup with a limited budget. At the same time, its mobile application is expected to gain more users in the future. Because of this, the company needs a cloud platform that can grow along with the application.

AWS can allow the startup to begin with a small amount of resources and increase them when needed. This can help the company manage its costs while still preparing for future growth.

I would use **Amazon EC2** to run the application, **Amazon S3** to store images and files, and **Amazon RDS** to handle the database.

**Recommended Services:**

* Amazon EC2
* Amazon S3
* Amazon RDS

---

## Client B – University

**Recommended Cloud Platform: Microsoft Azure**

For the university, I would recommend **Microsoft Azure** because it is already using Microsoft technologies such as Windows Server, Microsoft 365, and Active Directory.

Since the university is familiar with Microsoft's products, Azure would be a practical option when moving some of its existing systems to the cloud. The university could use **Azure Virtual Machines** for server workloads, **Microsoft Entra ID** for managing user accounts and access, and **Azure SQL Database** for applications that need a relational database.

I believe Azure would make the transition easier because the university can continue using many of the Microsoft technologies it already knows.

**Recommended Services:**

* Azure Virtual Machines
* Microsoft Entra ID
* Azure SQL Database

---

## Client C – AI Research Company

**Recommended Cloud Platform: Google Cloud**

For the AI research company, I would choose **Google Cloud** because the company's main goal is to develop artificial intelligence and machine learning applications.

Google Cloud provides services that can support AI development, machine learning, data processing, and computing. I would recommend **Vertex AI** for AI and machine learning projects, **Compute Engine** for computing resources, and **Cloud Storage** for storing datasets and research files.

If the company needs to work with containers, **Google Kubernetes Engine (GKE)** could also be used to deploy and manage containerized applications.

**Recommended Services:**

* Vertex AI
* Compute Engine
* Cloud Storage
* Google Kubernetes Engine (GKE)

---

## Client D – Global E-Commerce Company

**Recommended Cloud Platform: Amazon Web Services (AWS)**

For the global e-commerce company, I would recommend **AWS** because the business needs to support many customers and handle changes in website traffic.

E-commerce websites can experience a large increase in users during holidays, promotions, and special sales. Because of this, the company needs an infrastructure that can handle high traffic and adjust when demand changes.

I would use **Amazon EC2** for the application servers, **Elastic Load Balancing** to distribute traffic, and **Amazon RDS** for the database. **Amazon S3** could be used to store product images and other files, while **EC2 Auto Scaling** could help adjust computing resources when the workload increases or decreases.

**Recommended Services:**

* Amazon EC2
* Elastic Load Balancing
* Amazon RDS
* Amazon S3
* EC2 Auto Scaling

---

# My Overall Decision

| Client                       | Recommended Platform | Main Reason                                                                        |
| ---------------------------- | -------------------- | ---------------------------------------------------------------------------------- |
| Client A – Startup           | AWS                  | It can support the application's growth while allowing the company to start small. |
| Client B – University        | Microsoft Azure      | It fits well with the university's existing Microsoft technologies.                |
| Client C – AI Research       | Google Cloud         | It provides useful services for AI and machine learning projects.                  |
| Client D – Global E-Commerce | AWS                  | It can support applications that need scalability and high availability.           |

# My Understanding

After looking at the four different situations, I learned that there is no cloud provider that is automatically the best for every organization. The best choice depends on what the client needs, what technology they already use, their budget, and what they want to achieve.

For me, a Cloud Solutions Consultant should first understand the client's situation before recommending a platform. It is important to look at the requirements and choose services that can actually solve the client's problems.

I also learned that AWS, Azure, and Google Cloud each have their own strengths. AWS can be a good option for scalable applications, Azure can be useful for organizations that already use Microsoft products, and Google Cloud can be a strong choice for AI and machine learning projects.

---

# Multi-Cloud Decision Matrix

| Business Requirement    | Recommended Platform | Justification                                                                                                                                |
| ----------------------- | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Startup Company         | AWS                  | I would choose AWS because the company can start with basic resources and increase them as the number of users grows.                        |
| Enterprise Organization | AWS                  | I think AWS is suitable for large organizations because it offers many services for computing, storage, databases, networking, and security. |
| Microsoft Environment   | Microsoft Azure      | I would recommend Azure because it works well with Microsoft technologies such as Windows Server, Microsoft 365, and Microsoft Entra ID.     |
| AI / Machine Learning   | Google Cloud         | I would choose Google Cloud because it offers services that can support AI, machine learning, and data processing.                           |
| Kubernetes Deployment   | Google Cloud         | I would recommend Google Cloud because Google Kubernetes Engine provides a managed environment for running containerized applications.       |
| Global Web Application  | AWS                  | I would choose AWS because its scalable services and global infrastructure can support web applications with users from different locations. |

# Final Reflection

This activity helped me understand that choosing a cloud platform is not just about picking the most popular provider. The decision should be based on the client's actual needs and existing technology.

As an IT student, I learned that important factors such as **cost, scalability, performance, security, existing systems, and business requirements** should be considered before choosing a cloud solution.

Overall, this exercise helped me understand the role of a Cloud Solutions Consultant. The consultant needs to study the client's situation, compare different cloud options, and recommend a solution that is suitable for the organization's goals.
