# This project include 3 parts.
1. A crawler running on EC2 and write result to DynamoDB.
2. A lambda function launch several EC2 instances to run the crawlers.
3. A lambda check the crawler result in DynamoDB if it is OK then terminate the EC2.

Base on these 3 parts, you can run crawler on AWS with little human labor.
