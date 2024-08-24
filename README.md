**Step-by-Step Guide to Build Serverless File Sharing Platform**

**Project Description:**

The Serverless File Sharing Platform allows users to securely upload and download files via a simple HTTP API. It leverages AWS Lambda for serverless compute, API Gateway for RESTful API management, and Amazon S3 for durable and scalable object storage. Users can interact with the platform using any HTTP client (like Postman), making it versatile for various use cases that involve file sharing and storage.

**Use Cases:**

File Sharing: Users can upload files to the platform using a POST request, specifying the file name and content. This can be useful for sharing documents, images, or any other digital assets securely.
File Distribution: Content creators can distribute files (e.g., software updates, media files) to consumers by generating download links through the platform.
Collaborative Work: Teams can share project resources, documents, and data securely, facilitating collaboration across different locations.

**Project Architecture:**

<img width="500" alt="Architecture Diagram" src="https://github.com/user-attachments/assets/b75528a0-e620-401b-97a3-58df53633fbc">

**Steps to Build the Project:**

**Prerequisites**

AWS Account with appropriate permissions to create Lambda functions, API Gateway, and S3 buckets.

