# CloudWatch Dashboard Metrics Analysis

## 1. EC2 CPUUtilization

CPUUtilization measures the percentage of CPU resources being used by the EC2 instance. In a production environment, consistently high CPU usage may indicate increased application demand, inefficient code, or insufficient compute resources. Monitoring this metric helps identify performance bottlenecks and determine when scaling actions are required.

## 2. EC2 NetworkIn

NetworkIn tracks the volume of incoming network traffic to the EC2 instance. A sudden increase may indicate higher user activity, increased API requests, or potential malicious traffic. Monitoring this metric helps assess application usage patterns and detect unusual network behavior that could impact performance or security.

## 3. Lambda Invocations

Lambda Invocations represent the number of times the ProcessPaymentNotification function is executed. This metric provides visibility into application activity and workload trends. A healthy application should show invocation patterns that align with expected user transactions and business operations.

## 4. Lambda Errors

The Errors metric records the number of failed Lambda executions. An increase in errors may indicate issues such as invalid input data, application bugs, dependency failures, or configuration problems. Monitoring this metric is critical for maintaining application reliability and ensuring successful transaction processing.

## 5. Overall Application Health Monitoring

By analyzing these metrics together, operations teams can gain a comprehensive view of system health. CPUUtilization and NetworkIn provide insight into infrastructure performance, while Lambda Invocations and Errors reveal application behavior and reliability. Correlating these metrics enables faster troubleshooting, proactive capacity planning, and improved user experience in a production environment.
