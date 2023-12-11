# 

### You are building an automated transcription service in which Amazon EC2 worker instances process an uploaded audio file and generate a text file. You must store both of these files in the same durable storage until the text file is retrieved. You do not know what the storage capacity requirements are. Which storage option is both cost-efficient and scalable?

- [ ] Multiple Amazon EBS volume with snapshots.
- [ ] A single Amazon Glacier vault.
- [x] A single Amazon S3 bucket.
- [ ] Multiple instance stores.

**[⬆ Back to Top](#table-of-contents)**

### Your company has recently extended its datacenter into a VPC on AVVS to add burst computing capacity as needed Members of your Network Operations Center need to be able to go to the AWSManagement Console and administer Amazon EC2 instances as necessary You don't want to create new IAM users for each NOC member and make those users sign in again to the AWS Management Console Which option below will meet the needs for your NOC members?

- [ ] Use OAuth 2 0 to retrieve temporary AWS security credentials to enable your NOC members to sign in to the AVVS Management Console.
- [ ] Use web Identity Federation to retrieve AWS temporary security credentials to enable your NOC members to sign in to the AWS Management Console.
- [ ] Use your on-premises SAML 2.0-compliant identity provider (IOP) to grant the NOC members federated access to the AWS Management Console via the AWS sing le sign-on (550) endpoint.
- [x] Use your on-premises SAML2.0-compliam identity provider (IOP) to retrieve temporary security credentials to enable NOC members to sign in to the AWS Management Console.

**[⬆ Back to Top](#table-of-contents)**

### What is the maximum response time for a Business level Premium Support case?

- [ ] 30 minutes.
- [ ] You always get instant responses (within a few seconds).
- [ ] 10 minutes.
- [x] 1 hour.

**[⬆ Back to Top](#table-of-contents)**

### You have just set up your first Elastic Load Balancer (ELB) but it does not seem to be configured properly. You discover that before you start using ELB, you have to configure the listeners for your load balancer. Which protocols does ELB use to support the load balancing of applications?

- [ ] HTTP and HTTPS.
- [ ] HTTP, HTTPS, TCP, SSL and SSH.
- [x] HTTP, HTTPS, TCP, and SSL.
- [ ] HTTP, HTTPS, TCP, SSL and SFTP.

**[⬆ Back to Top](#table-of-contents)**

### A t2.medium EC2 instance type must be launched with what type of Amazon Machine Image (AMI)?

- [x] An Instance store Hardware Virtual Machine AMI.
- [ ] An Instance store Paravirtual AMI.
- [ ] An Amazon EBS-backed Hardware Virtual Machine AMI.
- [ ] An Amazon EBS-backed Paravirtual AMI.

**[⬆ Back to Top](#table-of-contents)**

### A user has created a subnet in VPC and launched an EC2 instance within it. The user has not selected the option to assign the IP address while launching the instance. The user has 3 elastic IPs and is trying to assign one of the Elastic IPs to the VPC instance from the console. The console does not show any instance in the IP assignment screen. What is a possible reason that the instance is unavailable in the assigned IP console?

- [ ] The IP address may be attached to one of the instances.
- [ ] The IP address belongs to a different zone than the subnet zone.
- [ ] The user has not created an internet gateway.
- [x] The IP addresses belong to EC2 Classic; so they cannot be assigned to VPC.

**[⬆ Back to Top](#table-of-contents)**

### Will I be alerted when automatic fail over occurs?

- [ ] Only if SNS configured.
- [x] Yes.
- [ ] No.
- [ ] Only if Cloud watch configured.

**[⬆ Back to Top](#table-of-contents)**

### Amazon EC2 provides a [...]. It is an HTTP or HTTPS request that uses the HTTP verbs GET or POST.

- [ ] web database.
- [ ] .NET framework.
- [x] Query API.
- [ ] C library.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following requires a custom Cloud Watch metric to monitor?

- [ ] Memory Utilization of an EC2 instance.
- [ ] CPU Utilization of an EC2 instance.
- [x] Disk usage activity of an EC2 instance.
- [ ] Data transfer of an EC2 instance.

**[⬆ Back to Top](#table-of-contents)**

### An International company has deployed a multi-tier web application that relies on DynamoDB in a single region For regulatory reasons they need disaster recovery capability in a separate region with a Recovery Time Objective of 2 hours and a Recovery Point Objective of 24 hours They should synchronize their data on a regular basis and be able to provision me web application rapidly using CloudFormation. The objective is to minimize changes to the existing web application, control the throughput of DynamoDB used for the synchronization of data and synchronize only the modified elements. Which design would you choose to meet these requirements?

- [x] Use AWS data Pipeline to schedule a DynamoDB cross region copy once a day. create a Last updated' attribute in your DynamoDB table that would represent the timestamp of the last update and use it as a filter.
- [ ] Use EMR and write a custom script to retrieve data from DynamoDB in the current region using a SCAN operation and push it to Dynamo DB in the second region.
- [ ] Use AWS data Pipeline to schedule an export of the DynamoDB table to S3 in the current region once a day then schedule another task immediately after it that will import data from S3 to DynamoDB in the other region.
- [ ] Send also each Ante into an SQS queue in me second region; use an auto-scaling group behind the SQS queue to replay the write in the second region.

**[⬆ Back to Top](#table-of-contents)**

### An Elastic IP address (EIP) is a static IP address designed for dynamic cloud computing. With an EIP, you can mask the failure of an instance or software by rapidly remapping the address to another instance in your account. Your EIP is associated with your AWS account, not a particular EC2 instance, and it remains associated with your account until you choose to explicitly release it. By default how many EIPs is each AWS account limited to on a per region basis?

- [ ] 1.
- [x] 5.
- [ ] Unlimited.
- [ ] 10.

**[⬆ Back to Top](#table-of-contents)**

### Which Amazon Storage behaves like raw, unformatted, external block devices that you can attach to your instances?

- [ ] None of these.
- [ ] Amazon Instance Storage
- [x] Amazon EBS
- [ ] All of these.

**[⬆ Back to Top](#table-of-contents)**

### You currently operate a web application in the AWS US-East region The application runs on an autoscaled layer of EC2 instances and an RDS Multi-AZ database Your IT security compliance officer has tasked you to develop a reliable and durable logging solution to track changes made to your EC2.1AM And RDS resources. The solution must ensure the integrity and confidentiality of your log data. Which of these solutions would you recommend?

- [x] Create a new CloudTrail trail with one new S3 bucket to store the logs and with the global services option selected Use IAM roles S3 bucket policies and Multi Factor Authentication (MFA) Delete on the S3 bucket that stores your logs.
- [ ] Create a new CloudTrail with one new S3 bucket to store the logs Configure SNS to send log file delivery notifications to your management system Use IAM roles and S3 bucket policies on the S3 bucket mat stores your logs.
- [ ] Create a new CloudTrail trail with an existing S3 bucket to store the logs and with the global services option selected Use S3 ACLs and Multi Factor Authentication (MFA) Delete on the S3 bucket that stores your logs.
- [ ] Create three new CloudTrail trails with three new S3 buckets to store the logs one for the AWS Management console, one for AWS SDKs and one for command line tools Use IAM roles and S3 bucket policies on the S3 buckets that store your logs.

**[⬆ Back to Top](#table-of-contents)**

### Does DynamoDB support in-place atomic updates?

- [x] Yes.
- [ ] No.
- [ ] It does support in-place non-atomic updates.
- [ ] It is not defined.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following is true of Amazon EC2 security group?

- [ ] You can modify the outbound rules for EC2-Classic.
- [ ] You can modify the rules for a security group only if the security group controls the traffic for just one instance.
- [ ] You can modify the rules for a security group only when a new instance is created.
- [x] You can modify the rules for a security group at any time.

**[⬆ Back to Top](#table-of-contents)**

### You need to set up security for your VPC and you know that Amazon VPC provides two features that you can use to increase security for your VPC: security groups and network access control lists (ACLs). You have already looked into security groups and you are now trying to understand ACLs. Which statement below is incorrect in relation to ACLs?

- [ ] Supports allow rules and deny rules.
- [x] Is stateful: Return traffic is automatically allowed, regardless of any rules.
- [ ] Processes rules in number order when deciding whether to allow traffic.
- [ ] Operates at the subnet level (second layer of defense).

**[⬆ Back to Top](#table-of-contents)**

### A user is trying to launch a similar EC2 instance from an existing instance with the option 'Launch More like this'. The AMI of the selected instance is deleted. What will happen in this case?

- [ ] AWS does not need an AMI for the 'Launch more like this' option.
- [ ] AWS will launch the instance but will not create a new AMI.
- [ ] AWS will create a new AMI and launch the instance.
- [x] AWS will throw an error saying that the AMI is deregistered.

**[⬆ Back to Top](#table-of-contents)**

### True or False: When you use the AWS Management Console to delete an IAM user, IAM also deletes any signing certificates and any access keys belonging to the user.

- [ ] False.
- [ ] This is configurable.
- [x] True.

**[⬆ Back to Top](#table-of-contents)**

### You are working with a customer who is using Chef configuration management in their data center. Which service is designed to let the customer leverage existing Chef recipes in AWS?

- [ ] Amazon Simple Workflow Service.
- [ ] AWS Elastic Beanstalk.
- [ ] AWS CloudFormation.
- [x] AWS OpsWorks.

**[⬆ Back to Top](#table-of-contents)**

### Does Amazon RDS for SQL Server currently support importing data into the msdb database?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### How can an EBS volume that is currently attached to an EC2 instance be migrated from one Availability Zone to another?

- [ ] Detach the volume and attach it to another EC2 instance in the other AZ.
- [ ] Simply create a new volume in the other AZ and specify the original volume as the source.
- [x] Create a snapshot of the volume, and create a new volume from the snapshot in the other AZ.
- [ ] Detach the volume, then use the ec2-migrate-voiume command to move it to another AZ.

**[⬆ Back to Top](#table-of-contents)**

### Having set up a website to automatically be redirected to a backup website if it fails, you realize that there are different types of failovers that are possible. You need all your resources to be available the majority of the time. Using Amazon Route 53 which configuration would best suit this requirement?

- [x] Active-active failover.
- [ ] None. Route 53 can't failover.
- [ ] Active-passive failover.
- [ ] Active-active-passive and other mixed configurations.

**[⬆ Back to Top](#table-of-contents)**

### A client application requires operating system privileges on a relational database server. What is an appropriate configuration for a highly available database architecture?

- [ ] A standalone Amazon EC2 instance.
- [ ] Amazon RDS in a Multi-AZ configuration.
- [ ] Amazon EC2 instances in a replication configuration utilizing a single Availability Zone.
- [x] Amazon EC2 instances in a replication configuration utilizing two different Availability Zones.

**[⬆ Back to Top](#table-of-contents)**

### Is decreasing the storage size of a DB Instance permitted?

- [ ] Depends on the ROMS used.
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Can you encrypt EBS volumes?

- [x] Yes, you can enable encryption when you create a new EBS volume using the AWS Management Console, API, or CLI.
- [ ] No, you should use a third-party software to perform raw block-level encryption of an EBS volume.
- [ ] Yes, but you must use a third-party API for encrypting data before it's loaded on EBS.
- [ ] Yes, you can encrypt with the special 'ebs_encrypt' command through Amazon APIs.

**[⬆ Back to Top](#table-of-contents)**

### You must assign each server to at least [...] security group.

- [x] 3.
- [ ] 2.
- [ ] 4.
- [ ] 1.

**[⬆ Back to Top](#table-of-contents)**

### Is the encryption of connections between my application and my DB Instance using SSL for the MySQL server engines available?

- [x] Yes.
- [ ] Only in VPC.
- [ ] Only in certain regions.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Your manager has come to you saying that he is very confused about the bills he is receiving from AWS as he is getting different bills for every user and needs you to look into making it more understandable. Which of the following would be the best solution to meet his request?

- [ ] AWS Billing Aggregation.
- [x] Consolidated Billing.
- [ ] Deferred Billing.
- [ ] Aggregated Billing.

**[⬆ Back to Top](#table-of-contents)**

### Regarding Amazon Route 53, if your application is running on Amazon EC2 instances in two or more Amazon EC2 regions and if you have more than one Amazon EC2 instance in one or more regions, you can use [...] to route traffic to the correct region and then use [...] route traffic to instances within the region, based on probabilities that you specify.

- [ ] weighted-based routing; alias resource record sets.
- [x] latency-based routing; weighted resource record sets.
- [ ] weighted-based routing; weighted resource record sets.
- [ ] latency-based routing; alias resource record sets.

**[⬆ Back to Top](#table-of-contents)**

### If I scale the storage capacity provisioned to my DB Instance by mid of a billing month, how will I be charged?

- [ ] You will be charged for the highest storage capacity you have used.
- [x] On a proration basis.

**[⬆ Back to Top](#table-of-contents)**

### When using the following AWS services, which should be implemented in multiple Availability Zones for high availability solutions? (Choose 2 answers)

- [ ] Amazon Dynamo DB.
- [x] Amazon Elastic Compute Cloud (EC2).
- [x] Amazon Elastic Load Balancing.
- [ ] Amazon Simple Notification Service (SNS).
- [ ] Amazon Simple Storage Service (S3).

**[⬆ Back to Top](#table-of-contents)**

### A customer is hosting t heir company website on a cluster of web servers that are behind a public facing load balancer. The customer also uses Amazon Route 53 to manage their public DNS. How should the customer configure the DNS zone apex record to point to the load balancer?

- [ ] Create an A record pointing to the IP address of the load balancer.
- [ ] Create a CNAME record pointing to the load balancer DNS name.
- [x] Create a CNAME record aliased to the load balancer DNS name.
- [ ] Create an A record aliased to the load balancer DNS name.

**[⬆ Back to Top](#table-of-contents)**

### True or False: REST or Query requests are HTTP or HTTPS requests that use an HTTP verb (such as GET or POST) and a parameter named Action or Operation that specifies the API you are calling.

- [ ] True.
- [x] False.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following features ensures even distribution of traffic to Amazon EC2 instances in multiple Availability Zones registered with a load balancer?

- [x] Elastic Load Balancing request routing.
- [ ] An Amazon Route 53 weighted routing policy.
- [ ] Elastic Load Balancing cross-zone load balancing.
- [ ] An Amazon Route 53 latency routing pol icy.

**[⬆ Back to Top](#table-of-contents)**

### Groups can't [...].

- [ ] be nested more than 3 levels.
- [x] be nested at all.
- [ ] be nested more than 4 levels.
- [ ] be nested more than 2 levels.

**[⬆ Back to Top](#table-of-contents)**

### You have been using T2 instances as your CPU requirements have not been that intensive. However you now start to think about larger instance types and start looking at M1 and M3 instances. You are a little confused as to the differences between them as they both seem to have the same ratio of CPU and memory. Which statement below is incorrect as to why you would use one over the other?

- [ ] M3 instances are less expensive than M1 instances.
- [x] M3 instances are configured with more swap memory than M1 instances.
- [ ] M3 instances provide better, more consistent performance that M1 instances for most use-cases.
- [ ] M3 instances also offer SSD-based instance storage that delivers higher I/O performance.

**[⬆ Back to Top](#table-of-contents)**

### Do the system resources on the Micro instance meet the recommended configuration for Oracle?

- [ ] Yes, completely.
- [x] Yes, but only for certain situations.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following are t rue regarding AWS CloudTrail? (Choose 3 answers)

- [ ] CloudTrail is enabled globally.
- [ ] CloudTrail is enabled by default.
- [x] CloudTrail is enabled on a per-region basis.
- [x] CloudTrail is enabled on a per-service basis.
- [x] Logs can be delivered to a single Amazon S3 bucket for aggregation.
- [ ] CloudTrail is enabled for all available services within a region.
- [ ] Logs can only be processed and delivered to the region in which they are generated.

**[⬆ Back to Top](#table-of-contents)**

### If you're unable to connect via SSH to your EC2 instance, which of the following should you check and possibly correct to restore connectivity?

- [ ] Adjust Security Group to permit egress traffic over TCP port 443 from your IP.
- [ ] Configure the JAM role to permit changes to security group settings.
- [ ] Modify the instance security group to allow ingress of ICMP packets from your IP.
- [x] Adjust the instance's Security Group to permit ingress traffic over port 22 from your IP.
- [ ] Apply the most recently released Operating System security patches.

**[⬆ Back to Top](#table-of-contents)**

### A major finance organisation has engaged your company to set up a large data mining application. Using AWS you decide the best service for this is Amazon Elastic MapReduce (EMR) which you know uses Hadoop. Which of the following statements best describes Hadoop?

- [ ] Hadoop is 3rd Party software which can be installed using AMI.
- [ ] Hadoop is an open source python web framework.
- [x] Hadoop is an open source Java software framework.
- [ ] Hadoop is an open source javascript framework.

**[⬆ Back to Top](#table-of-contents)**

### A customer has established an AWS Direct Connect connection to AWS. The link is up and routes are being advertised from the customer's end, however the customer is unable to connect from EC2 instances inside its VPC to servers residing in its datacenter. Which of the following options provide a viable solution to remedy this situation? (Choose 2 answers)

- [ ] Add a route to the route table with an IPsec VPN connection as the target.
- [x] Enable route propagation to the virtual pinnate gateway (VGW).
- [ ] Enable route propagation to the customer gateway (CGW).
- [ ] Modify the route table of all Instances using the 'route' command.
- [x] Modify the Instances VPC subnet route table by adding a route back to the customer's on-premises environment.

**[⬆ Back to Top](#table-of-contents)**

### While creating a network in the VPC, which of the following is true of a NAT device?

- [ ] You have to administer the NAT Gateway Service provided by AW
- [x] You can choose to use any of the three kinds of NAT devices offered by AWS for special purposes.
- [ ] You can use a NAT device to enable instances in a private subnet to connect to the Internet.
- [ ] You are recommended to use AWS NAT instances over NAT gateways, as the instances provide better availability and bandwidth.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following statements is NOT true about using Elastic IP Address (EIP) in EC2-Classic and EC2-VPC platforms?

- [x] In the EC2-VPC platform, the Elastic IP Address (EIP) does not remain associated with the instance when you stop it.
- [ ] In the EC2-Classic platform, stopping the instance disassociates the Elastic IP Address (EIP) from it.
- [ ] In the EC2-VPC platform, if you have attached a second network interface to an instance, when you disassociate the Elastic IP Address (EIP) from that instance, a new public IP address is not assigned to the instance automatically; you'll have to associate an EIP with it manually.
- [ ] In the EC2-Classic platform, if you disassociate an Elastic IP Address (EIP) from the instance, the instance is automatically assigned a new public IP address within a few minutes.

**[⬆ Back to Top](#table-of-contents)**

### A user has hosted an application on EC2 instances. The EC2 instances are configured with ELB and Auto Scaling. The application server session time out is 2 hours. The user wants to configure connection draining to ensure that all in-flight requests are supported by ELB even though the instance is being deregistered. What time out period should the user specify for connection draining?

- [x] 1 hour.
- [ ] 30 minutes.
- [ ] 5 minutes.
- [ ] 2 hours.

**[⬆ Back to Top](#table-of-contents)**

### What does the following command do with respect to the Amazon EC2 security groups? ec2-create-group CreateSecurityGroup

- [ ] Groups the user created security groups in to a new group for easy access.
- [x] Creates a new security group for use with your account.
- [ ] Creates a new group inside the security group.
- [ ] Creates a new rule inside the security group.

**[⬆ Back to Top](#table-of-contents)**

### You are in the process of moving your friend's WordPress site onto AWS to try and save him some money, and you have told him that he should probably also move his domain name. He asks why he can't leave his domain name where it is and just have his infrastructure on AWS. What would be an incorrect response to his question?

- [ ] Route 53 offers low query latency for your end users.
- [ ] Route 53 is designed to automatically answer queries from the optimal location depending on network conditions.
- [ ] The globally distributed nature of AWS's DNS servers helps ensure a consistent ability to route your end users to your application.
- [x] Route 53 supports Domain Name System Security Extensions (DNSSEC).

**[⬆ Back to Top](#table-of-contents)**

### Which of the following are characteristics of a reserved instance? (Choose 3 answers)

- [x] It can be migrated across Availability Zones.
- [ ] It is specific to an Amazon Machine Image (AMI).
- [ ] It can be applied to instances launched by Auto Scaling.
- [x] It is specific to an instance Type.
- [x] It can be used to lower Total Cost of Ownership (TCO) of a system.

**[⬆ Back to Top](#table-of-contents)**

### A user has defined an AutoScaling termination policy to first delete the instance with the nearest billing hour. AutoScaling has launched 3 instances in the US-East-1A region and 2 instances in the US-East-1B region. One of the instances in the US-East-1B region is running nearest to the billing hour. Which instance will AutoScaling terminate first while executing the termination action?

- [ ] Random Instance from US-East-1A.
- [ ] Instance with the nearest billing hour in US-East-1B.
- [x] Instance with the nearest billing hour in US-East-1A.
- [ ] Random instance from US-East-1B.

**[⬆ Back to Top](#table-of-contents)**

### You have an environment that consists of a public subnet using Amazon VPC and 3 instances that are running in this subnet. These three instances can successfully communicate with other hosts on the Internet. You launch a fourth instance in the same subnet, using the same AMI and security group configuration you used for the others, but find that this instance cannot be accessed from the internet. What should you do to enable Internet access?

- [ ] Deploy a NAT instance into the public subnet.
- [x] Assign an Elastic IP address to the fourth instance.
- [ ] Configure a publically routable IP Address in the host OS of the fourth instance.
- [ ] Modify the routing table for the public subnet.

**[⬆ Back to Top](#table-of-contents)**

### What does the 'Server Side Encryption' option on Amazon S3 provide?

- [x] It provides an encrypted virtual disk in the Cloud.
- [ ] It doesn't exist for Amazon S3, but only for Amazon EC2.
- [ ] It encrypts the files that you send to Amazon S3, on the server side.
- [ ] It allows to upload fi les using an SSL endpoint, for a secure transfer.

**[⬆ Back to Top](#table-of-contents)**

### What is a placement group?

- [ ] A collection of Auto Scaling groups in the same region.
- [x] A feature that enables EC2 instances to interact with each other via high bandwidth, low latency connections.
- [ ] A collection of authorized CloudFront edge locations for a distribution.
- [ ] A collection of Elastic Load Balancers in the same Region or Availability Zone.

**[⬆ Back to Top](#table-of-contents)**

### You are checking the workload on some of your General Purpose (SSD) and Provisioned IOPS (SSD) volumes and it seems that the I/O latency is higher than you require. You should probably check the [...] to make sure that your application is not trying to drive more IOPS than you have provisioned.

- [ ] amount of IOPS that are available.
- [ ] acknowledgement from the storage subsystem.
- [x] average queue length.
- [ ] time it takes for the I/O operation to complete.

**[⬆ Back to Top](#table-of-contents)**

### Within the IAM service a GROUP is regarded as a:

- [ ] A collection of AWS accounts.
- [ ] It's the group of EC2 machines that gain t he permissions specified in the GROUP.
- [ ] There's no GROUP in IAM, but only USERS and RESOURCES.
- [x] A collection of users.

**[⬆ Back to Top](#table-of-contents)**

### Doug has created a VPC with CIDR 10.201.0.0/16 in his AWS account. in this VPC he has created a public subnet with CIDR block 10.201.31.0/24. While launching a new EC2 from the console, he is not able to assign the private IP address 10.201.31.6 to this instance. Which is the most likely reason for this issue?

- [ ] Private IP address 10.201.31.6 is blocked via ACLs in Amazon infrastructure as a part of platform security.
- [x] Private address IP 10.201.31.6 is currently assigned to another interface.
- [ ] Private IP address 10.201.31.6 is not part of the associated subnet's IP address range.
- [ ] Private IP address 10.201.31.6 is reserved by Amazon for IP networking purposes.

**[⬆ Back to Top](#table-of-contents)**

### A user is planning to make a mobile game which can be played online or offline and will be hosted on EC2. The user wants to ensure that if someone breaks the highest score or they achieve some milestone they can inform all their colleagues through email. Which of the below mentioned AWS services helps achieve this goal?

- [ ] AWS Simple Workflow Service.
- [x] AWS Simple Email Service.
- [ ] Amazon Cognito.
- [ ] AWS Simple Queue Service.

**[⬆ Back to Top](#table-of-contents)**

### Is creating a Read Replica of another Read Replica supported?

- [ ] Only in VPC.
- [ ] Yes.
- [ ] Only in certain regions.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following is NOT a characteristic of Amazon Elastic Compute Cloud (Amazon EC2)?

- [ ] It can be used to launch as many or as few virtual servers as you need.
- [x] It increases the need to forecast traffic by providing dynamic IP addresses for static cloud computing.
- [ ] It eliminates your need to invest in hardware up front, so you can develop and deploy applications faster.
- [ ] It offers scalable computing capacity in the Amazon Web Services (AWS) cloud.

**[⬆ Back to Top](#table-of-contents)**

### A user has launched one EC2 instance in the US East region and one in the US West region. The user has launched an RDS instance in the US East region. How can the user configure access from both the EC2 instances to RDS?

- [ ] It is not possible to access RDS of the US East region from the US West region.
- [ ] Configure the US West region's security group to allow a request from the US East region's instance and configure the RDS security group's ingress rule for the US East EC2 group.
- [x] Configure the security group of the US East region to allow traffic from the US West region's instance and configure the RDS security group's ingress rule for the US East EC2 group.
- [ ] Configure the security group of both instances in the ingress rule of the RDS security group.

**[⬆ Back to Top](#table-of-contents)**

### What happens to the 1/0 operations while you take a database snapshot?

- [ ] 1/0 operations to the database are suspended for an hour while the backup is in progress.
- [ ] 1/0 operations to the database are sent to a Replica (if available) for a few minutes while the backup is in progress.
- [ ] 1/0 operations will be functioning normally.
- [x] 1/0 operations to the database are suspended for a few minutes while the backup is in progress.

**[⬆ Back to Top](#table-of-contents)**

### When an EC2 EBS-backed (EBS root) instance is stopped, what happens to the data on any ephemeral store volumes?

- [ ] Data is automatically saved in an EBS volume.
- [x] Data is unavailable until the instance is restarted.
- [ ] Data will be deleted and will no longer be accessible.
- [ ] Data is automatically saved as an EBS snapshot.

**[⬆ Back to Top](#table-of-contents)**

### [...] is a durable, block-level storage volume that you can attach to a single, running Amazon EC2 instance.

- [ ] Amazon S3.
- [x] Amazon EBS.
- [ ] None of these.
- [ ] All of these.

**[⬆ Back to Top](#table-of-contents)**

### A favored client needs you to quickly deploy a database that is a relational database service with minimal administration as he wants to spend the least amount of time administering it. Which database would be the best option?

- [ ] Amazon SimpleDB.
- [ ] Your choice of relational AMIs on Amazon EC2 and EB.
- [x] Amazon RDS.
- [ ] Amazon Redshift.

**[⬆ Back to Top](#table-of-contents)**

### You have a number of image files to encode. in an Amazon SQS worker queue, you create an Amazon SQS message for each file specifying the command (jpeg-encode) and the location of the file in Amazon S3. Which of the following statements best describes the functionality of Amazon SQS?

- [x] Amazon SQS is a distributed queuing system that is optimized for horizontal scalability, not for single-threaded sending or receiving speeds.
- [ ] Amazon SQS is for single-threaded sending or receiving speeds.
- [ ] Amazon SQS is a non-distributed queuing system.
- [ ] Amazon SQS is a distributed queuing system that is optimized for vertical scalability and for single-threaded sending or receiving speeds.

**[⬆ Back to Top](#table-of-contents)**

### While creating an Amazon RDS DB, your first task is to set up a DB [...] that controls what IP addresses or EC2 instances have access to your DB Instance.

- [ ] Security Pool.
- [ ] Secure Zone.
- [ ] Security Token Pool.
- [x] Security Group.

**[⬆ Back to Top](#table-of-contents)**

### What happens to the 1/0 operations while you take a database snapshot?

- [x] 1/0 operations to the database are suspended for a few minutes while the backup is in progress.
- [ ] 1/0 operations to the database are sent to a Replica (if available) for a few minutes while the backup is in progress.
- [ ] 1/0 operations will be functioning normally.
- [ ] 1/0 operations to the database are suspended for an hour while the backup is in progress.

**[⬆ Back to Top](#table-of-contents)**

### After launching an instance that you intend to serve as a NAT (Network Address Translation) device in a public subnet you modify your route tables to have the NAT device be the target of internet bound traffic of your private subnet. When you try and make an outbound connection to the internet from an instance in the private subnet, you are not successful. Which of the following steps could resolve the issue?

- [x] Disabling the Source/Destination Check attribute on the NAT instance.
- [ ] Attaching an Elastic IP address to the instance in the private subnet.
- [ ] Attaching a second Elastic Network Interface (EN I) to the NAT instance, and placing it in the private subnet.
- [ ] Attaching a second Elastic Network Interface (ENI) to the instance in the private subnet, and placing it in the public subnet.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following would you use to list your AWS Import/Export jobs?

- [ ] Amazon RDS.
- [ ] AWS Import/Export Web Service Tool.
- [x] Amazon S3 REST API.
- [ ] AWS Elastic Beanstalk.

**[⬆ Back to Top](#table-of-contents)**

### Company B is launching a new game app for mobile devices. Users will log into the game using their existing social media account to streamline data capture. Company B would like to directly save player data and scoring information from the mobile app to a DynamoDS table named Score Data. When a user saves their game the progress data will be stored to the Game state S3 bucket. What is the best approach for storing data to DynamoDB and S3?

- [ ] Use an EC2 Instance that is launched with an EC2 role providing access to the Score Data DynamoDB table and the GameState S3 bucket that communicates with the mobile app via web services.
- [x] Use temporary security credentials that assume a role providing access to the Score Data DynamoDB table and the Game State S3 bucket using web identity federation.
- [ ] Use Login with Amazon allowing users to sign in with an Amazon account providing the mobile app with access to the Score Data DynamoDB table and the Game State S3 bucket.
- [ ] Use an IAM user with access credentials assigned a role providing access to the Score Data DynamoDB table and the Game State S3 bucket for distribution with the mobile app.

**[⬆ Back to Top](#table-of-contents)**

### If your DB instance runs out of storage space or file system resources, its status will change to [...] and your DB Instance will no longer be available.

- [ ] storage-overflow.
- [x] storage-full.
- [ ] storage-exceed.
- [ ] storage-overage.

**[⬆ Back to Top](#table-of-contents)**

### Your application is using an ELB in front of an Auto Scaling group of web/application servers deployed across two AZs and a Multi-AZ RDS Instance for data persistence. The database CPU is often above 80% usage and 90% of 1/0 operations on the database are reads. To improve performance you recently added a single-node Memcached ElastiCache Cluster to cache frequent DB query results. in the next weeks the overall workload is expected to grow by 30%. Do you need to change anything in the architecture to maintain the high availability or the application with the anticipated additional load? Why?

- [x] Yes, you should deploy two Memcached ElastiCache Clusters in different AZs because the RDS instance will not be able to handle the load if the cache node fails.
- [ ] No, if the cache node fails you can always get the same data from the DB without having any availability impact.
- [ ] No, if the cache node fails the automated ElastiCache node recovery feature will prevent any availability impact.
- [ ] Yes, you should deploy the Memcached ElastiCache Cluster with two nodes in the same AZ as the RDS DB master instance to handle the load if one cache node fails.

**[⬆ Back to Top](#table-of-contents)**

### How many Elastic IP by default in Amazon Account?

- [ ] 1 Elastic IP.
- [ ] 3 Elastic IP.
- [ ] 5 Elastic IP.
- [x] 0 Elastic IP.

**[⬆ Back to Top](#table-of-contents)**

### What would be the best way to retrieve the public IP address of your EC2 instance using the CLI?

- [ ] Using tags.
- [ ] Using traceroute.
- [ ] Using ipconfig.
- [x] Using instance metadata.

**[⬆ Back to Top](#table-of-contents)**

### A company is building a two-tier web application to serve dynamic transaction-based content. The data tier is leveraging an Online Transactional Processing (OLTP) database. What services should you leverage to enable an elastic and scalable web tier?

- [x] Elastic Load Balancing, Amazon EC2, and Auto Scaling.
- [ ] Elastic Load Balancing, Amazon RDS with Multi-AZ, and Amazon S3.
- [ ] Amazon RDS with Multi-AZ and Auto Scaling.
- [ ] Amazon EC2, Amazon DynamoDB, and Amazon S3.

**[⬆ Back to Top](#table-of-contents)**

### You are designing a connectivity solution between on-premises infrastructure and Amazon VPC. Your server's on-premises will De communicating with your VPC instances. You will De establishing IPSec tunnels over the internet You will be using VPN gateways and terminating the IPsec tunnels on AWS supported customer gateways. Which of the following objectives would you achieve by implementing an IPSec tunnel as outlined above? (Choose 4 answers)

- [ ] End-to-end protection of data in transit.
- [ ] End-to-end Identity authentication.
- [x] Data encryption across the Internet.
- [x] Protection of data in transit over the Internet.
- [x] Peer identity authentication between VPN gateway and customer gateway.
- [x] Data integrity protection across the Internet.

**[⬆ Back to Top](#table-of-contents)**

### You have been storing massive amounts of data on Amazon Glacier for the past 2 years and now start to wonder if there are any limitations on this. What is the correct answer to your question?

- [ ] The total volume of data is limited but the number of archives you can store are unlimited.
- [ ] The total volume of data is unlimited but the number of archives you can store are limited.
- [x] The total volume of data and number of archives you can store are unlimited.
- [ ] The total volume of data is limited and the number of archives you can store are limited.

**[⬆ Back to Top](#table-of-contents)**

### How are the EBS snapshots saved on Amazon S3?

- [ ] Exponentially.
- [x] Incrementally.
- [ ] EBS snapshots are not stored in the Amazon S3.
- [ ] Decrementally.

**[⬆ Back to Top](#table-of-contents)**

### An online gaming site asked you if you can deploy a database that is a fast, highly scalable NoSQL database service in AWS for a new site that he wants to build. Which database should you recommend?

- [x] Amazon DynamoDB.
- [ ] Amazon RDS.
- [ ] Amazon Redshift.
- [ ] Amazon SimpleDB.

**[⬆ Back to Top](#table-of-contents)**

### You have three Amazon EC2 instances with Elastic IP addresses in the US East (Virginia) region, and you want to distribute requests across all three IPs evenly for users for whom US East (Virginia) is the appropriate region. How many EC2 instances would be sufficient to distribute requests in other regions?

- [ ] 3.
- [ ] 9.
- [ ] 2.
- [x] 1.

**[⬆ Back to Top](#table-of-contents)**

### You are the new IT architect in a company that operates a mobile sleep tracking application. When activated at night, the mobile app is sending collected data points of 1 kilobyte every 5 minutes to your backend. The backend takes care of authenticating the user and writing the data points into an Amazon DynamoDB table. Every morning, you scan the table to extract and aggregate last night's data on a per user basis, and store the results in Amazon S3. Users are notified via Amazon 5M5 mobile push notifications that new data is available, which is parsed and visualized by The mobile app Currently you have around lOOk users who are mostly based out of North America. You have been tasked to optimize the architecture of the backend system to lower cost what would you recommend? (Choose 2 answers)

- [x] Create a new Amazon DynamoDB able each day and drop the one for the previous day after its data is on Amazon S3.
- [ ] Have the mobile app access Amazon DynamoDB directly instead of J50N files stored on Amazon S3.
- [x] Introduce an Amazon SQS queue to buffer writes to the Amazon DynamoDB table and reduce provisioned write throughput.
- [ ] Introduce Amazon Elasticache to cache reads from the Amazon DynamoDB table and reduce provisioned read throughput.
- [ ] Write data directly into an Amazon Redshift cluster replacing both Amazon DynamoDB and Amazon S3.

**[⬆ Back to Top](#table-of-contents)**

### You are implementing a URL whitelisting system for a company that wants to restrict outbound HTTP'S connections to specific domains from their EC2-hosted applications you deploy a single EC2 instance running proxy software and configure It to accept traffic from all subnets and EC2 instances in the VPC. You configure the proxy to only pass through traffic to domains that you define in its whitelist configuration You have a nightly maintenance window or 10 minutes where all instances fetch new software updates. Each update Is about 200MB in size and there are 500 instances in theVPC that routinely fetch updates After a few days you notice that some machines are failing to successfully download some, but not all of their updates within the maintenance window. The download URLs used for these updates are correctly listed in the proxy's whitelist configuration and you are able to access them manually using a web browser on the instances. What might be happening? (Choose 2 answers)

- [x] You are running the proxy on an undersized EC2 instance type so network throughput is not sufficient for all instances to download their updates in time.
- [x] You are running the proxy on a sufficiently-sized EC2 instance in a private subnet and its network throughput is being throttled by a NAT running on an undersized EC2 instance.
- [ ] The route table for the subnets containing the affected EC2 instances is not configured to direct network traffic for the software update locations to the proxy.
- [ ] You have not allocated enough storage to t he EC2 instance running the proxy so the network buffer is filling up, causing some requests to fail.
- [ ] You are running the proxy in a public subnet but have not allocated enough EIPs to support the needed network throughput through the Internet Gateway (IGW).

**[⬆ Back to Top](#table-of-contents)**

### You are playing around with setting up stacks using JSON templates in CloudFormation to try and understand them a little better. You have set up about 5 or 6 but now start to wonder if you are being charged for these stacks. What is AWS's billing policy regarding stack resources?

- [ ] You are not charged for the stack resources if they are not taking any traffic.
- [x] You are charged for the stack resources for the time they were operating (even if you deleted the stack right away).
- [ ] You are charged for the stack resources for the time they were operating (but not if you deleted the stack within 60 minutes).
- [ ] You are charged for the stack resources for the time they were operating (but not if you deleted the stack within 30 minutes).

**[⬆ Back to Top](#table-of-contents)**

### What does Amazon Cloud Formation provide?

- [ ] The ability to setup Autoscaling for Amazon EC2 instances.
- [ ] None of these.
- [ ] A templated resource creation for Amazon Web Services.
- [x] A template to map network resources for Amazon Web Services.

**[⬆ Back to Top](#table-of-contents)**

### You are signed in as root user on your account but there is an Amazon S3 bucket under your account that you cannot access. What is a possible reason for this?

- [x] An IAM user assigned a bucket policy to an Amazon S3 bucket and didn't specify the root user as a principal
- [ ] The S3 bucket is full.
- [ ] The S3 bucket has reached the maximum number of objects allowed.
- [ ] You are in the wrong Availability Zone.

**[⬆ Back to Top](#table-of-contents)**

### When creation of an EBS snapshot is initiated, but not completed, the EBS volume?

- [ ] Can be used while the snapshot is in progress.
- [ ] Cannot be detached or attached to an EC2 instance until the snapshot completes.
- [ ] Can be used in read-only mode while the snapshot is in progress.
- [x] Cannot be used until the snapshot completes.

**[⬆ Back to Top](#table-of-contents)**

### What does Amazon SES stand for?

- [ ] Simple Elastic Server.
- [x] Simple Email Service.
- [ ] Software Email Solution.
- [ ] Software Enabled Server.

**[⬆ Back to Top](#table-of-contents)**

### You receive a bill from AWS but are confused because you see you are incurring different costs for the exact same storage size in different regions on Amazon S3. You ask AWS why this is so. What response would you expect to receive from AWS?

- [ ] We charge less in different time zones.
- [x] We charge less where our costs are less.
- [ ] This will balance out next bill.
- [ ] It must be a mistake.

**[⬆ Back to Top](#table-of-contents)**

### Disabling automated backups [...] disable the point-in-time recovery.

- [ ] if configured to can.
- [ ] will never.
- [x] will.

**[⬆ Back to Top](#table-of-contents)**

### A user has launched a large EBS backed EC2 instance in the US-East-1a region. The user wants to achieve Disaster Recovery (DR) for that instance by creating another small instance in Europe. How can the user achieve DR?

- [ ] Copy the instance from the US East region to the EU region.
- [ ] Use the 'Launch more like this' option to copy the instance from one region to another.
- [ ] Copy the running instance using the 'Instance Copy' command to the EU region.
- [x] Create an AMI of the instance and copy the AMI to the EU region. Then launch the instance from the EU AMI.

**[⬆ Back to Top](#table-of-contents)**

### How many relational database engines does RDS currently support?

- [x] Three: MySQL, Oracle and Microsoft SQL Server.
- [ ] Just two: MySQL and Oracle.
- [ ] Five: MySQL, PostgreSQL, MongoDB, Cassandra and SQLite.
- [ ] Just one: MySQL.

**[⬆ Back to Top](#table-of-contents)**

### Are you able to integrate a multi-factor token service with the AWS Platform?

- [ ] Yes, you can integrate private multi-factor token devices to authenticate users to the AWS platform.
- [ ] No, you cannot integrate multi-factor token devices with the AWS platform.
- [x] Yes, using the AWS multi-factor token devices to authenticate users on the AWS platform.

**[⬆ Back to Top](#table-of-contents)**

### What is the default maximum number of MFA devices in use per AWS account (at the root account level)?

- [x] 1.
- [ ] 5.
- [ ] 15.
- [ ] 10.

**[⬆ Back to Top](#table-of-contents)**

### Select the correct statement: Within Amazon EC2, when using Linux instances, the device name /dev/sda1 is [...].

- [ ] reserved for EBS volumes.
- [ ] recommended for EBS volumes.
- [ ] recommended for instance store volumes.
- [x] reserved for the root device.

**[⬆ Back to Top](#table-of-contents)**

### Does Amazon Route 53 support NS Records?

- [ ] Yes, it supports Name Service records.
- [ ] No.
- [ ] It supports only MX records.
- [x] Yes, it supports Name Server records.

**[⬆ Back to Top](#table-of-contents)**

### Your web application front end consists of multiple EC2 instances behind an Elastic Load Balancer. You configured ELB to perform health checks on these EC2 instances, if an instance fails to pass health checks, which statement will be true?

- [ ] The instance gets terminated automatically by the ELB.
- [ ] The instance gets quarantined by the ELB for root cause analysis.
- [ ] The instance is replaced automatically by the ELB.
- [x] The ELB stops sending traffic to the instance that failed its health check.

**[⬆ Back to Top](#table-of-contents)**

### George has launched three EC2 instances inside the US-East-1a zone with his AWS account. Ray has launched two EC2 instances in the US-East-1a zone with his AWS account. Which of the below mentioned statements will help George and Ray understand the Availability Zone (AZ) concept better?

- [ ] All the instances of George and Ray can communicate over a private IP with a minimal cost.
- [x] The US-East-1a region of George and Ray can be different Availability Zones.
- [ ] All the instances of George and Ray can communicate over a private IP without any cost.
- [ ] The instances of George and Ray will be running in the same data centre.

**[⬆ Back to Top](#table-of-contents)**

### Once again your customers are concerned about the security of their sensitive data and with their latest enquiry ask about what happens to old storage devices on AWS. What would be the best answer to this question?

- [ ] AWS reformats the disks and uses them again.
- [x] AWS uses the techniques detailed in DoD 5220.22-M to destroy data as part of the decommissioning process.
- [ ] AWS uses their own proprietary software to destroy data as part of the decommissioning process.
- [ ] AWS uses a 3rd party security organization to destroy data as part of the decommissioning process.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following are characteristics of Amazon VPC subnets? (Choose 2 answers)

- [ ] Each subnet spans at least 2 Availability Zones to provide a high-availability environment.
- [x] Each subnet maps to a single Availability Zone.
- [ ] CIDR block mask of/25 is the smallest range supported.
- [ ] By default, all subnets can route between each other, whether they are private or public.
- [x] Instances in a private subnet can communicate with the Internet only if they have an Elastic IP.

**[⬆ Back to Top](#table-of-contents)**

### Which AWS instance address has the following characteristics? 'If you stop an instance, its Elastic IP address is unmapped, and you must remap it when you restart the instance.'

- [ ] Both A and B.
- [ ] None of these.
- [ ] VPC Addresses.
- [x] EC2 Addresses.

**[⬆ Back to Top](#table-of-contents)**

### You are designing a data leak prevention solution for your VPC environment. You want your VPC Instances to be able to access software depots and distributions on the Internet for product updates. The depots and distributions are accessible via third party CONs by their URLs. You want to explicitly deny any other outbound connections from your VPC instances to hosts on the internet. Which of the following options would you consider?

- [x] Configure a web proxy server in your VPC and enforce URL-based ru les for outbound access Remove default routes.
- [ ] Implement security groups and configure outbound rules to only permit traffic to software depots.
- [ ] Move all your instances into private VPC subnets remove default routes from all routing tables and add specific routes to the software depots and distributions only.
- [ ] Implement network access control lists to all specific destinations, with an Implicit deny as a rule.

**[⬆ Back to Top](#table-of-contents)**

### What is an isolated database environment running in the cloud (Amazon RDS) called?

- [x] DB Instance.
- [ ] DB Unit.
- [ ] DB Server.
- [ ] DB Volume.

**[⬆ Back to Top](#table-of-contents)**

### A user is sending bulk emails using AWS SES. The emails are not reaching some of the targeted audience because they are not authorized by the ISPs. How can the user ensure that the emails are all delivered?

- [x] Send an email using DKIM with SE.
- [ ] Send an email using SMTP with SE.
- [ ] Open a ticket with AWS support to get it authorized with the IS.
- [ ] Authorize the ISP by sending emails from the development account.

**[⬆ Back to Top](#table-of-contents)**

### What's an ECU?

- [ ] Extended Cluster User.
- [ ] None of these.
- [ ] Elastic Computer Usage.
- [x] Elastic Compute Unit.

**[⬆ Back to Top](#table-of-contents)**

### You would like to create a mirror image of your production environment in another region for disaster recovery purposes. Which of the following AWS resources do not need to be recreated in the second region? (Choose 2 answers)

- [x] Route 53 Record Sets.
- [x] IAM Roles.
- [ ] Elastic IP Addresses (EIP).
- [ ] EC2 Key Pairs.
- [ ] Launch configurations.
- [ ] Security Groups.

**[⬆ Back to Top](#table-of-contents)**

### Which procedure for backing up a relational database on EC2 that is using a set of RAIDed EBS volumes for storage minimizes the time during which the database cannot be written to and results in a consistent backup?

- [x] 1. Detach EBS volumes, 2. Start EBS snapshot of volumes, 3. Re-attach EBS volumes.
- [ ] 1. Stop the EC2 Instance. 2. Snapshot the EBS volumes.
- [ ] 1. Suspend disk 1/0, 2. Create an image of the EC2 Instance, 3. Resume disk 1/0.
- [ ] 1. Suspend disk 1/0, 2. Start EBS snapshot of volumes, 3. Resume disk 1/0.
- [ ] 1. Suspend disk 1/0, 2. Start EBS snapshot of volumes, 3. Wait for snapshots to complete, 4. Resume disk 1/0.

**[⬆ Back to Top](#table-of-contents)**

### My Read Replica appears 'stuck' after a Multi-AZ failover and is unable to obtain or apply updates from the source DB Instance. What do I do?

- [x] You will need to delete the Read Replica and create a new one to rep lace it.
- [ ] You will need to disassociate the DB Engine and re associate it.
- [ ] The instance should be deployed to Single AZ and then moved to Multi-AZ once again.
- [ ] You will need to delete the DB Instance and create a new one to replace it.

**[⬆ Back to Top](#table-of-contents)**

### You are setting up some IAM user policies and have also become aware that some services support resource-based permissions, which let you attach policies to the service's resources instead of to IAM users or groups. Which of the below statements is true in regards to resource-level permissions?

- [ ] All services support resource-level permissions for all actions.
- [ ] Resource-level permissions are supported by Amazon CloudFront.
- [ ] All services support resource-level permissions only for some actions.
- [x] Some services support resource-level permissions only for some actions.

**[⬆ Back to Top](#table-of-contents)**

### You have some very sensitive data stored on AWS S3 and want to try every possible alternative to keeping it secure in regards to access control. What are the mechanisms available for access control on AWS S3?

- [x] (IAM) policies, Access Control Lists (ACLs), bucket policies, and query string authentication.
- [ ] (IAM) policies, Access Control Lists (ACLs) and bucket policies.
- [ ] Access Control Lists (ACLs), bucket policies, and query string authentication.
- [ ] (IAM) policies, Access Control Lists (ACLs), bucket policies, query string authentication and encryption.

**[⬆ Back to Top](#table-of-contents)**

### You are implementing AWS Direct Connect. You intend to use AWS public service end points such as Amazon S3, across the AWS Direct Connect link. You want other Internet traffic to use your existing link to an Internet Service Provider. What is the correct way to configure AWS Direct connect for access to services such as Amazon S3?

- [ ] Configure a public Interface on your AWS Direct Connect link. Configure a static route via your AWS Direct Connect link that points to Amazon S3 Advertise a default route to AWS using BGP.
- [ ] Create a private interface on your AWS Direct Connect link. Configure a static route via your AWS Direct connect link that points to Amazon S3 Configure specific routes to your network in your VPC.
- [x] Create a public interface on your AWS Direct Connect link. Redistribute BGP routes into your existing routing infrastructure; advertise specific routes for your network to AWS.
- [ ] Create a private interface on your AWS Direct connect link. Redistribute BGP routes into your existing routing infrastructure and advertise a default route to AWS.

**[⬆ Back to Top](#table-of-contents)**

### What is the charge for the data transfer incurred in replicating data between your primary and standby?

- [ ] No charge. It is free.
- [ ] Double the standard data transfer charge.
- [x] Same as the standard data transfer charge.
- [ ] Half of the standard data transfer charge.

**[⬆ Back to Top](#table-of-contents)**

### You are setting up your first Amazon Virtual Private Cloud (Amazon VPC) network so you decide you should probably use the AWS Management Console and the VPC Wizard. Which of the following is not an option for network architectures after launching the 'Start VPC Wizard' in Amazon VPC page on the AWS Management Console?

- [ ] VPC with a Single Public Subnet Only.
- [x] VPC with a Public Subnet Only and Hardware VPN Access.
- [ ] VPC with Public and Private Subnets and Hardware VPN Access.
- [ ] VPC with a Private Subnet Only and Hardware VPN Access.

**[⬆ Back to Top](#table-of-contents)**

### True or False: A VPC contains multiple subnets, where each subnet can span multiple Availability Zones.

- [ ] This is true only if requested during the set-up of VPC.
- [x] This is true.
- [ ] This is false.
- [ ] This is true only for US regions.

**[⬆ Back to Top](#table-of-contents)**

### Amazon RDS automated backups and DB Snapshots are currently supported for only the [...] storage engine.

- [x] InnoDB.
- [ ] MyISAM.

**[⬆ Back to Top](#table-of-contents)**

### While signing in REST/ Query requests, for additional security, you should transmit your requests using Secure Sockets Layer (SSL) by using [...].

- [ ] HTTP.
- [ ] Internet Protocol Security (IPsec).
- [ ] TLS (Transport Layer Security).
- [x] HTTPS.

**[⬆ Back to Top](#table-of-contents)**

### Out of the stripping options available for the EBS volumes, which one has the following disadvantage: 'Doubles the amount of 1/0 required from the instance to EBS compared to RAID 0, because you're mirroring all writes to a pair of volumes, limiting how much you can stripe.'?

- [ ] Raid 0.
- [x] RAID 1+0 (RAID 10).
- [ ] Raid 1.
- [ ] Raid.

**[⬆ Back to Top](#table-of-contents)**

### Can I encrypt connections between my application and my DB Instance using SSL?

- [x] Yes.
- [ ] Only in VPC.
- [ ] Only in certain regions.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following items are required to allow an application deployed on an EC2 instance to write data to a DynamoDB table? Assume that no security keys are allowed to be stored on the EC2 instance. (Choose 3 answers)

- [x] Create an IAM Role that allows write access to the DynamoDB table.
- [x] Add an IAM Role to a running EC2 instance.
- [ ] Create an IAM User that al lows write access to the Dynamo DB table.
- [ ] Add an IAM User to a running EC2 instance.
- [x] Launch an EC2 Instance with the IAM Role included in the launch configuration.

**[⬆ Back to Top](#table-of-contents)**

### Identify a true statement about the On-Demand instances purchasing option provided by Amazon EC2.

- [x] Pay for the instances that you use by the hour, with no long-term commitments or up-front payments.
- [ ] Make a low, one-time, up-front payment for an instance, reserve it for a one- or three-year term, and pay a significantly lower hourly rate for these instances.
- [ ] Pay for the instances that you use by the hour, with long-term commitments or up-front payments.
- [ ] Make a high, one-time, all-front payment for an instance, reserve it for a one- or three-year term, and pay a significantly higher hourly rate for these instances.

**[⬆ Back to Top](#table-of-contents)**

### When will you incur costs with an Elastic IP address (EIP)?

- [ ] When an EIP is allocated.
- [ ] When it is allocated and associated with a running instance.
- [ ] When it is allocated and associated with a stopped instance.
- [x] Costs are incurred regardless of whether the ElP is associated with a running instance.

**[⬆ Back to Top](#table-of-contents)**

### IAM provides several policy templates you can use to automatically assign permissions to the groups you create. The [...] policy template gives the Admins group permission to access all account resources, except your AWS account information.

- [ ] Read Only Access.
- [ ] Power User Access.
- [ ] AWS Cloud Formation Read Only Access.
- [x] Administrator Access.

**[⬆ Back to Top](#table-of-contents)**

### What does RRS stand for when talking about S3?

- [ ] Redundancy Removal System.
- [ ] Relational Rights Storage.
- [ ] Regional Rights Standard.
- [x] Reduced Redundancy Storage.

**[⬆ Back to Top](#table-of-contents)**

### Can I change the EC2 security groups after an instance is launched in EC2-Classic?

- [ ] Yes, you can change security groups after you launch an instance in EC2-Classic.
- [x] No, you cannot change security groups after you launch an instance in EC2-Classic.
- [ ] Yes, you can only when you remove rules from a security group.
- [ ] Yes, you can only when you add rules to a security group.

**[⬆ Back to Top](#table-of-contents)**

### Please select the Amazon EC2 resource which cannot be tagged.

- [ ] Images (AMIs, kernels, RAM disks).
- [ ] Amazon EBS volumes.
- [x] Elastic IP addresses.
- [ ] VPCs.

**[⬆ Back to Top](#table-of-contents)**

### Does Route 53 support MX Records?

- [x] Yes.
- [ ] It supports CNAME records, but not MX records.
- [ ] No.
- [ ] Only Primary MX records. Secondary MX records are not supported.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following notification endpoints or clients are supported by Amazon Simple Notification Service? (Choose 2 answers)

- [x] Email.
- [ ] CloudFront distribution.
- [ ] File Transfer Protocol.
- [x] Short Message Service.
- [ ] Simple Network Management Protocol.

**[⬆ Back to Top](#table-of-contents)**

### AWS Identity and Access Management is a web service that enables Amazon Web Services (AWS) customers to manage users and user permissions in AWS. In addition to supporting IAM user policies, some services support resource-based permissions. Which of the following services are supported by resource-based permissions?

- [ ] Amazon SNS, and Amazon SQS and AWS Direct Connect.
- [ ] Amazon S3 and Amazon SQS and Amazon ElastiCache.
- [x] Amazon S3, Amazon SNS, Amazon SQS, Amazon Glacier and Amazon EB
- [ ] Amazon Glacier, Amazon SNS, and Amazon CloudWatch.

**[⬆ Back to Top](#table-of-contents)**

### What does the following policy for Amazon EC2 do? { 'Statement':[{ 'Effect': 'Allow', 'Action':'ec2: Describe*', 'Resource':'*' }] }

- [x] Allow users to use actions that start with 'Describe' over all the EC2 resources.
- [ ] Share an AMI with a partner.
- [ ] Share an AMI within the account.
- [ ] Allow a group to only be able to describe, run, stop, start, and terminate instances.

**[⬆ Back to Top](#table-of-contents)**

### Which IAM role do you use to grant AWS Lambda permission to access a DynamoDB Stream?

- [ ] Dynamic role.
- [ ] Invocation role.
- [x] Execution role.
- [ ] Event Source role.

**[⬆ Back to Top](#table-of-contents)**

### Can resource record sets in a hosted zone have a different domain suffix (for example, <www.blog>. acme.com and <www.acme.ca>)?

- [ ] Yes, it can have for a maximum of three different TLDs.
- [ ] Yes.
- [x] Yes, it can have depending on the TL.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### In Amazon Elastic Compute Cloud, which of the following is used for communication between instances in the same network (EC2-Classic or a VPC)?

- [x] Private IP addresses.
- [ ] Elastic IP addresses.
- [ ] Static IP addresses.
- [ ] Public IP addresses.

**[⬆ Back to Top](#table-of-contents)**

### A user is planning to host a mobile game on EC2 which sends notifications to active users on either high score or the addition of new features. The user should get this notification when he is online on his mobile device. Which of the below mentioned AWS services can help achieve this functionality?

- [x] AWS Simple Notification Service.
- [ ] AWS Simple Email Service.
- [ ] AWS Mobile Communication Service.
- [ ] AWS Simple Queue Service.

**[⬆ Back to Top](#table-of-contents)**

### You need to create an Amazon Machine Image (AMI) for a customer for an application which does not appear to be part of the standard AWS AMI template that you can see in the AWS console. What are the alternative possibilities for creating an AMI on AWS?

- [ ] You can purchase an AMIs from a third party but cannot create your own AMI.
- [x] You can purchase an AMIs from a third party or can create your own AMI.
- [ ] Only AWS can create AMIs and you need to wait till it becomes available.
- [ ] Only AWS can create AMIs and you need to request them to create one for you.

**[⬆ Back to Top](#table-of-contents)**

### Will I be charged if the DB instance is idle?

- [x] Yes.
- [ ] Only is running in GovCloud.
- [ ] Only if running in VPC.

**[⬆ Back to Top](#table-of-contents)**

### Your company has been storing a lot of data in Amazon Glacier and has asked for an inventory of what is in there exactly. So you have decided that you need to download a vault inventory. Which of the following statements is incorrect in relation to Vault Operations in Amazon Glacier?

- [ ] You can use Amazon Simple Notification Service (Amazon SNS) notifications to notify you when the job completes.
- [ ] A vault inventory refers to the list of archives in a vault.
- [x] You can use Amazon Simple Queue Service (Amazon SQS) notifications to notify you when the job completes.
- [ ] Downloading a vault inventory is an asynchronous operation.

**[⬆ Back to Top](#table-of-contents)**

### Your fortune 500 company has under taken a TCO analysis evaluating the use of Amazon S3 versus acquiring more hardware The outcome was that ail employees would be granted access to use Amazon S3 for storage of their personal documents. Which of the following will you need to consider so you can set up a solution that incorporates single sign-on from your corporate AD or LDAP directory and restricts access for each user to a designated user folder in a bucket? (Choose 3 answers)

- [x] Setting up a federation proxy or identity provider.
- [x] Using AWS Security Token Service to generate temporary tokens.
- [ ] Tagging each folder in the bucket.
- [x] Configuring IAM role.
- [ ] Setting up a matching IAM user for every user in your corporate directory that needs access to a folder in the bucket.

**[⬆ Back to Top](#table-of-contents)**

### Your company policies require encryption of sensitive data at rest. You are considering the possible options for protecting data while storing it at rest on an EBS data volume, attached to an EC2 instance. Which of these options would allow you to encrypt your data at rest? (Choose 3 answers)

- [x] Implement third party volume encryption tools.
- [ ] Do nothing as EBS volumes are encrypted by default.
- [x] Encrypt data inside your applications before storing it on EBS.
- [x] Encrypt data using native data encryption drivers at the file system level.
- [ ] Implement SSL/TLS for all services running on the server.

**[⬆ Back to Top](#table-of-contents)**

### A scope has been handed to you to set up a super fast gaming server and you decide that you will use Amazon DynamoDB as your database. For efficient access to data in a table, Amazon DynamoDB creates and maintains indexes for the primary key attributes. A secondary index is a data structure that contains a subset of attributes from a table, along with an alternate key to support Query operations. How many types of secondary indexes does DynamoDB support?

- [x] 2.
- [ ] 16.
- [ ] 4.
- [ ] As many as you need.

**[⬆ Back to Top](#table-of-contents)**

### True or False: in Amazon Route 53, you can create a hosted zone for a top-level domain (TLD).

- [x] False.
- [ ] False, Amazon Route 53 automatically creates it for you.
- [ ] True, only if you send an XML document with a CreateHostedZoneRequest element for TLD.
- [ ] True.

**[⬆ Back to Top](#table-of-contents)**

### You want to use AWS Import/Export to send data from your S3 bucket to several of your branch offices. What should you do if you want to send 10 storage units to AWS?

- [ ] Make sure your disks are encrypted prior to shipping.
- [ ] Make sure you format your disks prior to shipping.
- [ ] Make sure your disks are 1TB or more.
- [x] Make sure you submit a separate job request for each device.

**[⬆ Back to Top](#table-of-contents)**

### You are deploying an application to track GPS coordinates of delivery trucks in the United States. Coordinates are transmitted from each delivery t ruck once every three seconds. You need to design an architecture that will enable real-time processing of these coordinates from multiple consumers. Which service should you use to implement data ingestion?

- [x] Amazon Kinesis.
- [ ] AWS Data Pipeline.
- [ ] Amazon AppStream.
- [ ] Amazon Simple Queue Service.

**[⬆ Back to Top](#table-of-contents)**

### While performing the volume status checks, if the status is insufficient-data, what does it mean?

- [x] The checks may still be in progress on the volume.
- [ ] The check has passed.
- [ ] The check has failed.

**[⬆ Back to Top](#table-of-contents)**

### Can you create IAM security credentials for existing users?

- [x] Yes, existing users can have security credentials associated with their account.
- [ ] No, IAM requires that all users who have credentials set up are not existing users.
- [ ] No, security credentials are created within GROUPS, and then users are associated to GROUPS at a later time.
- [ ] Yes, but only IAM credentials, not ordinary security credentials.

**[⬆ Back to Top](#table-of-contents)**

### Can I move a Reserved Instance from one Region to another?

- [x] No.
- [ ] Only if they are moving into GovCloud.
- [ ] Yes.
- [ ] Only if they are moving to US East from another region.

**[⬆ Back to Top](#table-of-contents)**

### A user has created an ELB with the Availability Zone US-East-1A. The user wants to add more zones to ELB to achieve High Availability. How can the user add more zones to the existing ELB?

- [ ] The user should stop the ELB and add zones and instances as required.
- [ ] The only option is to launch instances in different zones and add to ELB.
- [ ] It is not possible to add more zones to the existing ELB.
- [x] The user can add zones on the fly from the AWS console.

**[⬆ Back to Top](#table-of-contents)**

### Amazon SWF is designed to help users …

- [ ] Design graphical user interface interactions.
- [ ] Manage user identification and authorization.
- [ ] Store Web content.
- [x] Coordinate synchronous and asynchronous tasks which are distributed and fault tolerant.

**[⬆ Back to Top](#table-of-contents)**

### Which technique can be used to integrate AWS IAM (Identity and Access Management) with an on-premise LDAP (Lightweight Directory Access Protocol) directory service?

- [ ] Use an IAM policy that references the LDAP account identifiers and the AWS credentials.
- [x] Use SAML (Security Assertion Markup Language) to enable single sign-on between AWS and LDAP.
- [ ] Use AWS Security Token Service from an identity broker to issue short-lived AWS credentials.
- [ ] Use IAM roles to automatically rotate the IAM credentials when LDAP credentials are updated.
- [ ] Use the LDAP credentials to restrict a group of users from launching specific EC2 instance types.

**[⬆ Back to Top](#table-of-contents)**

### You are building a solution for a customer to extend their on-premises data center to AWS. The customer requires a 50-Mbps dedicated and private connection to their VPC. Which AWS product or feature satisfies this requirement?

- [ ] Amazon VPC peering.
- [ ] Elastic IP Addresses.
- [x] AWS Direct Connect.
- [ ] Amazon VPC virtual private gateway.

**[⬆ Back to Top](#table-of-contents)**

### A customer wants to leverage Amazon Simple Storage Service (S3) and Amazon Glacier as part of their backup and archive infrastructure. The customer plans to use third-party software to support this integration. Which approach will limit the access of the third party software to only the Amazon S3 bucket named 'company-backup'?

- [ ] A custom bucket policy limited to the Amazon S3 API in the Amazon Glacier archive 'company backup'.
- [ ] A custom bucket policy limited to the Amazon S3 API in 'company-backup'.
- [ ] A custom IAM user policy limited to the Amazon S3 API for the Amazon Glacier archive 'company backup'.
- [x] A custom IAM user policy limited to the Amazon S3 API in 'company-backup'.

**[⬆ Back to Top](#table-of-contents)**

### A user needs to run a batch process which runs for 10 minutes. This will only be run once, or at maximum twice, in the next month, so the processes will be temporary only. The process needs 15 X-Large instances. The process downloads the code from S3 on each instance when it is launched, and then generates a temporary log file. Once the instance is terminated, all the data will be lost. Which of the below mentioned pricing models should the user choose in this case?

- [x] Spot instance.
- [ ] Reserved instance.
- [ ] On-demand instance.
- [ ] EBS optimized instance.

**[⬆ Back to Top](#table-of-contents)**

### You have been doing a lot of testing of your VPC Network by deliberately failing EC2 instances to test whether instances are failing over properly. Your customer who will be paying the AWS bill for all this asks you if he being charged for all these instances. You try to explain to him how the billing works on EC2 instances to the best of your knowledge. What would be an appropriate response to give to the customer in regards to this?

- [ ] Billing commences when Amazon EC2 AMI instance is completely up and billing ends as soon as the instance starts to shutdown.
- [ ] Billing only commences only after 1 hour of uptime and billing ends when the instance terminates.
- [x] Billing commences when Amazon EC2 initiates the boot sequence of an AMI instance and billing ends when the instance shuts down.
- [ ] Billing commences when Amazon EC2 initiates the boot sequence of an AMI instance and billing ends as soon as the instance starts to shutdown.

**[⬆ Back to Top](#table-of-contents)**

### Refer to the architecture diagram above of a batch processing solution using Simple Queue Service (SQS) to set up a message queue between EC2 instances which are used as batch processors Cloud Watch monitors the number of Job requests (queued messages) and an Auto Scaling group adds or deletes batch servers automatically based on parameters set in Cloud Watch alarms. You can use this architecture to implement which of the following features in a cost effective and efficient manner?

![Question 563](images/question563.jpg)

- [ ] Reduce the overall lime for executing jobs through parallel processing by allowing a busy EC2 instance that receives a message to pass it to the next instance in a daisy-chain setup.
- [ ] Implement fault tolerance against EC2 instance failure since messages would remain in SQS and worn can continue with recovery of EC2 instances implement fault tolerance against SQS failure by backing up messages to S3.
- [x] Implement message passing between EC2 instances within a batch by exchanging messages through SQS.
- [ ] Coordinate number of EC2 instances with number of job requests automatically thus Improving cost effectiveness.
- [ ] Handle high priority jobs before lower priority jobs by assigning a priority metadata fie ld to SQS messages.

**[⬆ Back to Top](#table-of-contents)**

### You are migrating an internal server on your DC to an EC2 instance with EBS volume. Your server disk usage is around 500GB so you just copied all your data to a 2TB disk to be used with AWS Import/Export. Where will the data be imported once it arrives at Amazon?

- [ ] To a 2TB EBS volume.
- [x] To an S3 bucket with 2 objects of 1TB.
- [ ] To an 500GB EBS volume.
- [ ] To an S3 bucket as a 2TB snapshot.

**[⬆ Back to Top](#table-of-contents)**

### Is there any way to own a direct connection to Amazon Web Services?

- [ ] You can create an encrypted tunnel to VPC, but you don't own the connection.
- [ ] Yes, it's called Amazon Dedicated Connection.
- [ ] No, AWS only allows access from the public Internet.
- [x] Yes, it's called Direct Connect.

**[⬆ Back to Top](#table-of-contents)**

### Which of the following strategies can be used to control access to your Amazon EC2 instances?

- [ ] DB security groups.
- [ ] IAM policies.
- [ ] None of these.
- [x] EC2 security groups.

**[⬆ Back to Top](#table-of-contents)**

### A client of yours has a huge amount of data stored on Amazon S3, but is concerned about someone stealing it while it is in transit. You know that all data is encrypted in transit on AWS, but which of the following is wrong when describing server-side encryption on AWS?

- [ ] Amazon S3 server-side encryption employs strong multi-factor encryption.
- [ ] Amazon S3 server-side encryption uses one of the strongest block ciphers available, 256-bit Advanced Encryption Standard (AES-256), to encrypt your data.
- [x] In server-side encryption, you manage encryption/decryption of your data, the encryption keys, and related tools.
- [ ] Server-side encryption is about data encryption at rest―that is, Amazon S3 encrypts your data as it writes it to disks.

**[⬆ Back to Top](#table-of-contents)**

### When you run a DB Instance as a Multi-AZ deployment, the [...] serves database writes and reads

- [ ] secondary.
- [ ] backup.
- [ ] stand by.
- [x] primary.

**[⬆ Back to Top](#table-of-contents)**

### In Amazon EC2, how many Elastic IP addresses can you have by default?

- [ ] 10.
- [ ] 2.
- [x] 5.
- [ ] 20.

**[⬆ Back to Top](#table-of-contents)**

### A user has created photo editing software and hosted it on EC2. The software accepts requests from the user about the photo format and resolution and sends a message to S3 to enhance the picture accordingly. Which of the below mentioned AWS services will help make a scalable software with the AWS infrastructure in this scenario?

- [ ] AWS Simple Notification Service.
- [x] AWS Simple Queue Service.
- [ ] AWS Elastic Transcoder.
- [ ] AWS Glacier.

**[⬆ Back to Top](#table-of-contents)**

### Using Amazon CloudWatch's Free Tier, what is the frequency of metric updates which you receive?

- [x] 5 minutes.
- [ ] 500 milliseconds.
- [ ] 30 seconds
- [ ] 1 minute.

**[⬆ Back to Top](#table-of-contents)**

### When you resize the Amazon RDS DB instance, Amazon RDS will perform the upgrade during the next maintenance window. If you want the upgrade to be performed now, rather than waiting for the maintenance window, specify the [...] option.

- [ ] Apply Now.
- [ ] Apply Soon.
- [ ] Apply This.
- [x] Apply Immediately.

**[⬆ Back to Top](#table-of-contents)**

### A user is running a webserver on EC2. The user wants to receive the SMS when the EC2 instance utilization is above the threshold limit. Which AWS services should the user configure in this case?

- [ ] AWS CloudWatch + AWS SQS.
- [x] AWS CloudWatch + AWS SNS.
- [ ] AWS CloudWatch + AWS SES.
- [ ] AWS EC2 + AWS Cloudwatch.

**[⬆ Back to Top](#table-of-contents)**

### You're running an application on-premises due to its dependency on non-x86 hardware and want to use AWS for data backup. Your backup application is only able to write to POSIX-compatible block based storage. You have 140TB of data and would like to mount it as a single folder on your file server Users must be able to access portions of this data while the backups are taking place. What backup solution would be most appropriate for this use case?

- [x] Use Storage Gateway and configure it to use Gateway Cached volumes.
- [ ] Configure your backup software to use S3 as the target for your data backups.
- [ ] Configure your backup software to use Glacier as the target for your data backups.
- [ ] Use Storage Gateway and configure it to use Gateway Stored volumes.

**[⬆ Back to Top](#table-of-contents)**

### What happens to Amazon EBS root device volumes, by default, when an instance terminates?

- [ ] Amazon EBS root device volumes are moved to IA
- [x] Amazon EBS root device volumes are copied into Amazon RD
- [ ] Amazon EBS root device volumes are automatically deleted.
- [ ] Amazon EBS root device volumes remain in the database until you delete them.

**[⬆ Back to Top](#table-of-contents)**

### You require the ability to analyze a customer's clickstream data on a website so they can do behavioral analysis. Your customer needs to know what sequence of pages and ads their customer clicked on. This data will be used in real time to modify the page layouts as customers click through the site to increase stickiness and advertising click-through. Which option meets the requirements for captioning and analyzing this data?

- [ ] Log clicks in weblogs by URL store to Amazon S3, and then analyze with Elastic MapReduce.
- [x] Push web clicks by session to Amazon Kinesis and analyze behavior using Kinesis workers.
- [ ] Write click events directly to Amazon Redshift and then analyze with SQL.
- [ ] Publish web clicks by session to an Amazon SQS queue men periodically drain these events to Amazon RDS and analyze with SQL.

**[⬆ Back to Top](#table-of-contents)**

### What happens when you create a topic on Amazon SNS?

- [ ] The topic is created, and it has the name you specified for it.
- [x] An ARN (Amazon Resource Name) is created.
- [ ] You can create a topic on Amazon SQS, not on Amazon SNS.
- [ ] This question doesn't make sense.

**[⬆ Back to Top](#table-of-contents)**

### A company needs to deploy virtual desktops to its customers in a virtual private cloud, leveraging existing security controls. Which set of AWS services and features will meet the company's requirements?

- [ ] Virtual Private Network connection. AWS Directory Services, and Classic link.
- [ ] Virtual Private Network connection. AWS Di rectory Services, and Amazon Workspaces.
- [x] AWS Directory Service, Amazon Workspaces, and AWS Identity and Access Management.
- [ ] Amazon Elastic Compute Cloud, and AWS Identity and Access Management.

**[⬆ Back to Top](#table-of-contents)**

### You are designing a multi-platform web application for AWS The application will run on EC2 instances and will be accessed from PCs. tablets and smart phones Supported accessing platforms are Windows, macOS, iOS and Android Separate sticky session and SSL certificate setups are required for different platform types which of the following describes the most cost effective and performance efficient architecture setup?

- [ ] Setup a hybrid architecture to handle session state and SSL certificates on-prem and separate EC2 Instance groups running web applications for different platform types running in a VPC.
- [ ] Set up one ELB for all platforms to distribute load among multiple instance under it Each EC2 instance implements ail functionality for a particular platform.
- [ ] Set up two ELBs The first ELB handles SSL certificates for all platforms and the second ELB handles session stickiness for all platforms for each ELB run separate EC2 instance groups to handle the web application for each platform.
- [x] Assign multiple ELBS to an EC2 instance or group of EC2 instances running the common components of the web application, one ELB for each platform type Session stickiness and SSLtermination are done at the ELBs.

**[⬆ Back to Top](#table-of-contents)**

### A company is deploying a two-tier, highly available web application to AWS. Which service provides durable storage for static content while utilizing lower Overall CPU resources for the web tier?

- [ ] Amazon EBS volume.
- [x] Amazon S3.
- [ ] Amazon EC2 instance store.
- [ ] Amazon RD5 instance.

**[⬆ Back to Top](#table-of-contents)**

### Select the incorrect statement.

- [ ] In Amazon EC2, the private IP addresses only returned to Amazon EC2 when the instance is stopped or terminated.
- [ ] In Amazon VPC, an instance retains its private IP addresses when the instance is stopped.
- [x] In Amazon VPC, an instance does NOT retain its private IP addresses when the instance is stopped.
- [ ] In Amazon EC2, the private IP address is associated exclusive ly with the instance for its lifetime.

**[⬆ Back to Top](#table-of-contents)**

### An organization has a statutory requirement to protect the data at rest for data stored in EBS volumes. Which of the below mentioned options can the organization use to achieve data protection?

- [ ] Data replication.
- [ ] Data encryption.
- [ ] Data snapshot.
- [x] All the options listed here.

**[⬆ Back to Top](#table-of-contents)**

### A web design company currently runs several FTP servers that their 250 customers use to upload and download large graphic files They wish to move this system to AWS to make it more scalable, butthey wish to maintain customer privacy and Keep costs to a minimum. What AWS architecture would you recommend?

- [x] Ask their customers to use an S3 client instead of an FTP client. Create a single S3 bucket Create an IAM user for each customer Put the IAM Users in a Group that has an IAM policy that permits access to sub-directories within the bucket via use of the 'username' Policy variable.
- [ ] Create a single S3 bucket with Reduced Redundancy Storage turned on and ask their customers to use an S3 client instead of an FTP client Create a bucket for each customer with a Bucket Policy that permits access only to that one customer.
- [ ] Create an auto-scaling group of FTP servers with a scaling policy to automatically scale-in when minimum network traffic on the auto-scaling group is below a given threshold. Load a central list of ftp users from S3 as part of the user Data startup script on each Instance.
- [ ] Create a single S3 bucket with Requester Pays turned on and ask their customers to use an S3 client instead of an FTP client Create a bucket tor each customer with a Bucket Policy that permits access only to that one customer.

**[⬆ Back to Top](#table-of-contents)**

### Amazon RDS DB snapshots and automated backups are stored in:

- [x] Amazon S3.
- [ ] Amazon ECS Volume.
- [ ] Amazon RDS.
- [ ] Amazon EMR.

**[⬆ Back to Top](#table-of-contents)**

### Can Amazon S3 uploads resume on failure or do they need to restart?

- [ ] Restart from beginning.
- [ ] You can resume them, if you flag the 'resume on fai lure' option before uploading.
- [x] Resume on failure.
- [ ] Depends on the file size.

**[⬆ Back to Top](#table-of-contents)**

### Prior to the introduction of this function, the HA feature provided redundancy and performance, but required that a failed/lost group member be [...] reinstated.

- [ ] automatically.
- [ ] periodically.
- [x] manually.
- [ ] continuously.

**[⬆ Back to Top](#table-of-contents)**

### A company has a workflow that sends video files from their on-premise system to AWS for transcoding. They use EC2 worker instances that pull transcoding jobs from SQS. Why is SQS an appropriate service for this scenario?

- [ ] SQS guarantees the order of the messages.
- [ ] SQS synchronously provides transcoding output.
- [ ] SQS checks the health of the worker instances.
- [x] SQS helps to facilitate horizontal scaling of encoding tasks.

**[⬆ Back to Top](#table-of-contents)**

### Which statement below best describes what thresholds you can set to trigger a CloudWatch Alarm?

- [x] Set a target value and choose whether the alarm will trigger when the value is greater than (>), greater than or equal to (>=), less than (<), or less than or equal to (<=) that value.
- [ ] Thresholds need to be set in IAM not CloudWatch.
- [ ] Only default thresholds can be set you can't choose your own thresholds.
- [ ] Set a target value and choose whether the alarm will trigger when the value hits this threshold.

**[⬆ Back to Top](#table-of-contents)**

### You are designing a web application that stores static assets in an Amazon Simple Storage Service (S3) bucket. You expect this bucket to immediately receive over 150 PUT requests per second. What should you do to ensure optimal performance?

- [x] Use multi-part upload.
- [ ] Add a random prefix to the key names.
- [ ] Amazon S3 will automatically manage performance at this scale.
- [ ] Use a predictable naming scheme, such as sequential numbers or date time sequences, in the key names.

**[⬆ Back to Top](#table-of-contents)**

### What does Amazon EC2 provide?

- [x] Virtual servers in the Cloud.
- [ ] A platform to run code (Java, PHP, Python), paying on an hourly basis.
- [ ] Computer Clusters in the Cloud.
- [ ] Physical servers, remotely managed by the customer.

**[⬆ Back to Top](#table-of-contents)**

### A customer has a single 3-TB volume on-premises that is used to hold a large repository of images and print layout files. This repository is growing at 500 GB a year and must be presented as a single logical volume. The customer is becoming increasingly constrained with their local storage capacity and wants an off-site backup of this data, while maintaining low-latency access to their frequently accessed data. Which AWS Storage Gateway configuration meets the customer requirements?

- [ ] Gateway-Cached volumes with snapshots scheduled to Amazon S3.
- [ ] Gateway-Stored volumes with snapshots scheduled to Amazon S3.
- [ ] Gateway-Virtual Tape Library with snapshots to Amazon S3.
- [x] Gateway-Virtual Tape Library with snapshots to Amazon Glacier.

**[⬆ Back to Top](#table-of-contents)**

### You are architecting an auto-scalable batch processing system using video processing pipelines and Amazon Simple Queue Service (Amazon SQS) for a customer. You are unsure of the limitations of SQS and need to find out. What do you think is a correct statement about the limitations of Amazon SQS?

- [ ] It supports an unlimited number of queues but a limited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 weeks.
- [x] It supports an unlimited number of queues and unlimited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 days.
- [ ] It supports an unlimited number of queues but a limited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 days.
- [ ] It supports an unlimited number of queues and unlimited number of messages per queue for each user but automatically deletes messages that have been in the queue for more than 4 weeks.

**[⬆ Back to Top](#table-of-contents)**

### Which Amazon service can I use to define a virtual network that closely resembles a traditional data center?

- [x] Amazon VPC.
- [ ] Amazon Service Bus.
- [ ] Amazon EMR.
- [ ] Amazon RDS.

**[⬆ Back to Top](#table-of-contents)**

### Select the correct set of options. These are the initial settings for the default security group:

- [x] Allow no inbound traffic, Allow all outbound traffic and Allow instances associated with this security group to talk to each other.
- [ ] Allow all inbound traffic, Allow no outbound traffic and Allow instances associated with this security group to talk to each other.
- [ ] Allow no inbound traffic, Allow all outbound traffic and Does NOT allow instances associated with this security group to talk to each other.
- [ ] Al low all inbound traffic, Allow all outbound traffic and Does NOT allow instances associated with this security group to talk to each other.

**[⬆ Back to Top](#table-of-contents)**

### You need to migrate a large amount of data into the cloud that you have stored on a hard disk and you decide that the best way to accomplish this is with AWS Import/Export and you mail the hard disk to AWS. Which of the following statements is incorrect in regards to AWS Import/Export?

- [ ] It can export from Amazon S3.
- [ ] It can Import to Amazon Glacier.
- [x] It can export from Amazon Glacier.
- [ ] It can Import to Amazon EBS.

**[⬆ Back to Top](#table-of-contents)**

### Can I control if and when MySQL based RDS Instance is upgraded to new supported versions?

- [ ] No.
- [ ] Only in VPC.
- [x] Yes.

**[⬆ Back to Top](#table-of-contents)**

### If I have multiple Read Replicas for my master DB Instance and I promote one of them, what happens to the rest of the Read Replicas?

- [x] The remaining Read Replicas will still replicate from the older master DB Instance.
- [ ] The remaining Read Replicas will be deleted.
- [ ] The remaining Read Replicas will be combined to one read replica.

**[⬆ Back to Top](#table-of-contents)**

### A user is running a batch process which runs for 1 hour every day. Which of the below mentioned options is the right instance type and costing model in this case if the user performs the same task for the whole year?

- [x] EBS backed instance with on-demand instance pricing.
- [ ] EBS backed instance with heavy utilized reserved instance pricing.
- [ ] EBS backed instance with low utilized reserved instance pricing.
- [ ] Instance store backed instance with spot instance pricing.

**[⬆ Back to Top](#table-of-contents)**

### You are in the process of building an online gaming site for a client and one of the requirements is that it must be able to process vast amounts of data easily. Which AWS Service would be very helpful in processing all this data?

- [ ] Amazon S3.
- [ ] AWS Data Pipeline.
- [ ] AWS Direct Connect.
- [x] Amazon EMR.

**[⬆ Back to Top](#table-of-contents)**

### Your team has a tomcat-based Java application you need to deploy into development, test and production environments. After some research, you opt to use Elastic Beanstalk due to its tight integration with your developer tools and RDS due to its ease of management. Your QA team lead points out that you need to roll a sanitized set of production data into your environment on a nightly basis. Similarly, other software teams in your org want access to that same restored data via their EC2 instances in your VPC. The optimal setup for persistence and security that meets the above requirements would be the following:

- [x] Create your RDS instance as part of your Elastic Beanstalk definition and alter its security group to allow access to it from hosts in your application subnets.
- [ ] Create your RDS instance separately and add its IP address to your application's DB connection strings in your code Alter its security group to allow access to it from hosts within your VPC's IPaddress block.
- [ ] Create your RDS instance separately and pass its DNS name to your app's DB connection string as an environment variable. Create a security group for client machines and add it as a valid source for DB traffic to the security group of the RDS instance itself.
- [ ] Create your RDS instance separately and pass its DNS name to your's DB connection string as an environment variable Alter its security group to allow access to It from hosts in your application subnets.

**[⬆ Back to Top](#table-of-contents)**

### What are characteristics of Amazon S3? (Choose 2 answers)

- [ ] Amazon S3 allows you to store objects of virtually unlimited size.
- [ ] Amazon S3 offers Provisioned IOP.
- [x] Amazon S3 allows you to store unlimited amounts of data.
- [ ] Amazon S3 should be used to host a relational database.
- [x] Objects are directly accessible via a URL.

**[⬆ Back to Top](#table-of-contents)**

### You need to set up a complex network infrastructure for your organization that will be reasonably easy to deploy, replicate, control, and track changes on. Which AWS service would be best to use to help you accomplish this?

- [ ] AWS Import/Export.
- [x] AWS CloudFormation.
- [ ] Amazon Route 53.
- [ ] Amazon CloudWatch.

**[⬆ Back to Top](#table-of-contents)**

### How should the application use AWS credentials to access the S3 bucket securely?

- [ ] Use the AWS account access Keys the application retrieves the credentials from the source code of the application.
- [ ] Create an IAM user for the application with permissions that allow list access to the S3 bucket launch the instance as the IAM user and retrieve the IAM user's credentials from the EC2 instance user data.
- [x] Create an IAM role for EC2 that allows list access to objects in the S3 bucket. Launch the instance with the role, and retrieve the role's credentials from the EC2 Instance metadata.
- [ ] Create an IAM user for the application with permissions that allow list access to the S3 bucket. The application retrieves the IAM user credentials from a temporary directory with permissions that allow read access only to the application user.

**[⬆ Back to Top](#table-of-contents)**

### You are setting up a VPC and you need to set up a public subnet within that VPC. Which following requirement must be met for this subnet to be considered a public subnet?

- [ ] Subnet's traffic is not routed to an internet gateway but has its traffic routed to a virtual private gateway.
- [x] Subnet's traffic is routed to an internet gateway.
- [ ] Subnet's traffic is not routed to an internet gateway.
- [ ] None of these answers can be considered a public subnet.

**[⬆ Back to Top](#table-of-contents)**

### Is it possible to access your EBS snapshots?

- [ ] Yes, through the Amazon S3 APIs.
- [x] Yes, through the Amazon EC2 APIs.
- [ ] No, EBS snapshots cannot be accessed; they can only be used to create a new EBS volume.
- [ ] EBS doesn't provide snapshots.

**[⬆ Back to Top](#table-of-contents)**

### How many types of block devices does Amazon EC2 support?

- [ ] 4.
- [ ] 5.
- [x] 2.
- [ ] 1.

**[⬆ Back to Top](#table-of-contents)**

### SQL Server [...] store log ins and passwords in the master database.

- [ ] can be configured to but by default does not.
- [ ] doesn't.
- [x] does.

**[⬆ Back to Top](#table-of-contents)**

### You are using an m1.small EC2 Instance with one 300GB EBS volume to host a relational database. You determined that write throughput to the database needs to be increased. Which of the following approaches can help achieve this? (Choose 2 answers)

- [x] Use an array of EBS volumes.
- [ ] Enable Multi-AZ mode.
- [ ] Place the instance in an Auto Scaling Groups.
- [ ] Add an EBS volume and place into RAID 5.
- [x] Increase the size of the EC2 Instance.
- [ ] Put the database behind an Elastic Load Balancer.

**[⬆ Back to Top](#table-of-contents)**

### A user is hosting a website in the US West-1 region. The website has the highest client base from the Asia-Pacific (Singapore / Japan) region. The application is accessing data from S3 before serving it to client. Which of the below mentioned regions gives a better performance for S3 objects?

- [ ] Japan.
- [ ] Singapore.
- [ ] US East.
- [x] US West-1.

**[⬆ Back to Top](#table-of-contents)**

### You need to set up security for your VPC and you know that Amazon VPC provides two features that you can use to increase security for your VPC: Security groups and network access control lists (ACLs). You start to look into security groups first. Which statement below is incorrect in relation to security groups?

- [ ] Are stateful: Return traffic is automatically allowed, regardless of any rules.
- [ ] Evaluate all rules before deciding whether to allow traffic.
- [x] Support allow rules and deny rules.
- [ ] Operate at the instance level (first layer of defense).

**[⬆ Back to Top](#table-of-contents)**

### Can a single EBS volume be attached to multiple EC2 instances at the same time?

- [ ] Yes.
- [x] No.
- [ ] Only for high-performance EBS volumes.
- [ ] Only when the instances are located in the US regions.

**[⬆ Back to Top](#table-of-contents)**

### You are planning and configuring some EBS volumes for an application. in order to get the most performance out of your EBS volumes, you should attach them to an instance with enough [...] to support your volumes.

- [ ] redundancy.
- [ ] storage.
- [x] bandwidth.
- [ ] memory.

**[⬆ Back to Top](#table-of-contents)**

### An organization has three separate AWS accounts, one each for development, testing, and production. The organization wants the testing team to have access to certain AWS resources in the production account. How can the organization achieve this?

- [ ] It is not possible to access resources of one account with another account.
- [x] Create the IAM roles with cross account access.
- [ ] Create the IAM user in a test account, and allow it access to the production environment with the IAM policy.
- [ ] Create the IAM users with cross account access.

**[⬆ Back to Top](#table-of-contents)**

### A benefits enrollment company is hosting a 3-tier web application running in a VPC on AWS which includes a NAT (Network Address Translation) instance in the public Web tier. There is enough provisioned capacity for the expected workload tor the new fiscal year benefit enrollment period plus some extra overhead Enrollment proceeds nicely for two days and then the web tier becomes unresponsive, upon investigation using CloudWatch and other monitoring tools it is discovered that there is an extremely large and unanticipated amount of inbound traffic coming from a set of 15specific IP addresses over port 80 from a country where the benefits company has no customers. The web tier instances are so overloaded that benefit enrollment administrators cannot even SSH into them. Which activity would be useful in defending against this attack?

- [ ] Create a custom route table associated with the web tier and block the attacking IP addresses from the IGW (Internet Gateway).
- [ ] Change the EIP (Elastic IP Address) of the NAT instance in the web tier subnet and update the Main Route Table with the new EIP.
- [ ] Create 15 Security Group rules to block the attacking IP addresses over port 80.
- [x] Create an inbound NACL (Network Access control list) associated with the web tier subnet with deny rules to block the attacking IP addresses.

**[⬆ Back to Top](#table-of-contents)**

### You launch an Amazon EC2 instance without an assigned AVVS identity and Access Management (IAM) role. Later, you decide that the instance should be running with an IAM role. Which action must you take in order to have a running Amazon EC2 instance with an IAM role assigned to it?

- [ ] Create an image of the instance, and register the image with an IAM role assigned and an Amazon EBS volume mapping.
- [ ] Create a new IAM role with the same permissions as an existing IAM role, and assign it to the running instance.
- [ ] Create an image of the instance, add a new IAM role with the same permissions as the desired IAM role, and deregister the image with the new role assigned.
- [x] Create an image of the instance, and use this image to launch a new instance with the desired Lam role assigned.

**[⬆ Back to Top](#table-of-contents)**

### Does AWS Direct Connect allow you access to all Availabilities Zones within a Region?

- [x] Depends on the type of connection.
- [ ] Yes.
- [ ] No.
- [ ] Only when there's just one Availability Zone in a region. If there are more than one, only one availability zone can be accessed directly.

**[⬆ Back to Top](#table-of-contents)**

### What is the durability of S3 RRS?

- [x] 99.99%.
- [ ] 99.95%.
- [ ] 99.995%.
- [ ] 99.999999999%.

**[⬆ Back to Top](#table-of-contents)**

### Your organization is in the business of architecting complex transactional databases. For a variety of reasons, this has been done on EBS. What is AWS's recommendation for customers who have architected databases using EBS for backups?

- [x] Backups to Amazon S3 be performed through the database management system.
- [ ] Backups to AWS Storage Gateway be performed through the database management system.
- [ ] If you take regular snapshots no further backups are required.
- [ ] Backups to Amazon Glacier be performed through the database management system.

**[⬆ Back to Top](#table-of-contents)**

### You need to create a load balancer in a VPC network that you are building. You can make your load balancer internal (private) or internet-facing (public). When you make your load balancer internal, a DNS name will be created, and it will contain the private IP address of the load balancer. An internal load balancer is not exposed to the internet. When you make your load balancer internet-facing, a DNS name will be created with the public IP address. If you want the Internet-facing load balancer to be connected to the Internet, where must this load balancer reside?

- [x] The load balancer must reside in a subnet that is connected to the internet using the internet gateway.
- [ ] The load balancer must reside in a subnet that is not connected to the internet.
- [ ] The load balancer must not reside in a subnet that is connected to the internet.
- [ ] The load balancer must be completely outside of your IP.

**[⬆ Back to Top](#table-of-contents)**

### In the Amazon CloudWatch, which metric should I be checking to ensure that your DB Instance has enough free storage space?

- [ ] Free Storage.
- [x] Free Storage Space.
- [ ] Free Storage Volume.
- [ ] Free DB Storage Space.

**[⬆ Back to Top](#table-of-contents)**

### A web-startup runs its very successful social news application on Amazon EC2 with an Elastic Load Balancer, an Auto-Scaling group of Java/Tomcat application-servers, and DynamoDB as data store. The main web-application best runs on m2 x large instances since it is highly memory- bound Each new deployment requires semi-automated creation and testing of a new AMI for the application servers which takes quite a while ana is therefore only done once per week. Recently, a new chat feature has been implemented in nodejs and wails to be integrated in the architecture. First tests show that the new component is CPU bound Because the company has some experience with using Chef, they decided to streamline the deployment process and use AWS OpsWorks as an application life cycle tool to simplify management of the application and reduce the deployment cycles. What configuration in AWS OpsWorks is necessary to integrate the new chat module in the most cost-efficient and flexible way?

- [ ] Create one AWS OpsWorks stack, create one AWS OpsWorks layer, create one custom recipe.
- [ ] Create one AWS OpsWorks stack create two AWS OpsWorks layers create one custom recipe.
- [x] Create two AWS OpsWorks stacks create two AWS OpsWorks layers create one custom recipe.
- [ ] Create two AWS OpsWorks stacks create two AWS OpsWorks layers create two custom recipe.

**[⬆ Back to Top](#table-of-contents)**

### A client needs you to import some existing infrastructure from a dedicated hosting provider to AWS to try and save on the cost of running his current website. He also needs an automated process that manages backups, software patching, automatic failure detection, and recovery. You are aware that his existing set up currently uses an Oracle database. Which of the following AWS databases would be best for accomplishing this task?

- [x] Amazon RDS.
- [ ] Amazon Redshift.
- [ ] Amazon SimpleDB.
- [ ] Amazon ElastiCache.

**[⬆ Back to Top](#table-of-contents)**

### A user is currently building a website which will require a large number of instances in six months, when a demonstration of the new site will be given upon launch. Which of the below mentioned options allows the user to procure the resources beforehand so that they need not worry about infrastructure availability during the demonstration?

- [x] Procure all the instances as reserved instances beforehand.
- [ ] Launch all the instances as part of the cluster group to ensure resource availability.
- [ ] Pre-warm all the instances one month prior to ensure resource availability.
- [ ] Ask AWS now to procure the dedicated instances in 6 months.

**[⬆ Back to Top](#table-of-contents)**

### Amazon RDS creates an SSL certificate and installs the certificate on the DB Instance when Amazon RDS provisions the instance. These certificates are signed by a certificate authority. The [...] is stored at <https://rds.amazonaws.com/doc/rds-ssl-ca-cert.pem>.

- [x] private key.
- [ ] foreign key.
- [ ] public key.
- [ ] protected key.

**[⬆ Back to Top](#table-of-contents)**

### What happens to data on an ephemeral volume of an EBS-backed EC2 instance if it is terminated or if it fails?

- [ ] Data is automatically copied to another volume.
- [ ] The volume snapshot is saved in S3.
- [ ] Data persists.
- [x] Data is deleted.

**[⬆ Back to Top](#table-of-contents)**

### You manually launch a NAT AMI in a public subnet. The network is properly configured. Security groups and network access control lists are property configured. Instances in a private subnet can access the NAT. The NAT can access the Internet. However, private instances cannot access the Internet. What additional step is required to allow access from the private instances?

- [ ] Enable Source/Destination Check on the private Instances.
- [x] Enable Source/Destination Check on the NAT instance.
- [ ] Disable Source/Destination Check on the private instances.
- [ ] Disable Source/Destination Check on the NAT instance.

**[⬆ Back to Top](#table-of-contents)**

### You have just discovered that you can upload your objects to Amazon S3 using Multipart Upload API. You start to test it out but are unsure of the benefits that it would provide. Which of the following is not a benefit of using multipart uploads?

- [ ] You can begin an upload before you know the final object size.
- [ ] Quick recovery from any network issues.
- [ ] Pause and resume object uploads.
- [x] It's more secure than normal upload.

**[⬆ Back to Top](#table-of-contents)**

### To help you manage your Amazon EC2 instances, images, and other Amazon EC2 resources, you can assign your own metadata to each resource in the form of [...].

- [ ] special filters.
- [ ] functions.
- [x] tags.
- [ ] wildcards.

**[⬆ Back to Top](#table-of-contents)**

### Are you able to integrate a multi-factor token service with the AWS Platform?

- [x] Yes, using the AWS multi-factor token devices to authenticate users on the AWS platform.
- [ ] No, you cannot integrate multi-factor token devices with the AWS platform.
- [ ] Yes, you can integrate private multi-factor token devices to authenticate users to the AWS platform.

**[⬆ Back to Top](#table-of-contents)**

### Do the Amazon EBS volumes persist independently from the running life of an Amazon EC2 instance?

- [ ] No.
- [ ] Only if instructed to when created.
- [x] Yes.

**[⬆ Back to Top](#table-of-contents)**

### If I write the below command, what does it do? ec2-run ami-e3a5408a -n 20 -g appserver

- [x] Start twenty instances as members of appserver group.
- [ ] Creates 20 rules in the security group named appserver.
- [ ] Terminate twenty instances as members of appserver group.
- [ ] Start 20 security groups.

**[⬆ Back to Top](#table-of-contents)**

### A company is deploying a new two-tier web application in AWS. The company has limited staff and requires high availability, and the application requires complex queries and table joins. Which configuration provides the solution for the company's requirements?

- [ ] MySQL Installed on two Amazon EC2 Instances in a single Availability Zone.
- [ ] Amazon RDS for MySQL with Multi-AZ.
- [ ] Amazon ElastiCache
- [x] Amazon DynamoDB.

**[⬆ Back to Top](#table-of-contents)**

### Is creating a Read Replica of another Read Replica supported?

- [ ] Only in certain regions.
- [ ] Only with MSSQL based RDS.
- [ ] Only for Oracle RDS types.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### In order to optimize performance for a compute cluster that requires low inter-node latency, which of the following feature should you use?

- [ ] Multiple Availability Zones.
- [ ] AWS Direct Connect.
- [ ] EC2 Dedicated Instances.
- [x] Placement Groups.
- [ ] VPC private subnets.

**[⬆ Back to Top](#table-of-contents)**

### Regarding the attaching of ENI to an instance, what does 'warm attach' refer to?

- [x] Attaching an ENI to an instance when it is stopped.
- [ ] This question doesn't make sense.
- [ ] Attaching an ENI to an instance when it is running.
- [ ] Attaching an ENI to an instance during the launch process.

**[⬆ Back to Top](#table-of-contents)**

### Can I attach more than one policy to a particular entity?

- [x] Yes always.
- [ ] Only if within GovCloud.
- [ ] No.
- [ ] Only if within VPC.

**[⬆ Back to Top](#table-of-contents)**

### By default, when an EBS volume is attached to a Windows instance, it may show up as any drive letter on the instance. You can change the settings of the [...] Service to set the drive letters of the EBS volumes per your specifications.

- [ ] EBS Config Service.
- [ ] AMI Config Service.
- [x] EC2 Config Service.
- [ ] EC2-AMI Config Service.

**[⬆ Back to Top](#table-of-contents)**

### Select the correct set of steps for exposing the snapshot only to specific AWS accounts.

- [ ] Select public for all the accounts and check mark t hose accounts with whom you want to expose the snapshots and cl ick save.
- [ ] Select Private, enter the IDs of t hose AWS accounts, and click Save.
- [x] Select Public, enter the IDs of those AWS accounts, and click Save.
- [ ] Select Public, mark the IDs of those AWS accounts as private, and click Save.

**[⬆ Back to Top](#table-of-contents)**

### How can you apply more than 100 rules to an Amazon EC2-Classic?

- [ ] By adding more security groups.
- [ ] You need to create a default security group specifying your required rules if you need to use more than 100 rules per security group.
- [ ] By default the Amazon EC2 security groups support 500 rules.
- [x] You can't add more than 100 rules to security groups for an Amazon EC2 instance.

**[⬆ Back to Top](#table-of-contents)**

### A user has created an ELB with Auto Scaling. Which of the below mentioned offerings from ELB helps the user to stop sending new requests traffic from the load balancer to the EC2 instance when the instance is being deregistered while continuing in-flight requests?

- [ ] ELB sticky session.
- [ ] ELB deregistration check.
- [ ] ELB auto registration Off.
- [x] ELB connection draining.

**[⬆ Back to Top](#table-of-contents)**

### What can I access by visiting the URL: http://status.aws.amazon.com/?

- [ ] Amazon Cloud Watch.
- [ ] Status of the Amazon RDS DB.
- [x] AWS Service Health Dashboard.
- [ ] AWS Cloud Monitor.

**[⬆ Back to Top](#table-of-contents)**

### In Route 53, what does a Hosted Zone refer to?

- [ ] A hosted zone is a collection of geographical load balancing rules for Route 53.
- [x] A hosted zone is a collection of resource record sets hosted by Route 53.
- [ ] A hosted zone is a selection of specific resource record sets hosted by CloudFront for distribution to Route 53.
- [ ] A hosted zone is the Edge Location that hosts the Route 53 records for a user.

**[⬆ Back to Top](#table-of-contents)**

### A user is launching an EC2 instance in the US East region. Which of the below mentioned options is recommended by AWS with respect to the selection of the Availability Zone?

- [ ] Always select the AZ while launching an instance.
- [ ] Always select the US-East-1-a zone for HA.
- [x] Do not select the AZ; instead let AWS select the AZ.
- [ ] The user can never select the Availability Zone while launching an instance.

**[⬆ Back to Top](#table-of-contents)**

### ec2-revoke RevokeSecurityGroup Ingress

- [ ] Removes one or more security groups from a rule.
- [ ] Removes one or more security groups from an Amazon EC2 instance.
- [x] Removes one or more rules from a security group.
- [ ] Removes a security group from our account.

**[⬆ Back to Top](#table-of-contents)**

### Select the correct statement

- [ ] You don't need not specify the resource identifier while stopping a resource.
- [ ] You can terminate, stop, or delete a resource based solely on its tags.
- [x] You can't terminate, stop, or delete a resource based solely on its tags.
- [ ] You don't need to specify the resource identifier while terminating a resource.

**[⬆ Back to Top](#table-of-contents)**

### What is the time period with which metric data is sent to CloudWatch when detailed monitoring is enabled on an Amazon EC2 instance?

- [ ] 15 minutes.
- [ ] 5 minutes.
- [x] 1 minute.
- [ ] 45 seconds.

**[⬆ Back to Top](#table-of-contents)**

### A large real -estate brokerage is exploring the option of adding a cost-effective location based alert to their existing mobile application The application backend infrastructure currently runs on AWS Users who opt in to this service will receive alerts on their mobile device regarding real-estate otters in proximity to their location. For the alerts to be relevant delivery time needs to be in the low minute count the existing mobile app has 5 million users across the us. Which one of the following architectural suggestions would you make to the customer?

- [x] The mobile application will submit its location to a web service endpoint utilizing Elastic Load Balancing and EC2 instances: DynamoDB will be used to store and retrieve relevant otters EC2 instances will communicate with mobile earners/device providers to push alerts back to mobile application.
- [ ] Use AWS DirectConnect or VPN to establish connectivity with mobile carriers EC2 instances will receive the mobile applications' location through carrier connection: ROS will be used to store and relevant relevant offers EC2 instances will communicate with mobile carriers to push alerts back to the mobile application.
- [ ] The mobile application will send device location using SQS.
- [ ] EC2 instances will retrieve the re levant others from DynamoDB AWS Mobile Push will be used to send offers to the mobile application to push alerts back to the mobile application.
- [ ] The mobile application will send device location using AWS Mobile Push EC2 instances will retrieve the relevant offers from DynamoDB EC2 instances will communicate with mobile carriers/device providers to push alerts back to the mobile application.

**[⬆ Back to Top](#table-of-contents)**

### You are running PostgreSQL on Amazon RDS and it seems to be all running smoothly deployed in one Availability Zone. A database administrator asks you if DB instances running PostgreSQL support Multi-AZ deployments. What would be a correct response to this question?

- [x] Yes.
- [ ] Yes but only for small db instances.
- [ ] No.
- [ ] Yes but you need to request the service from AWS.

**[⬆ Back to Top](#table-of-contents)**

### What is the data model of DynamoDB?

- [ ] Since DynamoDB is schema-less, there is no data model.
- [ ] 'Items', with Keys and one or more Attribute; and 'Attribute', with Name and Value.
- [x] 'Table', a collection of Items; 'Items', with Keys and one or more Attribute; and 'Attribute', with Name and Value.
- [ ] 'Database', which is a set of 'Tables', which is a set of 'Items', which is a set of 'Attributes'.

**[⬆ Back to Top](#table-of-contents)**

### What is a placement group in Amazon EC2?

- [x] It is a group of EC2 instances within a single Availability Zone.
- [ ] It the edge location of your web content.
- [ ] It is the AWS region where you run the EC2 instance of your web content.
- [ ] It is a group used to span multiple Availability Zones.

**[⬆ Back to Top](#table-of-contents)**
