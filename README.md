# AWS Application Migration Service

### Install AWS Replication Agent:
The process begins by installing the AWS Replication Agent on your source servers. This agent handles the continuous replication of data to AWS.

### Replication:
The replication process occurs in real-time, capturing all changes to the source servers' disk volumes. The replicated data is stored in a staging area in your AWS account.

### Launch Test Instances:
AWS MGN allows you to launch test instances using the replicated data. These test instances can be used to verify application functionality and performance in the cloud.

### Cutover:
When ready, you can initiate a cutover by launching the fully replicated and tested instances in AWS. The service ensures minimal downtime during the cutover process.
