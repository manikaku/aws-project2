**Key AWS Services Used**

**1) Amazon CloudFront:**

Role:
 Utilized CloudFront as a Content Delivery Network (CDN) to cache data closer to the end-users.

Benefit: 
This significantly reduced latency, ensuring that users have instant access to data by serving content from edge locations nearest to them.

**2) Amazon EC2:**

Role: 
Deployed web servers on Amazon EC2 instances to handle incoming traffic efficiently.

Benefit:
 Provided scalable computing resources that could be adjusted based on traffic demands, ensuring high availability and performance.

**3) Elastic Load Balancing (ELB):**

Role:
 Implemented ELB to distribute incoming traffic across multiple EC2 instances.

Benefit: 
Enhanced fault tolerance and ensured that no single server was overwhelmed, improving the overall reliability of the web service.

**4) Amazon VPC (Virtual Private Cloud):**

Role: 
Configured a secure VPC to host our EC2 instances and other resources.

Benefit: 
Provided network isolation and control over our resources, enhancing security and management.
