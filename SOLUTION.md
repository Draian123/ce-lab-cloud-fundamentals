# Student Solution

Name:

GitHub Username:

---

# Part 1

### What is cloud computing?

Cloud computing is the on-demand delivery of IT resources (such as servers, storage, databases, networking, and software) over the internet with pay-as-you-go pricing.

Key characteristics
On-demand – Provision resources whenever needed.
Scalable – Increase or decrease capacity quickly.
Pay-as-you-go – Pay only for what you use.
Managed – The cloud provider maintains the infrastructure.
Example

Instead of buying a physical server, you launch an Amazon EC2 instance in minutes and pay only while it's running.
...

### Three advantages

1.
Cost savings – No upfront hardware costs; pay only for what you use.
2.
Scalability – Easily scale resources up or down based on demand.
3.
Flexibility – Access services from anywhere and deploy applications quickly.

### Two challenges

1. **Security & Privacy** – Protecting sensitive data and ensuring compliance.

2. **Downtime & Internet Dependency** – Access to cloud services depends on a stable internet connection and provider availability.

---

# Part 2

|----------|---------------|------|
| Hosting your own web server | **IaaS** | You manage the server, OS, and application while the cloud provider manages the infrastructure. |
| Gmail | **SaaS** | A fully managed application accessed through a web browser. |
| Web application development | **PaaS** | The provider manages the infrastructure and runtime, allowing you to focus on developing the application. |
| Virtual machine | **IaaS** | You provision and manage the virtual machine, including the operating system. |
| Microsoft 365 | **SaaS** | A fully managed software suite delivered over the internet. |

---

# Part 3

| Responsibility | AWS | Customer |
|---------------|------|----------|
| Physical servers | X | |
| Operating system | | X |
| IAM | | X |
| Data | | X |
| Security Groups | | X |
| Application Code | | X |

---

# Part 4
Which deployment model would you recommend?

Explain your answer.
Scenario 1

A startup wants the lowest cost and needs to launch quickly.

### Startup

| **Public Cloud** | AWS provides ready-to-use infrastructure without upfront hardware costs, allowing fast deployment and easy scaling. |

...

Scenario 2

A hospital stores highly sensitive patient records.

### Hospital

| **Private Cloud** | A private cloud provides more control over security, compliance, and sensitive data management. |
...

Scenario 3

A bank wants to keep customer data on-premises but run its website in AWS.

### Bank

| **Hybrid Cloud** | Combines on-premises infrastructure with AWS, allowing sensitive data to stay private while using cloud flexibility for applications. |
...

---

# Part 5

Imagine your company currently owns physical servers.

Describe three reasons why moving to AWS could help the business.

...

1. **Cost Savings**  
   - No need to buy and maintain expensive hardware. You pay only for the resources you use.

2. **Scalability**  
   - Easily increase or decrease resources based on business demand without buying new servers.

3. **Reliability and Availability**  
   - AWS provides highly available infrastructure with backup, disaster recovery, and multiple data centers.

---

# Reflection

1. Which cloud service model interests you most?

   **PaaS (Platform as a Service)** interests me most because it allows developers to focus on building applications without managing servers and infrastructure.


2. Which concept was hardest to understand?

   The hardest concept was understanding the difference between **IaaS, PaaS, and SaaS** and how much responsibility belongs to the customer versus the cloud provider.


3. What surprised you most about cloud computing?

   It was surprising how quickly companies can create and scale infrastructure without owning any physical servers.

...

---

# Bonus

Research one AWS service you have never heard of.

Describe:

- What it does
- Which service model it belongs to
- One real-world use case


## AWS Service: Amazon Rekognition

### What it does
Amazon Rekognition is an AWS service that uses artificial intelligence to analyze images and videos. It can detect objects, faces, text, and activities.

### Service Model
**SaaS (Software as a Service)**  
AWS provides the ready-to-use AI service through APIs, so users do not need to build or manage the underlying machine learning infrastructure.

### Real-world Use Case
A security company can use Amazon Rekognition to analyze surveillance videos and detect people or suspicious activities automatically.
...